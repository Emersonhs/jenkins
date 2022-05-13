FROM jenkins/jenkins

USER root
RUN apt-get update
RUN apt-get install -y apt-transport-https

RUN apt-get update && apt-get -y upgrade &&\
  apt-get install -y snap snapd
RUN snap --version

#RUN snap install donet-sdk --classic 
#RUN snap alias dotnet-sdk.dotnet dotnet
