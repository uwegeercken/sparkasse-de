# sparkasse-de

GERMAN:
ETL Prozess um Bankdaten der Sparkasse zu verarbeiten. Die Idee ist hier die Transaktionen in einer Datenbank zu akkumulieren, so daß sie einfach abfragbar sind.

Der ETL Prozess benutzt Deutsch als Sprache für alle Elemente.

Mann kann bei der Sparkasse die Transaktionen für einen gegebenen Zeitraum als CSV Datei(en) herunterladen. Die Dateien werden verarbeitet und die Daten in einer MongoDb abgelegt.

Der ETL:
- verarbeitet eine oder mehrere CSV Dateien
- erlaubt es Kategorien und Subkategorien zu definieren und diese den Transaktionen zuzuordnen
- erlaubt das definieren von Übersetzungen von Empfängern zu einer eindeutigen Gruppe oder eindeutigen Namen


ENGLISH:

ETL to process bank account data for the german Sparkasse (bank). The idea is to accumulate the transactions into a database to make the data easily queryable.

The ETL uses german for all elements.

Download one or multiple CSV files with the transactions of a defined period from the online banking website. The files are processed and can be stored in a MongoDb instance.

The ETL:
- processes one or multiple CSV input files
- allows to define categories and subkategories and map them to the individual tranactions
- allows to define a mapping of recipient to a unified group/name



last update: Uwe Geercken - 2021-12-04
