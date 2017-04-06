# Data Mining/Analytics Toolbox

The modules, operators and libraries included in the data mining and analytics toolbox can be classified in:

* [legacy software components](#legacy-software-components);
* [new software components](#new-software-components).

## Legacy software components

### Ophidia Primitives

*Ophidia Primitives* provide a wide set of array-based functionalities that can be applied through SQL-like queries on the single arrays stored in Ophidia data cubes. 

Links:

* Primitives description: [http://ophidia.cmcc.it/documentation/users/primitives/index.html](http://ophidia.cmcc.it/documentation/users/primitives/index.html)
* Documentation: [http://ophidia.cmcc.it/documentation/admin/install/components/install_primitives.html](http://ophidia.cmcc.it/documentation/admin/install/components/install_primitives.html)
* Source code: [https://github.com/OphidiaBigData/ophidia-primitives](https://github.com/OphidiaBigData/ophidia-primitives)

### Ophidia Operators

*Ophidia Operators* provide metadata and data cube-oriented operators used to process and manage the whole data cube. The operators are executed within the Ophidia Analytics Framework, which provides the environment for the execution of parallel operations over the distributed data in Ophidia. 

Links:

* Operators description: [http://ophidia.cmcc.it/documentation/users/operators/index.html](http://ophidia.cmcc.it/documentation/users/operators/index.html)
* Documentation: [http://ophidia.cmcc.it/documentation/admin/install/components/install_framework.html](http://ophidia.cmcc.it/documentation/admin/install/components/install_framework.html)
* Source code: [https://github.com/OphidiaBigData/ophidia-analytics-framework](https://github.com/OphidiaBigData/ophidia-analytics-framework)

### Spark Dataframe API

*Apache Spark* is a fast and general-purpose cluster computing system. It provides high-level APIs in Java, Scala, Python and R, and an optimized engine that supports general execution graphs. 

Links:

* Documentation: [http://spark.apache.org/docs/latest/sql-programming-guide.html](http://spark.apache.org/docs/latest/sql-programming-guide.html)
* Source code: [https://github.com/apache/spark](https://github.com/apache/spark)
* Pre-built Spark download: [http://spark.apache.org/downloads.html](http://spark.apache.org/downloads.html)

### Spark MLLib Dataframe API and Spark MLLib RDD API

Spark includes two large sets of APIs related to machine learning, *Dataframe MLLib API* and *RDD MLLib API*. These two APIs use two different abstractions in order to represent and store internal data for processing.

Links:

* Spark Dataframe MLLib documentation: [http://spark.apache.org/docs/latest/ml-guide.html](http://spark.apache.org/docs/latest/ml-guide.html) 
* Spark RDD MLLib documentation: [http://spark.apache.org/docs/latest/mllib-guide.html](http://spark.apache.org/docs/latest/mllib-guide.html) 
* Pre-built Spark download: [http://spark.apache.org/downloads.html](http://spark.apache.org/downloads.html)
* Spark source code: [https://github.com/apache/spark](https://github.com/apache/spark)

## New software components

### Extensions for privacy

*oph_encrypt* primitive provides tight integration of data privacy support in Ophidia. It can be used to replace certain types of sensitive attributes in the data with the equivalent encrypted values.

Links:

* Documentation: [http://ophidia.cmcc.it/documentation/admin/install/components/install_primitives.html](http://ophidia.cmcc.it/documentation/admin/install/components/install_primitives.html)
* Source code: [https://github.com/OphidiaBigData/ophidia-primitives](https://github.com/OphidiaBigData/ophidia-primitives)

### Mining/analytics algorithms based on Ophidia

The data mining/analytics applications based on Ophidia use pipelines of operators (and primitives) to build more articulated algorithms. These applications exploit PyOphidia and are executed with COMPSs through PyCOMPSs. 

Links:

* Application requirements and usage: [https://github.com/eubr-bigsea/ophidia-compss/blob/master/README.md](https://github.com/eubr-bigsea/ophidia-compss/blob/master/README.md)
* Source code: [https://github.com/eubr-bigsea/ophidia-compss](https://github.com/eubr-bigsea/ophidia-compss) 

### Mining/analytics algorithms based on Spark

#### ST-DBScan

*ST-DBScan* is a density-based clustering algorithm, based on DBSCAN. ST-DBScan algorithm has the ability of discovering clusters according to non-spatial, spatial and temporal values of the objects. 

Links:

* Source code of initial implementation in Python: [https://github.com/eubr-bigsea/py-st-dbscan](https://github.com/eubr-bigsea/py-st-dbscan)

#### Data Quality as a Service

The *Data Quality as a Service* (DQaaS) component allows users/applications to get information about the quality of the sources. 

Links:

* Source code: [https://github.com/eubr-bigsea/DQaaS](https://github.com/eubr-bigsea/DQaaS)

#### Entity Matching Generic Entity Representation

The *Entity Matching Generic Entity* component is an abstraction layer which is used to extract data from any data source and convert it into the RDD JSON format.

Links:

* Source code of the EMaaS algorithms is available at: [https://github.com/eubr-bigsea/EMaaS](https://github.com/eubr-bigsea/EMaaS)

#### Geo-matching Approaches

The *Entity Matching as a Service* (EMaaS) offers several Spark-based approaches (i.e., Geo-matching, Semistructured, and Incremental) to identify similar data. 

Links:

* Source code of the EMaaS algorithms is available at: [https://github.com/eubr-bigsea/EMaaS](https://github.com/eubr-bigsea/EMaaS)

