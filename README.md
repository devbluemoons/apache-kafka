# kafka `(data bus)`

## Concept
- [zookeeper](zookeeper) : coodinator to manage a metadata
- [broker](broker) : server or node that installed kafka application
- client
  - [producer](producer) : create message and send
    - [partitioner](partitioner) : 
      - [stickyPartitioning](stickyPartitioning) :
  - [consumer](consumer) : select message and use
- [topic](topic) : divide message pid
- [partition](partition) : divide one of topic to serveral
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
