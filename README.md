# AWS Kinesis minitoring datsource for Grafana

This is Grafana Data Source Backend Plugin. Backend part is written in Go lang.

## Basics

AWS Kinesis Data Streams basic monitoring can be performed with CludWatch metrics:
https://docs.aws.amazon.com/streams/latest/dev/monitoring-with-cloudwatch.html

Amazon Kinesis Data Streams and Amazon CloudWatch are integrated so that you can collect, view, and analyze CloudWatch metrics for your Kinesis data streams.

## Advanced monitoring

This plugin uses AWS SDK for Go lang: https://github.com/aws/aws-sdk-go

Additional data about Kinesis service state retrieved with:

 * DescribeStreamSummary
 * ListShards
 * ListStreamConsumers
 * ListStreams

## Bug reports

This plugin is my pet project, I do in free time.

If you have suggestions to improve - please make a pull request or post an issue:
https://github.com/vsergeyev/aws-kinesis/issues

Thank you!
