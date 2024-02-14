# PowerBI
PowerBI practice projects

## PowerBI report
The stages involves prepare data, designing models, and creating reports. 
In preparing data phase, I imported data through excel workbook. The data columns includes movie names, release data, duration and so on. In the transformation data stage, I eliminated the rows, filtered the rows in a query.  

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
- Displaying Movie ID, Title, Release Year, and Movie URL.
- Applied conditional formatting to highlight key data points.
- Adjusted column widths for optimal readability.

*Clustered Column Chart:*
- Visual representation illustrating movie count by release year.
- Employed a visually appealing color scheme.
- Included clear labels and legends.

*Line Chart:*
- Complementary line chart providing additional insights.
- Used distinct colors or styles for differentiation.
- Included a legend and axis labels for clarity.

**Section 2: Statistical Visualization**

*Logo Image:*
- Clear, appropriately sized logo strategically placed.
- Aligned with the overall theme of the report.

*Text Box:*
- Concise and relevant information presented in a readable font.
- Maintained a consistent text style.

**General Aesthetics:**
- Consistent color scheme throughout the report.
- Effective use of whitespace for improved readability.
- Proper alignment of visual elements for a professional appearance.

**Interactivity:**
- Implemented interactive features such as tooltips or filters for enhanced user engagement.
- Ensured the report is user-friendly and easy to navigate.

**Proofreading:**
- Conducted a thorough review to eliminate any typos or grammatical errors.


<img width="1175" alt="截屏2024-02-14 21 16 05" src="https://github.com/Felicia1993/PowerBI/assets/22839284/52b86d37-e25e-44eb-bba2-3c1e98d6bf76">


Sales Analysis

<img width="1050" alt="截屏2024-02-14 21 15 23" src="https://github.com/Felicia1993/PowerBI/assets/22839284/d0a324f6-5c1c-49ca-af5d-1feaf9398aba">


