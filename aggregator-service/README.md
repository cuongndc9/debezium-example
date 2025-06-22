# aggregator-service

```shell script
docker run --tty --rm \
    --network dev-env_4pet-net \
    debezium/tooling:1.1 \
    kafkacat -b broker:9092 -C -o beginning -q \
    -t customers-with-addresses
```


<!-- INSPIRATIONAL_QUOTE_START -->
> "People who are crazy enough to think they can change the world, are the ones who do." - Rob Siltanen
<!-- INSPIRATIONAL_QUOTE_END -->
