# MonitorSG

Uses AWS Config Custom rule (Guard) to monitor security groups that don't have specific port ranges & CIDR open

Tested using Zabbix

## run 
`aws configservice put-config-rule --config-rule file://security_group_config_rule.json`
