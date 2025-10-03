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
- [Log Management](#log-management)
- [System Ports](#system-ports)
- [Useful Commands](#useful-commands)

## Development Tools

| Tool | Default Port | Alternative Ports | Run Command | Purpose |
|------|-------------|-----------------|------------|--------|
| Node.js | 3000 | 3001, 8000, 8080 | `node app.js` | JavaScript Development Server |
| React | 3000 | 3001 | `npm start` | React Application |
| Next.js | 3000 | 3001 | `npm run dev` | Next.js Framework |
| Express.js | 3000 | 8000, 8080 | `node server.js` | Node.js Server |
| Vue.js | 8080 | 3000, 8081 | `npm run serve` | Vue.js Framework |
| Angular | 4200 | 4201, 3000 | `ng serve` | Angular Framework |
| Django | 8000 | 8001, 3000 | `python manage.py runserver` | Python Framework |
| Flask | 5000 | 5001, 3000 | `flask run` | Python Microframework |
| FastAPI | 8000 | 8001, 3000 | `uvicorn main:app` | Python Framework |
| Laravel | 8000 | 8001, 3000 | `php artisan serve` | PHP Framework |
| Symfony | 8000 | 8001, 3000 | `symfony serve` | PHP Framework |
| Spring Boot | 8080 | 8081, 3000 | `mvn spring-boot:run` | Java Framework |
| Rails | 3000 | 3001, 8000 | `rails server` | Ruby Framework |
| ASP.NET Core | 5000 | 5001, 3000 | `dotnet run` | .NET Framework |
| Gin (Go) | 8080 | 8081, 3000 | `go run main.go` | Go Framework |
| Fiber (Go) | 3000 | 3001, 8080 | `go run main.go` | Go Framework |
| Actix (Rust) | 8080 | 8081, 3000 | `cargo run` | Rust Framework |
| Rocket (Rust) | 8000 | 8001, 3000 | `cargo run` | Rust Framework |

## Databases

| Tool | Default Port | Alternative Port | Connection String | Type |
|------|-------------|-----------------|-----------------|-----|
| MongoDB | 27017 | 27018 | `mongodb://localhost:27017` | NoSQL |
| PostgreSQL | 5432 | 5433 | `postgresql://localhost:5432` | SQL |
| MySQL | 3306 | 3307 | `mysql://localhost:3306` | SQL |
| Redis | 6379 | 6380 | `redis://localhost:6379` | Cache |
| SQLite | - | - | `sqlite://database.db` | SQL |
| MariaDB | 3306 | 3307 | `mariadb://localhost:3306` | SQL |
| Cassandra | 9042 | 9043 | `cassandra://localhost:9042` | NoSQL |
| CouchDB | 5984 | 5985 | `http://localhost:5984` | NoSQL |
| Neo4j | 7474 | 7475 | `bolt://localhost:7687` | Graph |
| InfluxDB | 8086 | 8087 | `http://localhost:8086` | Time Series |
| TimescaleDB | 5432 | 5433 | `postgresql://localhost:5432` | Time Series |
| ClickHouse | 8123 | 8124 | `http://localhost:8123` | OLAP |
| Elasticsearch | 9200 | 9201 | `http://localhost:9200` | Search |
| Solr | 8983 | 8984 | `http://localhost:8983` | Search |
| ArangoDB | 8529 | 8530 | `http://localhost:8529` | Multi-Model |
| OrientDB | 2480 | 2481 | `http://localhost:2480` | Graph |
| RethinkDB | 28015 | 28016 | `rethinkdb://localhost:28015` | NoSQL |

## Web Servers

| Tool | HTTP Port | HTTPS Port | Alternative Port | Platform |
|------|-----------|-----------|-----------------|----------|
| Apache | 80 | 443 | 8080 | Cross-platform |
| Nginx | 80 | 443 | 8080 | Cross-platform |
| IIS | 80 | 443 | 8080 | Windows |
| Tomcat | 8080 | 8443 | 8081 | Java |
| Jetty | 8080 | 8443 | 8081 | Java |
| Caddy | 80 | 443 | 8080 | Cross-platform |
| Lighttpd | 80 | 443 | 8080 | Cross-platform |
| Cherokee | 80 | 443 | 8080 | Cross-platform |
| H2O | 80 | 443 | 8080 | Cross-platform |
| Traefik | 80 | 443 | 8080 | Cross-platform |
| Envoy | 80 | 443 | 8080 | Cross-platform |
| HAProxy | 80 | 443 | 8080 | Load Balancer |
| Varnish | 80 | 443 | 8080 | Cache |

## Docker & Kubernetes

| Tool | Main Port | Secure Port | Registry Port | Purpose |
|------|-----------|------------|---------------|--------|
| Docker Engine | 2375 | 2376 | 5000 | Container Engine |
| Docker Compose | متغیر | متغیر | - | Multi-container |
| Docker Swarm | 2377 | 2378 | - | Orchestration |
| Portainer | 9000 | 9443 | - | Docker Management |
| Kubernetes | 6443 | 6444 | - | Container Orchestration |
| Minikube | 8443 | 8444 | - | Local Kubernetes |
| Kind | 6443 | 6444 | - | Kubernetes in Docker |
| K3s | 6443 | 6444 | - | Lightweight Kubernetes |
| Rancher | 80 | 443 | 8080 | Kubernetes Management |
| Lens | 3000 | 3001 | - | Kubernetes IDE |
| Octant | 7777 | 7778 | - | Kubernetes Dashboard |
| K9s | - | - | - | Kubernetes CLI |

## Monitoring

| Tool | Default Port | Alternative Port | Web UI | Purpose |
|------|-------------|-----------------|--------|--------|
| Prometheus | 9090 | 9091 | http://localhost:9090 | Metrics Collection |
| Grafana | 3000 | 3001 | http://localhost:3000 | Visualization |
| Elasticsearch | 9200 | 9201 | http://localhost:9200 | Search Engine |
| Kibana | 5601 | 5602 | http://localhost:5601 | Data Visualization |
| Jaeger | 16686 | 16687 | http://localhost:16686 | Distributed Tracing |
| Zipkin | 9411 | 9412 | http://localhost:9411 | Distributed Tracing |
| InfluxDB | 8086 | 8087 | http://localhost:8086 | Time Series DB |
| Chronograf | 8888 | 8889 | http://localhost:8888 | Time Series UI |
| Telegraf | 8125 | 8126 | - | Metrics Agent |
| Kapacitor | 9092 | 9093 | http://localhost:9092 | Alerting |
| Sensu | 3000 | 3001 | http://localhost:3000 | Monitoring |
| Nagios | 80 | 443 | 8080 | Infrastructure Monitoring |
| Zabbix | 80 | 443 | 8080 | Network Monitoring |
| Datadog | - | - | - | Cloud Monitoring |
| New Relic | - | - | - | APM |
| AppDynamics | - | - | - | APM |

## Message Queues

| Tool | Management Port | Main Port | Alternative Port | Protocol |
|------|-----------------|-----------|-----------------|---------|
| RabbitMQ | 15672 | 5672 | 5673 | AMQP |
| RabbitMQ Management | 15672 | 15673 | - | Web UI |
| RabbitMQ STOMP | 61613 | 61614 | - | STOMP Protocol |
| RabbitMQ MQTT | 1883 | 1884 | - | MQTT Protocol |
| Apache Kafka | - | 9092 | 9093 | Kafka Protocol |
| Apache Pulsar | 8080 | 6650 | 6651 | Pulsar Protocol |
| NATS | 8222 | 4222 | 4223 | NATS Protocol |
| Apache ActiveMQ | 8161 | 5672 | 5673 | JMS |
| Apache Artemis | 8161 | 5672 | 5673 | JMS |
| ZeroMQ | - | 5555 | 5556 | ZMQ Protocol |
| MQTT Broker | - | 1883 | 1884 | MQTT |
| Mosquitto | - | 1883 | 1884 | MQTT |
| EMQX | 18083 | 1883 | 1884 | MQTT |
| VerneMQ | 8888 | 1883 | 1884 | MQTT |
| Apache RocketMQ | 9876 | 10911 | 10912 | Message Queue |
| Amazon SQS | - | - | - | Cloud Queue |
| Google Pub/Sub | - | - | - | Cloud Messaging |
| Azure Service Bus | - | - | - | Cloud Messaging |

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

| Tool | Test Port | Dashboard Port | Coverage Port | Test Type |
|------|-----------|----------------|---------------|-----------|
| Jest | 3000 | - | 3001 | Unit Testing |
| Cypress | 3000 | 3001 | - | E2E Testing |
| Playwright | 3000 | 3001 | - | E2E Testing |
| Selenium | 4444 | 4445 | - | Web Testing |
| TestCafe | 3000 | 3001 | - | E2E Testing |
| Mocha | 3000 | 3001 | - | Unit Testing |
| Jasmine | 3000 | 3001 | - | Unit Testing |
| Karma | 9876 | 9877 | - | Test Runner |
| Protractor | 4444 | 4445 | - | Angular Testing |
| WebdriverIO | 4444 | 4445 | - | Web Testing |
| Nightwatch | 4444 | 4445 | - | E2E Testing |
| Puppeteer | 3000 | 3001 | - | Headless Testing |
| Artillery | 3000 | 3001 | - | Load Testing |
| JMeter | 1099 | 1100 | - | Performance Testing |
| Gatling | 3000 | 3001 | - | Load Testing |
| K6 | 3000 | 3001 | - | Load Testing |
| Postman | 3000 | 3001 | - | API Testing |
| Newman | 3000 | 3001 | - | API Testing |
| Insomnia | 3000 | 3001 | - | API Testing |
| REST Assured | 3000 | 3001 | - | API Testing |

## Security Tools

| Tool | Default Port | Alternative Port | Web UI | Purpose |
|------|-------------|-----------------|--------|--------|
| OWASP ZAP | 8080 | 8081 | http://localhost:8080 | Security Testing |
| Burp Suite | 8080 | 8081 | http://localhost:8080 | Web Security |
| Nessus | 8834 | 8835 | https://localhost:8834 | Vulnerability Scanner |
| OpenVAS | 9392 | 9393 | https://localhost:9392 | Vulnerability Scanner |
| Nikto | 80 | 443 | 8080 | Web Scanner |
| Nmap | - | - | - | Network Scanner |
| Metasploit | 4444 | 4445 | - | Penetration Testing |
| Wireshark | - | - | - | Network Analysis |
| Aircrack-ng | - | - | - | WiFi Security |
| John the Ripper | - | - | - | Password Cracking |
| Hashcat | - | - | - | Password Cracking |
| Hydra | - | - | - | Brute Force |
| SQLMap | - | - | - | SQL Injection |
| W3af | 8080 | 8081 | http://localhost:8080 | Web Application Scanner |
| Skipfish | - | - | - | Web Security Scanner |
| Arachni | 7331 | 7332 | http://localhost:7331 | Web Security Scanner |
| Wapiti | - | - | - | Web Vulnerability Scanner |
| Vega | 8443 | 8444 | https://localhost:8443 | Web Security Scanner |

## CI/CD

| Tool | Default Port | Alternative Port | Web UI | Purpose |
|------|-------------|-----------------|--------|--------|
| Jenkins | 8080 | 8081 | http://localhost:8080 | CI/CD Server |
| GitLab CI | 80 | 443 | http://localhost | Git-based CI |
| GitHub Actions | - | - | - | Cloud CI/CD |
| Azure DevOps | - | - | - | Cloud CI/CD |
| CircleCI | - | - | - | Cloud CI/CD |
| Travis CI | - | - | - | Cloud CI/CD |
| Bamboo | 8085 | 8086 | http://localhost:8085 | CI/CD Server |
| TeamCity | 8111 | 8112 | http://localhost:8111 | CI/CD Server |
| Drone | 3000 | 3001 | http://localhost:3000 | CI/CD Platform |
| Concourse | 8080 | 8081 | http://localhost:8080 | CI/CD Platform |
| Tekton | 8080 | 8081 | http://localhost:8080 | Kubernetes CI |
| ArgoCD | 8080 | 8081 | http://localhost:8080 | GitOps |
| Flux | - | - | - | GitOps |
| Spinnaker | 9000 | 9001 | http://localhost:9000 | CD Platform |
| Harness | 8080 | 8081 | http://localhost:8080 | CD Platform |

## DevOps Tools

| Tool | Default Port | Alternative Port | Web UI | Purpose |
|------|-------------|-----------------|--------|--------|
| Ansible | - | - | - | Configuration Management |
| Terraform | - | - | - | Infrastructure as Code |
| Puppet | 8140 | 8141 | - | Configuration Management |
| Chef | 443 | 444 | - | Configuration Management |
| SaltStack | 4505 | 4506 | - | Configuration Management |
| Vagrant | 2222 | 2223 | - | Development Environment |
| Packer | - | - | - | Image Builder |
| Consul | 8500 | 8501 | http://localhost:8500 | Service Discovery |
| Vault | 8200 | 8201 | http://localhost:8200 | Secrets Management |
| Nomad | 4646 | 4647 | http://localhost:4646 | Workload Orchestration |
| Serf | 7946 | 7947 | - | Service Discovery |
| Etcd | 2379 | 2380 | http://localhost:2379 | Key-Value Store |
| Zookeeper | 2181 | 2182 | - | Coordination Service |

## Log Management

| Tool | Default Port | Alternative Port | Web UI | Purpose |
|------|-------------|-----------------|--------|--------|
| ELK Stack | 9200 | 9201 | http://localhost:5601 | Log Management |
| Fluentd | 24224 | 24225 | - | Log Collector |
| Logstash | 5044 | 5045 | - | Log Processing |
| Filebeat | - | - | - | Log Shipper |
| Fluent Bit | 2020 | 2021 | - | Log Processor |
| Graylog | 9000 | 9001 | http://localhost:9000 | Log Management |
| Splunk | 8000 | 8001 | http://localhost:8000 | Log Analytics |
| Loki | 3100 | 3101 | http://localhost:3100 | Log Aggregation |
| Promtail | - | - | - | Log Shipper |
| Vector | 8686 | 8687 | http://localhost:8686 | Log Router |

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
