# Cassandra Driver

## Usage

```bash
migrate -url cassandra://host:port/keyspace -path ./db/migrations create add_field_to_table
migrate -url cassandra://host:port/keyspace -path ./db/migrations up
migrate help # for more info
```