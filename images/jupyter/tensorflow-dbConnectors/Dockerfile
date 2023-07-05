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
# RUN pip install pyodbc==4.0.34

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

USER jovyan
WORKDIR /home/jovyan