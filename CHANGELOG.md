# Changelog

## 1.1.0

Features:
* Adding resource IP Pool
* Adding resource IPv6 Pool 
* Adding resource DNS SMART
* Adding resource DNS Server
* Adding resource DNS Forward Zone (issue #21)
* Adding resource Application
* Adding resource Application Pool
* Adding resource Application Node
* Adding data source DNS SMART
* Adding data source IP Address
* Adding data source IP Pool
* Adding data source IP Subnet
* Adding data source IP Space

Fixes:
* Fixing data source DNS server
* Fixing issue with nested subnets (issue #14)
* Adding support of "space" parameter on DNS Zone (issue #16)

## 1.0.10

Features:
* data source DNS server

Quality:
* add acceptance tests and framework for subnet and datasource dns server
* review the return code and content for most of the calls to trap messages

## 1.0.8

Features:
* user management
* user group management

Quality:
* add acceptance tests and framework for user and user group

## 1.0.7

Fixes:
* mac address setup for IPv6 addresses was not using the proper field in the API

## 1.0.6

Features:
* mac address object management for IPv4 and IPv6

Fixes:
* vxlan support for SOLIDserver 7.0, not previous versions
* some formating for go linter
* small fixes on mac address manager

## 1.0.5

Features:
* adding Netmask attribute to Subnet resources
