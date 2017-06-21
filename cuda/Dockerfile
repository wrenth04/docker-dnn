FROM nvidia/cuda
MAINTAINER Phil Huang <wrenth04@gmail.com>
RUN apt-get -y update && \
  apt-get -y install python python-pip vim wget curl openssh-client
RUN pip install --upgrade pip && \
  pip install "ipython[notebook]"

