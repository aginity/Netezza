# Netezza Package Summary

|Package Name| Package Description| Number of Queries in Package|
|------------|--------------------|-----------------------------|
|Aginity-Pro-Netezza-Admin-Set1 |Contains common SQL queries to better understand Netezza objects   | 5  |




### The table below details all queries within the [Aginity-Pro-Netezza-Admin-Set1]() package.

|Catalog Item Name               |Catalog Item Description            | Required Table     |
|--------------------------|------------------------------------|--------------------|
|Count of rows per dataslice for a Table   | Shows the number of rows in each data slice giving you a sense for whether the distribution on a table is skewed  | N/A interrogate the table itself  |
|Current sessions and their queries   |Show open running sessions and queries being executed   | _v_session  |
|Server I/O Usage per date   | Total I/O (reads/writes) on appliance by day | _V_SCHED_GRA_EXT  |
|Tables size in MB   | The size in MB of tables in the database  | _v_table_storage_stat  |
|Tables Statistics in current schema   | Key statistics about each table within a schema  | _v_relation_column,_v_statistic,_V_TABLE  |
