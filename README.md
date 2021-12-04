# sparkasse-de
ETL to process bank account data for the german Sparkasse (bank). The idea is to accumulate the transactions into a database to make the data easily queryable.

The ETL uses german for descriptions, categories, documentation, etc.

Download one or multiple CSV files with the transactions of a defined period from the online banking website. The files are processed and can be stored in a MongoDb instance.

The ETL:
- processes multiple CSV input files
- allows to define categories and subkategories and map them to the individual tranactions
- allows to define a mapping of recipient to a unified name




last update: Uwe Geercken - 2021-12-04
