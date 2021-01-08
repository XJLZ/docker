FROM centos:7.5.1804

MAINTAINER XJL "xiaonokia_no1@qq.com"

WORKDIR /usr/local

ADD jdk-8u261-linux-x64.tar.gz /usr/local/


ENV JAVA_HOME=/usr/local/jdk1.8.0_261
ENV PATH=$PATH:$JAVA_HOME/bin
ENV CLASSPATH=.:$JAVA_HOME/lib/dt.jar:$JAVA_HOME/lib/tools.jar

RUN ["java","-version"]
