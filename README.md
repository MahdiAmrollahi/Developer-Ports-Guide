# 🔌 Dev & DevOps Ports Reference
> A comprehensive collection of ports, tools, and useful commands for developers, DevOps engineers, and system administrators

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg)
![Made with ❤️](https://img.shields.io/badge/made%20with-%E2%9D%A4-red)

## 📖 Table of Contents
- [Development Tools](#development-tools)
- [Databases](#databases)
- [Web Servers](#web-servers)
- [Docker & Kubernetes](#docker--kubernetes)
- [Monitoring](#monitoring)
- [Message Queues](#message-queues)
- [RabbitMQ Details](#rabbitmq---complete-details)
- [Testing Tools](#testing-tools)
- [Security Tools](#security-tools)
- [CI/CD](#cicd)
- [DevOps Tools](#devops-tools)
- [Data Processing & Workflow Tools](#data-processing--workflow-tools)
- [Apache Tools](#apache-tools)
- [Log Management](#log-management)
- [System Ports](#system-ports)
- [Useful Commands](#useful-commands)

## Development Tools

| Tool | Default Port | Alternative Ports | Run Command | Website | Purpose |
|------|-------------|-----------------|------------|---------|--------|
| Node.js | 3000 | 3001, 8000, 8080 | `node app.js` | [nodejs.org](https://nodejs.org) | JavaScript Development Server |
| React | 3000 | 3001 | `npm start` | [reactjs.org](https://reactjs.org) | React Application |
| Next.js | 3000 | 3001 | `npm run dev` | [nextjs.org](https://nextjs.org) | Next.js Framework |
| Express.js | 3000 | 8000, 8080 | `node server.js` | [expressjs.com](https://expressjs.com) | Node.js Server |
| Vue.js | 8080 | 3000, 8081 | `npm run serve` | [vuejs.org](https://vuejs.org) | Vue.js Framework |
| Angular | 4200 | 4201, 3000 | `ng serve` | [angular.io](https://angular.io) | Angular Framework |
| Django | 8000 | 8001, 3000 | `python manage.py runserver` | [djangoproject.com](https://djangoproject.com) | Python Framework |
| Flask | 5000 | 5001, 3000 | `flask run` | [flask.palletsprojects.com](https://flask.palletsprojects.com) | Python Microframework |
| FastAPI | 8000 | 8001, 3000 | `uvicorn main:app` | [fastapi.tiangolo.com](https://fastapi.tiangolo.com) | Python Framework |
| Laravel | 8000 | 8001, 3000 | `php artisan serve` | [laravel.com](https://laravel.com) | PHP Framework |
| Symfony | 8000 | 8001, 3000 | `symfony serve` | [symfony.com](https://symfony.com) | PHP Framework |
| Spring Boot | 8080 | 8081, 3000 | `mvn spring-boot:run` | [spring.io](https://spring.io) | Java Framework |
| Rails | 3000 | 3001, 8000 | `rails server` | [rubyonrails.org](https://rubyonrails.org) | Ruby Framework |
| ASP.NET Core | 5000 | 5001, 3000 | `dotnet run` | [dotnet.microsoft.com](https://dotnet.microsoft.com) | .NET Framework |
| Gin (Go) | 8080 | 8081, 3000 | `go run main.go` | [gin-gonic.com](https://gin-gonic.com) | Go Framework |
| Fiber (Go) | 3000 | 3001, 8080 | `go run main.go` | [gofiber.io](https://gofiber.io) | Go Framework |
| Actix (Rust) | 8080 | 8081, 3000 | `cargo run` | [actix.rs](https://actix.rs) | Rust Framework |
| Rocket (Rust) | 8000 | 8001, 3000 | `cargo run` | [rocket.rs](https://rocket.rs) | Rust Framework |

## Databases

| Tool | Default Port | Alternative Port | Connection String | Website | Type |
|------|-------------|-----------------|-----------------|---------|-----|
| MongoDB | 27017 | 27018 | `mongodb://localhost:27017` | [mongodb.com](https://mongodb.com) | NoSQL |
| PostgreSQL | 5432 | 5433 | `postgresql://localhost:5432` | [postgresql.org](https://postgresql.org) | SQL |
| MySQL | 3306 | 3307 | `mysql://localhost:3306` | [mysql.com](https://mysql.com) | SQL |
| Redis | 6379 | 6380 | `redis://localhost:6379` | [redis.io](https://redis.io) | Cache |
| SQLite | - | - | `sqlite://database.db` | [sqlite.org](https://sqlite.org) | SQL |
| MariaDB | 3306 | 3307 | `mariadb://localhost:3306` | [mariadb.org](https://mariadb.org) | SQL |
| Cassandra | 9042 | 9043 | `cassandra://localhost:9042` | [cassandra.apache.org](https://cassandra.apache.org) | NoSQL |
| CouchDB | 5984 | 5985 | `http://localhost:5984` | [couchdb.apache.org](https://couchdb.apache.org) | NoSQL |
| Neo4j | 7474 | 7475 | `bolt://localhost:7687` | [neo4j.com](https://neo4j.com) | Graph |
| InfluxDB | 8086 | 8087 | `http://localhost:8086` | [influxdata.com](https://influxdata.com) | Time Series |
| TimescaleDB | 5432 | 5433 | `postgresql://localhost:5432` | [timescale.com](https://timescale.com) | Time Series |
| ClickHouse | 8123 | 8124 | `http://localhost:8123` | [clickhouse.com](https://clickhouse.com) | OLAP |
| Elasticsearch | 9200 | 9201 | `http://localhost:9200` | [elastic.co](https://elastic.co) | Search |
| Solr | 8983 | 8984 | `http://localhost:8983` | [solr.apache.org](https://solr.apache.org) | Search |
| ArangoDB | 8529 | 8530 | `http://localhost:8529` | [arangodb.com](https://arangodb.com) | Multi-Model |
| OrientDB | 2480 | 2481 | `http://localhost:2480` | [orientdb.org](https://orientdb.org) | Graph |
| RethinkDB | 28015 | 28016 | `rethinkdb://localhost:28015` | [rethinkdb.com](https://rethinkdb.com) | NoSQL |

## Web Servers

| Tool | HTTP Port | HTTPS Port | Alternative Port | Website | Platform |
|------|-----------|-----------|-----------------|---------|----------|
| Apache | 80 | 443 | 8080 | [apache.org](https://apache.org) | Cross-platform |
| Nginx | 80 | 443 | 8080 | [nginx.org](https://nginx.org) | Cross-platform |
| IIS | 80 | 443 | 8080 | [iis.net](https://iis.net) | Windows |
| Tomcat | 8080 | 8443 | 8081 | [tomcat.apache.org](https://tomcat.apache.org) | Java |
| Jetty | 8080 | 8443 | 8081 | [eclipse.org/jetty](https://eclipse.org/jetty) | Java |
| Caddy | 80 | 443 | 8080 | [caddyserver.com](https://caddyserver.com) | Cross-platform |
| Lighttpd | 80 | 443 | 8080 | [lighttpd.net](https://lighttpd.net) | Cross-platform |
| Cherokee | 80 | 443 | 8080 | [cherokee-project.com](https://cherokee-project.com) | Cross-platform |
| H2O | 80 | 443 | 8080 | [h2o.examp1e.net](https://h2o.examp1e.net) | Cross-platform |
| Traefik | 80 | 443 | 8080 | [traefik.io](https://traefik.io) | Cross-platform |
| Envoy | 80 | 443 | 8080 | [envoyproxy.io](https://envoyproxy.io) | Cross-platform |
| HAProxy | 80 | 443 | 8080 | [haproxy.org](https://haproxy.org) | Load Balancer |
| Varnish | 80 | 443 | 8080 | [varnish-cache.org](https://varnish-cache.org) | Cache |

## Docker & Kubernetes

| Tool | Main Port | Secure Port | Registry Port | Website | Purpose |
|------|-----------|------------|---------------|---------|--------|
| Docker Engine | 2375 | 2376 | 5000 | [docker.com](https://docker.com) | Container Engine |
| Docker Compose | متغیر | متغیر | - | [docs.docker.com/compose](https://docs.docker.com/compose) | Multi-container |
| Docker Swarm | 2377 | 2378 | - | [docs.docker.com/swarm](https://docs.docker.com/swarm) | Orchestration |
| Portainer | 9000 | 9443 | - | [portainer.io](https://portainer.io) | Docker Management |
| Kubernetes | 6443 | 6444 | - | [kubernetes.io](https://kubernetes.io) | Container Orchestration |
| Minikube | 8443 | 8444 | - | [minikube.sigs.k8s.io](https://minikube.sigs.k8s.io) | Local Kubernetes |
| Kind | 6443 | 6444 | - | [kind.sigs.k8s.io](https://kind.sigs.k8s.io) | Kubernetes in Docker |
| K3s | 6443 | 6444 | - | [k3s.io](https://k3s.io) | Lightweight Kubernetes |
| Rancher | 80 | 443 | 8080 | [rancher.com](https://rancher.com) | Kubernetes Management |
| Lens | 3000 | 3001 | - | [k8slens.dev](https://k8slens.dev) | Kubernetes IDE |
| Octant | 7777 | 7778 | - | [octant.dev](https://octant.dev) | Kubernetes Dashboard |
| K9s | - | - | - | [k9scli.io](https://k9scli.io) | Kubernetes CLI |

## Monitoring

| Tool | Default Port | Alternative Port | Web UI | Website | Purpose |
|------|-------------|-----------------|--------|---------|--------|
| Prometheus | 9090 | 9091 | http://localhost:9090 | [prometheus.io](https://prometheus.io) | Metrics Collection |
| Grafana | 3000 | 3001 | http://localhost:3000 | [grafana.com](https://grafana.com) | Visualization |
| Elasticsearch | 9200 | 9201 | http://localhost:9200 | [elastic.co](https://elastic.co) | Search Engine |
| Kibana | 5601 | 5602 | http://localhost:5601 | [elastic.co/kibana](https://elastic.co/kibana) | Data Visualization |
| Jaeger | 16686 | 16687 | http://localhost:16686 | [jaegertracing.io](https://jaegertracing.io) | Distributed Tracing |
| Zipkin | 9411 | 9412 | http://localhost:9411 | [zipkin.io](https://zipkin.io) | Distributed Tracing |
| InfluxDB | 8086 | 8087 | http://localhost:8086 | [influxdata.com](https://influxdata.com) | Time Series DB |
| Chronograf | 8888 | 8889 | http://localhost:8888 | [influxdata.com](https://influxdata.com) | Time Series UI |
| Telegraf | 8125 | 8126 | - | [influxdata.com](https://influxdata.com) | Metrics Agent |
| Kapacitor | 9092 | 9093 | http://localhost:9092 | [influxdata.com](https://influxdata.com) | Alerting |
| Sensu | 3000 | 3001 | http://localhost:3000 | [sensu.io](https://sensu.io) | Monitoring |
| Nagios | 80 | 443 | 8080 | [nagios.org](https://nagios.org) | Infrastructure Monitoring |
| Zabbix | 80 | 443 | 8080 | [zabbix.com](https://zabbix.com) | Network Monitoring |
| Datadog | - | - | - | [datadoghq.com](https://datadoghq.com) | Cloud Monitoring |
| New Relic | - | - | - | [newrelic.com](https://newrelic.com) | APM |
| AppDynamics | - | - | - | [appdynamics.com](https://appdynamics.com) | APM |

## Message Queues

| Tool | Management Port | Main Port | Alternative Port | Website | Protocol |
|------|-----------------|-----------|-----------------|---------|---------|
| RabbitMQ | 15672 | 5672 | 5673 | [rabbitmq.com](https://rabbitmq.com) | AMQP |
| RabbitMQ Management | 15672 | 15673 | - | [rabbitmq.com](https://rabbitmq.com) | Web UI |
| RabbitMQ STOMP | 61613 | 61614 | - | [rabbitmq.com](https://rabbitmq.com) | STOMP Protocol |
| RabbitMQ MQTT | 1883 | 1884 | - | [rabbitmq.com](https://rabbitmq.com) | MQTT Protocol |
| Apache Kafka | - | 9092 | 9093 | [kafka.apache.org](https://kafka.apache.org) | Kafka Protocol |
| Apache Pulsar | 8080 | 6650 | 6651 | [pulsar.apache.org](https://pulsar.apache.org) | Pulsar Protocol |
| NATS | 8222 | 4222 | 4223 | [nats.io](https://nats.io) | NATS Protocol |
| Apache ActiveMQ | 8161 | 5672 | 5673 | [activemq.apache.org](https://activemq.apache.org) | JMS |
| Apache Artemis | 8161 | 5672 | 5673 | [activemq.apache.org](https://activemq.apache.org) | JMS |
| ZeroMQ | - | 5555 | 5556 | [zeromq.org](https://zeromq.org) | ZMQ Protocol |
| MQTT Broker | - | 1883 | 1884 | [mqtt.org](https://mqtt.org) | MQTT |
| Mosquitto | - | 1883 | 1884 | [mosquitto.org](https://mosquitto.org) | MQTT |
| EMQX | 18083 | 1883 | 1884 | [emqx.io](https://emqx.io) | MQTT |
| VerneMQ | 8888 | 1883 | 1884 | [vernemq.com](https://vernemq.com) | MQTT |
| Apache RocketMQ | 9876 | 10911 | 10912 | [rocketmq.apache.org](https://rocketmq.apache.org) | Message Queue |
| Amazon SQS | - | - | - | [aws.amazon.com/sqs](https://aws.amazon.com/sqs) | Cloud Queue |
| Google Pub/Sub | - | - | - | [cloud.google.com/pubsub](https://cloud.google.com/pubsub) | Cloud Messaging |
| Azure Service Bus | - | - | - | [azure.microsoft.com/service-bus](https://azure.microsoft.com/service-bus) | Cloud Messaging |

## RabbitMQ - Complete Details

| Service | Port | Protocol | Purpose | Access |
|--------|------|---------|--------|--------|
| RabbitMQ Server | 5672 | AMQP | Main Messaging | amqp://localhost:5672 |
| RabbitMQ Management | 15672 | HTTP | Management UI | http://localhost:15672 |
| RabbitMQ STOMP | 61613 | STOMP | STOMP Messaging | stomp://localhost:61613 |
| RabbitMQ MQTT | 1883 | MQTT | IoT Messaging | mqtt://localhost:1883 |
| RabbitMQ Web STOMP | 15674 | WebSocket | STOMP over WebSocket | ws://localhost:15674 |
| RabbitMQ Web MQTT | 15675 | WebSocket | MQTT over WebSocket | ws://localhost:15675 |

### RabbitMQ Setup
```bash
# Install RabbitMQ
# Ubuntu/Debian
sudo apt-get install rabbitmq-server

# CentOS/RHEL
sudo yum install rabbitmq-server

# Docker
docker run -d --name rabbitmq -p 5672:5672 -p 15672:15672 rabbitmq:3-management

# Enable Management Plugin
sudo rabbitmq-plugins enable rabbitmq_management

# Create User
sudo rabbitmqctl add_user admin password
sudo rabbitmqctl set_user_tags admin administrator
sudo rabbitmqctl set_permissions -p / admin ".*" ".*" ".*"
```

## Testing Tools

| Tool | Test Port | Dashboard Port | Coverage Port | Website | Test Type |
|------|-----------|----------------|---------------|---------|-----------|
| Jest | 3000 | - | 3001 | [jestjs.io](https://jestjs.io) | Unit Testing |
| Cypress | 3000 | 3001 | - | [cypress.io](https://cypress.io) | E2E Testing |
| Playwright | 3000 | 3001 | - | [playwright.dev](https://playwright.dev) | E2E Testing |
| Selenium | 4444 | 4445 | - | [selenium.dev](https://selenium.dev) | Web Testing |
| TestCafe | 3000 | 3001 | - | [testcafe.io](https://testcafe.io) | E2E Testing |
| Mocha | 3000 | 3001 | - | [mochajs.org](https://mochajs.org) | Unit Testing |
| Jasmine | 3000 | 3001 | - | [jasmine.github.io](https://jasmine.github.io) | Unit Testing |
| Karma | 9876 | 9877 | - | [karma-runner.github.io](https://karma-runner.github.io) | Test Runner |
| Protractor | 4444 | 4445 | - | [protractortest.org](https://protractortest.org) | Angular Testing |
| WebdriverIO | 4444 | 4445 | - | [webdriver.io](https://webdriver.io) | Web Testing |
| Nightwatch | 4444 | 4445 | - | [nightwatchjs.org](https://nightwatchjs.org) | E2E Testing |
| Puppeteer | 3000 | 3001 | - | [pptr.dev](https://pptr.dev) | Headless Testing |
| Artillery | 3000 | 3001 | - | [artillery.io](https://artillery.io) | Load Testing |
| JMeter | 1099 | 1100 | - | [jmeter.apache.org](https://jmeter.apache.org) | Performance Testing |
| Gatling | 3000 | 3001 | - | [gatling.io](https://gatling.io) | Load Testing |
| K6 | 3000 | 3001 | - | [k6.io](https://k6.io) | Load Testing |
| Postman | 3000 | 3001 | - | [postman.com](https://postman.com) | API Testing |
| Newman | 3000 | 3001 | - | [postman.com](https://postman.com) | API Testing |
| Insomnia | 3000 | 3001 | - | [insomnia.rest](https://insomnia.rest) | API Testing |
| REST Assured | 3000 | 3001 | - | [rest-assured.io](https://rest-assured.io) | API Testing |

## Security Tools

| Tool | Default Port | Alternative Port | Web UI | Website | Purpose |
|------|-------------|-----------------|--------|---------|--------|
| OWASP ZAP | 8080 | 8081 | http://localhost:8080 | [owasp.org/zap](https://owasp.org/zap) | Security Testing |
| Burp Suite | 8080 | 8081 | http://localhost:8080 | [portswigger.net](https://portswigger.net) | Web Security |
| Nessus | 8834 | 8835 | https://localhost:8834 | [tenable.com](https://tenable.com) | Vulnerability Scanner |
| OpenVAS | 9392 | 9393 | https://localhost:9392 | [openvas.org](https://openvas.org) | Vulnerability Scanner |
| Nikto | 80 | 443 | 8080 | [cirt.net/nikto2](https://cirt.net/nikto2) | Web Scanner |
| Nmap | - | - | - | [nmap.org](https://nmap.org) | Network Scanner |
| Metasploit | 4444 | 4445 | - | [metasploit.com](https://metasploit.com) | Penetration Testing |
| Wireshark | - | - | - | [wireshark.org](https://wireshark.org) | Network Analysis |
| Aircrack-ng | - | - | - | [aircrack-ng.org](https://aircrack-ng.org) | WiFi Security |
| John the Ripper | - | - | - | [openwall.com/john](https://openwall.com/john) | Password Cracking |
| Hashcat | - | - | - | [hashcat.net](https://hashcat.net) | Password Cracking |
| Hydra | - | - | - | [github.com/vanhauser-thc/thc-hydra](https://github.com/vanhauser-thc/thc-hydra) | Brute Force |
| SQLMap | - | - | - | [sqlmap.org](https://sqlmap.org) | SQL Injection |
| W3af | 8080 | 8081 | http://localhost:8080 | [w3af.org](https://w3af.org) | Web Application Scanner |
| Skipfish | - | - | - | [code.google.com/skipfish](https://code.google.com/skipfish) | Web Security Scanner |
| Arachni | 7331 | 7332 | http://localhost:7331 | [arachni-scanner.com](https://arachni-scanner.com) | Web Security Scanner |
| Wapiti | - | - | - | [wapiti.sourceforge.net](https://wapiti.sourceforge.net) | Web Vulnerability Scanner |
| Vega | 8443 | 8444 | https://localhost:8443 | [subgraph.com/vega](https://subgraph.com/vega) | Web Security Scanner |

## CI/CD

| Tool | Default Port | Alternative Port | Web UI | Website | Purpose |
|------|-------------|-----------------|--------|---------|--------|
| Jenkins | 8080 | 8081 | http://localhost:8080 | [jenkins.io](https://jenkins.io) | CI/CD Server |
| GitLab CI | 80 | 443 | http://localhost | [gitlab.com](https://gitlab.com) | Git-based CI |
| GitHub Actions | - | - | - | [github.com/features/actions](https://github.com/features/actions) | Cloud CI/CD |
| Azure DevOps | - | - | - | [azure.microsoft.com/devops](https://azure.microsoft.com/devops) | Cloud CI/CD |
| CircleCI | - | - | - | [circleci.com](https://circleci.com) | Cloud CI/CD |
| Travis CI | - | - | - | [travis-ci.com](https://travis-ci.com) | Cloud CI/CD |
| Bamboo | 8085 | 8086 | http://localhost:8085 | [atlassian.com/software/bamboo](https://atlassian.com/software/bamboo) | CI/CD Server |
| TeamCity | 8111 | 8112 | http://localhost:8111 | [jetbrains.com/teamcity](https://jetbrains.com/teamcity) | CI/CD Server |
| Drone | 3000 | 3001 | http://localhost:3000 | [drone.io](https://drone.io) | CI/CD Platform |
| Concourse | 8080 | 8081 | http://localhost:8080 | [concourse-ci.org](https://concourse-ci.org) | CI/CD Platform |
| Tekton | 8080 | 8081 | http://localhost:8080 | [tekton.dev](https://tekton.dev) | Kubernetes CI |
| ArgoCD | 8080 | 8081 | http://localhost:8080 | [argo-cd.readthedocs.io](https://argo-cd.readthedocs.io) | GitOps |
| Flux | - | - | - | [fluxcd.io](https://fluxcd.io) | GitOps |
| Spinnaker | 9000 | 9001 | http://localhost:9000 | [spinnaker.io](https://spinnaker.io) | CD Platform |
| Harness | 8080 | 8081 | http://localhost:8080 | [harness.io](https://harness.io) | CD Platform |

## DevOps Tools

| Tool | Default Port | Alternative Port | Web UI | Website | Purpose |
|------|-------------|-----------------|--------|---------|--------|
| Ansible | - | - | - | [ansible.com](https://ansible.com) | Configuration Management |
| Terraform | - | - | - | [terraform.io](https://terraform.io) | Infrastructure as Code |
| Puppet | 8140 | 8141 | - | [puppet.com](https://puppet.com) | Configuration Management |
| Chef | 443 | 444 | - | [chef.io](https://chef.io) | Configuration Management |
| SaltStack | 4505 | 4506 | - | [saltproject.io](https://saltproject.io) | Configuration Management |
| Vagrant | 2222 | 2223 | - | [vagrantup.com](https://vagrantup.com) | Development Environment |
| Packer | - | - | - | [packer.io](https://packer.io) | Image Builder |
| Consul | 8500 | 8501 | http://localhost:8500 | [consul.io](https://consul.io) | Service Discovery |
| Vault | 8200 | 8201 | http://localhost:8200 | [vaultproject.io](https://vaultproject.io) | Secrets Management |
| Nomad | 4646 | 4647 | http://localhost:4646 | [nomadproject.io](https://nomadproject.io) | Workload Orchestration |
| Serf | 7946 | 7947 | - | [serf.io](https://serf.io) | Service Discovery |
| Etcd | 2379 | 2380 | http://localhost:2379 | [etcd.io](https://etcd.io) | Key-Value Store |
| Zookeeper | 2181 | 2182 | - | [zookeeper.apache.org](https://zookeeper.apache.org) | Coordination Service |

## Data Processing & Workflow Tools

| Tool | Default Port | Alternative Port | Web UI | Website | Purpose |
|------|-------------|-----------------|--------|---------|--------|
| Prefect | 4200 | 4201 | http://localhost:4200 | [prefect.io](https://prefect.io) | Workflow Orchestration |
| Dagster | 3000 | 3001 | http://localhost:3000 | [dagster.io](https://dagster.io) | Data Orchestration |
| Luigi | 8082 | 8083 | http://localhost:8082 | [luigi.readthedocs.io](https://luigi.readthedocs.io) | Pipeline Builder |
| Celery | 5555 | 5556 | http://localhost:5555 | [celeryproject.org](https://celeryproject.org) | Task Queue |
| Apache Storm | 8080 | 8081 | http://localhost:8080 | [storm.apache.org](https://storm.apache.org) | Real-time Processing |
| Apache Flink | 8081 | 8082 | http://localhost:8081 | [flink.apache.org](https://flink.apache.org) | Stream Processing |
| Apache Pulsar | 8080 | 8081 | http://localhost:8080 | [pulsar.apache.org](https://pulsar.apache.org) | Messaging & Streaming |
| Apache Druid | 8888 | 8889 | http://localhost:8888 | [druid.apache.org](https://druid.apache.org) | Real-time Analytics |
| Apache Hive | 10000 | 10001 | - | [hive.apache.org](https://hive.apache.org) | Data Warehouse |
| Apache HBase | 16010 | 16020 | http://localhost:16010 | [hbase.apache.org](https://hbase.apache.org) | NoSQL Database |

## Apache Tools

| Tool | Default Port | Alternative Port | Web UI | Website | Purpose |
|------|-------------|-----------------|--------|---------|--------|
| Apache Airflow | 8080 | 8081 | http://localhost:8080 | [airflow.apache.org](https://airflow.apache.org) | Workflow Orchestration |
| Apache NiFi | 8443 | 8444 | https://localhost:8443/nifi | [nifi.apache.org](https://nifi.apache.org) | Data Flow Management |
| Apache Spark | 4040 | 4041 | http://localhost:4040 | [spark.apache.org](https://spark.apache.org) | Big Data Processing |
| Apache Kafka | 9092 | 9093 | - | [kafka.apache.org](https://kafka.apache.org) | Message Streaming |
| Apache Kafka Connect | 8083 | 8084 | http://localhost:8083 | [kafka.apache.org](https://kafka.apache.org) | Data Integration |
| Apache Superset | 8088 | 8089 | http://localhost:8088 | [superset.apache.org](https://superset.apache.org) | Data Visualization |
| Apache Zeppelin | 8080 | 8081 | http://localhost:8080 | [zeppelin.apache.org](https://zeppelin.apache.org) | Data Analytics |
| Apache Livy | 8998 | 8999 | http://localhost:8998 | [livy.apache.org](https://livy.apache.org) | Spark REST API |
| Apache Oozie | 11000 | 11001 | http://localhost:11000 | [oozie.apache.org](https://oozie.apache.org) | Workflow Scheduler |
| Apache Ranger | 6080 | 6081 | http://localhost:6080 | [ranger.apache.org](https://ranger.apache.org) | Security Framework |
| Apache Atlas | 21000 | 21001 | http://localhost:21000 | [atlas.apache.org](https://atlas.apache.org) | Data Governance |
| Apache Knox | 8443 | 8444 | https://localhost:8443 | [knox.apache.org](https://knox.apache.org) | Security Gateway |
| Apache Ambari | 8080 | 8081 | http://localhost:8080 | [ambari.apache.org](https://ambari.apache.org) | Cluster Management |
| Apache Hue | 8888 | 8889 | http://localhost:8888 | [gethue.com](https://gethue.com) | Data Analytics Workbench |

## Log Management

| Tool | Default Port | Alternative Port | Web UI | Website | Purpose |
|------|-------------|-----------------|--------|---------|--------|
| ELK Stack | 9200 | 9201 | http://localhost:5601 | [elastic.co](https://elastic.co) | Log Management |
| Fluentd | 24224 | 24225 | - | [fluentd.org](https://fluentd.org) | Log Collector |
| Logstash | 5044 | 5045 | - | [elastic.co/logstash](https://elastic.co/logstash) | Log Processing |
| Filebeat | - | - | - | [elastic.co/beats/filebeat](https://elastic.co/beats/filebeat) | Log Shipper |
| Fluent Bit | 2020 | 2021 | - | [fluentbit.io](https://fluentbit.io) | Log Processor |
| Graylog | 9000 | 9001 | http://localhost:9000 | [graylog.org](https://graylog.org) | Log Management |
| Splunk | 8000 | 8001 | http://localhost:8000 | [splunk.com](https://splunk.com) | Log Analytics |
| Loki | 3100 | 3101 | http://localhost:3100 | [grafana.com/oss/loki](https://grafana.com/oss/loki) | Log Aggregation |
| Promtail | - | - | - | [grafana.com/oss/loki](https://grafana.com/oss/loki) | Log Shipper |
| Vector | 8686 | 8687 | http://localhost:8686 | [vector.dev](https://vector.dev) | Log Router |

## System Ports

| Port Range | Name | Description |
|------------|------|------------|
| 0-1023 | System Ports | Reserved system ports |
| 1024-49151 | Registered Ports | Registered ports |
| 49152-65535 | Dynamic/Private Ports | Private ports |

## Common Development Ports

| Port | Primary Use | Related Tools |
|------|-------------|---------------|
| 3000 | Frontend Development | React, Next.js, Node.js |
| 4200 | Angular | Angular CLI |
| 5000 | Flask, ASP.NET Core | Python, .NET |
| 8000 | Django, FastAPI | Python |
| 8080 | Java, Vue.js | Spring Boot, Tomcat |
| 8081 | Alternative Port | Most Tools |
| 5432 | PostgreSQL | Database |
| 3306 | MySQL | Database |
| 27017 | MongoDB | Database |
| 6379 | Redis | Cache |

## Real-time Tools

| Tool | Main Port | Alternative Port | Protocol | Purpose |
|------|-----------|-----------------|----------|--------|
| Socket.IO | 3000 | 3001 | WebSocket | Real-time Communication |
| Pusher | - | - | WebSocket | Real-time APIs |
| Ably | - | - | WebSocket | Real-time Messaging |
| SignalR | 5000 | 5001 | WebSocket | ASP.NET Real-time |
| Firebase | - | - | WebSocket | Google Real-time |
| Deepstream | 6020 | 6021 | WebSocket | Real-time Server |

## Best Practices

### Port Security
- 🔒 Always close unnecessary ports
- 🔐 Use secure ports (HTTPS/SSL)
- 🛡️ Configure firewall for open ports

### Development
- 🎯 Use standard ports
- 🔄 Have alternative ports for different environments
- 📝 Keep port documentation updated

## Troubleshooting Guide

### "Port already in use" Error
```bash
# Find process using port
lsof -i :3000
sudo netstat -tulpn | grep :3000
ss -tulpn | grep :3000

# Free up port
kill -9 $(lsof -t -i:3000)
sudo fuser -k 3000/tcp
```

### Change Port in Docker
```yaml
# docker-compose.yml
services:
  app:
    ports:
      - "3001:3000"  # host:container
```

## Useful Commands

### Check Port Usage
```bash
# Windows
netstat -an | findstr :3000

# Linux/Mac
netstat -an | grep :3000
lsof -i :3000
```

### Free Up Port
```bash
# Windows
taskkill /PID <PID> /F

# Linux/Mac
kill -9 <PID>
```

### Change Port in Projects
```bash
# React
PORT=3001 npm start

# Next.js
npm run dev -- -p 3001

# Express
process.env.PORT = 3001
```

## Contributing

Feel free to contribute to this reference by:
- Adding new tools and their ports
- Updating existing information
- Improving documentation
- Adding more examples

## License

MIT License - feel free to use this reference in your projects!

---

**Made with ❤️ for the developer community**
