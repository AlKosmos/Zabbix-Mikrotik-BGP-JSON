# Zabbix-Mikrotik-BGP-JSON

The Zabbix Mikrotik BGP template for 4.0, which uses LLD, JSON, SSH for connection to Mikrotik router wihout externel scripts.

Inspired by:
https://share.zabbix.com/network_devices/mikrotik/mikrotik-bgp-lld#login-modal

The diferenses is this template uses one ssh connection for getting all parametrs through JSON.

This template requires changing macroses:
{$MIKROTIK_SSH_PASS}
{$MIKROTIK_SSH_PORT}
{$MIKROTIK_SSH_USER}

