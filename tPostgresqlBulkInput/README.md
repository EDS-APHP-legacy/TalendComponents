# tPostgresqlBulkInput

- works with JDBC CopyOut function
- get directly the stream from database : no client disk use
- More 2 times faster than official tPostgresqlInput (working with JDBC resultSet)
- postgresql >= 9.X
- for now manage only dates, integer & character fields
