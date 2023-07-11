ARG IMAGE

FROM ${IMAGE} as parent

USER root
WORKDIR /

#---------------------------------------------------------------------------------------------
# Install msodbcsql18 - pyodbc
RUN apt-get update && apt-get upgrade -y
RUN apt-get install gnupg2 -y
RUN apt-get install curl -y

RUN curl https://packages.microsoft.com/keys/microsoft.asc | apt-key add -
RUN curl https://packages.microsoft.com/config/ubuntu/22.04/prod.list > /etc/apt/sources.list.d/mssql-release.list
RUN apt-get update

RUN ACCEPT_EULA=Y apt-get install -y msodbcsql18
# optional: for bcp and sqlcmd
RUN ACCEPT_EULA=Y apt-get install -y mssql-tools18
RUN echo 'export PATH="$PATH:/opt/mssql-tools18/bin"' >> ~/.bashrc
#RUN source ~/.bashrc
# optional: for unixODBC development headers
RUN apt-get install -y unixodbc-dev
RUN apt-get install postgresql libpq-dev -y

#Install JRE
RUN apt-get update && apt-get install -y default-jre

RUN pip install upgrade-pip

# Install ANSIBLE
RUN pip install ansible-kernel
RUN python -m ansible_kernel.install
RUN apt-get install -y sshpass

# Install Terraform
RUN apt-get update && sudo apt-get install -y gnupg software-properties-common

RUN wget -O- https://apt.releases.hashicorp.com/gpg | \
    gpg --dearmor | \
    tee /usr/share/keyrings/hashicorp-archive-keyring.gpg


RUN gpg --no-default-keyring \
    --keyring /usr/share/keyrings/hashicorp-archive-keyring.gpg \
    --fingerprint

RUN echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] \
    https://apt.releases.hashicorp.com $(lsb_release -cs) main" | \
    tee /etc/apt/sources.list.d/hashicorp.list

RUN apt update
RUN apt-get install terraform

# Install kubectl tools
RUN curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"
RUN curl -LO "https://dl.k8s.io/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl.sha256"
RUN echo "$(cat kubectl.sha256)  kubectl" | sha256sum --check
RUN install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl

# Install Azure CLI
RUN curl -sL https://aka.ms/InstallAzureCLIDeb | bash

# Install AWS CLI
RUN apt install -y groff
RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
RUN unzip awscliv2.zip
RUN  ./aws/install

# Install Napptive CLI
RUN curl -O https://storage.googleapis.com/artifacts.playground.napptive.dev/installer.sh && bash installer.sh

COPY images/jupyter/tensorflow-dbConnectors/requirements.txt requirements.txt
RUN pip install -r requirements.txt

USER jovyan
WORKDIR /home/jovyan