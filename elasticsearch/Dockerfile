FROM docker.elastic.co/elasticsearch/elasticsearch-oss:6.1.0

RUN yum install -y  epel-release \
    && yum install -y  nodejs \
    && npm install elasticdump -g
