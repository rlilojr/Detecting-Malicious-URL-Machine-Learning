This source code expects that the following requirements are met:

Apache Spark 2.0 in installed
Jupyter Notebook is intalled - Installing Anacoda takes care of all dependencies

OS: Linux
Programing Languare use: python - (pyspark in Apache Spark)

We have three options of datasets that we use in our project. Either one of can be used to see the usage of the code.

1. Github - The datasets from Github are already labelled and can be used on the fly using our source_code
	Link: nhttps://github.com/surajr/URL-Classification



2. We customized our own datasets from the following: THis datasets is about 1.1 million as we combined all the below datasets.
   We used a another source code to pre-process and generate this our new datasets with contains benign and malicious labels

	Phishtank: This contains a datasets of phising URL. THese are raw datasets that needs to be cleaned. 
	Link: https://www.phishtank.com/developer_info.php

	Majestic: THi contains 1 million benign (genuine) datasets
	Link: https://majestic.com/reports/majestic-million
	
	JWSPAMSPY: These are spam URLs
	http://www.joewein.de/sw/blacklist.htm



3. Kaggle: These are datasets obtained from Kaggle. 
	https://www.kaggle.com/antonyj453/urldataset/data



IMPORTANT - The above links are the orginal places where we got our datasets. However, we have put all the above datasets
in one location to make usage easy. All the above mentioned ready-to-run, cleaned datasets can be found in:

Link: https://github.com/rlilojr/Detecting-Malicious-URL-Machine-Learning/tree/master/processed_data