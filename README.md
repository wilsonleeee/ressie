# Ressie SIEM Elastic plugin

<img src="./ressie.png" alt="Ressie" width="100px"> + 
<img src="http://www.emerce.nl/content/uploads/2016/10/elastic_stack.png" alt="Ressie" width="280px">



Ressie is open source SIEM component for ELK stack, it provides real time monitoring, alerting and threat analysis.

#### Note:
**This work is just SIEM proof of concept. Use at your own risk!**

#### Contains:
* MySql 5.7 - https://hub.docker.com/_/mysql/
* Postgres 9.5  - https://hub.docker.com/_/postgres/
* Ubuntu + Php 5.6 + Apache 2 
* Ubuntu + NodeJs
* Ubuntu + Python 2.7 + Django
* ElasticSearch 5 
* Logstash 5 
* Kibana 5

## Installation

### Requirements & Configuration

* Docker
* Docker-compose

Create and configure variables.env file based on variables.env.example

```
PostgreSQL settings

POSTGRES_USER=postgres
POSTGRES_PASSWORD=secret
PGDATA=/var/lib/postgresql/data/pgdata

MySQL settings
MYSQL_ROOT_PASSWORD=secret
MYSQL_DATABASE=databaseName
MYSQL_USER=databaseUser
MYSQL_PASSWORD=databaseSecret
```

## Usage

Run architecture

```
$ docker-composer up
```

Navigate to project root

```
$ cd ./ressie
```

Then run

```python
$ python -m project param1 param2

```
---
**Lovro Predovan**
2017
