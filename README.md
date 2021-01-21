## snmp_mibs_files
One stop repository for over 12000+ MIBS files

## Why?
Recently, I play alot with network devices monitoring. I've use prometheus and telegraf to monitor multiple network devices. Finding the complete MIBS is really pain in the ass.
For example, using snmptraps input plugin from telegraf I still see errors in parsing the OIDs.

## Use case?
1. Telegraf [snmp](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/snmp "Telegraf snmp")
2. Telegraf [snmp_trap](https://github.com/influxdata/telegraf/tree/master/plugins/inputs/snmp_trap "Telegraf snmp_trap")
2. Prometheus [snmp_exporter](https://github.com/prometheus/snmp_exporter/tree/master/generator "snmp_exporter")

## Contributing?
Send a pull request with the missing MIBS