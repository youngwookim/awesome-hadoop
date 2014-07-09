# Awesome Hadoop

A curated list of amazingly awesome Hadoop and Hadoop ecosystem resources. Inspired by [Awesome PHP](https://github.com/ziadoz/awesome-php), [Awesome Python](https://github.com/vinta/awesome-python) and [Awesome Sysadmin](https://github.com/kahun/awesome-sysadmin)

- [Awesome Hadoop](#awesome-hadoop)
	- [Hadoop](#hadoop)
	- [HBase](#hbase)
	- [SQL on Hadoop](#sql-on-hadoop)
	- [Workflow](#workflow)
	- [Data Ingestion and Integration](#data-ingestion-and-integration)
	- [DSL](#dsl)
	- [Libraries and Tools](#libraries-and-tools)
	- [Realtime Data Processing](#realtime-data-processing)
	- [Packaging, Provisioning and Monitoring](#packaging-provisioning-and-monitoring)
	- [Monitoring](#monitoring)
	- [Benchmark](#benchmark)
- [Resources](#resources)
	- [Websites](#websites)
	- [Books](#books)

## Hadoop
*HDFS, MapReduce and YARN*

* [Apache Hadoop](http://hadoop.apache.org/) - Apache Hadoop
* [dumbo](https://github.com/klbostee/dumbo) - Python module that allows you to easily write and run Hadoop programs.
* [Apache Twill](http://twill.incubator.apache.org/)
* [Apache Tez](http://tez.incubator.apache.org/)
* [Apache Spark](http://spark.apache.org/)
* [Apache Falcon](http://falcon.incubator.apache.org/) - Data management and processing platform
* [SpatialHadoop](http://spatialhadoop.cs.umn.edu/) - SpatialHadoop is a MapReduce extension to Apache Hadoop designed specially to work with spatial data. 
* [GIS Tools for Hadoop](http://esri.github.io/gis-tools-for-hadoop/) - Big Data Spatial Analytics for the Hadoop Framework
* [Elasticsearch Hadoop](https://github.com/elasticsearch/elasticsearch-hadoop) - Elasticsearch real-time search and analytics natively integrated with Hadoop. Supports Map/Reduce, Cascading, Apache Hive and Apache Pig.
* [hadoopy](https://github.com/bwhite/hadoopy) - Python MapReduce library written in Cython. 
* [mrjob](https://github.com/Yelp/mrjob/) - mrjob is a Python 2.5+ package that helps you write and run Hadoop Streaming jobs.
* [pydoop](http://pydoop.sourceforge.net/) - Pydoop is a package that provides a Python API for Hadoop.
* [hdfs-du](https://github.com/twitter/hdfs-du) - HDFS-DU is an interactive visualization of the Hadoop distributed file system. 

## HBase
**

* [Apache HBase](http://hbase.apache.org) - Apache HBase
* [Apache Phoenix](http://phoenix.apache.org/) - A SQL skin over HBase
* [happybase](https://github.com/wbolster/happybase) - A developer-friendly Python library to interact with Apache HBase.
* [Hannibal](https://github.com/sentric/hannibal) - Hannibal is tool to help monitor and maintain HBase-Clusters that are configured for manual splitting.
* [Haeinsa](https://github.com/VCNC/haeinsa) - Haeinsa is linearly scalable multi-row, multi-table transaction library for HBase
* [hindex](https://github.com/Huawei-Hadoop/hindex) - Secondary Index for HBase

## SQL on Hadoop
*SQL on Hadoop*

* [Apache Hive](http://hive.apache.org)
* [Impala](https://github.com/cloudera/impala)
* [Presto](http://prestodb.io/)
* [Apache Tajo](http://tajo.apache.org/)
* Hive Plugins
 * UDF
  * http://nexr.github.io/hive-udf/
  * https://github.com/edwardcapriolo/hive_cassandra_udfs
  * https://github.com/livingsocial/HiveSwarm
  * https://github.com/ThinkBigAnalytics/Hive-Extensions-from-Think-Big-Analytics
  * https://github.com/karthkk/udfs
  * https://github.com/kevinweil/elephant-bird - Twitter
  * https://github.com/lovelysystems/ls-hive
  * https://github.com/stewi2/hive-udfs
  * https://github.com/klout/brickhouse
  * https://github.com/markgrover/hive-translate (PostgreSQL translate())
  * https://github.com/deanwampler/HiveUDFs
  * https://github.com/myui/hivemall (Machine Learning UDF/UDAF/UDTF)
  * https://github.com/edwardcapriolo/hive-geoip (GeoIP UDF)
 * Storage Handler
  * https://github.com/dvasilen/Hive-Cassandra
  * https://github.com/yc-huang/Hive-mongo
  * https://github.com/balshor/gdata-storagehandler
  * https://github.com/karthkk/hive-hbase-json
  * https://github.com/sunsuk7tp/hive-hbase-integration
  * https://bitbucket.org/rodrigopr/redisstoragehandler
  * https://github.com/zhuguangbin/HiveJDBCStorageHanlder
  * https://github.com/chimpler/hive-solr
  * https://github.com/bfemiano/accumulo-hive-storage-manager
 * SerDe
  * https://github.com/rcongiu/Hive-JSON-Serde
  * https://github.com/mochi/hive-json-serde
  * https://github.com/ogrodnek/csv-serde
  * https://github.com/parag/HiveJsonSerde
  * https://github.com/johanoskarsson/hive-json-serde
  * https://github.com/electrum/hive-serde - JSON
  * https://github.com/karthkk/hive-hbase-json
 * Libraries
  * https://github.com/forward/rbhive
  * https://github.com/synctree/activerecord-hive-adapter
  * https://github.com/hrp/sequel-hive-adapter
  * https://github.com/forward/node-hive
  * https://github.com/recruitcojp/WebHive
  * [shib](https://github.com/tagomoris/shib) - WebUI for query engines: Hive and Presto
  * [clive](https://github.com/bmuller/clive) - Clojure library for interacting with Hive via Thrift
  * https://bitbucket.org/vadim/hive-sharp
  * http://www.phphiveadmin.net/
  * https://github.com/anjuke/hwi
  * https://code.google.com/a/apache-extras.org/p/hipy/
  * https://github.com/dmorel/Thrift-API-HiveClient2 (Perl - HiveServer2)
  * [PyHive](https://github.com/dropbox/PyHive) - Python interface to Hive and Presto
  * https://github.com/recruitcojp/OdbcHive
  * [Hive-Sharp](https://bitbucket.org/vadim/hive-sharp)

## Workflow

* [Apache Oozie](http://oozie.apche.org) - Apache Oozie
* [Azkaban](http://azkaban.github.io/)

## Data Ingestion and Integration

* [Apache Flume](http://flume.apache.org) - Apache Flume
* [Apache Sqoop](http://sqoop.apache.org) - Apache Sqoop
* [Apache Kafka](http://kafka.apache.org/) - Apache Kafka
* Flume Plugins
 * [Flume MongoDB Sink](https://github.com/leonlee/flume-ng-mongodb-sink)
 * (https://github.com/btoddb/flume-ng-hornetq-channel)
 * (https://github.com/leonlee/flume-ng-msgpack-source)
 * (https://github.com/jcustenborder/flume-ng-rabbitmq)
 * [Flume UDP Source](https://github.com/whitepages/flume-udp-source)
 * [Stratio Ingestion](https://github.com/Stratio/stratio-ingestion) - Custom sinks: Cassandra, MongoDB, Stratio Streaming and JDBC
 * (https://github.com/relistan/flume-serializers)
 * (https://github.com/jrkinley/flume-interceptor-analytics)
 * [.Net FlumeNG Clients](https://github.com/marksl/DotNetFlumeNG.Clients)

## DSL
**

* [Apache Pig](http://pig.apache.org) - Apache Pig
* [Apache DataFu](http://datafu.incubator.apache.org/) - A collection of libraries for working with large-scale data in Hadoop
* [vahara](https://github.com/Ganglion/varaha) - Machine learning and natural language processing with Apache Pig
* [packetpig](https://github.com/packetloop/packetpig) - Open Source Big Data Security Analytics
* [akela](https://github.com/mozilla-metrics/akela) - Mozilla's utility library for Hadoop, HBase, Pig, etc.
* [seqpig](http://seqpig.sourceforge.net/) - Simple and scalable scripting for large sequencing data set(ex: bioinfomation) in Hadoop 
* [Lipstick](https://github.com/Netflix/Lipstick) - Pig workflow visualization tool. [Introducing Lipstick on A(pache) Pig](http://techblog.netflix.com/2013/06/introducing-lipstick-on-apache-pig.html)

## Libraries and Tools
**

* [Apache Crunch](http://crunch.apache.org)
* [Kite Software Development Kit](http://kitesdk.org/) - A set of libraries, tools, examples, and documentation
* [gohadoop](https://github.com/hortonworks/gohadoop) - Native go clients for Apache Hadoop YARN.
* [HUE](http://gethue.com/)
* [Zeppelin](http://zeppelin-project.org/)

## Realtime Data Processing

* [Apache Storm](https://storm.incubator.apache.org/)
* [Apache Samza](http://samza.incubator.apache.org/)

## Packaging, Provisioning and Monitoring

* [Apache Bigtop](http://bigtop.apache.org/) - Packaging and tests of the Apache Hadoop ecosystem 
* [Apache Ambari](http://ambari.apache.org/)
* [Ganglia Monitoring System](http://ganglia.sourceforge.net/)

## Benchmark
**

* [Big Data Benchmark](https://amplab.cs.berkeley.edu/benchmark/)
* [HiBench](https://github.com/intel-hadoop/HiBench)
* [Big-Bench](https://github.com/intel-hadoop/Big-Bench)
* [hive-benchmarks](https://github.com/yhuai/hive-benchmarks)
* [hive-testbench](https://github.com/cartershanklin/hive-testbench) - Testbench for experimenting with Apache Hive at any data scale.

# Resources
Various resources, such as books, websites and articles.

## Websites
*Useful websites and articles*

* [Hadoop Weekly](http://www.hadoopweekly.com/)
* [Hadoop 1.x vs 2](http://www.slideshare.net/RommelGarcia2/hadoop-1x-vs-2)
* [All you wanted to know about Hadoop, but were too afraid to ask: genealogy of elephants.](https://blogs.apache.org/bigtop/entry/all_you_wanted_to_know)
* [Introducing Apache Hadoop YARN](http://hortonworks.com/blog/introducing-apache-hadoop-yarn/)
* [Apache Hadoop YARN - Background and an Overview](http://hortonworks.com/blog/apache-hadoop-yarn-background-and-an-overview/)
* [Apache Hadoop YARN - Concepts and Applications](http://hortonworks.com/blog/apache-hadoop-yarn-concepts-and-applications/)
* [Apache Hadoop YARN - ResourceManager](http://hortonworks.com/blog/apache-hadoop-yarn-resourcemanager/)
* [Apache Hadoop YARN - NodeManager](http://hortonworks.com/blog/apache-hadoop-yarn-nodemanager/)
* [Hadoop Operations at LinkedIn](http://www.slideshare.net/allenwittenauer/2013-hadoopsummitemea)
* [Hadoop Performance at LinkedIn](http://www.slideshare.net/allenwittenauer/2012-lihadoopperf)
* [Hadoop and Big Data: Use Cases at Salesforce.com](http://blogs.developerforce.com/engineering/2013/03/hadoop-use-cases-at-salesforce-com.html)
* [Hadoop 24/7](http://www.slideshare.net/allenwittenauer/aw-apachecon2009-15342917)
* [Migrating to MapReduce 2 on YARN (For Users)](http://blog.cloudera.com/blog/2013/11/migrating-to-mapreduce-2-on-yarn-for-users/)
* [Migrating to MapReduce 2 on YARN (For Operators)](http://blog.cloudera.com/blog/2013/11/migrating-to-mapreduce-2-on-yarn-for-operators/)
* [An example Apache Hadoop Yarn upgrade](http://www.slideshare.net/mikejf12/an-example-apache-hadoop-yarn-upgrade)
* [Apache Hadoop In Theory And Practice](http://www.slideshare.net/AdamKawa/hadoop-intheoryandpractice)
* [What is Bigtop, and Why Should You Care?](https://blogs.apache.org/bigtop/entry/bigtop_and_why_should_you)
* [Hadoop - Distributions and Commercial Support](http://wiki.apache.org/hadoop/Distributions%20and%20Commercial%20Support)
* [Ganglia configuration for a small Hadoop cluster and some troubleshooting](http://hakunamapdata.com/ganglia-configuration-for-a-small-hadoop-cluster-and-some-troubleshooting/)

## Books
