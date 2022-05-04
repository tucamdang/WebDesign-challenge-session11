# Web Design Homework - Web Visualization Dashboard (Latitude)

Link to check output: https://tucamdang.github.io/WebDesign-challenge-ss11/

This project is about design html with 7 pages, building the text, column and images and attached database (convert from csv to html). After that, we edit the colour by applying style.css and bootstrap.
Generally we will have index.html is the homepage and connect index.html to the rest five html.

## Latitude - Latitude Analysis Dashboard with Attitude
In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### By Following the requirements:
The website must consist of 7 pages total, including:
- A landing page containing:

    An explanation of the project.
    Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
    
![1 homepage](https://user-images.githubusercontent.com/99168697/166690585-a10de82c-3a7e-44eb-b2f2-b3995f19e6f0.png)

- Four visualization pages, each with: 
    A descriptive title and heading tag.
    The plot/visualization itself for the selected comparison.
    A paragraph describing the plot and its significance.
![2 max temperature](https://user-images.githubusercontent.com/99168697/166690749-0d9591f2-1f74-451d-a003-719d918cdaf0.png)
![3 humidity](https://user-images.githubusercontent.com/99168697/166690762-103ffbb5-42c6-40ab-b8f6-324ca026dbba.png)
![4 cloudiness](https://user-images.githubusercontent.com/99168697/166690766-b75aa39b-52cc-4de7-a73d-a234b2655346.png)
![5 wind speed](https://user-images.githubusercontent.com/99168697/166690779-8628c318-8f5f-4431-bc2a-50595c797194.png)

- A "Comparisons" page that:
![6 comparison](https://user-images.githubusercontent.com/99168697/166690850-ddaa3fa8-b4b1-497b-8374-88b313c85538.png)

A "Data" page that:
``````
import pandas as pd
df = pd.read_csv('./Resources/cities.csv')
df.to_html('data.html',index=True)
table = df.to_html()
print(table)
``````
We will have this dataset as html
![image](https://user-images.githubusercontent.com/99168697/166691076-3ab570db-020b-4643-a5d0-d823e3f17afc.png)

Export the data and edit the beginning of the code:
![7 data](https://user-images.githubusercontent.com/99168697/166691098-4ea09f85-ac50-4c4d-a909-11f97523308a.png)
