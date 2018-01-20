## ELK by Sowa


### Requeriments

```
# Oracle Java 8 (Oracle JDK version 1.8.0_73 onwards) should be installed.

1. Add Oracle Java PPA (Personal Package Archive) to apt repository list:

sudo add-apt-repository -y ppa:webupd8team/java

2. Update the apt package database to include all the latest files under the packages:

sudo apt-get update

3. Install the latest version of Oracle Java 8:

sudo apt-get -y install oracle-java8-installer

4. To check whether Java has successfully installed, type the following command
into the terminal:

java -version

```




### Start ELK Stack

- Open config/kibana.yml in an editor
- Set elasticsearch.url to point at your Elasticsearch instance





```markdown
1.From Terminal 1

Run `bin/elasticsearch` (http://localhost:9200)


2.From Terminal 2

Run `bin/kibana` (http://localhost:5601)


3.From Terminal 3

Run `bin/logstash -f logstash.conf` 



***optional***
-Run Grafana [more info](https://grafana.com/) 

4.From Terminal 4

Run `bin/grafana-server`  (localhost:3000  admin/admin) 

```



### Support or Contact

Having trouble with this distribution ? [contact support](mailto:info@sowa.io) and we’ll help you sort it out.
