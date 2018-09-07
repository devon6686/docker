FROM local/centos:6.10

ENV JDK_VERSION=1.8.0_144
ADD jdk-8u144-linux-x64.tar.gz /usr/local/
ADD java.sh /etc/profile.d/java.sh
LABEL centos version = 6.10\
     jdk version = $JDK_VERSION

RUN source /etc/profile.d/java.sh
CMD ["/bin/bash"]
