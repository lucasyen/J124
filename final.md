# J124 Final Project Process
 *Lucas Yen*


## Steps to recreate my data analysis:
1. Download dataset, copy and paste values into Google Sheets
!['Downloading Dataset','This is a picture of me downloading the dataset from Kaggle'](https://user-images.githubusercontent.com/87663499/128904904-c1ec3468-65ae-417c-a34f-1d0ed25329bf.png)

2. Come up with reporting questions to answer:
   * Which has a greater impact on starting median salary: school type or region?
   * Which school types have the largest percentage increase from starting median salary to mid-career median salary?
   * Which school types have the largest disparity between their mid-career 75th percentile salary earners and their mid-career 25th percentile salary earners?
   * Which degrees have the largest disparity between their mid-career 90th percentile salary earners and their mid-career 10th percentile salary earners?
   * Which region has the largest percent increase from starting median salary to mid-career median salary?
   
3. Answer your questions using data analysis skills!

#### "Which has a greater impact on starting median salary: school type or region?"<br>
Use VLOOKUP to add region into the salaries by college sheet.
!['Combining Datasets','This is a picture of me adding a region column into the salaries by college sheet using VLOOKUP'](https://user-images.githubusercontent.com/87663499/128911059-e2c9ecd9-e948-4a49-a6d8-cdabef8659f3.png)

Create a pivot table that has columns with different regions and rows with different school types. Then, insert average starting median salary as the value and compare.
!['College Type vs. Region Pivot Table','This is a picture of a table that compares average starting median salaries when sorted by college type and region.'](https://user-images.githubusercontent.com/87663499/129066297-cfe7bf3c-605c-4fa0-a4f3-0e98aa94ebe4.png)

Come to a conclusion:<br>
Though region clearly impacts sarting median salary, there seems to a bigger disparity when comparing starting median salaries between college types. For example, even though many of the Ivy League schools are not all that different from liberal arts schools, their students enjoy a much higher starting median salary when compared to Northeastern liberal arts students.

#### "Which school types have the largest percentage increase from starting median salary to mid-career median salary?"
Add column into the salaries by college sheet. This column should show the percentage increase from starting median salary to mid-career median salary.
!['Percent Increase from Starting to Mid-Career Median Salary','This is a picture that shows me adding a column that calculates the percent increase from starting median salary to mid-career median salary for each college'](https://user-images.githubusercontent.com/87663499/129069954-97a2f2a5-97ee-4f70-885f-5f9d422d981c.png)

Create a pivot table with college type as the rows and average of percentage increase from starting to mid-career median salary as the values.<br>
!['Percentage Increase from Starting to Mid-Career Median Salary Pivot Table', 'This is a picture of a pivot table that shows the average percentage increase from starting to mid-career median salary for different college types'](https://user-images.githubusercontent.com/87663499/129070986-2d83196a-f5c7-4426-8a6f-898c53c2df9a.png)

Come to a conclusion:<br>
On average, graduates of Ivy League schools experience the largest growth in terms of percentage increase between starting median salary and mid-career median salary. By contrast, engineering graduates experience the smallest growth; this may be a byproduct of engineers' high starting median salary.

#### "Which school types have the largest disparity between their mid-career 75th percentile salary earners and their mid-career 25th percentile salary earners?"
Add a column to the salaries by colleges sheet that calculates the difference between mid-career 75th percentile salary and mid-career 25th percentile for each college.<br>
!['Mid-Career 75th Percentile Salary vs. Mid-Career 25th Percentile Salary','This picture shows me adding a column that calculates the difference between mid-career 75th percentile and mmid-career 25th percentile salary for each college'](https://user-images.githubusercontent.com/87663499/129075329-5d38896b-278c-4969-b2c5-9bd82c9a91b0.png)

Create a pivot table with school type as the rows and the average of the new column as the values.
!['Mid-Career 75th Percentile Salary vs. Mid-Career 25th Percentile Salary Pivot Table', 'This is a picture of a pivot table that shows the average difference for mid-career 75th percentile salary vs. mid-career 25th percentile by college type'](https://user-images.githubusercontent.com/87663499/129075851-148f774d-f465-48a2-b438-c656f982cf62.png)

Come to a conclusion:<br>
After analyzing the data, it becomes clear that Ivy League schools have the largest difference between the mid-career 75th percentile salary and mid-career 25th percentile salary, making their interquartile the largest of the different school type categories. Conversely, state schools had the smallest interquartile range. This shows that Ivy Legaue graduates had a larger overall range of earning within its middle 50% while state school graduates had the smallest range within its middle 50%.

#### "Which degrees have the largest disparity between their mid-career 90th percentile salary earners and their mid-career 10th percentile salary earners?"
Add a column to the degrees that pay back sheet that calculates the difference between mid-career 90th percentile salary and mid-career 10th percentile salary for each degree. Sort Z to A for the largest disparity.
!['Mid-Career 90th Percentile Salary vs. Mid-Career 10th Percentile Salary','This is a picture that shows the 90th percentile salary vs. 10th percentile salary for different degrees at the mid-career stage'](https://user-images.githubusercontent.com/87663499/129090218-5e620569-34b6-4f14-879f-798a40847d22.png)

Come to a conclusion:<br>
Economics is the degree with the largest difference between top earners and bottom earners. Finance, math, marketing, and philosophy round out the rest of the top five for largest difference between top earners and bottom earners. On the other hand, nursing, physician assistant, nutrition, Spanish, and health care administration degrees form the top five for the smallest difference between top earners and bottom earners.

#### "Which region has the largest percent increase from starting median salary to mid-career median salary?"
Add a column to the salaries by region sheet that calculates the percent increase from starting median salary to mid-career median salary.
!['Percent Increase from Starting to Mid-Career Median Salary','This is a picture of a column that calculates the percent increase of each college from starting to mid-career median salary'](https://user-images.githubusercontent.com/87663499/129135552-1a0439ac-ec2a-4b10-8bdc-bde8bf8986cf.png)

Create a pivot table with region as the rows and the average of the new column as the values.
!['Average Percent Increase from Starting to Mid-Career Median Salary by Region', 'This is a picture of a pivot table that shows the average percent increase from starting to mid-career median salary by region'](https://user-images.githubusercontent.com/87663499/129135852-62122e54-ae08-409a-80ed-35ef9743af16.png)

Come to a conclusion:<br>
On average, Northeastern college graduates experience the largest percent increase from starting median salary to mid-career median salary. The other end of the spectrum, the lowest percent increase from starting median salary to mid-career median salary, is the West when not including California.

## Story Pitch
Short Summary:<br>
After conducting this data analysis, I could write a story that advises students to consider future earning potential when deciding on a college. Using information from the purely dispassionate earning point of view, the data does not consider personal factors like attachment to a hometown or passion for a particular field after all, and the understanding that students must consider more than future earnings, I could write about the most logical college routes in terms of earning potential. The article could neither be as simple as telling readers to earn an engineering degree from California since that route provides the highest average starting median salary; nor could it be as simple as telling readers to earn an Ivy League degree since those graduates, on average, experience the most growth from starting to median salary. Instead, this article would provide a comprehensive list of pathways for prospecting college students to maximize their earning potential based on various personal situations like preferred region and proessional field or degree.

Potential Interviews:<br>
Jaison Abel - Assistant Vice President and Head of the Regional Analysis Function at the Federal Reserve Bank of New York; jaison.abel@ny.frb.org<br>
As the co-author of a paper titled "Do the Benefits of College Still Outweigh the Costs?" and by virtue of his professional position at the Federal Reserve Bank of New York, Jaison Abel seems like he would be an ideal choice for this kind of article as he can expertly explain the economics of a college degree.<br>

Richard Deitz - Assistant Vice President and Senior Economist for the Federal Reserve Bank of New York, has been with the Federal Reserve since 1998; richard.deitz@ny.frb.org<br>
Richard Deitz is the co-author of the "Do the Benefits of College Still Outweight the Costs?" paper and would also be an ideal interview to explain the economics of the modern college degree.

Martin Van Der Werf - Associate Director of Editorial and Postsecondary Policy for the Center on Education and the Workforce which is part of Georgetown University; @M_Vanderwerf on Twitter<br>
Martin Van Der Werf is the co-author of "Buyer Beware: FIRST-YEAR EARNINGS AND DEBT FOR 37,000 COLLEGE MAJORS AT 4,400 INSTITUTIONS", a 2020 report on the value of different college degrees at many of the major United States universities.

Additional Reports:<br>
I would use the 2020 report called "Buyer Beware: First-Year Earnings and Debt for 37,000 College Majors at 4,400 Institutions" since it provides some of the most current data on exactly the topic that I would be reporting on.<br>
Link: https://1gyhoq479ufd3yna29x7ubjn-wpengine.netdna-ssl.com/wp-content/uploads/CEW-Buyer-Beware.pdf

I would use this 2019 research paper called "The Relationship Between Work During College and Post College Earnings" because I think the wrinkle that this paper could add to the overall reporting could be a really interesting angle to add to the piece.<br>
Link: https://www.frontiersin.org/articles/10.3389/fsoc.2019.00078/full

## Data Visualization
!['Average of Starting Median Salary for College Type vs. Region Bar Chart','This is a picture of a bar chart that shows the average starting median salary for different school types and for different regions'](https://user-images.githubusercontent.com/87663499/129158228-b86170d0-518f-4d9f-b413-69fd82fa154e.png)
Link to the chart: https://datawrapper.dwcdn.net/DFkbY/1/

## CSV Files used for this project:<br>
[Degrees that pay back dataset](https://github.com/lucasyen/J124/files/6973722/degrees-that-pay-back.csv)<br>
[Salaries by college type dataset](https://github.com/lucasyen/J124/files/6973723/salaries-by-college-type.csv)<br>
[Salaries by region dataset](https://github.com/lucasyen/J124/files/6973724/salaries-by-region.csv)




