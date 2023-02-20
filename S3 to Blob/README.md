R### Project 1 -  JSON TO CSV Iin shifting Blob1 to Blob 2 and create matrics

```
🎯 we have data in json format which store into blob file and we need to convert this json to json to csv format and store in 
output folder we will mount owner data bricks to output container perform some basic data cleaning operation and convert intoproper 
reporting format and finally we will derive business metrics with the help of power bi

```


<img width="500" src="Json to databricks/Copy of Cloud Architecture.png"/>

Services used -
- S3 Bucket
- Storage Account
- container (blob)
- Azure data factory
- Data bricks
- Azure Data pipeline
- power bi (no an cloud service)

#### Scope / Future step - next step to increace data source and make automation, try to use azure synapse analytics 

Some screenshot of project
 1. S3 FILE
<img width="500" src="S3 to Blob/s3.jpeg"/>
 2. Blob storage setup
<img width="500" src="S3 to Blob/img9.jpeg"/>
 3. Azure Data Factory
<img width="500" src="S3 to Blob/img5.jpeg"/>
pipeline creation.
<img width="500" src="S3 to Blob/img6.jpeg"/>
5. mount on data bricks
<img width="500" src="S3 to Blob/data.jpeg"/>
output file
<img width="500" src="S3 to Blob/img10.jpeg"/>
