# Spring_Data_Elasticsearch
Spring Data Elasticsearch 연동 및 테스트 작성하기


-- Docker 
$ docker pull docker.elastic.co/elasticsearch/elasticsearch:7.10.0
$ docker run -d -p 9200:9200 -p 9300:9300 -e "discovery.type=single-node"
