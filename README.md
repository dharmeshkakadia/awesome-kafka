# awesome-kafka
Everything about Apache Kafka

Share your Kafka ❤️ through pull requests :)

What can you expect to see here?

* [Development](#development)
  * [Client libraries](#client-libraries)
  * [Kafka Streams libraries](#kafka-streams-libraries)
  * [KSQL](#ksql)
  * [Connectors](#connectors)
  * [Producers](#producers)
  * [Consumers](#consumers)
  * [Transformations](#transformations)
  * [Testing](#testing)
* [Operations](#operations)
  * [Operational Utilities](#operational-utilities)
  * [Monitoring](#monitoring)
  * [Performance tools](#performance-tools)
  * [Security](#security)
  * [Audit](#audit)
  * [Mirroring](#mirroring)
  * [Backup](#backup)
  * [Tools](#tools)
  * [Metadata Management](#metadata-management)
  * [Schema Management](#schema-management)
  * [UI](#ui)
* [Deployment](#deployment)
  * [Kubernetes](#kubernetes)
  * [Docker](#docker)
  * [Integrations](#integrations)
  * [Alternative Implementations](#alternative-implementations)
* [Unsorted](#unsorted)


## Development

### Client libraries

* [Go](https://github.com/Shopify/sarama)
* [Go](https://github.com/jdamick/kafka)
* [Go](https://github.com/optiopay/kafka)
* [Go Kafka streaming](https://github.com/lovoo/goka)
* [Node](https://github.com/oleksiyk/kafka)
* [Node](https://github.com/nodefluent/node-sinek)
* [Node Kafka streams](https://github.com/nodefluent/kafka-streams)
* [Node librdkafka](https://github.com/nodefluent/node-rdkafka)
* [Php](https://github.com/weiboad/kafka-php)
* [Php](https://github.com/arnaud-lb/php-rdkafka)
* [Perl](https://github.com/TrackingSoft/Kafka)
* [Python](https://github.com/Parsely/pykafka)
* [Ruby](https://github.com/zendesk/ruby-kafka)
* [Phobos - Ruby App framework](https://github.com/klarna/phobos)
* [Karafka - Ruby and Rails framework](https://github.com/karafka/karafka)
* [Dart](https://github.com/dart-kafka/kafka)
* [JRuby](https://github.com/joekiller/jruby-kafka)
* [Elixir](https://github.com/kafkaex/kafka_ex)
* [Erlang](https://github.com/klarna/brod)
* [Rust](https://github.com/spicavigo/kafka-rust)
* [LinkedIn wrapper library](https://github.com/linkedin/li-apache-kafka-clients)
* [kasper - a lightweight library for processing Kafka topics](https://github.com/movio/kasper)
* and [others](https://cwiki.apache.org/confluence/display/KAFKA/Clients)

### Kafka Streams Libraries 
* [Scala](https://github.com/lightbend/kafka-streams-scala)
* [faust - Python Stream Processing](https://github.com/robinhood/faust)
* [Southpaw - Streaming left joins for data change capture](https://github.com/jwplayer/southpaw)

### KSQL
* [KSQL JDBC Driver](https://github.com/mmolimar/ksql-jdbc-driver)
* [KSQL Addon - User Defined Function (UDF) for Machine Learning](https://github.com/kaiwaehner/ksql-machine-learning-udf)

### Connectors 

* [JDBC](https://github.com/confluentinc/kafka-connect-jdbc)
* [Elasticsearch](https://github.com/confluentinc/kafka-connect-elasticsearch)
* [HDFS](https://github.com/confluentinc/kafka-connect-hdfs)
* [BigQuery](https://github.com/nodefluent/bigquery-kafka-connect)
* [SQL](https://github.com/nodefluent/sequelize-kafka-connect)
* [GCloud pubsub](https://github.com/nodefluent/gcloud-pubsub-kafka-connect)
* [BigTable](https://github.com/nodefluent/bigtable-kafka-connect)  
* [Google Cloud Storage (GCS)](https://github.com/aiven/aiven-kafka-connect-gcs)
* [HBase](https://github.com/mravi/kafka-connect-hbase)
* [FileSystem](https://github.com/mmolimar/kafka-connect-fs)
* [Streaming files from a local filesystem](https://github.com/streamthoughts/kafka-connect-file-pulse)
* [kafka-connect-protobuf-converter](https://github.com/blueapron/kafka-connect-protobuf-converter)
* [IBM MQ Source](https://github.com/ibm-messaging/kafka-connect-mq-source)
* [IBM MQ Sink](https://github.com/ibm-messaging/kafka-connect-mq-sink)
* [Azure IoT Hub](https://github.com/Azure/toketi-kafka-connect-iothub)
* [Pulsar](https://github.com/streamnative/pulsar-io-kafka)


### Producers
* [Maxwell's daemon - a mysql-to-json kafka producer](https://github.com/zendesk/maxwell)

### Consumers
* [Spark](https://github.com/dibbhatt/kafka-spark-consumer)
* [Storm](http://storm.apache.org/)
* [Mapreduce](https://github.com/Conductor/kangaroo)

### Transformations
* [Single Message Transformations (SMT)](https://github.com/aiven/aiven-kafka-connect-transforms)

### Testing
* [Mocked Streams - Topology testing library for Kafka Streams (no broker required)](https://github.com/jpzk/mockedstreams)
* [Unit-testing for embedded kafka services](https://github.com/Landoop/kafka-testing)
* [Synthetic avro message generator for Kafka](https://github.com/Landoop/landoop-avro-generator)
* [Kafka JUnit](https://github.com/salesforce/kafka-junit)
* [Kafka Unit](https://github.com/chbatey/kafka-unit)
* [Kafka for JUnit](https://github.com/mguenther/kafka-junit)
* [embedded-kafka - in-memory Kafka instance to run your tests against](https://github.com/embeddedkafka/embedded-kafka)

<!--- ### Managed Services  -->
## Operations

### Operational Utilities
* [Cruise control](https://github.com/linkedin/cruise-control)
* [DoctorKafka](https://github.com/pinterest/doctorkafka/)
* [Brucke - Inter-cluster bridge of kafka topics](https://github.com/klarna/brucke)
* [Kafka-Kit](https://github.com/DataDog/kafka-kit)
* [Secor - service for persisting Kafka logs](https://github.com/pinterest/secor)
* [kafkabalancer](https://github.com/CAFxX/kafkabalancer)
* [Yelp Kafka-Utils](https://github.com/Yelp/kafka-utils)
* [Cerner Common Kafka utilities](https://github.com/cerner/common-kafka)
* [connectctl - manage kafka connect connectors easily](https://github.com/90poe/connectctl)

### Monitoring
* [Kafka Offset Exporter](https://github.com/echojc/kafka-offset-exporter)
* [Fluent plugin](https://github.com/fluent/fluent-plugin-kafka)
* [Burrow - Kafka Consumer Lag Checking](https://github.com/linkedin/Burrow)
* [Remora](https://github.com/zalando-incubator/remora)
* [Kafka Offset Monitoring](https://github.com/Morningstar/kafka-offset-monitor)
* [kafka-eagle](https://github.com/smartloli/kafka-eagle)
* [Kafka-prometheus](https://github.com/streamthoughts/kafka-monitoring-suite-demo-prometheus)
* [Consumer lag monitoring](https://github.com/omarsmak/kafka-consumer-lag-monitoring)

### Performance tools
* [sangrenel](https://github.com/jamiealquiza/sangrenel)

### Security
* [Kafka Security Manager](https://github.com/simplesteph/kafka-security-manager)

### Audit
* [chaperone - A Kafka audit system](https://github.com/uber/chaperone)

### Mirroring
* [MirrorMaker](https://cwiki.apache.org/confluence/pages/viewpage.action?pageId=27846330)
* [uReplicator](https://github.com/uber/uReplicator)
* [MirrorTool for Kafka Connect](https://github.com/Comcast/MirrorTool-for-Kafka-Connect)
* [Mirus](https://github.com/salesforce/mirus)

### Backup
* [Backup and Restore topics & offsets](https://github.com/itadventurer/kafka-backup)

### Tools

* [REST-proxy](https://github.com/confluentinc/kafka-rest)
* [Kafka-Pixy - gRPC/REST Proxy](https://github.com/mailgun/kafka-pixy)
* [Kafka Proxy providing SASL/PLAIN authentication and SSL](https://github.com/grepplabs/kafka-proxy)
* [Reactive/Akka API](https://github.com/akka/reactive-kafka)
* [kafkat](https://github.com/airbnb/kafkat)
* [kt](https://github.com/fgeller/kt)
* [kafka-connect-tools](https://github.com/datamountaineer/kafka-connect-tools)
* [Node Kafka connect](https://github.com/nodefluent/kafka-connect)
* [Kafka-monitor](https://github.com/linkedin/kafka-monitor)
* [Kafka Auto completion](https://github.com/Landoop/kafka-autocomplete)
* [Kafka Cheet Sheet](https://github.com/Landoop/kafka-cheat-sheet)
* [Kafka Write Protocol encoder/decoder](https://github.com/klarna/kafka_protocol)
* [Winton Kafka Streams](https://github.com/wintoncode/winton-kafka-streams)
* [Spring-kafka](https://github.com/spring-projects/spring-kafka)
* [Maven quick start for Kafka Connect connectors](https://github.com/jcustenborder/kafka-connect-archtype)
* [Trifecta](https://github.com/ldaniels528/trifecta)
* [Kafka Specs](https://github.com/streamthoughts/kafka-specs)

### Metadata Management
* [Go library for Kafka metadata in Zookeeper](https://github.com/wvanbergen/kazoo-go)

### Schema Management
* [Schema registry](https://github.com/confluentinc/schema-registry)
* [Node Schema registry](https://github.com/nodefluent/schema-registry)
* [Schema Registry Transfer SMT](https://github.com/cricket007/schema-registry-transfer-smt)
* [Expedia Stream Registry](https://github.com/ExpediaGroup/stream-registry)

### UI
* [kafka-manager](https://github.com/yahoo/kafka-manager)
* [Kafka HQ](https://github.com/tchiotludo/kafkahq)
* [Kafdrop 3.x](https://github.com/obsidiandynamics/kafdrop) – web UI for Kafka. For versions older than 0.10.0 use [Kafdrop 2.x](https://github.com/HomeAdvisor/Kafdrop).
* [Kafka Webview](https://github.com/SourceLabOrg/kafka-webview)
* [Kafka Topics UI](https://github.com/Landoop/kafka-topics-ui)
* [Kafka Connect UI](https://github.com/Landoop/kafka-connect-ui)
* [Kafka Schema UI](https://github.com/Landoop/schema-registry-ui)
* [Kafkawize - self service topic management portal](https://github.com/muralibasani/kafkawize)
* [Kadmin - Kafka Producer/Consumer UI](https://github.com/BetterCloud/kadmin)

## Deployment

### Kubernetes
* [Kafka k8s operator](https://github.com/krallistic/kafka-operator)
* [Strimzi](https://github.com/strimzi/strimzi-kafka-operator) Operator for deploying and running Apache Kafka on Kubernetes

### Docker 
* [fast-data-dev](https://github.com/Landoop/fast-data-dev)

### Integrations

* [Ecosystem](https://cwiki.apache.org/confluence/display/KAFKA/Ecosystem)
* [asyncio](https://github.com/aio-libs/aiokafka)
* [hermes](https://github.com/allegro/hermes)
* [IBMStreams](https://github.com/IBMStreams/streamsx.kafka)

## Alternative Implementations

* [Go](https://github.com/travisjeffery/jocko)
* [C/C++](https://github.com/edenhill/librdkafka)

## Unsorted

* https://github.com/Landoop/kafka-connect-kcql-smt
* https://github.com/Landoop/kafka-addons
* https://github.com/nodefluent/purpur
* [Azkarra Streams - lightweight java framework which makes easy to create production-ready Kafka Streams applications](https://github.com/streamthoughts/azkarra-streams)
