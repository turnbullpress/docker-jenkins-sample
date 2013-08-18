FROM wiltan/debian-tiny
MAINTAINER James Turnbull "james@example.com"
ENV REFRESHED_AT 2013-08-01
RUN apt-get update
RUN apt-get -y install ruby rubygems rake
RUN gem install --no-rdoc --no-ri rspec ci_reporter
