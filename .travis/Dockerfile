FROM centos:7

MAINTAINER foreman-dev "https://github.com/theforeman"

RUN rpm -Uvh http://yum.puppetlabs.com/puppetlabs-release-pc1-el-7.noarch.rpm
RUN yum -y install puppet-agent rubygems
RUN gem install kafo
RUN /opt/puppetlabs/puppet/bin/gem install puppet-strings
