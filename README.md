Uber Data Analytics

The goal of this project is to perform data analytics on Uber data using various tools and technogies, including GCP storage, Python, Compute Instance, Mage Data Piepeline tool, BigQuery and Looker Studio.

The final report can be accessed here: https://lookerstudio.google.com/u/0/reporting/64bd04f0-9dd4-4f59-a4a2-c1bf6938cccf/page/i6WZD

Technologies used--
- Programmin Language - Python
- Dependencies
  1. pip
  2. distutils
  3. wget
  4. mage-ai
  5. pandas
  6. google-cloud
  7. google-cloud-bigquery

- Google Cloud Platform
  1. Google Storage
  2. Compute Instance
  3. BigQuery
  4. Looker Studio


- Data Pipeline tool - Mage.ai

###Dataset - TLC Trip Record Data
Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts.

###Architecture
  1. Data was preprocessed on Jupyter lab and then uploaded to a bucket in Google Storage,
  2. A virtual machine was created using GCP Compute Engine and then the project dependencies were installed onto the vm,
  3. Mage was started using the vm and the pipeline was built there and the output loaded onto BigQuery,
  4. A analytics report was developed on it using SQL,
  5. The data was visually represented using Looker Studio

Thank You!
Have a Nice Day!!
