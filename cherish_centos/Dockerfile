FROM centos:latest
LABEL author="Cheirsh" email="785427346@qq.com"
ENV REFRESHED_AT=2018-06-12

RUN curl https://setup.ius.io | sh
RUN yum update -y
RUN yum -y remove git | yum -y install git2u

RUN yum -y install java-1.8.0-openjdk java-1.8.0-openjdk-devel


# VOLUME [ "/data" ]
# WORKDIR /data

# ENTRYPOINT [ "java", "-jar" ]
# CMD [ "none.jar" ]
EXPOSE 8080
CMD [ "/bin/bash" ]