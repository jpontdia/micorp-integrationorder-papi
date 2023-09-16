# Salesforce Integration Order PAPI
![Powered by](https://img.shields.io/badge/Powered%20by-Mulesoft-535597.svg)
  ![Unit test](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/micorp-integrationorder-papi-ut.svg)
  ![Code coverage](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/micorp-integrationorder-papi-cc.svg)
  ![Build](https://github.com/jpontdia/micorp-integrationorder-papi/actions/workflows/build.yml/badge.svg)
  ![Build job](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/micorp-integrationorder-papi-wf.svg)
  ![Release](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/micorp-integrationorder-papi-re.svg)
  ![dev version](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/micorp-integrationorder-papi-dev.svg)
  ![dev test](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/micorp-integrationorder-papi-dev-test.svg)
  ![tst version](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/micorp-integrationorder-papi-tst.svg)
  ![tst test](https://gist.githubusercontent.com/jpontdia/2f22ca2ddf1ba473d6e2cff61cc2fba9/raw/micorp-integrationorder-papi-tst-test.svg)  
<br>

Mulesoft service for exporting orders from the Corporate Orders System to Salesforce.

  > This project follows the standards defined in the Development Process Document in Anypoint Exchange

## Table of contents
1. [Description](#description) 
1. [Configuration](#configuration)

## Description
Mulesoft service for exporting orders from the Corporate Orders System to Salesforce. The next diagram shows the architecture of the service:

![architecture](https://github.com/jpontdia/micorp-integrationorder-papi/raw/main/docs/architecture.png)

<br>

## Configuration



| Property                  | Description               |
| ------------------------- | ------------------------- |
| customer.host     | Customer SAPI Host                     |
| customer.port     | Customer SAPI Port                     |
| customer.protocol | Customer SAPI protocol: http or https  |
| customer.basepath | Customer SAPI base path, example: /api |
| order.host        | Order SAPI Host                        |
| order.port        | Order SAPI Port                        |
| order.protocol    | Order SAPI protocol: http or https     |
| order.basepath    | Order SAPI base path, example: /api    |
| item.host         | Item SAPI Host                         |
| item.port         | Item SAPI Port                         |
| item.protocol     | Item SAPI protocol: http or https      |
| item.basepath     | Item SAPI base path, example: /api     |

<br>

---

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
- [Mulesoft Documentation](https://docs.mulesoft.com/general/)