Master thesis new Kibana 4.3 Vagrant 
=======================

You need to install VirtualBox and Vagrant, than download or clone th

Installation
------------

Go to folder where you have downloaded Vagrant file and enter "vagrant up"

To destroy run "Vagrant destroy"

You can now access updated Kibana 4.3 (or ElasticSearch directly, if you need to):

| Service       | Address                                 |
|---------------|-----------------------------------------|
| Kibana 4      | [localhost:5601](http://localhost:5601) |
| ElasticSearch | [localhost:9200](http://localhost:9200) |

Data
-----------
Some data are loaded to ElasticSearch as an example. Take in mind, that they are only raw data without mapping etc.. It means that this data do not have to have real meaning.

To see data in Kibana you have to configure an index pattern. This site is displayed after first run of Kibana. Simple enter word "bank" to text field and push "Create" with all checkboxes unchecked.