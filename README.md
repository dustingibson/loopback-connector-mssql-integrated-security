# loopback-connector-mssql
Forked Loop back connector for mssql integrated security that uses msnodesqlv8 driver.

Config will look something like this:

```
const config = {
  name: 'name-of-connection',
  connector: 'package-name',
  host: '{your-host-name',
  database: 'your-datadb-name'
};

```