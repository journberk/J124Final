# J124Final

## Data Analysis 


## Sources

| **Name & Contact Information**                                      | **Why?**                                                                                                                                                                                                                                                                                                                                                           |
|---------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|UC Berkeley Office of Vice Provost for the Faculty | * Organized and manipulated data and information on spreadsheets on Microsoft Excel and Google Suite applications. * Communicate office updates between faculty through emailing and postings; trusted with classified information. * Updated website information and managed the Drupal website platform; conducted web research; scanned files.|
|World Legal Issues Eduexplora                      | * Taught first-year law school material to a class of 30+ students; mentored and guided students through a mock trial. * Communicated in Spanish, Portuguese, and English, to approach the material with an international perspective. * Collaborated with the professor to best assist class; communicated about student progress and instruction.|
|Berkeley Economic Review                           | * Research and edited articles to be published as qualitative articles as part of the Berkeley Economic Review Journal. * Discussed and researched economic trends and current events at weekly meetings; attended presentations on economics. * Collaborated with organization writers to maintain the style, check grammatical errors, and confirm statistics/graphics used.|

### Question 1 
#### *What percentage of the 2022 incoming law school students are people of color?*

###### The Break Down: 

1. Open the file in google sheets and label a new column "% People of Color FY of the Class Total."
![adding column on google sheets](addedcolumn.png)

2. Type in the formula "=(C2/B2)*100" (cell location may vary depending on sheet edits)
![adding a formula on google sheets](formula.png)

3. Click the cell with the formula and drag the formula down by clicking and holding the bottom right circle of the cell. Drag the formula until the last cell of data.
![dragging a formula on google sheets](dragforumla.png)

###### The Answer: 

### Question 2
#### *Which of the law schools had the highest percentage of incoming students of color in 2022?*

###### The Break Down:

1. Using the data gathered from question 1, we are going to create a pivot table.
2. In the tool bar at the top of the sheet, click "insert" and then select the "pivot table" option from those displayed.  
![Pivot table location in google sheets](PivotTableLocation.png)

3. When prompted to create a pivot table, you must "input the data range." Fill out the data range as follows: '{insert sheet name}'!{insert first cell of data}:{insert last cell of data}.
In our case, it should look like the following: 
![Pivot table range](PivotTableRange.png)

4. Before clicking the button "create" to create the pivot table, make sure to create it on a "new sheet." That sheet will then open with the pivot table. You must add qualifiers under the "pivot table editor" to add data to your pivot table. Under "Rows," add "School list" and under "Values" add "% People of Color FY of the Class Total." Lastly, to display only those with a greater percentage, add a "filter" of the "% People of Color FY of the Class Total" of "greater than 50." This way, only the school with 50% or more will be displayed.
Your pivot table should then look like this: 
![Pivot table after filters](PivotTable.png)

5. Lastly, double-click the top left corner right where the "1" row title and "A" column title meet. Then select "create filter" of the options presented. Then click the funnel or upside-down triangle on the right bottom corner of the title cell "% People of Color FY of the Class Total." You must then click the Z->A option, as it will present the percentages in order of greatest to least.
Your final pivot table will look like this:
 ![Sorting the pivot table](PivotTableSort.png)

###### The Answer: 

### Question 3
#### *What percentage of the 2022 incoming law school students are people of color?*

###### The Break Down:



###### The Answer: 

### Question 4
#### *What percentage of the 2022 incoming law school students are people of color?*

###### The Break Down:

###### The Answer: 



### Question 5
#### *What percentage of the 2022 incoming law school students are people of color?*

###### The Break Down:
