# Awesome Postgres [![awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[<img src="https://wiki.postgresql.org/images/a/a4/PostgreSQL_logo.3colors.svg" align="right"  width="100">](https://www.postgresql.org/)

> A curated list of awesome [PostgreSQL](https://www.postgresql.org/) software, libraries, tools and resources, inspired by [awesome-mysql](http://shlomi-noach.github.io/awesome-mysql/)

[PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL), often simply Postgres, is an [object-relational database](https://en.wikipedia.org/wiki/Object-relational_database) (ORDBMS). PostgreSQL is [ACID-compliant](https://en.wikipedia.org/wiki/ACID) and [transactional](https://en.wikipedia.org/wiki/Transaction_processing). (see more: [wikipedia:PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL), [PostgreSQL.org](https://www.postgresql.org))

 :elephant: Contributions welcome. Add links through [pull requests](https://github.com/dhamaniasad/awesome-postgres/pulls) or create an [issue](https://github.com/dhamaniasad/awesome-postgres/issues) to start a discussion. Please take a look at the [contribution guidelines](CONTRIBUTING.md).

## Contents

- [Awesome Postgres](#awesome-postgres-)
    - [High-Availability](#high-availability)
    - [Backups](#backups)
    - [GUI](#gui)
    - [Distributions](#distributions)
    - [CLI](#cli)
    - [Server](#server)
    - [Monitoring](#monitoring)
    - [Extensions](#extensions)
    - [Work Queues](#work-queues)
    - [Optimization](#optimization)
    - [Utilities](#utilities)
    - [Language bindings](#language-bindings)
    - [PaaS (PostgreSQL as a Service)](#paas-postgresql-as-a-service)
    - [Docker images](#docker-images)
    - [Kubernetes](#kubernetes)
- [Resources](#resources)
    - [Tutorials](#tutorials)
    - [Blogs](#blogs)
    - [Articles](#articles)
    - [Documentation](#documentation)
    - [Newsletters](#newsletters)
    - [Videos](#videos)
    - [Community](#community)
    - [Roadmaps](#roadmaps)
    - [External lists](#external-lists)

### High-Availability
* [autobase](https://github.com/vitabaks/autobase) - Autobase for PostgreSQL® is an open-source DBaaS that automates the deployment and management of highly available PostgreSQL clusters.
* [BDR](https://github.com/2ndQuadrant/bdr) - BiDirectional Replication - a multimaster replication system for PostgreSQL
* [Patroni](https://github.com/zalando/patroni) - Template for PostgreSQL HA with ZooKeeper or etcd.
* [Stolon](https://github.com/sorintlab/stolon) - PostgreSQL HA based on Consul or etcd, with Kubernetes integration.
* [pglookout](https://github.com/aiven/pglookout) - Replication monitoring and failover daemon.
* [repmgr](https://github.com/2ndQuadrant/repmgr) - Open-source tool suite to manage replication and failover in a cluster of PostgreSQL servers.
* [Slony-I](https://slony.info/) - "Master to multiple slaves" replication system with cascading and failover.
* [PAF](https://github.com/ClusterLabs/PAF) - PostgreSQL Automatic Failover: High-Availibility for Postgres, based on Pacemaker and Corosync.
* [SkyTools](https://github.com/pgq/skytools-legacy) - Replication tools, including PgQ, a queuing system, and Londiste, a replication system a bit simpler to manage than Slony.
* [pg_auto_failover](https://github.com/citusdata/pg_auto_failover) - Postgres extension and service for automated failover and high-availability.
* [pgrwl](https://github.com/hashmap-kz/pgrwl) - Stream write-ahead logs (WAL) from a PostgreSQL server in real time. A drop-in, container-friendly alternative to pg_receivewal.

### Backups
* [Barman](https://www.pgbarman.org/index.html) - Backup and Recovery Manager for PostgreSQL by 2ndQuadrant.
* [OmniPITR](https://github.com/omniti-labs/omnipitr) - Advanced WAL File Management Tools for PostgreSQL.
* [pg\_probackup](https://github.com/postgrespro/pg_probackup) – A fork of pg\_arman, improved by @PostgresPro, supports incremental backups, backups from replica, multithreaded backup and restore, and anonymous backup without archive command.
* [pgBackRest](https://pgbackrest.org/)  - Reliable PostgreSQL Backup & Restore.
* [pgbackweb](https://github.com/eduardolat/pgbackweb) - A Complete Docker-based Postgres backup and maintenance tool with Web UI. 
* [pg\_back](https://github.com/orgrim/pg_back/) - pg\_back is a simple backup script
* [pghoard](https://github.com/aiven/pghoard) - Backup and restore tool for cloud object stores (AWS S3, Azure, Google Cloud, OpenStack Swift).
* [wal-e](https://github.com/wal-e/wal-e) (obsolete) - Simple Continuous Archiving for PostgreSQL to S3, Azure, or Swift by Heroku.
* [wal-g](https://github.com/wal-g/wal-g) - The successor of WAL-E rewritten in Go. Currently supports cloud object storage services by AWS (S3), Google Cloud (GCS), Azure, as well as OpenStack Swift, MinIO, and file system storages. Supports block-level incremental backups, offloading backup tasks to a standby server, provides parallelization and throttling options. In addition to Postgres, WAL-G can be used for MySQL and MongoDB databases.
* [pitrery](https://dalibo.github.io/pitrery/) - pitrery is a set of Bash scripts to manage Point In Time Recovery (PITR) backups for PostgreSQL.
* [pgbackup-sidecar](https://github.com/Musab520/pgbackup-sidecar) - `pgbackup-sidecar` is a lightweight Docker sidecar container designed to automate regular backups of a PostgreSQL database using `pg_dump`, `cron`, and bash scripts while also sending output to a webhook.
* [pg-backups-to-s3](https://github.com/Saicheg/pg-backups-to-s3) - Docker-first solution on top of pg_dump with support for environment-based configuration for scheduled PostgreSQL backups with optional compression, GPG encryption, webhooks, automatic upload to Amazon S3.

### GUI
* [Adminer](https://www.adminer.org/) - Full-featured database management tool written in PHP.
* [Beekeeper Studio](https://www.beekeeperstudio.io) - Free and open source SQL client with a modern UI and great Postgres support. Cross platform.
* [Chartbrew](https://chartbrew.com) - Create live dashboards, charts, and client reports from PostgreSQL data. Features a query tool that works with SQL.
* [Count](https://count.co/) - Web-based analytics platform with a notebook interface which connects to PostgreSQL (Commercial Software).
* [DataGrip](https://www.jetbrains.com/datagrip/) - IDE with advanced tool sets and good cross-platform experience (Commercial Software).
* [Datazenit](https://datazenit.com/) - Web-based PostgreSQL GUI (Commercial Software).
* [DataRow](https://www.datarow.com/) - Cross-platform SQL Client for Amazon Redshift: Simple, Effortless, Extensible.
* [DBConvert Streams](https://streams.dbconvert.com/) - A cloud-native platform for real-time data migration and CDC replication between PostgreSQL and MySQL databases across various cloud environments. (Commercial Software).
* [DBeaver](https://dbeaver.io/) - Universal Database Manager with excellent support for PostgreSQL.
* [DbVisualizer](http://www.dbvis.com) - Cross-platform database client for developers, DBAs, and analysts (Commercial Software).
* [Holistics](https://www.holistics.io/) - Online cross platform database management tool and SQL query reporting GUI with strong PostgreSQL support (Commercial Software).
* [JackDB](https://www.jackdb.com/) - Web-based SQL query interface (Commercial Software).
* [Luna Modeler](http://www.datensen.com) - Cross-platform desktop data modeling tool (Commercial Software).
* [Mathesar](https://mathesar.org/) -  Web application providing an intuitive user experience to databases.
* [Metabase](https://www.metabase.com/) - Simple dashboards, charts and query tool for PostgreSQL.
* [Numeracy](https://numeracy.co/) - Fast SQL editor with charts and dashboards for PostgreSQL (Commercial Software).
* [pgAdmin](https://www.pgadmin.org/) - PostgreSQL Administration and Management GUI.
* [pgMagic🪄](https://pgmagic.app/?ref=awesomepostgres) - Chat to Postgres in Natural Language (Commercial Software).
* [pgModeler](https://pgmodeler.io/) - pgModeler is an open-source PostgreSQL Database Modeler.
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser written in Go.
* [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) - The Premier Web Based Administration Tool for PostgreSQL.
* [Postbird](https://github.com/Paxa/postbird) - PostgreSQL Client for macOS.
* [PostgresCompare](https://www.postgrescompare.com) - Cross-platform database comparison and deployment tool (Commercial Software).
* [Postico](https://eggerapps.at/postico/) - Modern PostgreSQL Client for macOS (Commercial Software).
* [PSequel](http://www.psequel.com/) - Clean and simple interface to perform common PostgreSQL tasks quickly (Commercial Software).
* [Redash](https://github.com/getredash/redash) - Connect to any data source, easily visualize and share your data.
* [SQL Tabs](http://www.sqltabs.com/) - Cross Platform Desktop Client for PostgreSQL written in JS.
* [SQLPro for Postgres](http://macpostgresclient.com/) - Simple, powerful PostgreSQL manager for macOS (Commercial Software).
* [temBoard](https://github.com/dalibo/temboard) - Web-based PostgreSQL GUI and monitoring.
* [Teable](https://github.com/teableio/teable) - A Super fast, Real-time, Professional, Developer friendly, No code database.
* [TablePlus](https://tableplus.com/) - Native App which let you edit database and structure. High-end security ensured (Commercial Software).
* [Valentina Studio](https://www.valentina-db.com/en/valentina-studio-overview) - Cross-platform database administration tool (Free/Commercial)
* [DbGate](https://dbgate.org) - The Smartest (no)SQL Database Client
* [WebDB](https://webdb.app) – Efficient Database IDE.

### Distributions
* [Postgres.app](https://postgresapp.com/) - The Easiest Way to Get Started with PostgreSQL on macOS.
* [Pigsty](https://github.com/Vonng/pigsty) - Battery-Included Open-Source Distribution for PostgreSQL with ultimate observability & Database-as-Code toolbox for developers.

### CLI
* [atlas](https://github.com/ariga/atlas) - Atlas is a tool for managing and migrating database schemas using modern DevOps principles.
* [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting
* [pg-schema-diff](https://github.com/stripe/pg-schema-diff) - CLI (and Golang library) for diffing Postgres schemas and generating SQL migrations with minimal locking.
* [pgsh](https://github.com/sastraxi/pgsh) - Branch your PostgreSQL Database like Git
* [psql](https://www.postgresql.org/docs/current/static/app-psql.html) - The built-in PostgreSQL CLI client
* [psql2csv](https://github.com/fphilipe/psql2csv) - Run a query in psql and output the result as CSV
* [schemaspy](https://github.com/schemaspy/schemaspy) - SchemaSpy is a JAVA JDBC-compliant tool for generating your database to HTML documentation, including Entity Relationship diagrams
* [pdot](https://gitlab.com/dmfay/pdot) - Visualize and explore database structures in your shell, from high-context views of the foreign key graph to trigger cascades, role inheritance and permissions, and many more

### Server
* [AgensGraph](https://bitnine.net/) - Powerful graph database based on the PostgreSQL.
* [Apache Cloudberry](https://github.com/apache/cloudberry) - And MPP PostgreSQL fork. Open source alternative to Greenplum Database.
* [FerretDB](https://www.ferretdb.io) - A truly Open Source MongoDB alternative on top of PostgreSQL.
* [Postgres-XL](https://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based Database Cluster.
* [YugabyteDB](https://yugabyte.com/) - Open Source Distributed SQL using  a fork of PostgreSQL on top of distributed storage and transaction

### Security
* [Acra](https://github.com/cossacklabs/acra) - SQL database security suite: proxy for data protection with transparent "on the fly" data encryption, SQL firewall (SQL injections prevention), intrusion detection system.

### Monitoring
* [check\_pgactivity](https://github.com/OPMDG/check_pgactivity) - check\_pgactivity is designed to monitor PostgreSQL clusters from Nagios. It offers many options to measure and monitor useful performance metrics.
* [Check\_postgres](https://github.com/bucardo/check_postgres) - Nagios check\_postgres plugin for checking status of PostgreSQL databases.
* [coroot](https://github.com/coroot/coroot) - Coroot is an open-source APM & Observability tool, a DataDog and NewRelic alternative. Powered by eBPF for rapid insights into system performance.
* [Datadog](https://www.datadoghq.com/product/database-monitoring/) - SaaS monitoring that collects and visualizes metrics, queries, and explain plans, and sends alerts when problems are encountered (Commercial Software).
* [Instrumental](https://github.com/Instrumental/instrumentald) - Real-time performance monitoring, including [pre-made graphs](https://instrumentalapp.com/docs/instrumentald/postgresql#suggested-graphs) for ease of setup (Commercial Software)
* [libzbxpgsql](https://github.com/cavaliercoder/libzbxpgsql) - Comprehensive PostgreSQL monitoring module for Zabbix.
* [PMM](https://github.com/percona/pmm) - Percona Monitoring and Management (PMM) is a Free and Open Source platform for monitoring and managing PostgreSQL, MySQL, and MongoDB.
* [Pome](https://github.com/rach/pome) - Pome stands for PostgreSQL Metrics. Pome is a PostgreSQL Metrics Dashboard to keep track of the health of your database.
* [pgmetrics](https://pgmetrics.io/) - pgmetrics is an open-source, zero-dependency, single-binary tool that can collect a lot of information and statistics from a running PostgreSQL server and display it in easy-to-read text format or export it as JSON and CSV for scripting.
* [pg\_view](https://github.com/zalando/pg_view) - Open-source command-line tool that shows global system stats, per-partition information, memory stats and other information.
* [pgwatch2](https://github.com/cybertec-postgresql/pgwatch2) - Flexible and easy to get started PostgreSQL metrics monitor focusing on Grafana dashboards.
* [pgbench](https://www.postgresql.org/docs/devel/static/pgbench.html) - Run a benchmark test on PostgreSQL.
* [opm.io](http://opm.io) -  Open PostgreSQL Monitoring is a free software suite designed to help you manage your PostgreSQL servers. It can gather stats, display dashboards and send warnings when something goes wrong.
* [okmeter.io](https://okmeter.io/pg) - Commercial SaaS agent-based monitoring with a very detailed PostgreSQL plugin. It automatically gathers 100s of stats, displays dashboards on every aspect and sends alerts when something goes wrong (Commercial Software).
* [dexter](https://github.com/ankane/dexter) - The automatic indexer for Postgres. Detects slow queries and creates indexes if configured to do so.
* [pg_exporter](https://github.com/Vonng/pg_exporter) - Fully customizable Prometheus exporter for PostgreSQL & Pgbouncer with fine-grained execution control.
* [postgres_exporter](https://github.com/wrouesnel/postgres_exporter) - Prometheus exporter for PostgreSQL server metrics.

### Extensions
* [AGE](https://github.com/apache/age) - Adds fully-functional graph database support including Cypher queries.
* [OrioleDB](https://www.orioledb.com/) - The cloud-native storage engine for PostgreSQL. OrioleDB is a PostgreSQL extension that combines the advantages of both on-disk and in-memory engines.
* [Citus](https://github.com/citusdata/citus) - Scalable PostgreSQL cluster for real-time workloads.
* [cstore\_fdw](https://github.com/citusdata/cstore_fdw) - Columnar store for analytics with PostgreSQL.
* [cyanaudit](https://pgxn.org/dist/cyanaudit/) - Cyan Audit provides in-database logging of all DML activity on a column-by-column basis.
* [pg_analytics](https://github.com/paradedb/pg_analytics) - pg_analytics is an extension that accelerates analytical query processing inside Postgres to a performance level comparable to dedicated OLAP databases.
* [pg_lakehouse](https://github.com/paradedb/paradedb/tree/dev/pg_lakehouse) - pg_lakehouse is an extension that transforms Postgres into an analytical query engine over object stores like AWS S3/GCS and table formats like Delta Lake/Iceberg.
* [pg_search](https://github.com/paradedb/paradedb/tree/dev/pg_search) - pg_search is a PostgreSQL extension that enables full-text search over SQL tables using the BM25 algorithm, the state-of-the-art ranking function for full-text search.
* [pg_cron](https://github.com/citusdata/pg_cron) - Run periodic jobs in PostgreSQL.
* [pglogical](https://github.com/2ndQuadrant/pglogical) - Extension that provides logical streaming replication.
* [pgcat](https://github.com/kingluo/pgcat) - Enhanced PostgreSQL logical replication
* [pg\_barcode](https://github.com/btouchard/pg_barcode/) - PostgreSQL SVG QRcode & Datamatrix generator.
* [pg\_partman](https://github.com/pgpartman/pg_partman) - Partition management extension for PostgreSQL.
* [pg\_paxos](https://github.com/citusdata/pg_paxos/) - Basic implementation of Paxos and Paxos-based table replication for a cluster of PostgreSQL nodes.
* [pg\_shard](https://github.com/citusdata/pg_shard) - Extension to scale out real-time reads and writes.
* [pg\_stat\_monitor](https://github.com/percona/pg_stat_monitor) - Query Performance Monitoring tool for PostgreSQL.
* [pg\_squeeze](https://github.com/cybertec-postgresql/pg_squeeze) - An extension for automatic bloat cleanup with minimal locking.
* [PGStrom](https://wiki.postgresql.org/wiki/PGStrom) - Extension to offload CPU intensive workloads to GPU.
* [pgxn](https://pgxn.org/) PostgreSQL Extension Network - central distribution point for many open-source PostgreSQL extensions
* [PipelineDB](https://www.confluent.io/blog/pipelinedb-team-joins-confluent/) - A PostgreSQL extension that runs SQL queries continuously on streams, incrementally storing results in tables.
* [plpgsql\_check](https://github.com/okbob/plpgsql_check) - Extension that allows to check plpgsql source code.
* [PostGIS](http://postgis.net/) - Spatial and Geographic objects for PostgreSQL.
* [PG\_Themis](https://github.com/cossacklabs/pg_themis) - Postgres binding as extension for crypto library Themis, providing various security services on PgSQL's side.
* [zomboDB](https://github.com/zombodb/zombodb) - Extension that enables efficient full-text searching via the use of indexes backed by Elasticsearch.
* [pgMemento](https://github.com/pgMemento/pgMemento) - Provides an audit trail for your data inside a PostgreSQL database using triggers and server-side functions written in PL/pgSQL.
* [TimescaleDB](https://www.timescale.com/) - Open-source time-series database fully compatible with Postgres, distributed as extension
* [pgTAP](https://pgtap.org/) - Database testing framework for Postgres
* [HypoPG](https://github.com/HypoPG/hypopg) - HypoPG provides hypothetical/virtual indexes feature.
* [pgRouting](https://github.com/pgRouting/pgrouting) - pgRouting extends the PostGIS/PostgreSQL geospatial database to provide geospatial routing and other network analysis functionality.
* [PGroonga](https://pgroonga.github.io/) - PGroonga provides a new index access method that uses Groonga allowing super fast full text search feature against all languages.
* [PGAudit](https://www.pgaudit.org/) - The PostgreSQL Audit Extension (or pgaudit) provides detailed session and/or object audit logging via the standard logging facility provided by PostgreSQL.
* [PostgresML](https://postgresml.org/) - Machine learning and AI inside your database, including vectors, LLMs, and classic ML. Train, predict and manage the entire lifecycle of machine learning models using only SQL.
* [ParadeDB](https://github.com/paradedb/paradedb) -  Postgres for Search and Analytics

### Work Queues
* [BeanQueue](https://github.com/LaunchPlatform/bq) - A Python work queue framework based on SKIP LOCKED, LISTEN and NOTIFY
* [pgmq](https://github.com/pgmq/pgmq) - A lightweight message queue. Like AWS SQS and RSMQ but on Postgres.
* [river](https://github.com/riverqueue/river) - A high-performance job processing system for Go and Postgres.

### Optimization
* [EverSQL](https://www.eversql.com/) - Automated query optimization tool, monitoring and analysis tool, indexing recommendation tool. (Commercial Software)
* [PEV2](https://github.com/dalibo/pev2) - Online Postgres Explain Visualizer.
* [pg_flame](https://github.com/mgartner/pg_flame) - A flamegraph generator for query plans.
* [PgHero](https://github.com/ankane/pghero) - PostgreSQL insights made easy.
* [pgMustard](https://www.pgmustard.com/) - A modern user interface
for `EXPLAIN`, that also provides performance tips (Commercial Software).
* [pgtune](https://github.com/gregs1104/pgtune/) - PostgreSQL configuration wizard.
* [pgtune](https://github.com/le0pard/pgtune) - Online version of PostgreSQL configuration wizard.
* [pgconfig.org](https://github.com/sebastianwebber/pgconfig) - PostgreSQL Online Configuration Tool (also based on pgtune).
* [PoWA](https://powa.readthedocs.io/en/latest/) - PostgreSQL Workload Analyzer gathers performance stats and provides real-time charts and graphs to help monitor and tune your PostgreSQL servers.
* [pg_web_stats](https://github.com/kirs/pg_web_stats) - Web UI to view pg_stat_statements.
* [TimescaleDB Tune](https://github.com/timescale/timescaledb-tune) - a program for tuning a TimescaleDB database to perform its best based on the host's resources such as memory and number of CPUs.
* [Metis](https://www.metisdata.io/product/troubleshooting) - Metis provides observability and performance tuning for SQL databases including PostgreSQL. (Commercial Software)
* [aqo](https://github.com/postgrespro/aqo) - Adaptive query optimization for PostgreSQL.
* [pgassistant](https://github.com/nexsol-technologies/pgassistant) - A DB optimization dashboard for PostgreSQL with LLM and pgTune integration.

### Utilities
* [apgdiff](https://www.apgdiff.com/) - Compares two database dump files and creates output with DDL statements that can be used to update old database schema to new one.
* [bemi](https://github.com/BemiHQ/bemi) - Automatic data change tracking for PostgreSQL
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - ERAlchemy generates Entity Relation (ER) diagram from databases.
* [flyway](https://flywaydb.org/) - Schema migration tool for Postgres and others.
* [GatewayD](https://github.com/gatewayd-io/gatewayd) - Cloud-native database gateway and framework for building data-driven applications. Like API gateways, for databases.
* [Hasura GraphQL Engine](https://github.com/hasura/graphql-engine) - Blazing fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events.
* [ldap2pg](https://github.com/dalibo/ldap2pg) - Synchronize roles and privileges from YML and LDAP.
* [migra](https://github.com/djrobstep/migra) - Like diff but for Postgres schemas.
* [mysql-postgresql-converter](https://github.com/lanyrd/mysql-postgresql-converter) - Lanyrd's MySQL to PostgreSQL conversion script.
* [NServiceBus.Transport.PostgreSql](https://github.com/Particular/NServiceBus.SqlServer) - The NServiceBus.Transport.PostgreSql library allows .NET developers to [use a PostgreSQL database as a message broker](https://docs.particular.net/transports/postgresql). (Commerical Software)
* [ora2pg](http://ora2pg.darold.net) - Perl module to export an Oracle database schema to a PostgreSQL compatible schema.
* [pg\_activity](https://github.com/dalibo/pg_activity) - top like application for PostgreSQL server activity monitoring.
* [pg-formatter](https://github.com/gajus/pg-formatter) - A PostgreSQL SQL syntax beautifier (Node.js).
* [pganalyze](https://pganalyze.com) - PostgreSQL Performance Monitoring (Commercial Software).
* [pgbadger](https://github.com/darold/pgbadger) - Fast PostgreSQL Log Analyzer.
* [PgBouncer](http://www.pgbouncer.org/) - Lightweight connection pooler for PostgreSQL.
* [pgCenter](https://github.com/lesovsky/pgcenter) - Provides convenient interface to various statistics, management task, reloading services, viewing log files and canceling or terminating database backends.
* [pg_chameleon](https://github.com/the4thdoctor/pg_chameleon) - Real time replica from MySQL to PostgreSQL with optional type override migration and migration capabilities.
* [pgclimb](https://github.com/lukasmartinelli/pgclimb) - Export data from PostgreSQL into different data formats.
* [pg_docs_bot](https://github.com/mchristofides/pg_docs_bot/) - Browser extension to redirect PostgreSQL docs links to the current version.
* [pgfutter](https://github.com/lukasmartinelli/pgfutter) - Import CSV and JSON into PostgreSQL the easy way.
* [PGInsight](http://pginsight.io/) - CLI tool to easily dig deep inside your PostgreSQL database.
* [pg_insights](https://github.com/lob/pg_insights) - Convenient SQL for monitoring Postgres database health.
* [pgloader](https://github.com/dimitri/pgloader) - Loads data into PostgreSQL using the COPY streaming protocol, and does so with separate threads for reading and writing data.
* [pgMonitor](https://github.com/CrunchyData/pgmonitor) - Postgres metrics collection and visualization that can be deployed to bare metal, virtual machines, or Kubernetes.
* [pgpool-II](https://www.pgpool.net/mediawiki/index.php/Main_Page) - Middleware that provides connection pooling, replication, load balancing and limiting exceeding connections.
* [pgspot](https://github.com/timescale/pgspot) - Spot vulnerabilities in PostgreSQL extension scripts.
* [pg-spot-operator](https://github.com/pg-spot-ops/pg-spot-operator) - A daemon to run stateful Postgres on cheap AWS Spot VMs
* [pgsync](https://github.com/ankane/pgsync) - Tool to sync PostgreSQL data to your local machine.
* [PGXN client](https://github.com/pgxn/pgxnclient) - Command line tool to interact with the PostgreSQL Extension Network
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) - Tool that extracts and provides metrics for your PostgreSQL database.
* [PostgREST](https://github.com/PostgREST/postgrest) - Serves a fully RESTful API from any existing PostgreSQL database.
* [pREST](https://github.com/prest/prest) - Serve a RESTful API from any PostgreSQL database (Golang)
* [PostGraphile](https://github.com/graphile/postgraphile) - Instant GraphQL API or GraphQL schema for your PostgreSQL database
* [yoke](https://github.com/nanopack/yoke) - PostgreSQL high-availability cluster with auto-failover and automated cluster recovery.
* [pglistend](https://github.com/kabirbaidhya/pglistend) - A lightweight PostgresSQL `LISTEN`/`NOTIFY` daemon built on top of `node-postgres`.
* [ZSON](https://github.com/postgrespro/zson) - PostgreSQL extension for transparent JSONB compression
* [pg_bulkload](http://ossc-db.github.io/pg_bulkload/index.html) - It's a high speed data loading utility for PostgreSQL.
* [pg_migrate](https://github.com/jwdeitch/pg_migrate) - Manage PostgreSQL codebases and make VCS simple.
* [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) - Advanced job scheduler for PostgreSQL.
* [sqitch](https://github.com/sqitchers/sqitch) - Tool for managing versioned schema deployment
* [pgmigrate](https://github.com/yandex/pgmigrate) - CLI tool to evolve schema migrations, developed by Yandex.
* [pgcmp](https://github.com/cbbrowne/pgcmp) - Tool to compare database schemas, with capability to accept some persistent differences
* [pg-differ](https://github.com/multum/pg-differ) - Tool for easy initialization / updating of the structure of PostgreSQL tables, migration alternative (Node.js).
* [sqlcheck](https://github.com/jarulraj/sqlcheck) - Automatically detects common SQL anti-patterns. Such anti-patterns often slow down queries. Addressing them will, therefore, help accelerate queries.
* [postgres-checkup](https://gitlab.com/postgres-ai/postgres-checkup) - a new-generation diagnostics tool that allows users to collect deep analysis of the health of a Postgres database.
* [Pyrseas](https://github.com/perseas/Pyrseas) - Postgres database schema versioning.
* [ScaffoldHub.io](https://scaffoldhub.io) - Generate fullstack PostgreSQL apps with Angular, Vue or React (Commercial Software).
* [planter](https://github.com/achiku/planter) - Generate PlantUML ER diagram textual description from PostgreSQL tables
* [pgroll](https://github.com/xataio/pgroll) - Zero-downtime, reversible, schema migrations for Postgres
* [RegreSQL](https://github.com/dimitri/regresql) - Tool to build, maintain and execute a regression testing suite for SQL queries.

### Language bindings
* Common Lisp: [Postmodern](https://github.com/marijnh/Postmodern)
* Clojure: [clj-postgresql](https://github.com/remodoy/clj-postgresql)
* Elixir: [postgrex](https://github.com/elixir-ecto/postgrex)
* Go: [pq](https://github.com/lib/pq), [pgx](https://github.com/jackc/pgx), [go-pg](https://github.com/go-pg/pg)
* Haskell: [postgresql-simple](http://hackage.haskell.org/package/postgresql-simple)
* Java: [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/), [Vert.x PostgreSQL Client](https://vertx.io/docs/vertx-pg-client/java/)
* Lua: [luapgsql](https://github.com/arcapos/luapgsql)
* .Net/.Net Core: [Npgsql](https://github.com/npgsql/npgsql)
* Node: [node-postgres](https://github.com/brianc/node-postgres), [pg-promise](https://github.com/vitaly-t/pg-promise), [pogi](https://github.com/holdfenytolvaj/pogi), [slonik](https://github.com/gajus/slonik), [postgres](https://github.com/porsager/postgres)
* Perl: [DBD-Pg](https://metacpan.org/pod/distribution/DBD-Pg/Pg.pm)
* PHP: [Pomm](http://www.pomm-project.org), [pecl/pq](https://github.com/m6w6/ext-pq)
* Python: [psycopg2](https://pypi.org/project/psycopg2/), [asyncpg](https://pypi.org/project/asyncpg/), [pg8000](https://pypi.org/project/pg8000/)
* R: [RPostgres](https://github.com/r-dbi/RPostgres), [RPostgreSQL](https://github.com/tomoakin/RPostgreSQL)
* Ruby: [pg](https://github.com/ged/ruby-pg)
* Rust: [rust-postgresql](https://github.com/sfackler/rust-postgres), [pgx](https://github.com/tcdi/pgx), [wtx](https://github.com/c410-f3r/wtx)
* TypeScript: [zapatos](https://github.com/jawj/zapatos)
* Zig: [pg.zig](https://github.com/karlseguin/pg.zig)

### PaaS *(PostgreSQL as a Service)*
* [Aiven PostgreSQL](https://aiven.io/postgresql) - PostgreSQL as a service in AWS, Azure, DigitalOcean, Google Cloud and UpCloud; plans range from $19/month single node instances to large highly-available setups, free trial for two weeks.
* [Amazon RDS for PostgreSQL](https://aws.amazon.com/rds/postgresql/) - Amazon Relational Database Service (RDS) for PostgreSQL
* [Azure Database for PostgreSQL](https://azure.microsoft.com/en-us/services/postgresql/) - Azure Database for PostgreSQL provides fully managed, enterprise-ready community PostgreSQL database as a service. It provides builtin HA, elastic scaling and native integration with Azure ecosystem.
* [Crunchy Bridge](https://www.crunchydata.com/products/crunchy-bridge/) - Fully managed Postgres from the Postgres experts. Available across all major cloud providers: Amazon AWS, Google GCP, Microsoft Azure. No lock-in with full super-user support.
* [Database Labs](https://www.databaselabs.io) - Get a production-ready cloud PostgreSQL server in minutes, from $20 a month Backups, monitoring, patches, and 24/7 tech support all included.
* [DigitalOcean Managed Databases](https://www.digitalocean.com/products/managed-databases/) - Fully managed PostgreSQL databases. No free plan. Starting at $15/mo. Daily backups with point-in-time recovery. Standby nodes with auto-failover.
* [Google Cloud SQL for PostgreSQL](https://cloud.google.com/sql/docs/postgres/) - Fully-managed database service that makes it easy to set up, maintain, manage, and administer your PostgreSQL relational databases on Google Cloud Platform.
* [Heroku Postgres](https://elements.heroku.com/addons/heroku-postgresql) - Plans from free to huge, operated by PostgreSQL experts. Does not require running your app on Heroku. Free plan includes 10,000 rows, 20 connections, up to two backups, and has PostGIS support.
* [OVHcloud Cloud Databases](https://www.ovhcloud.com/en/public-cloud/databases/) - Highly available, scalable, and secured PostgreSQL. Daily backups with point-in-time recovery, no lock-in, free incoming and outgoing traffic.
* [Render Managed PostgreSQL](https://render.com/docs/databases) - Secure, reliable, and completely hands-off managed PostgreSQL. Encryption at rest, automated backups, and expandable SSD storage included in all plans. Plans start at $7 per month for 256MB RAM and 1GB storage (free for first 90 days).
* [ScaleGrid PostgreSQL DBaaS](https://scalegrid.io/postgresql.html) - Fully managed PostgreSQL hosting with high availability, dedicated servers, and superuser control on the #1 multi-cloud Amazon RDS alternative.
* [Scaleway Managed Database](https://www.scaleway.com/en/database/) - Fully managed PostgreSQL databases with HA, scaling, and automated backups, hosted in the EU. Starting at €10 per month.
* [Supabase](https://www.supabase.com) - Fully managed Postgres with read replicas, point-in-time-recovery, support packages, browser based GUI, and a generous free tier.
* [Neon](https://neon.tech) - Fully managed serverless PostgreSQL. Neon separates storage and compute to offer modern developer features such as serverless, branching, bottomless storage, and more.
* [Nile](https://www.thenile.dev/) - Fully managed PostgreSQL . Nile decouples storage from compute and virtualizes tenants to ship multi-tenant AI applications fast, safe, and with limitless scale. Free tier provides unlimited databases.

### Docker images
* [citusdata/citus](https://hub.docker.com/r/citusdata/citus/) - Citus official images with citus extensions. Based on the official Postgres container.
* [mdillon/postgis](https://hub.docker.com/r/mdillon/postgis/) - PostGIS 2.3 on Postgres 9. Based on the official Postgres container.
* [paradedb/paradedb](https://hub.docker.com/r/paradedb/paradedb/) - ParadeDB is Postgres for Search and Analytics. Based on the Bitnami Postgres container with pg_search and pg_analytics Postgres extensions.
* [postgres](https://hub.docker.com/_/postgres/) -  Official postgres container (from Docker)

### Kubernetes
* [Crunchy Operator](https://github.com/CrunchyData/postgres-operator) - Production PostgreSQL for Kubernetes, from high availability Postgres clusters to full-scale database-as-a-service.
* [Fujitsu Enterprise Postgres for Kubernetes](https://www.postgresql.fastware.com/) - Enterprise-grade PostgreSQL on OpenShift Container Platform (Commercial Software).
* [Kubegres Operator](https://github.com/reactive-tech/kubegres) - Kubegres is a Kubernetes operator allowing to deploy one or many clusters of PostgreSql instances and manage databases replication, failover and backup.
* [StackGres Operator](https://github.com/ongres/stackgres/) -  Full Stack PostgreSQL on Kubernetes.
* [Zalando Operator](https://github.com/zalando/postgres-operator) - Creates and manages PostgreSQL clusters running in Kubernetes.
* [CloudNativePG operator](https://github.com/cloudnative-pg/cloudnative-pg) - A comprehensive platform designed to seamlessly manage PostgreSQL databases within Kubernetes environments.
* [KubeDB operator](https://kubedb.com/) - Run Production-Grade Databases on Kubernetes (Commercial Software).

## Resources

### Tutorials
* [Backup and recover a PostgreSQL DB using wal-e](https://coderwall.com/p/cwe2_a/backup-and-recover-a-postgres-db-using-wal-e) - Tutorial about setting up continuous archiving in PostgreSQL using wal-e.
* [Operations cheat sheet](https://wiki.postgresql.org/wiki/Operations_cheat_sheet) - Operations cheat sheet from PostgreSQL Wiki.
* [PG Casts](https://www.pgcasts.com) - Free weekly PostgreSQL screencasts by Hashrocket.
* [Postgres Guide](http://postgresguide.com/) - Guide designed as an aid for beginners and experienced users to find specific tips and explore tools available within PostgreSQL.
* [PostgreSQL Exercises](https://pgexercises.com/) - Site  to make it easy to learn PostgreSQL by doing exercises.
* [tutorialspoint PostgreSQL tutorial](http://www.tutorialspoint.com/postgresql/) - Very extensive collection of tutorials on PostgreSQL
* [postgresDBSamples](https://github.com/morenoh149/postgresDBSamples) - A collection of sample postgres schemas
* [PostgreSQL Primer for Busy People](https://zaiste.net/posts/postgresql-primer-for-busy-people/) - A collection of the most common commands used in PostgreSQL
* [pg-utils](https://github.com/dataegret/pg-utils) - Useful DBA tools by Data Egret
* [pagila](https://github.com/xzilla/pagila) - Pagila, Postgres Sample Database

### Blogs
* [Planet PostgreSQL](https://planet.postgresql.org/) - Blog aggregation service for PostgreSQL.
* [Andrew Dunstan's PostgreSQL and Technical blog](http://adpgtech.blogspot.com/search/label/PostgreSQL/)
* [Bruce Momjian's PostgreSQL blog](https://momjian.us/main/blogs/pgblog.html)
* [Craig Kerstiens PostgreSQL posts](http://www.craigkerstiens.com/categories/postgres/) - Set of posts on PostgreSQL cool features, tips and tricks.
* [Database Soup](http://www.databasesoup.com/search/label/postgresql/) - Josh Berkus' blog.
* [Michael Paquier's blog](https://paquier.xyz/)
* [Percona's PostgreSQL blog posts](https://www.percona.com/blog/category/postgresql/)
* [Robert Haas' blog](http://rhaas.blogspot.com/search/label/postgresql/)
* [select * from depesz;](https://www.depesz.com/tag/postgresql/) - Hubert Lubaczewski's blog.
* [Metis Blog](https://www.metisdata.io/blog) - Set of posts on PostgreSQL, SQL databases, performance, and tuning.
* [Digoal's PostgreSQL and Technical blog(Chinese Language)](https://github.com/digoal/blog/blob/master/README.md) 

### Articles

* [the ultimate postgres vs mysql blog post](https://di.nmfay.com/postgres-vs-mysql)
* [Debugging PostgreSQL performance, the hard way](https://www.justwatch.com/blog/post/debugging-postgresql-performance-the-hard-way/)
* [Why use Postgres?](http://www.craigkerstiens.com/2017/04/30/why-postgres-five-years-later/)
* [Superfast CSV imports using PostgreSQL's COPY command](https://infinum.com/the-capsized-eight/superfast-csv-imports-using-postgresqls-copy)
* [Tricking Postgres into using an insane – but 200x faster – query plan](https://spacelift.io/blog/tricking-postgres-into-using-query-plan)


### Books
* [PostgreSQL Mistakes and How to Avoid Them](https://www.manning.com/books/postgresql-mistakes-and-how-to-avoid-them)
* [The Internals of PostgreSQL](https://www.interdb.jp/pg/index.html) - A free e-book by Hironobu Suzuki
* [PostgreSQL 14 Internals](https://postgrespro.com/community/books/internals) - A free e-book by Egor Rogov


### Documentation
* [Wiki](https://wiki.postgresql.org/wiki/Main_Page) - user documentation, how-tos, and tips 'n' tricks
* [pgPedia](https://pgpedia.info/) - An encyclopedia of things related to postgreSQL.

### Newsletters

* [Postgres Weekly](https://postgresweekly.com/) - Weekly newsletter that contains articles, news, and repos relevant to PostgreSQL.
* [pgMustard newsletter](https://www.pgmustard.com/newsletter) - Monthly newsletter that contains Postgres performance articles and videos.

### Podcasts
* [PostgresFM](https://postgres.fm/) - Weekly discussions about Postgres topics.
* [Scaling Postgres](https://www.scalingpostgres.com/) - Weekly roundups of PostgreSQL related content.
* [Path to Citus Con](https://www.citusdata.com/podcast/path-to-citus-con/) - Monthly interviews with people in the Postgres world.

### Videos
* [Citus Data Youtube channel](https://www.youtube.com/channel/UC8jpoK1BqQhDh6HDGFnM_DA/videos) - Citus related videos
* [EnterpriseDB Youtube channel](https://www.youtube.com/channel/UCkIPoYyNr1OHgTo0KwE9HJw) -  EnterpriseDB related videos
* [Postgres Conference Youtube channel](https://www.youtube.com/channel/UCsJkVvxwoM7R9oRbzvUhbPQ/videos) - Conference videos
* [Scaling Postgres](https://www.scalingpostgres.com/) - Postgres video blog series by Creston Jamison
* [PostgresTV Youtube channel](https://www.youtube.com/@PostgresTV) - Postgres talks, hacking sessions, interviews, and podcast episodes

### Community
* [Mailing lists](https://www.postgresql.org/list/) - Official mailing lists for Postgres for support, outreach, and more. One of the primary channels of communication in the Postgres community.
* [Reddit](https://www.reddit.com/r/PostgreSQL/) - A reddit community for PostgreSQL users with over 12000 users
* [Slack](https://pgtreats.info/slack-invite) - Slack workspace for Postgres with over 20k members
* Telegram - Several groups for PostgreSQL in different languages: [Russian](https://t.me/pgsql) >4200 people, [Brazilian Portuguese](https://t.me/postgresqlbr) >2300 people, [Indonesian](https://t.me/postgresql_id) ~1000 people, [English](https://t.me/postgreschat) >750 people
* [#postgresql on Freenode](https://webchat.freenode.net/#postgresql) - The most popular IRC channel about Postgres on Freenode with over 1000 users
* [Discord](https://discord.gg/bW2hsax8We) - A Discord server for Postgres with over 6k members

### Roadmaps
* [PostgreSQL Roadmap](https://roadmap.sh/postgresql-dba) - A roadmap providing step wise guide to PostgreSQL.

### External lists
* [Wikipedia admin tools list](https://en.wikipedia.org/wiki/Comparison_of_database_tools) - Comparison of database administration tools on Wikipedia
* [PostgreSQL Wiki GUI tools list](https://wiki.postgresql.org/wiki/Community_Guide_to_PostgreSQL_GUI_Tools) - Community Guide to PostgreSQL GUI Tools
* [PostgreSQL Wiki Foreign Data Wrappers list](https://wiki.postgresql.org/wiki/Foreign_data_wrappers) - Foreign data wrappers
