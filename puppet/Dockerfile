FROM ubuntu:precise
MAINTAINER Eduardo Reimberg "eduardo.reimberg@gmail.com"
ENV UPDATED_AT 24-03-2015
RUN apt-get update
RUN apt-get install -y wget
RUN wget --no-check-certificate https://apt.puppetlabs.com/puppetlabs-release-precise.deb
RUN dpkg -i puppetlabs-release-precise.deb
RUN apt-get update
RUN apt-get install -y puppet
EXPOSE 8140
