FROM tensorflow/tensorflow:1.4.1

RUN apt-get update && apt-get install -y apt-utils iftop net-tools iputils-ping dnsutils vim tcpdump && apt-get clean

COPY tf-distributed.py /workdir/
COPY mnist_data/ /workdir/mnist_data/ 
WORKDIR /workdir
