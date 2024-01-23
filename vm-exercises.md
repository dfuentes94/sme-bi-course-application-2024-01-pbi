# Virtual Machine (VM) Exercises

## :information_source: Read this before getting started
- The two exercises should not replicate the exact actions shown in your screencast. The goal of exercises is for learners to apply what was learned in the screencasts to new problems or situations. This is best pedagogical practice for retaining and building skills. For example, this can be done by using another dataset between screencasts and exercises or focusing on a different portion of the dataset.
- Power BI / Tableau specific: We can only run free versions of BI software in our virtual machine exercises. In the case of Power BI, make sure the exercises can run on [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) without any additional paid products. 
- Unsure what the scope of an exercise should be? Here's an [example](https://campus.datacamp.com/courses/introduction-to-power-bi/getting-started-with-power-bi?ex=14) from Introduction to Power BI. The first chapter of most DataCamp courses are free, so take a look at our [BI courses](https://learn.datacamp.com/courses?technologies=Tableau&technologies=Power%20BI) to get a feel for how we assess and guide learners.

## 1st VM Exercise

#### Dataset

- [x] Added dataset used to the `datasets/` folder: `supermarket_sales.xlsx`

#### Files

- [x] **Initial**: Added file to the `exercises/`  folder with the name `ex-1-intial.pbix`, as I'm auditioning for a Power BI course.
- [x] **Solution**: Added file to the `exercises/`  folder with the name `ex-1-sol.pbix`

#### Learning Objective

Know how to use the Filters Pane and the Cross-Highlight options in the Power BI Service

#### Context

Most dashboards provide a general overview. Sometimes we need to do a deep dive to understand the underlying data behind certain category. For example, imagine if you're a Regional Sales Manager and you need to know the sales trend of a specific country, or which are your less profitable products, in order to take better decisions based on that data.

#### Steps to be executed by the student (max 6)

- Open the "SupermarketSales" Dashboard in Power BI Service
- Open the "Overview" page in view "Fit to page"
- Using "Filters on all pages" available, filter the "Customer type" to show only "Member" data
- Filter the "Product line" to show only categories that contain "accessories" in their name
- Select and cross-highlight the "Payment Method" to show only purchases by "Ewallet"

#### Exercise question:

How much was purchased by Members from "Accessories" Product Lines and paid by Ewallet? (rounded to 0 decimals)
- 1. $10,811
- 2. $15,992
- 3. $19,969 (right answer)
- 4. $26,324

#### End goal:

![Alt text](https://github.com/dfuentes94/sme-bi-course-application-2024-01-pbi/blob/master/exercises/ex-1-sol.png)


## 2nd VM Exercise

#### Dataset

- [x] Added dataset used to the `datasets/` folder: `supermarket_sales.xlsx`

#### Files

- [x] **Initial**: Added file to the `exercises/`  folder with the name `ex-2-intial.pbix`, as I'm auditioning for a Power BI course.
- [x] **Solution**: Added file to the `exercises/`  folder with the name `ex-2-sol.pbix`

#### Learning Objective

Understand the different options to Drill Down and Drill Up on a visualization in the Power BI Service

#### Context

Visualizations can be shown at different levels of details. For example: sales over time can be shown by year, month, day or even hour. Showing the data at different levels can help to identify trends like stationary sales by month and also prepare headcount for hours of higher demand in a restaurant.

#### Steps to be executed by the student (max 6)

- Open the "Locations" page in the "SupermarketSales" Dashboard in Power BI Service
- On the "Total Sales by City" visualization, sort city names descending by Total Sales
- Filter all report by city, showing only the city with the highest sales
- On the "Overview" page, filter the Date to show only data from the first half of February 2019 (Feb 01-14th)
- On the "Sales and Average Rating by Day" visualization, drill up to show data by month

#### Exercise question:

How much was the Average Rating for the first half of February 2019 in the city of highest sales overall? (rounded to 2 decimals)
- 1. 7.01
- 2. 7.07 
- 3. 7.13
- 4. 7.30 (right answer)

#### End goal:

![image](https://github.com/dfuentes94/sme-bi-course-application-2024-01-pbi/blob/master/exercises/ex-2-sol.png)
