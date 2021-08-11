# J124 Final Project Process
 *Lucas Yen*


## Steps to recreate my data analysis:
1. Download dataset, copy and paste values into Google Sheets
!['Downloading Dataset','This is a picture of me downloading the dataset from Kaggle'](https://user-images.githubusercontent.com/87663499/128904904-c1ec3468-65ae-417c-a34f-1d0ed25329bf.png)

2. Come up with reporting questions to answer:
   * Which has a greater impact on starting median salary: school type or region?
   * Which school types have the largest percentage increase from starting median salary to mid-career median salary?
   * Which school types have the largest disparity between their mid-career 75th percentile salary earners and their mid-career 25th percentile salary earners?
   
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

Come to a conclusion:



