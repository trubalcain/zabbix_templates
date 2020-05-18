# zabbix_templates
Zabbix 5.x templates
Zbx_export_APC_RackPDU.xml -> APC Rack PDU (Basic items only, 3 Phase only, triggers: fail(load>HLoad) error(load >NHload, fail-dependant), info (load < LowLoad), graphs (stacked 3phase no legend), using {$SNMP_COMMUNITY} in items)
Zabbix_APC_Smart_UPS.xml -> APC SmartUPS 10000 (Ambient temperature, battery status, output/input load and frequency, device details and network interface status.)
Zbx_export_ITWatchdog.xml -> IT Watchdogs 100
