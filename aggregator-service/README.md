# aggregator-service

```shell script
docker run --tty --rm \
    --network dev-env_4pet-net \
    debezium/tooling:1.1 \
    kafkacat -b broker:9092 -C -o beginning -q \
    -t customers-with-addresses
```


<!-- INSPIRATIONAL_QUOTE_START -->
![Image](https://github.com/user-attachments/assets/0e3d9ba0-f624-4a99-8a33-88703033a2a1)
<!-- INSPIRATIONAL_QUOTE_END -->
