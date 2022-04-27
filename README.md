# kafka `(data bus)`

## Concept
- [zookeeper](zookeeper) : coodinator to manage a metadata
- [broker](broker) : server or node that installed kafka application
- topic : divide message pid
  - [partition](partition) : divide one of topic to serveral
  - [replication-factor](replication-factor) : copy count of topic
  - [segment](segment) : log file of partition
- client
  - [producer](producer) : create message and send
    - [partitioner](partitioner) : 
      - [stickyPartitioning](stickyPartitioning) :
  - [consumer](consumer) : select message and use
- [segment](segment) : file that saved message to local disk of broker
- [message](message) : data piece or record
- [page-cache](page-cache) : usage physics memory
- replication
  - [factor](factor) :
  - [leader](leader) :
  - [follower](follower) :
  - [leaderEpoch](leaderEpoch) :
  - [highWaterMark](highWaterMark) :
  - [controller](controller) : 
- [schema-registry](schema-registry) :
- kafka-connect
  - [source-connect](source-connect) :
  - [sink-connect](sink-connect) :
