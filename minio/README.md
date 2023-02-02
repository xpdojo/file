# MinIO

[Object Storage](https://min.io/docs/minio/linux/index.html)

MinIO is a high performance object storage solution
that provides an Amazon Web Services S3-compatible API
and supports all core S3 features.
MinIO is built to deploy anywhere -
public or private cloud, baremetal infrastructure,
orchestrated environments, and edge infrastructure.

## Run

```sh
mkdir -p ~/minio/data
```

```sh
sudo docker compose up -d
```

- [Core Administration Concepts](https://min.io/docs/minio/linux/administration/concepts.html)
- [Bucket Replication](https://min.io/docs/minio/linux/administration/bucket-replication.html)
- [Erasure Coding](https://min.io/docs/minio/linux/operations/concepts/erasure-coding.html)
