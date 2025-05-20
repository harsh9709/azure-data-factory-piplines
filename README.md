# azure-data-factory-piplines

![image](https://github.com/user-attachments/assets/1eae4961-73e9-4d1c-a8db-cccc398543b4)
dynamically copy files from adls folder based on filenames

##dataflow transformation activityies in the pipeline to lastly sink data in adls 
![image](https://github.com/user-attachments/assets/e8c343e3-a4e0-4a23-aad5-897456be4d23)


##pipeline success output for the ETL job in azure data factory
using get meta data for only copy files from the particular adls folder based on condition on file name using forEach activity to iterate over all files in the folder
once the desired files are copied to teh destination, one of the file is the source dataset for data flow performing different transformations and dump final data in adls using sink

![image](https://github.com/user-attachments/assets/d481bf25-94b9-463e-9bf8-3a054d99b0df)
