# Episode 1: Architecture Overview

- API -> DynamoDB -> DynamoDB Streams -> Lambda -> Kinesis -> 3rd party integration (transactional)
- DynamoDB -> EMR (Hive, Spark) -> S3 (data export)
- S3 -> SparkSQL analysis (analytical)
- S3 -> Redshift (analytical)



todos:

- make diagram
- do a draft recording

