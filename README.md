## Project Overview
<img src="https://i.imgur.com/ZoWcqw6.png"  alt="img"/>

## Order Service
<img src="https://i.imgur.com/MYeTsZf.png"  alt="img"/>

## Order Service Logic Bussiness
<img src="https://i.imgur.com/Ji3r50n.png"  alt="img"/>


## TASK
docker-compose -f common.yml -f zookeeper.yml up
$env:KAFKA_VERSION="5.5.1"
docker-compose -f common.yml -f init_kafka.yml up
docker-compose -f common.yml -f kafka_cluster.yml up 