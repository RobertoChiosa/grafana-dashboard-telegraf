# Telegraf Dashboard for Grafana

This is the grafana version of the Telegraf metrics monitoring template for Influxdb available [here](https://github.com/influxdata/community-templates/tree/master/telegraf).

## Prerequisites
This templates assumes that you already set up
* An InfluxDB instance
* A bucket named `Telegraf` with 7 days retention
* A Telegraf `config` plugin for internal metrics collection and InfluxDB v2 output

Details about the setup instruction can be found [here](https://github.com/influxdata/community-templates/tree/master/telegraf)

## Metrics collected
Key Telegraf monitoring metrics to monitor
Some of the most important Telegraf monitoring metrics that you should proactively monitor include:

* Number of metrics collected
* Metrics collected vs written per second
* Metrics gathered per input per minute
* Write buffer size
* Memory Allocations
* Metrics written
* Input plugin errors
* Errors per input
* Errors per output
* Garbage collection

## Installation
Go to Grafana Dashboard and download the raw json file 


## References
* [Telegraf Dashboard](https://github.com/influxdata/community-templates/tree/master/telegraf)
* [Telegraf Monitoring Template](https://www.influxdata.com/influxdb-templates/telegraf-monitor/)
