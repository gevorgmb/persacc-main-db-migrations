# persacc-main-db-migrations

**Update DB:** docker compose --profile tools run --rm [ServiceName] update

**Rollback migrations:** docker compose --profile tools run --rm [ServiceName] rollback-count --count=[Count of migrations to rollback]