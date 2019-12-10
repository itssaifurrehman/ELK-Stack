# ELK-Stack 
All the necessary files needed to learn ELK Stack on Linux.

This is the project, I used to learn complete ELK stack. It contains 3 major files:
Logstash with version: 7.5.0 (https://www.elastic.co/downloads/logstash)

Elasticsearch with version:7.5.0 (https://www.elastic.co/downloads/elasticsearch)

Kibana with version: 7.5.0 (https://www.elastic.co/downloads/kibana)

Download all these tools and extract them on your machine. To run this successfully on your Linux machine, you need to have a log file(with .log extension), give its path in logstash configuration file (logstash.conf) and paste this configuration file into /logstash folder.
Open three different terminal tabs and open each tool's folder in each tab like elasticsearch, kibana and logstash. First, run bin/elasticsearch. When elasticsearch is started, switch tab to Kibana and run bin/kibana on the terminal. After that, go to Logstash folder and run "bin/logstash -f logstash.conf" command from the terminal.

An example of JSON File(products-bulk.json) is added to the project for practicing the queries of Kibana. Kibana queries are also added to the project. To run these queries, go to kibana(http://localhost:5601/) and locate the dev tools icon at the left bottom of the webpage and run the queries there. You can locate to Elasticsearch at (http://localhost:9200/) and logstash at(http://localhost:9201/)  by default.