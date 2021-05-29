FROM	centos:8

RUN	dnf --enablerepo=powertools install -y \
	make \
	gcc-c++ \
	glibc-static \
	libstdc++-static \
	python3

WORKDIR	/root
CMD	bash
