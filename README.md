# AWS & PostgreSQL Architecture Notes

Visual explainers breaking down cloud database architecture concepts into
simple, shareable diagrams — originally created and posted on LinkedIn.

## Contents

### AWS Aurora Storage & Replication — Architecture in a Nutshell
![Aurora Storage & Replication](images/aurora-storage-replication.png)

Covers:
- How Aurora decouples compute from storage
- Writer/reader instance roles and read-scaling (up to 15 readers)
- 6-way replication across 3 Availability Zones for durability and HA
- Continuous backups to Amazon S3 and self-healing storage
- End-to-end write/read/backup flow in plain terms

---

More architecture explainers will be added here over time as companion
material to LinkedIn posts — covering PostgreSQL internals, migration
architecture, and HA/DR design.

## About

Created by Rajiv joseph — Principal Consultant specializing in Oracle-to-PostgreSQL
migration and AWS Aurora/cloud database architecture. 

