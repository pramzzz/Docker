FROM centos
ENV ANSIBLE_HOST_KEY_CHECKING False
RUN yum install epel-release -y && \
    yum update -y && \
        yum install -y openssh-server openssh-clients net-tools && \
    yum install -y ansible
CMD /bin/bash