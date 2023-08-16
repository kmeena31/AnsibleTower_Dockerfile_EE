FROM registry.access.redhat.com/ubi8/ubi:latest
RUN yum -y update
RUN yum -y install python3 python3-pip git
RUN pip3 install --upgrade pip setuptools
#RUN pip3 install ansible
RUN pip3 install --upgrade git+https://github.com/vmware/vsphere-automation-sdk-python.git
#RUN pip3 install --upgrade git+https://github.com/vmware/vsphere-automation-sdk-python/releases/tag/v7.0.3.0
RUN pip3 install virtualenv pyvmomi requests urllib3 wheel lxml pywinrm requests-credssp
RUN pip3 install ansible
RUN cat /etc/os-release
