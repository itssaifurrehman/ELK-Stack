# ELK-Stack
All the necessary files needed to learn ELK Stack on linux

This is the project, i used to learn complete ELK stack. It contains 3 major files

Logstash with version: 7.5.0
(https://www.elastic.co/downloads/logstash)

Elasticsearch with version:7.5.0
(https://www.elastic.co/downloads/elasticsearch)

Kibana with version: 7.5.0
(https://www.elastic.co/downloads/kibana)

Download all these tools and extract them on your machine. To run this successfully on your linux machine, you need to have a log file(with .log extension) and give its path in logstash configuration(logstash.conf) file and paste this configuration file into /logstash folder.

Open three different terminal tabs and open each folder in each tab like elasticsearch, kibana and logstash
First Run bin/elasticsearch, then after successfully starting the elasticsearch go to kibana and run bin/kibana. After that go to Logstash folder and run "bin/logstash -f logstash.conf" this command.

I have also added an example json file(products-bulk.json) for practicing the queries and the queries which I used to learn this project. The queries are of Kibana which when you run the kibana, go to Dev Tools and use them there.