# aggregator-service

```shell script
docker run --tty --rm \
    --network dev-env_4pet-net \
    debezium/tooling:1.1 \
    kafkacat -b broker:9092 -C -o beginning -q \
    -t customers-with-addresses
```


<!-- INSPIRATIONAL_QUOTE_START -->
> "Success is not how high you have climbed, but how you make a positive difference to the world." - Roy T. Bennett
<!-- INSPIRATIONAL_QUOTE_END -->
