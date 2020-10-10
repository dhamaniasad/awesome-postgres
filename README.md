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
    - [Optimization](#optimization)
    - [Utilities](#utilities)
    - [Language bindings](#language-bindings)
    - [PaaS (PostgreSQL as a Service)](#paas-postgresql-as-a-service)
    - [Docker images](#docker-images)
- [Resources](#resources)
    - [Tutorials](#tutorials)
    - [Blogs](#blogs)
    - [Articles](#articles)
    - [Documentation](#documentation)
    - [Newsletters](#newsletters)
    - [Videos](#videos)
    - [Community](#community)

### High-Availability
* [BDR](https://github.com/2ndQuadrant/bdr) - BiDirectional Replication - a multimaster replication system for PostgreSQL
* [Patroni](https://github.com/zalando/patroni) - Template for PostgreSQL HA with ZooKeeper or etcd.
* [Stolon](https://github.com/sorintlab/stolon) - PostgreSQL HA based on Consul or etcd, with Kubernetes integration.
* [pglookout](https://github.com/aiven/pglookout) - Replication monitoring and failover daemon.
* [repmgr](https://github.com/2ndQuadrant/repmgr) - Open-source tool suite to manage replication and failover in a cluster of PostgreSQL servers.
* [Slony-I](https://slony.info/) - "Master to multiple slaves" replication system with cascading and failover.
* [PAF](https://github.com/ClusterLabs/PAF) - PostgreSQL Automatic Failover: High-Availibility for Postgres, based on Pacemaker and Corosync.
* [SkyTools](https://github.com/pgq/skytools-legacy) - Replication tools, including PgQ, a queuing system, and Londiste, a replication system a bit simpler to manage than Slony.

### Backups
* [Barman](https://www.pgbarman.org/index.html) - Backup and Recovery Manager for PostgreSQL by 2ndQuadrant.
* [OmniPITR](https://github.com/omniti-labs/omnipitr) - Advanced WAL File Management Tools for PostgreSQL.
* [pg\_probackup](https://github.com/postgrespro/pg_probackup) – A fork of pg\_arman, improved by @PostgresPro, supports incremental backups, backups from replica, multithreaded backup and restore, and anonymous backup without archive command.
* [pgBackRest](https://pgbackrest.org/)  - Reliable PostgreSQL Backup & Restore.
* [pg\_back](https://github.com/orgrim/pg_back/) - pg\_back is a simple backup script
* [pghoard](https://github.com/aiven/pghoard) - Backup and restore tool for cloud object stores (AWS S3, Azure, Google Cloud, OpenStack Swift).
* [wal-e](https://github.com/wal-e/wal-e) - Simple Continuous Archiving for PostgreSQL to S3, Azure, or Swift by Heroku.
* [wal-g](https://github.com/wal-g/wal-g) - The successor of WAL-E rewritten in Go. Currently supports cloud object storage services by AWS (S3), Google Cloud (GCS), Azure, as well as OpenStack Swift, MinIO, and file system storages. Supports block-level incremental backups, offloading backup tasks to a standby server, provides parallelization and throttling options. In addition to Postgres, WAL-G can be used for MySQL and MongoDB databases.
* [pitrery](https://dalibo.github.io/pitrery/) - pitrery is a set of Bash scripts to manage Point In Time Recovery (PITR) backups for PostgreSQL.

### GUI
* [Adminer](https://www.adminer.org/) - Full-featured database management tool written in PHP.
* [Beekeeper Studio](https://www.beekeeperstudio.io) - Free and open source SQL client with a modern UI and great Postgres support. Cross platform.
* [DataGrip](https://www.jetbrains.com/datagrip/) - IDE with advanced tool sets and good cross-platform experience (Commercial Software).
* [Datazenit](https://datazenit.com/) - Web-based PostgreSQL GUI (Commercial Software).
* [DataRow](https://www.datarow.com/) - Cross-platform SQL Client for Amazon Redshift: Simple, Effortless, Extensible.
* [DBeaver](https://dbeaver.io/) - Universal Database Manager with excellent support for PostgreSQL.
* [dbglass](http://dbglass.web-pal.com) - Cross-platform desktop client for PostgreSQL, built with Electron.
* [Holistics](https://www.holistics.io/) - Online cross platform database management tool and SQL query reporting GUI with strong PostgreSQL support (Commercial Software).
* [JackDB](https://www.jackdb.com/) - Web-based SQL query interface (Commercial Software).
* [Metabase](https://www.metabase.com/) - Simple dashboards, charts and query tool for PostgreSQL.
* [Numeracy](https://numeracy.co/) - Fast SQL editor with charts and dashboards for PostgreSQL (Commercial Software).
* [OmniDB](https://omnidb.org/en/) - Open Source Collaborative Environment
For Database Management
* [pgAdmin](https://www.pgadmin.org/) - PostgreSQL Administration and Management GUI.
* [pgModeler](https://pgmodeler.io/) - pgModeler is an open-source PostgreSQL Database Modeler.
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser written in Go.
* [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) - The Premier Web Based Administration Tool for PostgreSQL.
* [Postbird](https://github.com/Paxa/postbird) - PostgreSQL Client for macOS.
* [PostgresCompare](https://www.postgrescompare.com) - Cross-platform database comparison and deployment tool (Commercial Software).
* [Postico](https://eggerapps.at/postico/) - Modern PostgreSQL Client for macOS (Commercial Software).
* [PSequel](http://www.psequel.com/) - Clean and simple interface to perform common PostgreSQL tasks quickly (Commercial Software).
* [SQL Tabs](http://www.sqltabs.com/) - Cross Platform Desktop Client for PostgreSQL written in JS.
* [SQLPro for Postgres](http://macpostgresclient.com/) - Simple, powerful PostgreSQL manager for macOS (Commercial Software).
* [temBoard](https://github.com/dalibo/temboard) - Web-based PostgreSQL GUI and monitoring.
* [TablePlus](https://tableplus.com/) - Native App which let you edit database and structure. High-end security ensured (Commercial Software).
* [Valentina Studio](https://www.valentina-db.com/en/valentina-studio-overview) - Cross-platform database administration tool (Free/Commercial)

### Distributions
* [Postgres.app](https://postgresapp.com/) - The Easiest Way to Get Started with PostgreSQL on macOS.
* [PostgreSql.Binaries.Lite](https://github.com/mihasic/PostgreSql.Binaries.Lite) - Minimum set of Windows binaries of the PostgreSQL database. Also made available through NuGet.

### CLI
* [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting
* [pgsh](https://github.com/sastraxi/pgsh) - Branch your PostgreSQL Database like Git
* [psql](https://www.postgresql.org/docs/current/static/app-psql.html) - The built-in PostgreSQL CLI client
* [psql2csv](https://github.com/fphilipe/psql2csv) - Run a query in psql and output the result as CSV
* [nancy](https://gitlab.com/postgres-ai/nancy) - The Nancy CLI is a unified way to manage automated database experiments either in clouds or on-premise
* [schemaspy](https://github.com/schemaspy/schemaspy) - SchemaSpy is a JAVA JDBC-compliant tool for generating your database to HTML documentation, including Entity Relationship diagrams

### Server
* [Postgres-XL](https://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based Database Cluster.
* [AgensGraph](https://bitnine.net/) - Powerful graph database based on the PostgreSQL.
* [Greenplum Database](https://github.com/greenplum-db/gpdb) - Open source fork of PostgreSQL for large data volumes.

### Monitoring
* [check\_pgactivity](https://github.com/OPMDG/check_pgactivity) - check\_pgactivity is designed to monitor PostgreSQL clusters from Nagios. It offers many options to measure and monitor useful performance metrics.
* [Check\_postgres](https://github.com/bucardo/check_postgres) - Nagios check\_postgres plugin for checking status of PostgreSQL databases.
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

### Extensions
* [Citus](https://github.com/citusdata/citus) - Scalable PostgreSQL cluster for real-time workloads.
* [cstore\_fdw](https://github.com/citusdata/cstore_fdw) - Columnar store for analytics with PostgreSQL.
* [cyanaudit](https://pgxn.org/dist/cyanaudit/) - Cyan Audit provides in-database logging of all DML activity on a column-by-column basis.
* [pglogical](https://github.com/2ndQuadrant/pglogical) - Extension that provides logical streaming replication.
* [pg\_partman](https://github.com/pgpartman/pg_partman) - Partition management extension for PostgreSQL.
* [pg\_paxos](https://github.com/citusdata/pg_paxos/) - Basic implementation of Paxos and Paxos-based table replication for a cluster of PostgreSQL nodes.
* [pg\_shard](https://github.com/citusdata/pg_shard) - Extension to scale out real-time reads and writes.
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

### Optimization
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

### Utilities
* [apgdiff](https://www.apgdiff.com/) - Compares two database dump files and creates output with DDL statements that can be used to update old database schema to new one.
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - ERAlchemy generates Entity Relation (ER) diagram from databases.
* [Hasura GraphQL Engine](https://github.com/hasura/graphql-engine) - Blazing fast, instant realtime GraphQL APIs on Postgres with fine grained access control, also trigger webhooks on database events.
* [ldap2pg](https://github.com/dalibo/ldap2pg) - Synchronize roles and privileges from YML and LDAP.
* [mysql-postgresql-converter](https://github.com/lanyrd/mysql-postgresql-converter) - Lanyrd's MySQL to PostgreSQL conversion script.
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
* [pgpool-II](https://www.pgpool.net/mediawiki/index.php/Main_Page) - Middleware that provides connection pooling, replication, load balancing and limiting exceeding connections.
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
* [sqitch](https://github.com/sqitchers/sqitch) - Tool for managing versioned schema deployment
* [pgmigrate](https://github.com/yandex/pgmigrate) - CLI tool to evolve schema migrations, developed by Yandex.
* [pgcmp](https://github.com/cbbrowne/pgcmp) - Tool to compare database schemas, with capability to accept some persistent differences
* [pg-differ](https://github.com/multum/pg-differ) - Tool for easy initialization / updating of the structure of PostgreSQL tables, migration alternative (Node.js).
* [sqlcheck](https://github.com/jarulraj/sqlcheck) - Automatically detects common SQL anti-patterns. Such anti-patterns often slow down queries. Addressing them will, therefore, help accelerate queries.
* [postgres-checkup](https://gitlab.com/postgres-ai/postgres-checkup) - a new-generation diagnostics tool that allows users to collect deep analysis of the health of a Postgres database.
* [ScaffoldHub.io](https://scaffoldhub.io) - Generate fullstack PostgreSQL apps with Angular, Vue or React (Commercial Software). 

### Language bindings
* Common Lisp: [Postmodern](https://github.com/marijnh/Postmodern)
* Clojure: [clj-postgresql](https://github.com/remodoy/clj-postgresql)
* Elixir: [postgrex](https://github.com/elixir-ecto/postgrex)
* Go: [pq](https://github.com/lib/pq), [pgx](https://github.com/jackc/pgx)
* Haskell: [postgresql-simple](http://hackage.haskell.org/package/postgresql-simple)
* Java: [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/)
* .Net/.Net Core: [Npgsql](https://github.com/npgsql/npgsql)
* Node: [node-postgres](https://github.com/brianc/node-postgres), [pg-promise](https://github.com/vitaly-t/pg-promise), [pogi](https://github.com/holdfenytolvaj/pogi), [slonik](https://github.com/gajus/slonik), [postgres](https://github.com/porsager/postgres)
* Perl: [DBD-Pg](https://metacpan.org/pod/distribution/DBD-Pg/Pg.pm)
* PHP: [Pomm](http://www.pomm-project.org), [pecl/pq](https://github.com/m6w6/ext-pq)
* Python: [psycopg2](https://pypi.org/project/psycopg2/), [asyncpg](https://pypi.org/project/asyncpg/)
* Ruby: [pg](https://github.com/ged/ruby-pg)
* Rust: [rust-postgresql](https://github.com/sfackler/rust-postgres)
* Lua: [luapgsql](https://github.com/arcapos/luapgsql)

### PaaS *(PostgreSQL as a Service)*
* [Aiven PostgreSQL](https://aiven.io/postgresql) - PostgreSQL as a service in AWS, Azure, DigitalOcean, Google Cloud and UpCloud; plans range from $19/month single node instances to large highly-available setups, free trial for two weeks.
* [Amazon RDS for PostgreSQL](https://aws.amazon.com/rds/postgresql/) - Amazon Relational Database Service (RDS) for PostgreSQL
* [Azure Database for PostgreSQL](https://azure.microsoft.com/en-us/services/postgresql/) - Azure Database for PostgreSQL provides fully managed, enterprise-ready community PostgreSQL database as a service. It provides builtin HA, elastic scaling and native integration with Azure ecosystem.
* [Citus Cloud](https://www.citusdata.com/product/cloud) - Production grade scaled out PostgreSQL as a service enabling real-time workloads and sharding your multi-tenant apps.
* [Compose](https://www.compose.com/databases/postgresql) - PostgreSQL as a service in AWS, Google Cloud Platform, and IBM Cloud; plans range from $17.5/month for 1GB storage and scale at $12/GB beyond that. Free trial for 30 days available.
* [Database Labs](https://www.databaselabs.io) - Get a production-ready cloud PostgreSQL server in minutes, from $20 a month Backups, monitoring, patches, and 24/7 tech support all included.
* [DigitalOcean Managed Databases](https://www.digitalocean.com/products/managed-databases/) - Fully managed PostgreSQL databases. No free plan. Starting at $15/mo. Daily backups with point-in-time recovery. Standby nodes with auto-failover.
* [ElephantSQL](https://www.elephantsql.com/) - Offers databases ranging from shared servers for smaller projects and proof of concepts, up to enterprise grade multi server setups. Has free plan for up to 5 DBs, 20 MB each.
* [Google Cloud SQL for PostgreSQL](https://cloud.google.com/sql/docs/postgres/) - Fully-managed database service that makes it easy to set up, maintain, manage, and administer your PostgreSQL relational databases on Google Cloud Platform.
* [Heroku Postgres](https://elements.heroku.com/addons/heroku-postgresql) - Plans from free to huge, operated by PostgreSQL experts. Does not require running your app on Heroku. Free plan includes 10,000 rows, 20 connections, up to two backups, and has PostGIS support.

### Docker images
* [citusdata/citus](https://hub.docker.com/r/citusdata/citus/) - Citus official images with citus extensions. Based on the official Postgres container.
* [mdillon/postgis](https://hub.docker.com/r/mdillon/postgis/) - PostGIS 2.3 on Postgres 9. Based on the official Postgres container.
* [postgres](https://hub.docker.com/_/postgres/) -  Official postgres container (from Docker)

## Resources

### Tutorials
* [Backup and recover a PostgreSQL DB using wal-e](https://coderwall.com/p/cwe2_a/backup-and-recover-a-postgres-db-using-wal-e) - Tutorial about setting up continuous archiving in PostgreSQL using wal-e.
* [PG Casts](https://www.pgcasts.com) - Free weekly PostgreSQL screencasts by Hashrocket.
* [Postgres Guide](http://postgresguide.com/) - Guide designed as an aid for beginners and experienced users to find specific tips and explore tools available within PostgreSQL.
* [PostgreSQL Exercises](https://pgexercises.com/) - Site  to make it easy to learn PostgreSQL by doing exercises.
* [tutorialspoint PostgreSQL tutorial](http://www.tutorialspoint.com/postgresql/) - Very extensive collection of tutorials on PostgreSQL
* [postgresDBSamples](https://github.com/morenoh149/postgresDBSamples) - A collection of sample postgres schemas
* [PostgreSQL Primer for Busy People](https://zaiste.net/postgresql_primer_for_busy_people/) - A collection of the most common commands used in PostgreSQL
* [pg-utils](https://github.com/dataegret/pg-utils) - Useful DBA tools by Data Egret

### Blogs
* [Planet PostgreSQL](https://planet.postgresql.org/) - Blog aggregation service for PostgreSQL.
* [Andrew Dunstan's PostgreSQL and Technical blog](http://adpgtech.blogspot.com/search/label/PostgreSQL/)
* [Bruce Momjian's PostgreSQL blog](https://momjian.us/main/blogs/pgblog.html)
* [Craig Kerstiens PostgreSQL posts](http://www.craigkerstiens.com/categories/postgres/) - Set of posts on PostgreSQL cool features, tips and tricks.
* [Database Soup](http://www.databasesoup.com/search/label/postgresql/) - Josh Berkus' blog.
* [Michael Paquier's blog](https://paquier.xyz/)
* [Robert Haas' blog](http://rhaas.blogspot.com/search/label/postgresql/)
* [select * from depesz;](https://www.depesz.com/tag/postgresql/) - Hubert Lubaczewski's blog.

### Articles

* [What PostgreSQL has over other open source SQL databases: Part I](https://www.compose.com/articles/what-postgresql-has-over-other-open-source-sql-databases/)
* [What PostgreSQL has over other open source SQL databases: Part II](https://www.compose.com/articles/what-postgresql-has-over-other-open-source-sql-databases-part-ii/)
* [the ultimate postgres vs mysql blog post](https://di.nmfay.com/postgres-vs-mysql)
* [Debugging PostgreSQL performance, the hard way](https://www.justwatch.com/blog/post/debugging-postgresql-performance-the-hard-way/)
* [Why use Postgres?](http://www.craigkerstiens.com/2017/04/30/why-postgres-five-years-later/)
* [Superfast CSV imports using PostgreSQL's COPY command](https://infinum.com/the-capsized-eight/superfast-csv-imports-using-postgresqls-copy)

### Documentation
* [Wiki](https://wiki.postgresql.org/wiki/Main_Page) - user documentation, how-tos, and tips 'n' tricks

### Newsletters

* [Postgres Weekly](https://postgresweekly.com/) - Weekly newsletter that contains articles, news, and repos relevant to PostgreSQL.

### Videos
* [Citus Data Youtube channel](https://www.youtube.com/channel/UC8jpoK1BqQhDh6HDGFnM_DA/videos) - Citus related videos
* [EnterpriseDB Youtube channel](https://www.youtube.com/channel/UCkIPoYyNr1OHgTo0KwE9HJw) -  EnterpriseDB related videos
* [Postgres Conference Youtube channel](https://www.youtube.com/channel/UCsJkVvxwoM7R9oRbzvUhbPQ/videos) - Conference videos
* [Scaling Postgres](https://www.scalingpostgres.com/) - Postgres video blog series by Creston Jamison

### Community
* [Mailing lists](https://www.postgresql.org/list/) - Official mailing lists for Postgres for support, outreach, and more. One of the primary channels of communication in the Postgres community.
* [Reddit](https://www.reddit.com/r/PostgreSQL/) - A reddit community for PostgreSQL users with over 12000 users
* [Slack](https://postgres-slack.herokuapp.com/) - Slack channel for Postgres with over 7000 users
* Telegram - Several groups for PostgreSQL in different langauges: [Russian](https://t.me/pgsql) >4200 people, [Brazilian Portuguese](https://t.me/postgresqlbr) >2300 people, [Indonesian](https://t.me/postgresql_id) ~1000 people, [English](https://t.me/postgreschat) >750 people
* [#postgresql on Freenode](https://webchat.freenode.net/#postgresql) - The most popular IRC channel about Postgres on Freenode with over 1000 users
