# DVA-NYC_Congestion
Project for Data Visualization &amp; Analytics Class (CSE6242)


**INSTALLATION**

	1.	Open the notebook in Google Colab (recommended environment).
		You can upload the notebook directly to colab.research.google.com or open it from Google Drive.

	2.	Upload your Kaggle API token:
	•	Go to your Kaggle account settings and download your kaggle.json API key.
	•	In the notebook, use the upload widget to upload kaggle.json when prompted.
 
	3.	Run the first few cells to:
	•	Install the Kaggle API (!pip install -q kaggle)
	•	Configure your Kaggle credentials
	•	Automatically download and unzip the NYC rideshare dataset
 
	4.	Ensure your Colab environment supports PySpark:
	•	The notebook creates a Spark session using SparkSession.builder.appName("NYC_Rides").getOrCreate()
	•	No additional setup is needed in Colab, as it includes Java and Spark
 
	5.	Run each cell sequentially to perform data cleaning, feature extraction, and modeling.
The notebook uses PySpark for data processing and sklearn for gradient boosting regression.
