# Changelog

## v0.4.0

- Added IDE integration for VS Code
- Added auto-connect to IDE on extension installation
- Added `/ide` command to manage IDE connections (list, connect, disconnect, and status)
- Added tool for database administration (GRANT/REVOKE, CREATE/ALTER/DROP operations)
- Improved dbt integration: converted to flags (`--dbt`, `--dbt-project`, `--dbt-profile`, `--dbt-target`)
- Fixed Snowflake cross-database list operations (schemas, tables, columns now visible across databases)
- Fixed Snowflake RSA key pair authentication
- Fixed integer underflow panics in truncation calculations

## v0.3.0

- Added Ctrl+R shortcut to expand truncated content in terminal output
- Added `--local` flag to `login` command for directory-specific credentials
- Added `--dbt-profile` flag to override project's default dbt profile
- Added docs link to `/help` command for easier access to user guides
- Fixed markdown line break rendering in terminal output
- Improved Linux ODBC driver support
