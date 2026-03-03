# PostgreSQL Streaming Replication Lab

## Environment
- OS: Oracle Linux 7.9
- PostgreSQL: 16

## Steps Performed
1. Configured wal_level = replica
2. Set max_wal_senders
3. Took base backup using pg_basebackup
4. Started standby server

## Result
Standby successfully connected and receiving WAL files.
