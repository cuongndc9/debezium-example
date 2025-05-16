# aggregator-service

```shell script
docker run --tty --rm \
    --network dev-env_4pet-net \
    debezium/tooling:1.1 \
    kafkacat -b broker:9092 -C -o beginning -q \
    -t customers-with-addresses
```

<!-- INSPIRATIONAL_QUOTE_START -->
Stay curious. Keep learning. Keep growing.
🧑‍💻
<!-- INSPIRATIONAL_QUOTE_END -->
