### Agenda
This project mainly focuses on integrating PySpark with Apache Cassandra and Apache Hive to perform ETL(Extract-Transform-Load) and ELT(Extract-Load-Transform) operations.

### Tech Used
- Python
- PySpark
- Hive 
- Cassandra
- Docker

### Run the project
1. Clone the repository
```bash
git clone https://github.com/vishalsingh17/HiveCassandraDataPipeline.git
```

2. Change the directory
```bash
cd HiveCassandraDataPipeline
```

3. Get into the src directory
```bash
cd src
```

4. Run the docker compose file
```bash
docker-compose up
```

5. Open the browser and go to [link](https://localhost:4888)

6. Upload the data to the data folder.

7. Create a new notebook and run the commands in the pyspark_hive.ipynb


### Installing Cassandra DB

1. Download java 8 from [here](https://www.oracle.com/in/java/technologies/javase/javase8u211-later-archive-downloads.html)

2. Install Python 2.7 from [here](https://www.python.org/downloads/release/python-2718/)

3. Install Cassandra 3.11 from [here](https://www.apache.org/dyn/closer.lua/cassandra/3.11.15/apache-cassandra-3.11.15-bin.tar.gz) 

4. Follow the installation steps from [here](https://phoenixnap.com/kb/install-cassandra-on-windows)

5. Create a table using cql.

6. Create a new notebook and run the commands in the pyspark_cassandra.ipynb
