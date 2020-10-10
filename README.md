## Tejasri Surapaneni

## Certifications 

<a href="https://www.youracclaim.com/badges/ea4effc3-943c-4f0f-b8dc-6afe2cb2dbab"> <img src = "Images/AWSCSA.png" height = "150" width = "150"> </a> &nbsp; &nbsp; &nbsp; &nbsp; 
<a href="https://www.youracclaim.com/badges/d9766deb-479f-47fe-9604-aad72bda10ae/linked_in_profile"> <img src = "Images/tableau.png" height = "150" width = "200"> </a> &nbsp; &nbsp; &nbsp; &nbsp; 
<a href="https://verify.skilljar.com/c/nkgzyihh2cz8"> <img src = "Images/Dataiku.png" height = "130" width = "200"></a>


### Projects Worked on 

## Jira Project 

* We all know that Jira is an Issue and Project tracking software which is used in many organizations to keep a track of multiple components for each project.
* This tool generates an abundance of data for each ticket and surplus for each project. This data is originially retained in the JSON format which is a semi-structured data. 
* Through an API call the data is fetched using the Lambda function followed by the step function which can fetch all the data through multiple iterations and then store the raw data in the S3 bucket. 
* Once all the data is fetched in each iteration there comes the problem of structuring them to derive the useful insights from the data extracted. 
* The data is not just in the semi-structured format but, it has so many intra components where each field is having multiple fields within it and then again multiple and so on. 
* In order to reduce the complexity within it, we aimed at only the components which has to be derived for insightful visualizations at the higher level.
* Using pyspark, glue and sql context, the schema was extracted and extracted the components based on the names and the custom id's per each field. 
* Knowing which custom id specifies what data was a really important task as that broke the complex problem into a tiny pieces which can be easily processed and analyzed further. 
* 


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

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

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Tejasri-Surapaneni/Tejasri-Portfolio/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
