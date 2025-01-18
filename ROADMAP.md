# Roadmap

- [x] Overview Documentation
  - [x] README
  - [x] Diagram
- [ ] Setup
  - [x] Kafka
  - [x] Hadoop
  - [x] PostgreSQL
  - [ ] Spark
- [x] Kafka feed
  - [x] Stream data from the [IBM Transactions for AML](https://www.kaggle.com/datasets/ealtman2019/ibm-transactions-for-anti-money-laundering-aml) dataset
- [x] Data ingestion through Spark
  - [x] Extract from Kafka stream
  - [x] Load raw data to Hadoop
  - [x] Transform and Load Fact tables to PostgreSQL
  - [x] Validate data with Great Expectations

## Playground

- [x] Apply MapReduce with Hadoop
  - [x] Total inbound transaction money by account
  - [x] Total outbound transaction money by account
  - [x] Total inbound transaction money by bank
  - [x] Total outbound transaction money by bank
- [x] Apply MapReduce with Spark
  - [x] Total inbound transaction money by account
  - [x] Total outbound transaction money by account
  - [x] Total inbound transaction money by bank
  - [x] Total outbound transaction money by bank
  - [ ] Convert all currencies to EUR
- [ ] Use a Spark cluster to process data
