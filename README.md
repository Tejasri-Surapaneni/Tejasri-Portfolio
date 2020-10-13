
## My Journey of Data Science
<hr> 

## Certifications 
<hr> 

<a href="https://www.youracclaim.com/badges/ea4effc3-943c-4f0f-b8dc-6afe2cb2dbab" target="_blank"> <img src = "Images/AWSCSA.png" height = "150" width = "150"> </a> &nbsp; &nbsp; &nbsp; &nbsp; 
<a href="https://www.youracclaim.com/badges/d9766deb-479f-47fe-9604-aad72bda10ae/linked_in_profile"> <img src = "Images/tableau.png" height = "150" width = "200"> </a> &nbsp; &nbsp; &nbsp; &nbsp; 
<a href="https://verify.skilljar.com/c/nkgzyihh2cz8"> <img src = "Images/Dataiku.png" height = "130" width = "200"></a>

## Projects
<hr> 
<p>  &#9757; &nbsp; <a href="#Jira_Project">JIRA Project</a> </p>
<p>  &#127872; &nbsp; <a href="#Anomalies">Computer Vision - Detection of anamolies in the manufacturing industry</a>  </p>
<p>  &#9757; &nbsp; <a href="#Oil_gas">Oil and Gas Project - Seismic, las and tiff</a>  </p>
<p> &#127872; &nbsp; <a href="#Image">Image Redaction</a>  </p>
<p> &#9757; &nbsp; <a href="#Speech">Conversion of speech to text and populate in the health care form</a>  </p>
<p> &#127872; &nbsp; <a href="#Plugin">Plugin to Integrate Pega and Dataiku</a> </p>

<h2 id="Jira_Project">JIRA Project</h2>
<hr>

* We all know that Jira is an Issue and Project tracking software which is used in many organizations to keep a track of multiple components for each project.
* This tool generates an abundance of data for each ticket and surplus for each project. This data is originially retained in the JSON format which is a semi-structured data. 
* Through an API call the data is fetched using the Lambda function followed by the step function which can fetch all the data through multiple iterations and then store the raw data in the S3 bucket. 
* Once all the data is fetched in each iteration there comes the problem of structuring them to derive the useful insights from the data extracted. 
* The data is not just in the semi-structured format but, it has so many intra components where each field is having multiple fields within it and then again multiple and so on. 
* In order to reduce the complexity within it, we aimed at only the components which has to be derived for insightful visualizations at the higher level.
* Using pyspark, glue and sql context, the schema was extracted and extracted the components based on the names and the custom id's per each field. 
* Knowing which custom id specifies what data was a really important task as that broke the complex problem into a tiny pieces which can be easily processed and analyzed further. 


<h2 id="Anomalies">Computer Vision - Detection of anamolies</h2> 
<hr>

*	Worked on the computer vision project which is real time detection of anomalies in the manufacturing steel industry using computer vision techniques and algorithms. 
*	Training the model with the image dataset which is retrieved from the NEU database. Annotating the images (XML) and then training the model with both the raw images and annotated datasets.
*	Researching and implementing algorithms like YOLO, SSD using python, tweaking and tuning the parameters like image width, height, anchor boxes, bounding box width, batch size to get the desired predictions and validating the resulting prediction json file with the score and bounding box parameters. Validating the trained modeled and checked with the original annotation of the model to evaluate how well the model worked. 
*	Writing the test cases for all the predictions of the model and then identifying which model through which parameters yielded the better results which is identifying or classifying the defects well in an image given.
* Working with structured data, writing queries to extract, load and transform the data in SQL, querying in Athena. Implemented data manipulation, wrangling and visualizing the data for building useful and significant insights and empowering them using the dashboards of tableau, Power BI and AWS Quick sight. 
*	Worked on automating the ETL pipelines separately based on the domain data and the structure of it. 

<h2 id="Oil_gas">Oil and Gas Project - Seismic, las and tiff</h2>   
<hr>

*	Working on the industry (O&G) specific data standards and formats of data – seismic (.sgy), LAS and tiff files which are the standard formats for the oil and gas industry where the data is stored in the form of waves and traces not just the unstructured and structured like csv, parquet but also the binary structured files. 
*	Extracted the data from the seismic file which is in the binary structured format and then extracted the essential information like ARN, resource extracted (oil or gas), location, country, county and many more and converted into a structured file. 
*	Extracting the valuable information from the data which includes well location, county, resource extracted from the data files (binary, text, pdf, tiff) and converting the unstructured data into a structured data files (csv, parquet) maintaining the compatibility of all versions of the files extracted and integrating on a single format structure. 
*	Ingesting the data into the elastic search and enhancing the capabilities of searching, querying, visualizing the data in the Kibana dev-tools (dev-endpoint) which helps in retrieving the data based on the search request. 
*	To automate the ETL process by building ETL pipelines, CloudWatch events and s3 object notification are triggered periodically as per the DlaaS architecture which involves extracting and decoding the data in the desired format implemented in the AWS platform. 
*	Integrated the DLQ service to the architecture to tract the reason for the failure of extraction which can be the case of uploading the other file extensions.
*	Created visualizations using Kibana, tableau, Power BI, quick sight to elevate the number of resources, location, county, street and integrated the geospatial effects to highlight the states and country along with the resources.


### Markdown

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


