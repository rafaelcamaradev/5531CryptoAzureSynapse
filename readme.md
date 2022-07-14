Initialized by Azure Data Factory!

This is an example of Azure Synapse's project processing some massive data related to cryptocurrencies, including a Pipeline with the following components/funcionalities:
 
- Copy Command tasks;
- Remove task, used to remove all files from customized folders (using 'dynamic content' option) inside of Azure Data Lake Storage Gen2;
- Fail task, to report logs in case of failling process;
- Azure Spark notebook, with some scripts for data transformations in PySpark;
- Use of Dedicated pool tables, with Round-Robin (for load data) and Hash (for analytics)  distribuitions.


Enjoy! ;)
