# One DataSource

One DataSource to rule them all.  

This projects aims to decorate a [DataSource](https://docs.oracle.com/javase/8/docs/api/javax/sql/DataSource.html)
and thus provide plugabble features like monitoring and statistics.

Multiple features may take place, such as:

- Collect database access contribution to the total request time
- Query statistics: may show query time + result set fetch time per query
- Detect slow queries
- Detect slow ResultSet fetch
- Detect unclosed Connections, Statements and ResultSets (possibly causing leaks)
- ...
