# AWS Kinesis

The ability to ingest, process, and analyze real-time data enables companies to make quick data-driven decisions and react rapidly to changes. In we will look at how to implement a real-time streaming data pipeline using Amazon Kinesis.

## Overview of AWS Kinesis

`Amazon Kinesis` is a managed service provided by AWS for real-time data streaming. Kinesis provides capabilities to continuously capture and store terabytes of data per hour from hundreds of thousands of sources. The data can then be processed and analyzed in `real-time`.

## The main components of Kinesis are:

- `Kinesis Data Streams` — For ingesting `real-time` data from many sources. Data is stored in shards and retained for 24 hours by default.
- `Kinesis Data Firehose` — For loading streamed data into AWS data stores and analytics tools. It can capture, transform, and load data.
- `Kinesis Data Analytics` — For running SQL or `Apache Flink` code on streaming data to perform real-time analytics.