# Awesome Postgres
A curated list of awesome PostgreSQL software, libraries, tools and resources, inspired by awesome-mysql

- [Awesome Postgres](https://github.com/dhamaniasad/awesome-postgres#awesome-postgres)
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
  - [Newsletters](#newsletters)
  - [PaaS (Hosted Postgres)](#paas)

### Backups
* [wal-e](https://github.com/wal-e/wal-e) - Simple Continuous Archiving for Postgres to S3, Azure, or Swift by Heroku
* [Barman](http://www.pgbarman.org/) - Backup and Recovery Manager for Postgres by 2ndQuadrant

### GUI
* [Datazenit](https://datazenit.com/) - Web-based PostgreSQL GUI (Commercial Software)
* [pgAdmin](http://pgadmin.org/) - Postgres Administration and Management GUI
* [phpPgAdmin](https://github.com/phppgadmin/phppgadmin) - The Premier Web Based Administration Tool for Postgres
* [pgweb](https://github.com/sosedoff/pgweb) - Web-based PostgreSQL database browser written in Go
* [Postico](https://eggerapps.at/postico/) - A Modern PostgreSQL Client for OS X (Commercial Software)
* [PSequel](http://www.psequel.com/) - PSequel provides a clean and simple interface for you to perform common PostgreSQL tasks quickly (Commercial Software)

### Distributions
* [Postgres.app](http://postgresapp.com/) - The Easiest Way to Get Started with PostgreSQL on the Mac

### CLI
* [pgcli](https://github.com/dbcli/pgcli) - Postgres CLI with autocompletion and syntax highlighting
* [psql2csv](https://github.com/fphilipe/psql2csv) - Run a query in psql and output the result as CSV

### Server
* [Postgres-XL](http://www.postgres-xl.org/) - Scalable Open Source PostgreSQL-based Database Cluster

### Monitoring
* [Check_postgres](https://github.com/bucardo/check_postgres) - Nagios check_postgres plugin for checking status of PostgreSQL databases
* [Pome](https://github.com/rach/pome) - Pome stands for Postgres Metrics. Pome is a PostgreSQL Metrics Dashboard to keep track of the health of your database

### Extensions
* [PGStrom](https://wiki.postgresql.org/wiki/PGStrom) - Postgres extension to offload CPU intensive workloads to GPU
* [pg_shard](https://github.com/citusdata/pg_shard) - PostgreSQL extension to scale out real-time reads and writes
* [PostGIS](http://postgis.net/) - Spatial and Geographic objects for PostgreSQL
* [pg_paxos](https://github.com/citusdata/pg_paxos/) - Basic implementation of Paxos and Paxos-based table replication for a cluster of PostgreSQL nodes

### Optimization
* [PgHero](https://github.com/ankane/pghero) - Postgres insights made easy
* [pgtune](https://github.com/gregs1104/pgtune/) - PostgreSQL configuration wizard

### Utilities
* [PostgREST](https://github.com/begriffs/postgrest) - PostgREST serves a fully RESTful API from any existing PostgreSQL database
* [mysql-postgresql-converter](https://github.com/lanyrd/mysql-postgresql-converter) - Lanyrd's MySQL to PostgreSQL conversion script
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) - Tool that extracts and provides metrics on your PostgreSQL database
* [pgloader](https://github.com/dimitri/pgloader) - Pgloader loads data into PostgreSQL using the COPY streaming protocol, and does so with separate threads for reading and writing data
* [pgbadger](https://github.com/dalibo/pgbadger) - a fast PostgreSQL Log Analyzer
* [pg_activity](https://github.com/julmon/pg_activity) - pg_activity is a top like application for PostgreSQL server activity monitoring
* [pgfutter](https://github.com/lukasmartinelli/pgfutter) - Import CSV and JSON into PostgreSQL the easy way
* [pganalyze](https://pganalyze.com) - PostgreSQL Performance Monitoring (Commercial Software)
* [yoke](https://github.com/nanopack/yoke) - Postgres high-availability cluster with auto-failover and automated cluster recovery
* [pgCenter](https://github.com/lesovsky/pgcenter) - Provides convenient interface to various statistics, management task, reloading services, viewing log files and canceling or terminating database backends
* [ERAlchemy](https://github.com/Alexis-benoist/eralchemy) - ERAlchemy generates Entity Relation (ER) diagram from databases
* [apgdiff](http://www.apgdiff.com/) - Compares two database dump files and creates output with DDL statements that can be used to update old database schema to new one

### Language bindings
* Rust: [rust-postgresql](https://github.com/sfackler/rust-postgres)
* Perl: [DBD-Pg](http://search.cpan.org/~rudy/DBD-Pg/Pg.pm)
* Java: [PostgreSQL JDBC Driver](https://jdbc.postgresql.org/)
* Node: [node-postgres](https://github.com/brianc/node-postgres)
* PHP: [Pomm](http://www.pomm-project.org)
* Lua: [luapgsql](https://github.com/arcapos/luapgsql)

### Tutorials
* [tutorialspoint PostgreSQL tutorial](http://www.tutorialspoint.com/postgresql/) - A very extensive collection of tutorials on PostgreSQL
* [Postgres Guide](http://postgresguide.com/) - A guide designed as an aid for beginners and experienced users to find specific tips and explore tools available within Postgres
* [Backup and recover a Postgres DB using wal-e](https://coderwall.com/p/cwe2_a/backup-and-recover-a-postgres-db-using-wal-e) - A tutorial about setting up continuous archiving in PostgreSQL using wal-e
* [PostgreSQL Exercises](http://pgexercises.com/) - A site  to make it easy to learn PostgreSQL by doing

### Blogs
* [Planet PostgreSQL](https://planet.postgresql.org/) - A blog aggregation service for PostgreSQL
* [Craig Kerstiens Postgres Posts](http://www.craigkerstiens.com/categories/postgres/) - A set of posts on Postgres cool features/tips/tricks

### Newsletters

* [Postgres Weekly](http://www.postgresweekly.com) - A weekly newsletter that contains articles, news, and repos relevant to Postgres

### PaaS
*(Postgres as a Service)*
* [ElephantSQL](http://www.elephantsql.com) - Offers databases ranging from shared servers for smaller projects and proof of concepts, up to enterprise grade multi server setups. Has free plan for up to 5 DBs, 20 MB each.
