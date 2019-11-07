# loki-example-with-local-s3-dynamodb

This repository contains a configuration example to run Grafana [Loki](https://grafana.com/oss/loki/) with
[s3mock](https://github.com/adobe/S3Mock) and [dynamodb-local](https://hub.docker.com/r/amazon/dynamodb-local).

## Getting Started

```bash
docker-compose up
```

You can access... 

- Grafana at http://localhost:3000/explore to explore logs.
- DynamoDB Admin at http://localhost:7777.

