# aggregator-service

```shell script
docker run --tty --rm \
    --network dev-env_4pet-net \
    debezium/tooling:1.1 \
    kafkacat -b broker:9092 -C -o beginning -q \
    -t customers-with-addresses
```


<!-- INSPIRATIONAL_QUOTE_START -->
<p>🇻🇳</p>
![Image](https://github.com/user-attachments/assets/9d3847b4-d01e-4e62-b18e-12706b955cf3)
<!-- INSPIRATIONAL_QUOTE_END -->
