FROM centos:6.4
MAINTAINER James Turnbull "james@example.com"
ENV REFRESHED_AT 2014-06-01
RUN yum -y install ruby rubygems rubygem-rake
RUN gem install --no-rdoc --no-ri rspec -v 2.99.0
RUN gem install --no-rdoc --no-ri ci_reporter
