# PowerBI
PowerBI practice projects

## PowerBI report
The stages involves prepare data, designing models, and creating reports. 
In preparing data phase, I imported data through excel workbook. The data columns includes movie names, release data, duration and so on. In the transformation data stage, I eliminated the rows, filtered the rows in a query.  
### preprocessing

### Designing models
#### Queries
Queries are comprised of data sources and a sequence of transformation steps
#### Model tables
Model tables are loaded from queries and enhanced with relationships, property settings, and calculations
relationships

properties

calculations

The relationship among data.       
<img width="795" alt="截屏2024-02-14 21 47 57" src="https://github.com/Felicia1993/PowerBI/assets/22839284/cfa9cc36-cf66-4b82-8d91-7fbbad9b73b1">      
In the image, the Connections table has a movieID column that’s related to the Genre table, which also has a movieID column. The two tables have a One to One (1:1) relationship. An arrow in the middle of the line shows the direction of the filter context flow. 

I have created a calculated column, "Movie URL," using the formula "https://www.imdb.com/title/" & [Movie ID]. This generates a URL based on the movie title.       

In addition, I've implemented a measure to count movies by release year. The visual representation involves creating a table, duplicating and modifying a table, converting a table into a clustered column chart, and generating a line chart.       

For statistical visualization, I've incorporated a logo image, added a text box, and included a rectangle for enhanced aesthetics.      

The final report is outlined below:      

**Movie Analytics Report**

**Section 1: Movie Count by Release Year**

*Table Visualization:*
- Displaying Movie ID, Title, Release Year, Movie URL and other columns.

*Clustered Column Chart:*
- Visual representation illustrating movie count by release year.

*Line Chart:*
- Complementary line chart providing additional insights.

**Section 2: Statistical Visualization**

*Logo Image:*
- Aligned with the overall theme of the report.

*Text Box:*
- Concise and relevant information presented in a readable font.


<img width="1175" alt="截屏2024-02-14 21 16 05" src="https://github.com/Felicia1993/PowerBI/assets/22839284/52b86d37-e25e-44eb-bba2-3c1e98d6bf76">


Sales Analysis Dashboard   
This is the exercise Create a power BI dashboard on Microsoft Training.
I created a Sales Analysis Dashboard based on the sales analysis report. In the Overview page, set the Year slicer to FY2020. Then I hover the cursor over the Sales and Profit Margin by Month (column/line) visual, and select the pushpin to create a dashboard and pin a visual. 
![9-insights-card-ss](https://github.com/Felicia1993/PowerBI/assets/22839284/b2ed75ab-dbd6-4331-9fce-cc7864a18510)

Pin a live report page to a dashboard.

Use Q&A to create dashboard tiles

<img width="1050" alt="截屏2024-02-14 21 15 23" src="https://github.com/Felicia1993/PowerBI/assets/22839284/d0a324f6-5c1c-49ca-af5d-1feaf9398aba">


