# ETL music streaming Cassandra

The used dataset is the million songs dataset (http://millionsongdataset.com/). Also log data was created using
this event simulator (https://github.com/Interana/eventsim) that fits to the song data.
The tables are created for the type of queries that will be in demand that NoSQL approach leads to fast read times.
(no joins necessary).

1. the data is loaded into a list
2. tables are created to fit the queries which will be used
3. The queries are tested out

Detailed explanation in the Notebook.
