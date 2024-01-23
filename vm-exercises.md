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

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Open the "SupermarketSales" Dashboard in Power BI Service.
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

- [ ] Add datasets used to the `datasets/` folder

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-1-initial.yxmd`, depending if you are auditioning for a Tableau/Power BI/Alteryx course.
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix` or `ex-1-sol.yxmd`

#### Learning Objective

*One measurable learning objective that this exercise assesses*

#### Context

*3 - 4 sentence description of why it’s important to learn how to do this task (linking back to the learning objective). Explain how this would be used in a real-life situation. Why is it useful, what problem does it solve?*

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Step 1
- Step 2
- Step 3
- ...

#### Exercise question:
*This is a question presented to learners to check if the steps above were properly completed. It can be a multiple choice question or a question with a 1-3 word answer. It is often not possible to check if all the steps are completed, in this case; the priority is to check that the learner meets the learning objective.*

#### End goal:

*Add an image of the final visualization here.*

![image](https://github.com/dfuentes94/sme-bi-course-application-2024-01-pbi/assets/84543411/86bea731-f5b8-45ca-9d72-a504ad67d94d)
