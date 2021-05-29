FROM	centos:6.6

RUN	sed -e 's/^mirror/#mirror/g'             \
	    -e 's/^#base/base/g'                 \
	    -e 's/mirror\.centos/vault.centos/g' \
	    -i /etc/yum.repos.d/CentOS-Base.repo

RUN	yum update  -y &&\
	yum install -y gcc-c++

WORKDIR	/root
CMD	bash
