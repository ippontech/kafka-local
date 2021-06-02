# Run a local Kafka Cluster

Docker Compose configuration to run Kafka locally.

```bash
HOME=./ docker compose up
[+] Running 5/2
 ⠿ Network kafka-local_default      Created                                                                                                                3.3s
 ⠿ Container zookeeper              Created                                                                                                                0.1s
 ⠿ Container kafka-local_kafka-2_1  Created                                                                                                                0.1s
 ⠿ Container kafka-local_kafka-3_1  Created                                                                                                                0.1s
 ⠿ Container kafka-local_kafka-1_1  Created                                                                                                                0.1s
Attaching to kafka-1_1, kafka-2_1, kafka-3_1, zookeeper
zookeeper  | ===> User
zookeeper  | uid=0(root) gid=0(root) groups=0(root)
zookeeper  | ===> Configuring ...
```
