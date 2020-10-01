# loopback-connector-mssql-integrated-security
Forked Loop back connector for mssql integrated security that uses msnodesqlv8 driver.

Config will look something like this:

```
const config = {
  name: 'name-of-connection',
  connector: 'loopback-connector-mssql-integrated-security',
  host: 'your-host-name',
  database: 'your-datadb-name'
};

```