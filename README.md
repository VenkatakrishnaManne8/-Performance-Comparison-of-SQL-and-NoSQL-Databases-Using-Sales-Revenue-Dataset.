# -Performance-Comparison-of-SQL-and-NoSQL-Databases-Using-Sales-Revenue-Dataset.
Conducted performance measurements between SQL (Postgres DB) and NoSQL (MongoDB) databases using a revenue sales dataset of 5 million records.
Compared the performance of importing a 600MB CSV file, with MongoDB taking 1 minute 10 seconds and Postgres completing in 20 seconds.
Evaluated backup table creation times, where MongoDB took 1 minute 46 seconds and Postgres completed in 7 seconds.
Assessed the performance of simple and conditional select queries, with MongoDB taking 10 seconds to fetch 5 million records and Postgres 11 seconds. MongoDB outperformed in simple queries, while Postgres was faster for condition-based selects.
Measured the time taken to truncate tables, finding SQL (Postgres) to be significantly faster (65 milliseconds) compared to MongoDB (45 seconds).
Evaluated performance of nested queries with aggregation; SQL (Postgres) completed in 3.9 seconds, whereas MongoDB took 5.1 seconds.
Utilized MongoDB Shell, MongoDB Compass, and pgAdmin 4 for database management and performance evaluation.
