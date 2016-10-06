# Awesome Postgres
A curated list of awesome PostgreSQL software, libraries, tools and resources, inspired by awesome-mysql

- [Awesome Postgres](https://github.com/dhamaniasad/awesome-postgres#awesome-postgres)
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
  - [Tutorials](#tutorials)
  - [Blogs](#blogs)
  - [Articles](#articles)
  - [Newsletters](#newsletters)
  - [PaaS (Hosted Postgres)](#paas)

### High-Availability
* [Patroni](https://github.com/zalando/patroni) - A template for PostgreSQL HA with ZooKeeper or etcd
* [pglookout](https://github.com/ohmu/pglookout) - Replication monitoring and failover daemon
* [repmgr](https://github.com/2ndQuadrant/repmgr) - Is an open-source tool suite to manage replication and failover in a cluster of PostgreSQL servers
* [Slony-I](http://slony.info) - A "master to multiple slaves" replication system with cascading and failover

### Backups
* [Barman](http://www.pgbarman.org/) - Backup and Recovery Manager for Postgres by 2ndQuadrant
* [OmniPITR](https://github.com/omniti-labs/omnipitr) - Advanced WAL File Management Tools for PostgreSQL
* [pgBackRest](http://www.pgbackrest.org) - Reliable PostgreSQL Backup & Restore
* [pghoard](https://github.com/ohmu/pghoard) - Backup and restore tool for cloud object stores (AWS S3, Azure, Google Cloud, OpenStack Swift)
* [wal-e](https://github.com/wal-e/wal-e) - Simple Continuous Archiving for Postgres to S3, Azure, or Swift by Heroku

### GUI
* [Adminer](https://www.adminer.org/) – Full-featured database management tool written in PHP
* [DataGrip](https://www.jetbrains.com/datagrip/) - An IDE with advanced tool sets and good cross-platform experience (Commercial Software)
* [Datazenit](https://datazenit.com/) - Web-based PostgreSQL GUI (Commercial Software)
* [DBeaver](http://dbeaver.jkiss.org) - Universal Database Manager with excellent support for Postgres
* [JackDB](https://www.jackdb.com/) - Web-based SQL query interface (Commercial Software)
* [Metabase](http://www.metabase.com) - Simple dashboards, charts and query tool for your Postgres DB
* [pgAdmin](https://www.pgadmin.org/) - Postgres Administration and Management GUI
* [pgModeler](http://pgmodeler.com.br/) - pgModeler is an open-source PostgreSQL Database Modeler
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser written in Go
* [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) - The Premier Web Based Administration Tool for Postgres
* [Postbird](https://github.com/Paxa/postbird) - PostgreSQL Client for macOS
* [Postico](https://eggerapps.at/postico/) - A Modern PostgreSQL Client for macOS (Commercial Software)
* [PSequel](http://www.psequel.com/) - PSequel provides a clean and simple interface for you to perform common PostgreSQL tasks quickly (Commercial Software)
* [SQL Tabs](http://www.sqltabs.com/) - A Cross Platform Desktop Client for Postgres written in JS
* [SQLPro for Postgres](http://macpostgresclient.com/) - A simple, powerful Postgres manager for macOS (Commercial Software)
* [Warp](http://warp.one/) - macOS desktop tool for by-example querying and data transfer from/to PostgreSQL (Commercial Software)

### Distributions
* [Postgres.app](http://postgresapp.com/) - The Easiest Way to Get Started with PostgreSQL on macOS

### CLI
* [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting
* [psql2csv](https://github.com/fphilipe/psql2csv) - Run a query in psql and output the result as CSV

### Server
* [Postgres-XL](http://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based Database Cluster
* [Citus](https://github.com/citusdata/citus) - Scalable PostgreSQL cluster for real-time workloads

### Monitoring
* [check\_pgactivity](https://github.com/OPMDG/check_pgactivity) - check\_pgactivity is designed to monitor PostgreSQL clusters from Nagios. It offers many options to measure and monitor useful performance metrics
* [Check\_postgres](https://github.com/bucardo/check_postgres) - Nagios check\_postgres plugin for checking status of PostgreSQL databases
* [libzbxpgsql](https://github.com/cavaliercoder/libzbxpgsql) - A comprehensive PostgreSQL monitoring module for Zabbix
* [Pome](https://github.com/rach/pome) - Pome stands for Postgres Metrics. Pome is a PostgreSQL Metrics Dashboard to keep track of the health of your database
* [pg\_view](https://github.com/zalando/pg_view) - An open-source command-line tool that shows global system stats, per-partition information, memory stats and other information

### Extensions
* [cstore\_fdw](https://github.com/citusdata/cstore_fdw) - Columnar store for analytics with PostgreSQL
* [pglogical](https://github.com/2ndQuadrant/pglogical) - An extension that provides logical streaming replication
* [pg\_partman](https://github.com/keithf4/pg_partman) - Partition management extension for PostgreSQL
* [pg\_paxos](https://github.com/citusdata/pg_paxos/) - Basic implementation of Paxos and Paxos-based table replication for a cluster of PostgreSQL nodes
* [pg\_shard](https://github.com/citusdata/pg_shard) - PostgreSQL extension to scale out real-time reads and writes
* [PGStrom](https://wiki.postgresql.org/wiki/PGStrom) - Postgres extension to offload CPU intensive workloads to GPU
* [plpgsql\_check](https://github.com/okbob/plpgsql_check) - An extension that allows to check plpgsql source code
* [PostGIS](http://postgis.net/) - Spatial and Geographic objects for PostgreSQL
* [zomboDB](https://github.com/zombodb/zombodb) - Postgres extension that enables efficient full-text searching via the use of indexes backed by Elasticsearch

### Optimization
* [PgHero](https://github.com/ankane/pghero) - Postgres insights made easy
* [pgtune](https://github.com/gregs1104/pgtune/) - PostgreSQL configuration wizard
* [pgtune](http://pgtune.leopard.in.ua/) - Online version of PostgreSQL configuration wizard
* [PoWA](http://dalibo.github.io/powa/) - PostgreSQL Workload Analyzer gathers performance stats and provides real-time charts and graphs to help monitor and tune your PostgreSQL servers.

### Utilities
* [apgdiff](http://www.apgdiff.com/) - Compares two database dump files and creates output with DDL statements that can be used to update old database schema to new one
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - ERAlchemy generates Entity Relation (ER) diagram from databases
* [mysql-postgresql-converter](https://github.com/lanyrd/mysql-postgresql-converter) - Lanyrd's MySQL to PostgreSQL conversion script
* [ora2pg](http://ora2pg.darold.net) - a Perl module to export an Oracle database schema to a PostgreSQL compatible schema
* [pg\_activity](https://github.com/julmon/pg_activity) - pg\_activity is a top like application for PostgreSQL server activity monitoring
* [pganalyze](https://pganalyze.com) - PostgreSQL Performance Monitoring (Commercial Software)
* [pgbadger](https://github.com/dalibo/pgbadger) - a fast PostgreSQL Log Analyzer
* [PgBouncer](http://pgbouncer.github.io) - Lightweight connection pooler for PostgreSQL
* [pgCenter](https://github.com/lesovsky/pgcenter) - Provides convenient interface to various statistics, management task, reloading services, viewing log files and canceling or terminating database backends
* [pgclimb](https://github.com/lukasmartinelli/pgclimb) - Export data from PostgreSQL into different data formats
* [pgfutter](https://github.com/lukasmartinelli/pgfutter) - Import CSV and JSON into PostgreSQL the easy way
* [PGInsight](http://pginsight.io/) - CLI tool to easily dig deep inside your Postgresql database
* [pgloader](https://github.com/dimitri/pgloader) - Pgloader loads data into PostgreSQL using the COPY streaming protocol, and does so with separate threads for reading and writing data
* [pgpool-II](http://www.pgpool.net/mediawiki/index.php/Main_Page) - Middleware that provides connection pooling, replication, load balancing and limiting exceeding connections
* [pgsync](https://github.com/ankane/pgsync) - A tool to sync Postgres data to your local machine
* [PGXN client](https://github.com/dvarrazzo/pgxnclient) - A command line tool to interact with the PostgreSQL Extension Network
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) - Tool that extracts and provides metrics on your PostgreSQL database
* [PostgREST](https://github.com/begriffs/postgrest) - PostgREST serves a fully RESTful API from any existing PostgreSQL database
* [yoke](https://github.com/nanopack/yoke) - Postgres high-availability cluster with auto-failover and automated cluster recovery

### Language bindings
* Common Lisp: [Postmodern](https://github.com/marijnh/Postmodern)
* Elixir: [postgrex](https://github.com/elixir-ecto/postgrex)
* Go: [pgx](https://github.com/jackc/pgx)
* Java: [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/)
* Node: [node-postgres](https://github.com/brianc/node-postgres)
* Perl: [DBD-Pg](http://search.cpan.org/~turnstep/DBD-Pg/Pg.pm)
* PHP: [Pomm](http://www.pomm-project.org), [pecl/pq](https://github.com/m6w6/ext-pq)
* Python: [psycopg2](https://pypi.python.org/pypi/psycopg2)
* Ruby: [pg](https://bitbucket.org/ged/ruby-pg/wiki/Home)
* Rust: [rust-postgresql](https://github.com/sfackler/rust-postgres)

### Tutorials
* [Backup and recover a Postgres DB using wal-e](https://coderwall.com/p/cwe2_a/backup-and-recover-a-postgres-db-using-wal-e) - A tutorial about setting up continuous archiving in PostgreSQL using wal-e
* [PG Casts](https://www.pgcasts.com) - Free weekly PostgreSQL screencasts by Hashrocket
* [Postgres Guide](http://postgresguide.com/) - A guide designed as an aid for beginners and experienced users to find specific tips and explore tools available within Postgres
* [PostgreSQL Exercises](https://pgexercises.com/) - A site  to make it easy to learn PostgreSQL by doing
* [tutorialspoint PostgreSQL tutorial](http://www.tutorialspoint.com/postgresql/) - A very extensive collection of tutorials on PostgreSQL

### Blogs
* [Planet PostgreSQL](http://planet.postgresql.org/) - A blog aggregation service for PostgreSQL
* [Andrew Dunstan's PostgreSQL and Technical blog](http://adpgtech.blogspot.ru/search/label/PostgreSQL/)
* [Bruce Momjian's Postgres blog](http://momjian.us/main/blogs/pgblog.html)
* [Craig Kerstiens Postgres Posts](http://www.craigkerstiens.com/categories/postgres/) - A set of posts on Postgres cool features/tips/tricks
* [Database Soup](http://www.databasesoup.com/search/label/postgresql/) - Josh Berkus' blog
* [Michael Paquier's blog](http://paquier.xyz/)
* [Robert Haas' blog](http://rhaas.blogspot.ru/search/label/postgresql/)
* [select * from depesz;](https://www.depesz.com/tag/postgresql/) - Hubert Lubaczewski's blog

### Articles

* [What PostgreSQL has over other open source SQL databases: Part I](https://www.compose.com/articles/what-postgresql-has-over-other-open-source-sql-databases/)
* [Debugging PostgreSQL performance, the hard way](https://www.justwatch.com/blog/post/debugging-postgresql-performance-the-hard-way/)

### Newsletters

* [Postgres Weekly](http://postgresweekly.com/) - A weekly newsletter that contains articles, news, and repos relevant to Postgres

### PaaS
*(Postgres as a Service)*
* [Aiven PostgreSQL](https://aiven.io/postgresql) - PostgreSQL as a service in AWS, Azure, DigitalOcean, Google Cloud and UpCloud; plans range from $19/month single node instances to large highly-available setups, free trial for two weeks
* [Database Labs](https://www.databaselabs.io) - Get a production-ready cloud Postgres server in minutes, from $20 a month Backups, monitoring, patches, and 24/7 tech support all included
* [ElephantSQL](http://www.elephantsql.com) - Offers databases ranging from shared servers for smaller projects and proof of concepts, up to enterprise grade multi server setups. Has free plan for up to 5 DBs, 20 MB each
* [Heroku Postgres](https://elements.heroku.com/addons/heroku-postgresql) - Plans from free to huge, operated by Postgres experts. Does not require running your app on Heroku. Free plan includes 10,000 rows, 20 connections, up to two backups, and has PostGIS support
