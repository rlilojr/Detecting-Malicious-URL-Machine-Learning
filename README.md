# Detecting-Malicious-URL-Using-Pyspark

## Development Enviroment
1. Apache Spark 2.3.0
2. Jupyter Notebook

## Datasets
Datasets used in this project is manually obtained from the following sources:
##### Phising URLS
1. Phishtank - https://www.phishtank.com/developer_info.php
2. Open Phis - https://openphish.com/

##### SPAM URLS
1. JWSPAMSPY - http://www.joewein.de/sw/blacklist.htm

##### Malware URLS
1. DNS-BH - http://www.malwaredomains.com/wordpress/?page_id=66
2. https://www.malwarepatrol.net/my-account/
3. http://www.malwaredomainlist.com/

##### Benign URLS
1. Majestic - https://majestic.com/reports/majestic-million

##### Another Usefull Source to collect Malicious URLs
1. https://zeltser.com/malicious-ip-blocklists/

The Dataset.csv used in this project is the combination of the above sources. A data pre-processing program is used to clean and filter the data. Thus, the dataset is already being labelled and ready to be used in the project.
