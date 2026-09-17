# 🔌 Dev & DevOps Ports Reference
> A comprehensive collection of ports, tools, and useful commands for developers, DevOps engineers, and system administrators

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-active-brightgreen.svg)
![Made with ❤️](https://img.shields.io/badge/made%20with-%E2%9D%A4-red)

## 📖 Table of Contents
- [Development Tools](#development-tools)
- [Debugging & Dev Server Ports](#debugging--dev-server-ports)
- [Databases](#databases)
- [Vector Databases](#vector-databases)
- [AI / ML & LLM Serving](#ai--ml--llm-serving)
- [Web Servers](#web-servers)
- [API Gateways & Service Mesh](#api-gateways--service-mesh)
- [Docker & Kubernetes](#docker--kubernetes)
- [Monitoring](#monitoring)
- [Search Engines](#search-engines)
- [Message Queues](#message-queues)
- [RabbitMQ Details](#rabbitmq---complete-details)
- [Streaming, CDC & Data Integration](#streaming-cdc--data-integration)
- [Testing Tools](#testing-tools)
- [Security Tools](#security-tools)
- [CI/CD](#cicd)
- [DevOps Tools](#devops-tools)
- [Identity & Access Management](#identity--access-management)
- [Data Processing & Workflow Tools](#data-processing--workflow-tools)
- [Apache Tools](#apache-tools)
- [Big Data & Hadoop Ecosystem](#big-data--hadoop-ecosystem)
- [Log Management](#log-management)
- [System Ports](#system-ports)
- [Object Storage & File Services](#object-storage--file-services)
- [Email & Notification Services](#email--notification-services)
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
| Vite | 5173 | 4173 (preview), 3000 | `npm run dev` | [vitejs.dev](https://vitejs.dev) | Frontend Build Tool |
| Nuxt | 3000 | 3001, 8080 | `npm run dev` | [nuxt.com](https://nuxt.com) | Vue Meta-Framework |
| SvelteKit | 5173 | 4173 (preview) | `npm run dev` | [kit.svelte.dev](https://kit.svelte.dev) | Svelte Meta-Framework |
| Astro | 4321 | 4322, 3000 | `npm run dev` | [astro.build](https://astro.build) | Content-Driven Framework |
| Remix | 3000 | 3001, 5173 | `npm run dev` | [remix.run](https://remix.run) | React Framework |
| Gatsby | 8000 | 8001, 3000 | `gatsby develop` | [gatsbyjs.com](https://gatsbyjs.com) | React Static Site Generator |
| NestJS | 3000 | 3001, 8080 | `npm run start:dev` | [nestjs.com](https://nestjs.com) | Node.js Framework |
| Koa | 3000 | 3001 | `node app.js` | [koajs.com](https://koajs.com) | Node.js Framework |
| Hapi | 3000 | 3001 | `node server.js` | [hapi.dev](https://hapi.dev) | Node.js Framework |
| Deno | 8000 | 3000, 8080 | `deno run --allow-net main.ts` | [deno.com](https://deno.com) | JS/TS Runtime |
| Bun | 3000 | 3001 | `bun run index.ts` | [bun.sh](https://bun.sh) | JS Runtime & Toolkit |
| Ember | 4200 | 4201 | `ember serve` | [emberjs.com](https://emberjs.com) | Frontend Framework |
| Phoenix (Elixir) | 4000 | 4001 | `mix phx.server` | [phoenixframework.org](https://phoenixframework.org) | Elixir Framework |
| Play Framework | 9000 | 9001 | `sbt run` | [playframework.com](https://playframework.com) | JVM Framework |
| Quarkus | 8080 | 8081 | `./mvnw quarkus:dev` | [quarkus.io](https://quarkus.io) | Java Framework |
| Micronaut | 8080 | 8081 | `./gradlew run` | [micronaut.io](https://micronaut.io) | JVM Framework |
| Ktor | 8080 | 8081 | `./gradlew run` | [ktor.io](https://ktor.io) | Kotlin Framework |
| Vert.x | 8080 | 8081 | `mvn vertx:run` | [vertx.io](https://vertx.io) | JVM Toolkit |
| Meteor | 3000 | 3001 | `meteor` | [meteor.com](https://meteor.com) | Full-Stack JS |
| Storybook | 6006 | 6007 | `npm run storybook` | [storybook.js.org](https://storybook.js.org) | UI Component Workshop |
| Webpack Dev Server | 8080 | 3000 | `webpack serve` | [webpack.js.org](https://webpack.js.org) | Bundler Dev Server |
| Parcel | 1234 | 1235 | `parcel index.html` | [parceljs.org](https://parceljs.org) | Zero-Config Bundler |
| Browsersync | 3000 | 3001 | `browser-sync start --server` | [browsersync.io](https://browsersync.io) | Live Reload |
| JSON Server | 3000 | 3001 | `json-server db.json` | [github.com/typicode/json-server](https://github.com/typicode/json-server) | Mock REST API |
| http-server | 8080 | 8081 | `http-server` | [github.com/http-party/http-server](https://github.com/http-party/http-server) | Static File Server |
| Prisma Studio | 5555 | 5556 | `npx prisma studio` | [prisma.io](https://prisma.io) | Database GUI |
| Hasura | 8080 | 8081 | `hasura console` | [hasura.io](https://hasura.io) | GraphQL Engine |
| PostgREST | 3000 | 3001 | `postgrest postgrest.conf` | [postgrest.org](https://postgrest.org) | REST API for PostgreSQL |
| Supabase | 8000 | 54321 (local stack) | `supabase start` | [supabase.com](https://supabase.com) | Backend-as-a-Service |
| Appwrite | 80 | 8080 | `docker compose up -d` | [appwrite.io](https://appwrite.io) | Backend-as-a-Service |
| PocketBase | 8090 | 8091 | `./pocketbase serve` | [pocketbase.io](https://pocketbase.io) | Backend-as-a-Service |
| Parse Server | 1337 | 1338 | `npm start` | [parseplatform.org](https://parseplatform.org) | Backend-as-a-Service |
| WordPress | 80 | 8080 | `wp server` | [wordpress.org](https://wordpress.org) | CMS |
| Strapi | 1337 | 1338 | `npm run develop` | [strapi.io](https://strapi.io) | Headless CMS |
| Ghost | 2368 | 2369 | `ghost start` | [ghost.org](https://ghost.org) | CMS / Blog |
| Directus | 8055 | 8056 | `npx directus start` | [directus.io](https://directus.io) | Headless CMS |
| Payload | 3000 | 3001 | `npm run dev` | [payloadcms.com](https://payloadcms.com) | Headless CMS |
| Docusaurus | 3000 | 3001 | `npm run start` | [docusaurus.io](https://docusaurus.io) | Documentation Site |
| MkDocs | 8000 | 8001 | `mkdocs serve` | [mkdocs.org](https://mkdocs.org) | Documentation Site |
| VitePress | 5173 | 4173 (preview) | `vitepress dev` | [vitepress.dev](https://vitepress.dev) | Documentation Site |
| Hugo | 1313 | 1314 | `hugo server` | [gohugo.io](https://gohugo.io) | Static Site Generator |
| Jekyll | 4000 | 4001 | `bundle exec jekyll serve` | [jekyllrb.com](https://jekyllrb.com) | Static Site Generator |
| Medusa | 9000 | 9001 | `npm run dev` | [medusajs.com](https://medusajs.com) | E-commerce Platform |
| Saleor | 8000 | 8001 | `python manage.py runserver` | [saleor.io](https://saleor.io) | E-commerce Platform |

## Debugging & Dev Server Ports

| Tool / Runtime | Debug Port | Protocol | How to Start | Website | Purpose |
|----------------|-----------|----------|--------------|---------|--------|
| Node.js Inspector | 9229 | Chrome DevTools | `node --inspect app.js` | [nodejs.org](https://nodejs.org/en/docs/guides/debugging-getting-started) | JS Debugging |
| Deno Inspector | 9229 | Chrome DevTools | `deno run --inspect main.ts` | [deno.com](https://deno.com) | JS/TS Debugging |
| Bun Inspector | 6499 | WebSocket | `bun --inspect index.ts` | [bun.sh](https://bun.sh/docs/runtime/debugger) | JS/TS Debugging |
| Chrome DevTools Protocol | 9222 | HTTP/WS | `chrome --remote-debugging-port=9222` | [chromedevtools.github.io](https://chromedevtools.github.io/devtools-protocol) | Browser Automation |
| Python debugpy | 5678 | DAP/TCP | `python -m debugpy --listen 5678 app.py` | [github.com/microsoft/debugpy](https://github.com/microsoft/debugpy) | Python Debugging |
| PHP Xdebug | 9003 | DBGp | `xdebug.client_port=9003` | [xdebug.org](https://xdebug.org) | PHP Debugging |
| Java JDWP | 5005 | JDWP | `java -agentlib:jdwp=transport=dt_socket,server=y,address=5005` | [docs.oracle.com](https://docs.oracle.com) | JVM Debugging |
| Go Delve | 40000 | DAP/TCP | `dlv debug --headless --listen=:40000` | [github.com/go-delve/delve](https://github.com/go-delve/delve) | Go Debugging |
| Ruby rdbg | 12345 | DAP/TCP | `rdbg --open app.rb` | [github.com/ruby/debug](https://github.com/ruby/debug) | Ruby Debugging |
| JMX / RMI | 1099 | JMX | `-Dcom.sun.management.jmxremote.port=1099` | [docs.oracle.com](https://docs.oracle.com) | JVM Monitoring |
| Vite HMR | 24678 | WebSocket | automatic with `vite` | [vitejs.dev](https://vitejs.dev) | Hot Module Reload |
| React Native Metro | 8081 | HTTP/WS | `npx react-native start` | [metrobundler.dev](https://metrobundler.dev) | RN Bundler & Debugger |
| Expo Dev Server | 8081 | HTTP/WS | `npx expo start` | [expo.dev](https://expo.dev) | Expo Bundler |
| Expo Web | 19006 | HTTP | `npx expo start --web` | [expo.dev](https://expo.dev) | Expo Web Preview |
| Flutter DevTools | 9100 | HTTP | `dart devtools` | [devtools.flutter.dev](https://devtools.flutter.dev) | Flutter Debugging |
| Playwright Report | 9323 | HTTP | `npx playwright show-report` | [playwright.dev](https://playwright.dev) | Test Report Viewer |
| GDB Server | 1234 | GDB | `gdbserver :1234 ./app` | [sourceware.org/gdb](https://sourceware.org/gdb) | Native Debugging |
| OpenOCD | 3333 / 4444 | GDB / Telnet | `openocd` | [openocd.org](https://openocd.org) | Embedded Debugging |
| Android ADB | 5037 | ADB | `adb start-server` | [developer.android.com](https://developer.android.com/tools/adb) | Android Debug Bridge |
| Android Wireless ADB | 5555 | ADB | `adb tcpip 5555` | [developer.android.com](https://developer.android.com/tools/adb) | Wireless Debugging |

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
| Microsoft SQL Server | 1433 | 1434 (browser) | `mssql://localhost:1433` | [microsoft.com/sql-server](https://www.microsoft.com/sql-server) | SQL |
| Oracle Database | 1521 | 1522 | `oracle://localhost:1521` | [oracle.com/database](https://oracle.com/database) | SQL |
| IBM Db2 | 50000 | 50001 | `db2://localhost:50000` | [ibm.com/db2](https://ibm.com/db2) | SQL |
| Firebird | 3050 | 3051 | `firebird://localhost:3050` | [firebirdsql.org](https://firebirdsql.org) | SQL |
| CockroachDB | 26257 | 8080 (console) | `postgresql://localhost:26257` | [cockroachlabs.com](https://cockroachlabs.com) | Distributed SQL |
| TiDB | 4000 | 10080 (status), 2379 (PD) | `mysql://localhost:4000` | [pingcap.com](https://pingcap.com) | Distributed SQL |
| YugabyteDB | 5433 | 7000 (master), 9042 (YCQL) | `postgresql://localhost:5433` | [yugabyte.com](https://yugabyte.com) | Distributed SQL |
| ScyllaDB | 9042 | 9142 (SSL), 9180 (metrics) | `cassandra://localhost:9042` | [scylladb.com](https://scylladb.com) | NoSQL |
| Couchbase | 8091 | 8093 (query), 11210 (data) | `couchbase://localhost:11210` | [couchbase.com](https://couchbase.com) | NoSQL |
| Memcached | 11211 | 11212 | `memcached://localhost:11211` | [memcached.org](https://memcached.org) | Cache |
| DragonflyDB | 6379 | 6380 | `redis://localhost:6379` | [dragonflydb.io](https://dragonflydb.io) | Redis-Compatible Cache |
| KeyDB | 6379 | 6380 | `redis://localhost:6379` | [keydb.dev](https://keydb.dev) | Redis-Compatible Cache |
| Valkey | 6379 | 6380 | `redis://localhost:6379` | [valkey.io](https://valkey.io) | Redis-Compatible Cache |
| PgBouncer | 6432 | 6433 | `postgresql://localhost:6432` | [pgbouncer.org](https://pgbouncer.org) | PostgreSQL Pooler |
| ProxySQL | 6033 | 6032 (admin) | `mysql://localhost:6033` | [proxysql.com](https://proxysql.com) | MySQL Proxy |
| Vitess | 3306 | 15306 (vtgate), 15999 (vtctld) | `mysql://localhost:15306` | [vitess.io](https://vitess.io) | MySQL Scaling |
| FerretDB | 27017 | 27018 | `mongodb://localhost:27017` | [ferretdb.com](https://ferretdb.com) | MongoDB-Compatible (PostgreSQL) |
| QuestDB | 8812 | 9000 (web), 9009 (ILP) | `postgresql://localhost:8812` | [questdb.io](https://questdb.io) | Time Series |
| OpenTSDB | 4242 | 4243 | `http://localhost:4242` | [opentsdb.net](https://opentsdb.net) | Time Series |
| DuckDB | - | - | `duckdb://database.duckdb` | [duckdb.org](https://duckdb.org) | Embedded OLAP |
| H2 Database | 8082 (console) | 9092 (server) | `jdbc:h2:tcp://localhost:9092/~/test` | [h2database.com](https://h2database.com) | Embedded SQL |
| Redis Sentinel | 26379 | 26380 | `redis-sentinel://localhost:26379` | [redis.io](https://redis.io) | High Availability |
| Redis Cluster Bus | 16379 | 16380 | internal | [redis.io](https://redis.io) | Cluster Communication |
| MongoDB Shard | 27018 | 27019 (config) | `mongodb://localhost:27018` | [mongodb.com](https://mongodb.com) | Sharded Cluster |

### Database Admin & GUI Tools

| Tool | Default Port | Alternative Port | Web UI | Website | Purpose |
|------|-------------|-----------------|--------|---------|--------|
| pgAdmin | 5050 | 80 (legacy) | http://localhost:5050 | [pgadmin.org](https://pgadmin.org) | PostgreSQL Admin |
| Adminer | 8080 | 8081 | http://localhost:8080 | [adminer.org](https://adminer.org) | Multi-DB Admin |
| phpMyAdmin | 80 | 8080 | http://localhost | [phpmyadmin.net](https://phpmyadmin.net) | MySQL Admin |
| Mongo Express | 8081 | 8082 | http://localhost:8081 | [github.com/mongo-express](https://github.com/mongo-express/mongo-express) | MongoDB Admin |
| RedisInsight | 5540 | 8001 (legacy) | http://localhost:5540 | [redis.io/insight](https://redis.io/insight) | Redis GUI |
| CloudBeaver | 8978 | 8979 | http://localhost:8978 | [dbeaver.com/cloudbeaver](https://dbeaver.com/cloudbeaver) | Web DB Client |
| SQLPad | 3000 | 3001 | http://localhost:3000 | [sqlpad.io](https://sqlpad.io) | SQL Editor |
| NocoDB | 8080 | 8081 | http://localhost:8080 | [nocodb.com](https://nocodb.com) | No-Code DB UI |
| Baserow | 80 | 3000 | http://localhost | [baserow.io](https://baserow.io) | No-Code Database |
| Chat2DB | 10824 | 10825 | http://localhost:10824 | [chat2db.ai](https://chat2db.ai) | AI SQL Client |

## Vector Databases

| Tool | Default Port | Alternative Port | Endpoint / UI | Website | Purpose |
|------|-------------|-----------------|---------------|---------|--------|
| Qdrant | 6333 | 6334 (gRPC) | http://localhost:6333/dashboard | [qdrant.tech](https://qdrant.tech) | Vector Search Engine |
| Milvus | 19530 | 9091 (metrics) | http://localhost:9091 | [milvus.io](https://milvus.io) | Vector Database |
| Weaviate | 8080 | 50051 (gRPC) | http://localhost:8080 | [weaviate.io](https://weaviate.io) | Vector Database |
| Chroma | 8000 | 8001 | http://localhost:8000 | [trychroma.com](https://trychroma.com) | Vector Database |
| pgvector | 5432 | - | PostgreSQL extension | [github.com/pgvector/pgvector](https://github.com/pgvector/pgvector) | Vectors in PostgreSQL |
| Vespa | 8080 | 19071 (config) | http://localhost:8080 | [vespa.ai](https://vespa.ai) | Search & Vector DB |
| Marqo | 8882 | 8883 | http://localhost:8882 | [marqo.ai](https://marqo.ai) | Vector Search Engine |
| Vald | 8080 | 8081 | - | [vald.vdaas.org](https://vald.vdaas.org) | Distributed Vector Search |
| Redis Stack (RediSearch) | 6379 | 6380 | `redis://localhost:6379` | [redis.io](https://redis.io) | Vectors in Redis |
| LanceDB | - | - | embedded | [lancedb.com](https://lancedb.com) | Embedded Vector DB |
| FAISS | - | - | library | [github.com/facebookresearch/faiss](https://github.com/facebookresearch/faiss) | Similarity Search Library |
| Pinecone | - | - | cloud | [pinecone.io](https://pinecone.io) | Managed Vector DB |
| Zilliz Cloud | - | - | cloud | [zilliz.com](https://zilliz.com) | Managed Milvus |

## AI / ML & LLM Serving

| Tool | Default Port | Alternative Port | Endpoint / UI | Website | Purpose |
|------|-------------|-----------------|---------------|---------|--------|
| Ollama | 11434 | 11435 | http://localhost:11434 | [ollama.com](https://ollama.com) | Local LLM Runtime |
| vLLM | 8000 | 8001 | http://localhost:8000/docs | [docs.vllm.ai](https://docs.vllm.ai) | LLM Inference Server |
| LM Studio | 1234 | 1235 | http://localhost:1234 | [lmstudio.ai](https://lmstudio.ai) | Local LLM Server |
| llama.cpp Server | 8080 | 8081 | http://localhost:8080 | [github.com/ggerganov/llama.cpp](https://github.com/ggerganov/llama.cpp) | LLM Inference |
| LocalAI | 8080 | 8081 | http://localhost:8080 | [localai.io](https://localai.io) | OpenAI-Compatible API |
| Hugging Face TGI | 80 | 8080 (Docker) | http://localhost | [huggingface.co/docs/text-generation-inference](https://huggingface.co/docs/text-generation-inference) | LLM Inference |
| Xinference | 9997 | 9998 | http://localhost:9997 | [inference.readthedocs.io](https://inference.readthedocs.io) | Model Serving |
| Text Generation WebUI | 7860 | 5000 (API) | http://localhost:7860 | [github.com/oobabooga/text-generation-webui](https://github.com/oobabooga/text-generation-webui) | LLM Playground |
| Open WebUI | 8080 | 3000 | http://localhost:8080 | [openwebui.com](https://openwebui.com) | LLM Web Interface |
| LibreChat | 3080 | 3081 | http://localhost:3080 | [librechat.ai](https://librechat.ai) | Multi-LLM Chat |
| AnythingLLM | 3001 | 3002 | http://localhost:3001 | [anythingllm.com](https://anythingllm.com) | RAG & Chat UI |
| Dify | 80 | 5001 (API) | http://localhost | [dify.ai](https://dify.ai) | LLM App Platform |
| Flowise | 3000 | 3001 | http://localhost:3000 | [flowiseai.com](https://flowiseai.com) | LLM Flow Builder |
| Langflow | 7860 | 7861 | http://localhost:7860 | [langflow.org](https://langflow.org) | Visual LLM Builder |
| n8n | 5678 | 5679 | http://localhost:5678 | [n8n.io](https://n8n.io) | Workflow Automation |
| ComfyUI | 8188 | 8189 | http://localhost:8188 | [comfy.org](https://comfy.org) | Diffusion UI |
| AUTOMATIC1111 (SD WebUI) | 7860 | 7861 | http://localhost:7860 | [github.com/AUTOMATIC1111/stable-diffusion-webui](https://github.com/AUTOMATIC1111/stable-diffusion-webui) | Image Generation |
| InvokeAI | 9090 | 9091 | http://localhost:9090 | [invoke.ai](https://invoke.ai) | Image Generation |
| Jupyter Notebook / Lab | 8888 | 8889 | http://localhost:8888 | [jupyter.org](https://jupyter.org) | Notebooks |
| JupyterHub | 8000 | 8001 | http://localhost:8000 | [jupyter.org/hub](https://jupyter.org/hub) | Multi-User Notebooks |
| RStudio Server | 8787 | 8788 | http://localhost:8787 | [posit.co](https://posit.co) | R IDE |
| MLflow | 5000 | 5001 | http://localhost:5000 | [mlflow.org](https://mlflow.org) | ML Lifecycle |
| TensorBoard | 6006 | 6007 | http://localhost:6006 | [tensorflow.org/tensorboard](https://tensorflow.org/tensorboard) | Training Visualization |
| Ray Dashboard | 8265 | 6379 (GCS), 10001 (client) | http://localhost:8265 | [ray.io](https://ray.io) | Distributed ML |
| TorchServe | 8080 | 8081 (mgmt), 8082 (metrics) | http://localhost:8080 | [pytorch.org/serve](https://pytorch.org/serve) | PyTorch Serving |
| TensorFlow Serving | 8501 | 8500 (gRPC) | http://localhost:8501 | [tensorflow.org/serving](https://tensorflow.org/serving) | TF Model Serving |
| Triton Inference Server | 8000 | 8001 (gRPC), 8002 (metrics) | http://localhost:8000 | [developer.nvidia.com/triton-inference-server](https://developer.nvidia.com/triton-inference-server) | Multi-Framework Serving |
| Gradio | 7860 | 7861 | http://localhost:7860 | [gradio.app](https://gradio.app) | ML Demo UI |
| Streamlit | 8501 | 8502 | http://localhost:8501 | [streamlit.io](https://streamlit.io) | Data App Framework |
| Dash | 8050 | 8051 | http://localhost:8050 | [dash.plotly.com](https://dash.plotly.com) | Data App Framework |
| Panel | 5006 | 5007 | http://localhost:5006 | [panel.holoviz.org](https://panel.holoviz.org) | Data App Framework |
| Weights & Biases (local) | 8080 | 8081 | http://localhost:8080 | [wandb.ai](https://wandb.ai) | Experiment Tracking |

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
| OpenResty | 80 | 443 | 8080 | [openresty.org](https://openresty.org) | Nginx + Lua |
| Nginx Proxy Manager | 80 | 443 | 81 (admin UI) | [nginxproxymanager.com](https://nginxproxymanager.com) | Reverse Proxy UI |
| Caddy Admin API | 2019 | - | - | [caddyserver.com](https://caddyserver.com) | Caddy Config API |
| NGINX Unit | 80 | 443 | 8080 | [unit.nginx.org](https://unit.nginx.org) | Polyglot App Server |
| OpenLiteSpeed | 80 | 443 | 8088 (admin) | [openlitespeed.org](https://openlitespeed.org) | Web Server |
| LiteSpeed | 80 | 443 | 7080 (admin) | [litespeedtech.com](https://litespeedtech.com) | Web Server |
| Kestrel (ASP.NET) | 5000 | 5001 (HTTPS) | - | [learn.microsoft.com](https://learn.microsoft.com/aspnet/core/fundamentals/servers/kestrel) | .NET Web Server |
| Gunicorn | 8000 | 8001 | - | [gunicorn.org](https://gunicorn.org) | Python WSGI Server |
| uWSGI | 8000 | 8001 | 1717 (stats) | [uwsgi-docs.readthedocs.io](https://uwsgi-docs.readthedocs.io) | Python App Server |
| Hypercorn | 8000 | 8001 | - | [hypercorn.readthedocs.io](https://hypercorn.readthedocs.io) | Python ASGI Server |
| Daphne | 8000 | 8001 | - | [github.com/django/daphne](https://github.com/django/daphne) | Django ASGI Server |
| Puma | 9292 | 3000 | - | [puma.io](https://puma.io) | Ruby App Server |
| Unicorn | 8080 | 8081 | - | [unicorn.bogomips.org](https://unicorn.bogomips.org) | Ruby App Server |
| WildFly | 8080 | 9990 (mgmt) | - | [wildfly.org](https://wildfly.org) | Java App Server |
| Oracle WebLogic | 7001 | 7002 (SSL) | - | [oracle.com/weblogic](https://oracle.com/weblogic) | Java App Server |
| IBM WebSphere | 9080 | 9443 (SSL) | 9043 (admin) | [ibm.com/websphere](https://ibm.com/websphere) | Java App Server |
| GlassFish | 8080 | 8181 (SSL) | 4848 (admin) | [glassfish.org](https://glassfish.org) | Java App Server |
| Payara | 8080 | 8181 (SSL) | 4848 (admin) | [payara.fish](https://payara.fish) | Java App Server |
| Open Liberty | 9080 | 9443 (SSL) | - | [openliberty.io](https://openliberty.io) | Java App Server |

## API Gateways & Service Mesh

| Tool | Default Port | Alternative Ports | Web UI | Website | Purpose |
|------|-------------|------------------|--------|---------|--------|
| Kong | 8000 | 8443 (TLS), 8001 (admin), 8002 (manager) | http://localhost:8001 | [konghq.com](https://konghq.com) | API Gateway |
| Konga | 1337 | 1338 | http://localhost:1337 | [github.com/pantsel/konga](https://github.com/pantsel/konga) | Kong UI |
| Apache APISIX | 9080 | 9443 (TLS), 9180 (admin), 9000 (dashboard) | http://localhost:9000 | [apisix.apache.org](https://apisix.apache.org) | API Gateway |
| KrakenD | 8080 | 8081 | - | [krakend.io](https://krakend.io) | API Gateway |
| Tyk Gateway | 8080 | 8081 | http://localhost:3000 (dashboard) | [tyk.io](https://tyk.io) | API Gateway |
| Emissary-Ingress | 8080 | 8443, 8877 (admin) | - | [emissary-ingress.dev](https://emissary-ingress.dev) | Kubernetes Gateway |
| Gloo Edge | 8080 | 8443 | - | [solo.io/gloo-edge](https://solo.io/gloo-edge) | API Gateway |
| Traefik Dashboard | 8080 | 9000 (legacy) | http://localhost:8080 | [traefik.io](https://traefik.io) | Gateway Dashboard |
| Envoy Admin | 9901 | 15000 (Istio) | http://localhost:9901 | [envoyproxy.io](https://envoyproxy.io) | Proxy Admin |
| Istio Ingress Gateway | 80 | 443 | - | [istio.io](https://istio.io) | Service Mesh Gateway |
| Istio Envoy Sidecar | 15001 | 15006, 15008, 15021 (health), 15090 (metrics) | http://localhost:15000 | [istio.io](https://istio.io) | Sidecar Proxy |
| Istiod (Control Plane) | 15010 | 15012, 15014 (metrics), 15017 | - | [istio.io](https://istio.io) | Istio Control Plane |
| Kiali | 20001 | 20002 | http://localhost:20001 | [kiali.io](https://kiali.io) | Istio UI |
| Linkerd Proxy | 4143 | 4190 (tap), 4191 (admin) | - | [linkerd.io](https://linkerd.io) | Service Mesh Proxy |
| Linkerd Viz | 8084 | 50750 | http://localhost:8084 | [linkerd.io](https://linkerd.io) | Linkerd Dashboard |
| Open Service Mesh | 4443 | 15128 | - | [openservicemesh.io](https://openservicemesh.io) | Service Mesh |
| Consul Connect | 8500 | 8502 (gRPC) | http://localhost:8500 | [consul.io](https://consul.io) | Service Mesh |
| Kuma | 5681 | 5682 (data plane) | http://localhost:5681 | [kuma.io](https://kuma.io) | Service Mesh |
| Ambassador Edge Stack | 8080 | 8443, 8877 (admin) | - | [getambassador.io](https://getambassador.io) | API Gateway |

## Docker & Kubernetes

| Tool | Main Port | Secure Port | Registry Port | Website | Purpose |
|------|-----------|------------|---------------|---------|--------|
| Docker Engine | 2375 | 2376 | 5000 | [docker.com](https://docker.com) | Container Engine |
| Docker Compose | Dynamic | Dynamic (host-assigned) | - | [docs.docker.com/compose](https://docs.docker.com/compose) | Multi-container |
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
| Podman | - | 2375 (REST API) | - | [podman.io](https://podman.io) | Daemonless Containers |
| containerd | - | - | - | [containerd.io](https://containerd.io) | Container Runtime |
| BuildKit | - | - | - | [github.com/moby/buildkit](https://github.com/moby/buildkit) | Build Engine |

### Kubernetes Component Ports

| Component | Port | Protocol | Purpose |
|-----------|------|----------|--------|
| kube-apiserver | 6443 | HTTPS | Kubernetes API |
| etcd (client) | 2379 | HTTP/gRPC | Cluster key-value store |
| etcd (peer) | 2380 | HTTPS | etcd cluster communication |
| kubelet API | 10250 | HTTPS | Node agent API |
| kubelet (read-only) | 10255 | HTTP | Deprecated metrics endpoint |
| kube-scheduler | 10259 | HTTPS | Scheduler metrics/health |
| kube-controller-manager | 10257 | HTTPS | Controller metrics/health |
| kube-proxy | 10256 | HTTP | Health & metrics |
| NodePort Services | 30000-32767 | TCP/UDP | External service access |
| CoreDNS | 53 | UDP/TCP | Cluster DNS |
| CoreDNS metrics | 9153 | HTTP | DNS metrics |
| metrics-server | 4443 | HTTPS | Cluster metrics |
| Kubernetes Dashboard | 8443 | HTTPS | Web UI |
| kubectl proxy | 8001 | HTTP | Local API proxy |

### Kubernetes CNI & Networking Ports

| Component | Port | Protocol | Purpose |
|-----------|------|----------|--------|
| Calico | 179 | BGP | Route exchange |
| Calico VXLAN | 4789 | UDP | Overlay network |
| Flannel VXLAN | 8472 | UDP | Overlay network |
| Cilium health | 4240 | TCP | Health checks |
| Cilium Hubble | 4244 | TCP | Hubble observability |
| Cilium | 4245, 4250, 4251 | TCP | Cluster communication |
| Weave Net | 6783 | TCP/UDP | Control & data |
| Weave Net fast path | 6784 | UDP | Fast data path |
| MetalLB memberlist | 7946 | TCP/UDP | Speaker discovery |
| WireGuard overlay | 51820 | UDP | Encrypted overlay |
| NGINX Ingress Controller | 80, 443 | TCP | Traffic entry |
| NGINX Ingress metrics | 10254 | HTTP | Metrics & health |
| HAProxy Ingress | 80, 443 | TCP | Traffic entry |
| Contour / Envoy | 80, 443 | TCP | Traffic entry |
| Contour Envoy admin | 9001 | HTTP | Envoy admin |

### Container Registries, Artifacts & Git Services

| Tool | Default Port | Alternative Ports | Web UI | Website | Purpose |
|------|-------------|------------------|--------|---------|--------|
| Docker Registry | 5000 | 5001 | - | [distribution.github.io](https://distribution.github.io/distribution) | Private Registry |
| Harbor | 80 | 443, 8080 (core) | https://localhost | [goharbor.io](https://goharbor.io) | Registry + UI |
| Nexus Repository | 8081 | 8082/8083 (Docker) | http://localhost:8081 | [sonatype.com](https://sonatype.com) | Artifact Repository |
| JFrog Artifactory | 8081 | 8082 (Docker) | http://localhost:8081 | [jfrog.com](https://jfrog.com) | Artifact Repository |
| Verdaccio | 4873 | 4874 | http://localhost:4873 | [verdaccio.org](https://verdaccio.org) | Private npm Registry |
| devpi | 3141 | 3142 | http://localhost:3141 | [devpi.net](https://devpi.net) | Private PyPI |
| Gitea | 3000 | 2222 (SSH, Docker), 22 (SSH) | http://localhost:3000 | [gitea.com](https://gitea.com) | Git Service |
| Forgejo | 3000 | 2222 (SSH, Docker) | http://localhost:3000 | [forgejo.org](https://forgejo.org) | Git Service |
| Gogs | 3000 | 22 (SSH) | http://localhost:3000 | [gogs.io](https://gogs.io) | Git Service |
| GitLab | 80 | 443, 22 (SSH), 5050 (registry) | http://localhost | [gitlab.com](https://gitlab.com) | Git Platform |
| Gerrit | 8080 | 29418 (SSH) | http://localhost:8080 | [gerritcodereview.com](https://gerritcodereview.com) | Code Review |
| Bitbucket Server | 7990 | 7999 (SSH) | http://localhost:7990 | [atlassian.com/bitbucket](https://atlassian.com/bitbucket) | Git Platform |

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
| Alertmanager | 9093 | 9094 | http://localhost:9093 | [prometheus.io](https://prometheus.io) | Alert Routing |
| node_exporter | 9100 | 9101 | http://localhost:9100 | [prometheus.io](https://prometheus.io) | Host Metrics |
| Pushgateway | 9091 | 9092 | http://localhost:9091 | [prometheus.io](https://prometheus.io) | Batch Job Metrics |
| cAdvisor | 8080 | 8081 | http://localhost:8080 | [github.com/google/cadvisor](https://github.com/google/cadvisor) | Container Metrics |
| kube-state-metrics | 8080 | 8081 | - | [github.com/kubernetes/kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) | Kubernetes Object Metrics |
| VictoriaMetrics | 8428 | 8429 (vmagent), 8880 (vmalert) | http://localhost:8428 | [victoriametrics.com](https://victoriametrics.com) | Time Series DB |
| Thanos Query | 10902 | 10901 (gRPC) | http://localhost:10902 | [thanos.io](https://thanos.io) | Long-Term Metrics |
| Grafana Mimir | 9009 | 9095 (gRPC) | http://localhost:9009 | [grafana.com/oss/mimir](https://grafana.com/oss/mimir) | Scalable Metrics |
| Grafana Tempo | 3200 | 4317/4318 (OTLP) | http://localhost:3200 | [grafana.com/oss/tempo](https://grafana.com/oss/tempo) | Distributed Tracing |
| OpenTelemetry Collector | 4317 (gRPC) | 4318 (HTTP), 8888 (metrics), 13133 (health) | - | [opentelemetry.io](https://opentelemetry.io) | Telemetry Pipeline |
| Netdata | 19999 | 20000 | http://localhost:19999 | [netdata.cloud](https://netdata.cloud) | Real-Time Monitoring |
| Uptime Kuma | 3001 | 3002 | http://localhost:3001 | [github.com/louislam/uptime-kuma](https://github.com/louislam/uptime-kuma) | Uptime Monitoring |
| Healthchecks | 8000 | 8001 | http://localhost:8000 | [healthchecks.io](https://healthchecks.io) | Cron Job Monitoring |
| Gatus | 8080 | 8081 | http://localhost:8080 | [github.com/TwiN/gatus](https://github.com/TwiN/gatus) | Status Dashboard |
| Beszel | 8090 | 8091 | http://localhost:8090 | [beszel.dev](https://beszel.dev) | Lightweight Monitoring |
| Dozzle | 8080 | 8081 | http://localhost:8080 | [dozzle.dev](https://dozzle.dev) | Docker Log Viewer |
| Icinga 2 | 5665 | 5666 | http://localhost/icingaweb2 | [icinga.com](https://icinga.com) | Infrastructure Monitoring |
| Zabbix Server | 10051 | 10052 | http://localhost (frontend) | [zabbix.com](https://zabbix.com) | Network Monitoring |
| Zabbix Agent | 10050 | 10051 | - | [zabbix.com](https://zabbix.com) | Host Agent |
| Glances | 61208 | 61209 (XML-RPC) | http://localhost:61208 | [glances.readthedocs.io](https://glances.readthedocs.io) | System Monitoring |
| Checkmk | 5000 | 6557 (agent) | http://localhost:5000 | [checkmk.com](https://checkmk.com) | Infrastructure Monitoring |

### Prometheus Exporters

| Exporter | Default Port | Monitors | Website |
|----------|-------------|----------|---------|
| node_exporter | 9100 | Linux/Unix hosts | [github.com/prometheus/node_exporter](https://github.com/prometheus/node_exporter) |
| windows_exporter | 9182 | Windows hosts | [github.com/prometheus-community/windows_exporter](https://github.com/prometheus-community/windows_exporter) |
| blackbox_exporter | 9115 | HTTP/TCP/ICMP probes | [github.com/prometheus/blackbox_exporter](https://github.com/prometheus/blackbox_exporter) |
| postgres_exporter | 9187 | PostgreSQL | [github.com/prometheus-community/postgres_exporter](https://github.com/prometheus-community/postgres_exporter) |
| mysqld_exporter | 9104 | MySQL/MariaDB | [github.com/prometheus/mysqld_exporter](https://github.com/prometheus/mysqld_exporter) |
| redis_exporter | 9121 | Redis | [github.com/oliver006/redis_exporter](https://github.com/oliver006/redis_exporter) |
| mongodb_exporter | 9216 | MongoDB | [github.com/percona/mongodb_exporter](https://github.com/percona/mongodb_exporter) |
| elasticsearch_exporter | 9114 | Elasticsearch | [github.com/prometheus-community/elasticsearch_exporter](https://github.com/prometheus-community/elasticsearch_exporter) |
| kafka_exporter | 9308 | Kafka | [github.com/danielqsj/kafka_exporter](https://github.com/danielqsj/kafka_exporter) |
| nginx-prometheus-exporter | 9113 | Nginx | [github.com/nginxinc/nginx-prometheus-exporter](https://github.com/nginxinc/nginx-prometheus-exporter) |
| haproxy_exporter | 9101 | HAProxy | [github.com/prometheus/haproxy_exporter](https://github.com/prometheus/haproxy_exporter) |
| statsd_exporter | 9102 | StatsD metrics | [github.com/prometheus/statsd_exporter](https://github.com/prometheus/statsd_exporter) |
| snmp_exporter | 9116 | SNMP devices | [github.com/prometheus/snmp_exporter](https://github.com/prometheus/snmp_exporter) |
| process-exporter | 9256 | Linux processes | [github.com/ncabatoff/process-exporter](https://github.com/ncabatoff/process-exporter) |
| json_exporter | 7979 | JSON endpoints | [github.com/prometheus-community/json_exporter](https://github.com/prometheus-community/json_exporter) |

## Search Engines

| Tool | Default Port | Alternative Ports | Web UI | Website | Purpose |
|------|-------------|------------------|--------|---------|--------|
| Elasticsearch | 9200 | 9201 (HTTP), 9300/9301 (transport) | http://localhost:9200 | [elastic.co](https://elastic.co) | Search & Analytics |
| OpenSearch | 9200 | 9300 (transport) | http://localhost:9200 | [opensearch.org](https://opensearch.org) | Search & Analytics |
| OpenSearch Dashboards | 5601 | 5602 | http://localhost:5601 | [opensearch.org](https://opensearch.org) | Dashboards |
| Kibana | 5601 | 5602 | http://localhost:5601 | [elastic.co/kibana](https://elastic.co/kibana) | Dashboards |
| Meilisearch | 7700 | 7701 | http://localhost:7700 | [meilisearch.com](https://meilisearch.com) | Instant Search |
| Typesense | 8108 | 8109 | http://localhost:8108 | [typesense.org](https://typesense.org) | Typo-Tolerant Search |
| Apache Solr | 8983 | 8984 | http://localhost:8983 | [solr.apache.org](https://solr.apache.org) | Enterprise Search |
| Sphinx | 9312 | 9306 (MySQL), 9308 (HTTP) | - | [sphinxsearch.com](https://sphinxsearch.com) | Full-Text Search |
| Manticore Search | 9306 | 9312 (binary), 9308 (HTTP) | http://localhost:9308 | [manticoresearch.com](https://manticoresearch.com) | Full-Text Search |
| Quickwit | 7280 | 7281 (gRPC) | http://localhost:7280 | [quickwit.io](https://quickwit.io) | Log Search Engine |
| ZincSearch | 4080 | 4081 | http://localhost:4080 | [zincsearch.com](https://zincsearch.com) | Lightweight Search |
| Typesense Dashboard | 8108 | - | http://localhost:8108 | [typesense.org](https://typesense.org) | Typesense UI |
| Algolia | - | - | cloud | [algolia.com](https://algolia.com) | Search API |
| Vespa | 8080 | 19071 | http://localhost:8080 | [vespa.ai](https://vespa.ai) | Search & Vector |
| Sonic | 1491 | - | - | [github.com/valeriansaliou/sonic](https://github.com/valeriansaliou/sonic) | Lightweight Search |

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
| Redpanda | 8082 (Pandaproxy) | 9092 (Kafka API), 9644 (admin), 8081 (schema) | [redpanda.com](https://redpanda.com) | Kafka-Compatible Streaming |
| RabbitMQ Stream | 5552 | 5553 | [rabbitmq.com](https://rabbitmq.com) | Stream Protocol |
| Kafka KRaft Controller | 9093 | 9094 | [kafka.apache.org](https://kafka.apache.org) | KRaft Controller |
| Kafka Connect | 8083 | 8084 | [kafka.apache.org](https://kafka.apache.org) | Data Integration |
| Kafka REST Proxy | 8082 | 8083 | [docs.confluent.io](https://docs.confluent.io/platform/current/kafka-rest) | REST Gateway |
| Confluent Schema Registry | 8081 | 8082 | [docs.confluent.io](https://docs.confluent.io/platform/current/schema-registry) | Schema Management |
| ksqlDB | 8088 | 8089 | [ksqldb.io](https://ksqldb.io) | Streaming SQL |
| Kafka UI (Provectus) | 8080 | 8081 | [github.com/provectus/kafka-ui](https://github.com/provectus/kafka-ui) | Kafka Web UI |
| AKHQ | 8080 | 8081 | [akhq.io](https://akhq.io) | Kafka Web UI |
| Kafdrop | 9000 | 9001 | [github.com/obsidiandynamics/kafdrop](https://github.com/obsidiandynamics/kafdrop) | Kafka Web UI |
| Redpanda Console | 8080 | 8081 | [redpanda.com](https://redpanda.com) | Kafka Web UI |
| Pulsar Manager | 9527 | 9528 | [pulsar.apache.org](https://pulsar.apache.org) | Pulsar Web UI |
| Apache BookKeeper | 3181 | 3182 | [bookkeeper.apache.org](https://bookkeeper.apache.org) | Pulsar Storage |
| NATS Cluster Route | 6222 | - | [nats.io](https://nats.io) | Cluster Communication |
| MQTT over TLS | 8883 | 8884 | [mqtt.org](https://mqtt.org) | Secure MQTT |
| MQTT over WebSocket | 8083 | 8084 (TLS) | [mqtt.org](https://mqtt.org) | MQTT for Browsers |
| IBM MQ | 1414 | 9443 (console) | [ibm.com/products/mq](https://ibm.com/products/mq) | Enterprise Messaging |
| TIBCO EMS | 7222 | 7223 | [tibco.com](https://tibco.com) | Enterprise Messaging |
| Solace PubSub+ | 55555 | 8080 (SEMP), 1943 (TLS) | [solace.com](https://solace.com) | Event Broker |
| Beanstalkd | 11300 | 11301 | [beanstalkd.github.io](https://beanstalkd.github.io) | Work Queue |
| NSQ | 4150 | 4151 (admin), 4160/4161 (HTTP) | [nsq.io](https://nsq.io) | Distributed Queue |

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

## Streaming, CDC & Data Integration

| Tool | Default Port | Alternative Ports | Web UI | Website | Purpose |
|------|-------------|------------------|--------|---------|--------|
| Debezium | 8083 (via Kafka Connect) | 8084 | - | [debezium.io](https://debezium.io) | Change Data Capture |
| Confluent Schema Registry | 8081 | 8082 | - | [docs.confluent.io](https://docs.confluent.io/platform/current/schema-registry) | Schema Management |
| Karapace | 8081 | 8082 | - | [github.com/Aiven-Open/karapace](https://github.com/Aiven-Open/karapace) | Schema Registry |
| ksqlDB | 8088 | 8089 | - | [ksqldb.io](https://ksqldb.io) | Streaming SQL |
| Kafka REST Proxy | 8082 | 8083 | - | [docs.confluent.io](https://docs.confluent.io/platform/current/kafka-rest) | REST Gateway |
| Kafka UI (Provectus) | 8080 | 8081 | http://localhost:8080 | [github.com/provectus/kafka-ui](https://github.com/provectus/kafka-ui) | Kafka UI |
| AKHQ | 8080 | 8081 | http://localhost:8080 | [akhq.io](https://akhq.io) | Kafka UI |
| Kafdrop | 9000 | 9001 | http://localhost:9000 | [github.com/obsidiandynamics/kafdrop](https://github.com/obsidiandynamics/kafdrop) | Kafka UI |
| Redpanda Console | 8080 | 8081 | http://localhost:8080 | [redpanda.com](https://redpanda.com) | Kafka UI |
| Pulsar Manager | 9527 | 9528 | http://localhost:9527 | [pulsar.apache.org](https://pulsar.apache.org) | Pulsar UI |
| Apache BookKeeper | 3181 | 3182 | - | [bookkeeper.apache.org](https://bookkeeper.apache.org) | Pulsar Storage |
| Airbyte | 8000 | 8001 (API) | http://localhost:8000 | [airbyte.com](https://airbyte.com) | ELT Platform |
| dbt Docs | 8080 | 8081 | http://localhost:8080 | [getdbt.com](https://getdbt.com) | Transformation Docs |
| Meltano | 5000 | 5001 | http://localhost:5000 | [meltano.com](https://meltano.com) | ELT |
| Apache SeaTunnel | 5801 | - | http://localhost:5801 | [seatunnel.apache.org](https://seatunnel.apache.org) | Data Integration |
| Maxwell | - | - | - | [maxwells-daemon.io](https://maxwells-daemon.io) | MySQL CDC |
| Redpanda Connect (Benthos) | 4195 | 4196 | - | [redpanda.com/connect](https://redpanda.com/connect) | Stream Processing |

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

## Identity & Access Management

| Tool | Default Port | Alternative Ports | Web UI | Website | Purpose |
|------|-------------|------------------|--------|---------|--------|
| Keycloak | 8080 | 9000 (health/mgmt) | http://localhost:8080 | [keycloak.org](https://keycloak.org) | Identity & SSO |
| Authentik | 9000 | 9443 (HTTPS) | http://localhost:9000 | [goauthentik.io](https://goauthentik.io) | Identity Provider |
| Zitadel | 8080 | 8081 | http://localhost:8080 | [zitadel.com](https://zitadel.com) | Identity Platform |
| Casdoor | 8000 | 8001 | http://localhost:8000 | [casdoor.org](https://casdoor.org) | Identity & SSO |
| Ory Hydra | 4444 | 4445 (admin) | - | [ory.sh/hydra](https://ory.sh/hydra) | OAuth2 Server |
| Ory Kratos | 4433 | 4434 (admin) | - | [ory.sh/kratos](https://ory.sh/kratos) | Identity Management |
| Ory Keto | 4456 | 4466 (admin) | - | [ory.sh/keto](https://ory.sh/keto) | Authorization |
| Ory Oathkeeper | 4455 | 4456 (API) | - | [ory.sh/oathkeeper](https://ory.sh/oathkeeper) | Identity Proxy |
| Dex | 5556 | 5557 | - | [dexidp.io](https://dexidp.io) | OIDC Connector |
| Authelia | 9091 | 9092 | http://localhost:9091 | [authelia.com](https://authelia.com) | 2FA Portal |
| OAuth2 Proxy | 4180 | 4181 | - | [oauth2-proxy.github.io](https://oauth2-proxy.github.io) | Auth Proxy |
| Logto | 3001 | 3002 (admin) | http://localhost:3001 | [logto.io](https://logto.io) | Identity Platform |
| SuperTokens | 3567 | 3568 | - | [supertokens.com](https://supertokens.com) | Auth Service |
| FusionAuth | 9011 | 9012 | http://localhost:9011 | [fusionauth.io](https://fusionauth.io) | Identity Platform |
| WSO2 Identity Server | 9443 | 9763 | https://localhost:9443 | [wso2.com](https://wso2.com) | Identity Server |
| OpenLDAP | 389 | 636 (LDAPS) | - | [openldap.org](https://openldap.org) | Directory Server |
| 389 Directory Server | 389 | 636 (LDAPS) | - | [port389.org](https://port389.org) | Directory Server |
| Apache Directory Server | 10389 | 10636 (LDAPS) | - | [directory.apache.org](https://directory.apache.org) | Directory Server |
| FreeIPA | 389 | 636 (LDAPS), 88 (Kerberos), 80/443 (web) | https://localhost | [freeipa.org](https://freeipa.org) | Identity Management |
| HashiCorp Vault | 8200 | 8201 (cluster) | http://localhost:8200 | [vaultproject.io](https://vaultproject.io) | Secrets Management |
| OpenBao | 8200 | 8201 (cluster) | http://localhost:8200 | [openbao.org](https://openbao.org) | Secrets Management |
| Infisical | 80 | 8080 (API) | http://localhost | [infisical.com](https://infisical.com) | Secrets Management |
| Teleport | 3023 (auth) | 3024 (SSH), 3025 (proxy), 3022 (node), 3028 (k8s), 3080 (web) | https://localhost:3080 | [goteleport.com](https://goteleport.com) | Access Plane |
| Boundary | 9200 | 9201 (cluster), 9202 (proxy) | http://localhost:9200 | [boundaryproject.io](https://boundaryproject.io) | Secure Access |
| step-ca | 9000 | 9001 | - | [smallstep.com](https://smallstep.com) | Private CA |
| SPIRE Server | 8081 | - | - | [spiffe.io](https://spiffe.io) | Workload Identity |
| Kanidm | 8443 | 3636 (LDAP) | https://localhost:8443 | [kanidm.com](https://kanidm.com) | Identity Management |
| Okta / Auth0 / Entra ID | - | - | cloud | [okta.com](https://okta.com) | Cloud Identity |
| Clerk | - | - | cloud | [clerk.com](https://clerk.com) | Auth for Apps |

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

## Big Data & Hadoop Ecosystem

### HDFS & YARN

| Component | Default Port | Alternative Ports | Purpose |
|-----------|-------------|------------------|--------|
| NameNode RPC | 8020 | 9000 (legacy) | HDFS RPC |
| NameNode Web UI | 9870 | 50070 (Hadoop 2) | HDFS UI |
| DataNode Data Transfer | 9864 | 50075 (Hadoop 2) | Block transfer |
| DataNode IPC | 9867 | 50010 | Internal IPC |
| Secondary NameNode | 9868 | 50090 | Checkpointing |
| JournalNode | 8485 | 8480 | HA edit logs |
| YARN ResourceManager | 8088 | 8032 (scheduler), 8030 (tracker) | Resource UI |
| YARN NodeManager | 8042 | 8041 (IPC) | Node UI |
| YARN Timeline Server | 8188 | 10200 | Application history |
| MapReduce JobHistory | 19888 | 10020 | Job history |
| MapReduce Shuffle | 13562 | - | Shuffle handler |

### Hive, HBase & Warehouse

| Component | Default Port | Alternative Ports | Purpose |
|-----------|-------------|------------------|--------|
| Hive Metastore | 9083 | 9084 | Metadata service |
| HiveServer2 | 10000 | 10002 (HTTP) | SQL endpoint |
| Hive WebHCat | 50111 | - | REST API |
| HBase Master | 16000 | 16010 (web) | HBase master |
| HBase RegionServer | 16020 | 16030 (web) | Region server |
| HBase REST | 8080 | 8085 | REST API |
| HBase Thrift | 9090 | 9095 | Thrift API |
| Apache Phoenix | 8765 | - | SQL on HBase |
| Apache Impala | 21050 | 21000 (web), 25000/25010 (HS2) | MPP SQL |
| Apache Kudu | 7050 | 7051 (web), 8050/8051 (tablet) | Columnar storage |
| Apache Accumulo | 9999 | 9997, 50095 (monitor) | Key-value store |
| Apache Kylin | 7070 | 7071 | OLAP cube |
| Apache Falcon | 15000 | 15443 (TLS) | Data governance |
| Apache Sentry | 8038 | - | Authorization (legacy) |

### Spark, Flink & Stream Processing

| Component | Default Port | Alternative Ports | Purpose |
|-----------|-------------|------------------|--------|
| Spark Master | 7077 | 8080 (web UI) | Cluster manager |
| Spark Worker | 8081 | 8082 | Worker UI |
| Spark Application UI | 4040 | 4041+ (multiple apps) | Job UI |
| Spark History Server | 18080 | - | Job history |
| Spark Thrift Server | 10000 | 10001 | SQL endpoint |
| Spark REST API | 6066 | - | Job submission |
| Flink JobManager | 8081 | 6123 (RPC), 6124 (blob) | Web UI |
| Flink TaskManager | 6121 | 6122, 6125 (query) | Data plane |
| Flink History Server | 8082 | 8083 | Job history |
| Storm Nimbus | 6627 | 8080 (UI) | Cluster master |
| Storm Supervisor | 6700 | 6701, 6702, 6703 | Worker slots |
| Storm DRPC | 3772 | 3773 | RPC |
| Trino / Presto | 8080 | 8443 (TLS) | Distributed SQL |
| Apache Drill | 8047 | 8048 | SQL on Hadoop |

### ClickHouse & OLAP Details

| Service | Port | Protocol | Purpose |
|---------|------|----------|--------|
| ClickHouse HTTP | 8123 | HTTP | Query interface |
| ClickHouse Native | 9000 | TCP | Native protocol |
| ClickHouse MySQL | 9004 | MySQL | MySQL compatibility |
| ClickHouse PostgreSQL | 9005 | PostgreSQL | PostgreSQL compatibility |
| ClickHouse Interserver | 9009 | TCP | Replication |
| ClickHouse Keeper | 9181 | TCP | Coordination |

### Managed Big Data Platforms

| Platform | Website | Notes |
|----------|---------|-------|
| AWS EMR | [aws.amazon.com/emr](https://aws.amazon.com/emr) | Cloud Hadoop/Spark |
| Databricks | [databricks.com](https://databricks.com) | Managed Spark |
| Azure HDInsight | [azure.microsoft.com/hdinsight](https://azure.microsoft.com/services/hdinsight) | Cloud Hadoop |
| Google Dataproc | [cloud.google.com/dataproc](https://cloud.google.com/dataproc) | Managed Spark/Hadoop |
| Snowflake | [snowflake.com](https://snowflake.com) | Cloud Data Warehouse |
| BigQuery | [cloud.google.com/bigquery](https://cloud.google.com/bigquery) | Serverless Analytics |
| Redshift | [aws.amazon.com/redshift](https://aws.amazon.com/redshift) | Cloud Data Warehouse |

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
| SigNoz | 3301 | 4317/4318 (OTLP) | http://localhost:3301 | [signoz.io](https://signoz.io) | Observability Platform |
| Grafana Alloy | 12345 | 4317/4318 (OTLP) | http://localhost:12345 | [grafana.com/docs/alloy](https://grafana.com/docs/alloy) | Telemetry Collector |
| VictoriaLogs | 9428 | 9429 | http://localhost:9428 | [victoriametrics.com](https://victoriametrics.com) | Log Database |
| OpenSearch | 9200 | 5601 (dashboards) | http://localhost:9200 | [opensearch.org](https://opensearch.org) | Log Search |
| Seq | 5341 | 45341 (HTTPS) | http://localhost:5341 | [datalust.co/seq](https://datalust.co/seq) | Structured Logs |
| GoAccess | 7890 | 7891 | http://localhost:7890 | [goaccess.io](https://goaccess.io) | Real-Time Log Analyzer |
| Datadog Agent | 8125 (DogStatsD) | 8126 (APM) | - | [docs.datadoghq.com](https://docs.datadoghq.com) | Agent & APM |
| Elastic APM Server | 8200 | 8201 | - | [elastic.co/apm](https://elastic.co/apm) | APM Server |

### Syslog & Log Transport Ports

| Service | Port | Protocol | Purpose |
|---------|------|----------|--------|
| Syslog (UDP) | 514 | UDP | Classic syslog |
| Syslog (TCP) | 514 | TCP | Reliable syslog |
| Syslog (TLS) | 6514 | TCP/TLS | Secure syslog |
| RELP (rsyslog) | 20514 | TCP | Reliable event logging |
| Elastic Beats | 5044 | TCP | Filebeat/Logstash |
| Fluentd Forward | 24224 | TCP/UDP | Fluentd/Fluent Bit |
| GELF (Graylog) | 12201 | UDP/TCP | Graylog Extended Log Format |
| Graylog Syslog Input | 1514 | TCP/UDP | Graylog syslog |
| OTLP gRPC | 4317 | gRPC | OpenTelemetry |
| OTLP HTTP | 4318 | HTTP | OpenTelemetry |
| Splunk HEC | 8088 | HTTP | HTTP Event Collector |
| Splunk Indexer | 9997 | TCP | Indexer receiving |
| Splunk Management | 8089 | HTTPS | Splunkd management |

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

## Object Storage & File Services

### Self-Hosted Object Storage

| Tool | Default Port | Alternative Ports | Web UI | Website | Purpose |
|------|-------------|------------------|--------|---------|--------|
| MinIO | 9000 (S3 API) | 9001 (console) | http://localhost:9001 | [min.io](https://min.io) | S3-Compatible Storage |
| Ceph MON | 3300 | 6789 | - | [ceph.com](https://ceph.com) | Cluster Monitor |
| Ceph OSD | 6800-7300 | - | - | [ceph.com](https://ceph.com) | Object Storage Daemon |
| Ceph RGW | 7480 | 80/443 | - | [ceph.com](https://ceph.com) | S3/Swift Gateway |
| Ceph Dashboard | 8443 | 8080 | https://localhost:8443 | [ceph.com](https://ceph.com) | Ceph UI |
| SeaweedFS Master | 9333 | 9334 | http://localhost:9333 | [seaweedfs.com](https://seaweedfs.com) | Distributed Storage |
| SeaweedFS Filer | 8888 | 8889 | http://localhost:8888 | [seaweedfs.com](https://seaweedfs.com) | File System |
| SeaweedFS S3 | 8333 | 8334 | - | [seaweedfs.com](https://seaweedfs.com) | S3 API |
| Garage | 3900 (S3) | 3901 (RPC), 3902 (admin), 3903 (web) | http://localhost:3903 | [garagehq.deuxfleurs.fr](https://garagehq.deuxfleurs.fr) | S3 Storage |
| OpenStack Swift | 8080 (proxy) | 6000-6002 (backend) | - | [openstack.org](https://openstack.org) | Object Storage |
| Cloudflare R2 | - | - | cloud | [cloudflare.com/r2](https://cloudflare.com/r2) | Cloud Object Storage |
| Backblaze B2 | - | - | cloud | [backblaze.com](https://backblaze.com) | Cloud Object Storage |
| Wasabi | - | - | cloud | [wasabi.com](https://wasabi.com) | Cloud Object Storage |

### File Sharing & Sync

| Tool | Default Port | Alternative Ports | Web UI | Website | Purpose |
|------|-------------|------------------|--------|---------|--------|
| NFS | 2049 | 111 (rpcbind), 20048 (mountd) | - | [nfs.sourceforge.net](https://nfs.sourceforge.net) | Network File System |
| SMB / CIFS | 445 | 139 (NetBIOS) | - | [samba.org](https://samba.org) | Windows File Sharing |
| Samba | 445 | 139, 137/138 (NetBIOS) | - | [samba.org](https://samba.org) | File Server |
| rsync daemon | 873 | 874 | - | [rsync.samba.org](https://rsync.samba.org) | File Sync |
| SFTP | 22 | 2222 | - | [openssh.com](https://openssh.com) | Secure File Transfer |
| FTP | 21 | 20 (data), 990 (FTPS) | - | - | File Transfer |
| iSCSI Target | 3260 | - | - | [open-iscsi.org](https://open-iscsi.org) | Block Storage |
| WebDAV | 80 | 443 | - | [webdav.org](https://webdav.org) | HTTP File Access |
| Syncthing | 8384 (UI) | 22000 (sync), 21027 (discovery) | http://localhost:8384 | [syncthing.net](https://syncthing.net) | File Sync |
| Filebrowser | 8080 | 8081 | http://localhost:8080 | [filebrowser.org](https://filebrowser.org) | Web File Manager |
| Nextcloud | 80 | 443 | http://localhost | [nextcloud.com](https://nextcloud.com) | File Collaboration |
| Seafile | 80 | 443, 8082 (fileserver) | http://localhost | [seafile.com](https://seafile.com) | File Sync & Share |
| ownCloud | 80 | 443 | http://localhost | [owncloud.com](https://owncloud.com) | File Collaboration |

## Email & Notification Services

### Mail Servers & Protocols

| Service | Ports | Protocol | Website | Purpose |
|---------|-------|----------|---------|--------|
| SMTP | 25 | TCP | - | Mail transfer |
| SMTP Submission | 587 | TCP/STARTTLS | - | Client submission |
| SMTPS | 465 | TCP/TLS | - | Secure SMTP |
| POP3 | 110 | TCP | - | Mail retrieval |
| POP3S | 995 | TCP/TLS | - | Secure POP3 |
| IMAP | 143 | TCP | - | Mail access |
| IMAPS | 993 | TCP/TLS | - | Secure IMAP |
| ManageSieve | 4190 | TCP | - | Sieve scripts |
| LMTP | 24 | TCP | - | Local mail transfer |
| Postfix | 25, 587, 465 | SMTP | [postfix.org](https://postfix.org) | MTA |
| Dovecot | 143, 993, 110, 995 | IMAP/POP3 | [dovecot.org](https://dovecot.org) | Mail Server |
| Exim | 25, 587 | SMTP | [exim.org](https://exim.org) | MTA |
| Roundcube | 80, 443 | HTTP | [roundcube.net](https://roundcube.net) | Webmail |
| Mailu | 25, 80, 443, 993 | Multi | [mailu.io](https://mailu.io) | Mail Server Suite |
| iRedMail | 25, 80, 443, 993 | Multi | [iredmail.org](https://iredmail.org) | Mail Server Suite |
| Mailcow | 25, 80, 443, 993, 8443 | Multi | [mailcow.email](https://mailcow.email) | Mail Server Suite |

### Mail Testing & Notifications

| Tool | Default Port | Alternative Ports | Web UI | Website | Purpose |
|------|-------------|------------------|--------|---------|--------|
| Mailpit | 1025 (SMTP) | 8025 (UI) | http://localhost:8025 | [mailpit.axllent.org](https://mailpit.axllent.org) | Mail Testing |
| MailHog | 1025 (SMTP) | 8025 (UI) | http://localhost:8025 | [github.com/mailhog/MailHog](https://github.com/mailhog/MailHog) | Mail Testing |
| MailCatcher | 1025 (SMTP) | 1080 (UI) | http://localhost:1080 | [mailcatcher.me](https://mailcatcher.me) | Mail Testing |
| Maildev | 1025 (SMTP) | 1080 (UI) | http://localhost:1080 | [github.com/maildev/maildev](https://github.com/maildev/maildev) | Mail Testing |
| Ethereal | - | - | cloud | [ethereal.email](https://ethereal.email) | Fake SMTP |
| Listmonk | 9000 | 9001 | http://localhost:9000 | [listmonk.app](https://listmonk.app) | Newsletter Platform |
| Gotify | 80 | 8080 (Docker) | http://localhost | [gotify.net](https://gotify.net) | Push Notifications |
| ntfy | 80 | 8080 (Docker), 2586 | http://localhost | [ntfy.sh](https://ntfy.sh) | Push Notifications |
| Apprise API | 8000 | 8001 | http://localhost:8000 | [github.com/caronc/apprise-api](https://github.com/caronc/apprise-api) | Notification Gateway |
| Novu | 3000 | 3001 (API) | http://localhost:3000 | [novu.co](https://novu.co) | Notification Infrastructure |
| Centrifugo | 8000 | 8001 | http://localhost:8000 | [centrifugal.dev](https://centrifugal.dev) | Realtime Messaging |
| Soketi | 6001 | 6002 | - | [soketi.app](https://soketi.app) | Pusher-Compatible WS |
| Twilio / SendGrid / Mailgun | - | - | cloud | [twilio.com](https://twilio.com) | Cloud Messaging |
| Slack / Discord / Teams Webhooks | - | - | cloud | - | Team Notifications |

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
