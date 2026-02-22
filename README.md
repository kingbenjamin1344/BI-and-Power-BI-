<img width="633" height="307" alt="image" src="https://github.com/user-attachments/assets/20a52dda-0cbf-4d91-914b-059bac28da4a" />

PART 1: Launching Power BI & Loading Data
Step 1: Open Power BI Desktop
- Click Start
- Open Microsoft Power BI Desktop
- Wait for the startup screen

<img width="605" height="363" alt="image" src="https://github.com/user-attachments/assets/244ec71c-b3b2-4a43-9585-60926ced750b" />




Step 2: Load the Dataset
1. Click Home Tab
2. Click Get Data
3. Select Text/CSV
4. Browse and select:
Week1_Basic_Sales_Data.csv
5. Click Load

<img width="467" height="506" alt="image" src="https://github.com/user-attachments/assets/b976f170-eae2-436a-96c0-b116d970fdf6" />

**Step 3: Verify Data in Data View**
1. Click the Data View icon (table icon on the left)
2. Check:

- Are all columns visible? **Answer : Yes**
- Is “Date” formatted as Date? **Answer : Yes**
- Is “Sales” formatted as Decimal Number? **Answer : Yes**

If Data Type is Incorrect:
1. Click the column
2. Go to Column Tools
3. Change Data Type accordingly:
○ Date → Date
○ Sales → Decimal Number
○ Product/Category/Region → Text

<p align="center">
  <img src="https://github.com/user-attachments/assets/63210ed7-5c39-45eb-a680-81bbb529088b" width="150" alt="Date" />
  <img src="https://github.com/user-attachments/assets/5d8f6568-5ae6-473c-921b-bd4ed9c1b263" width="150" alt="Sales" />
  <img src="https://github.com/user-attachments/assets/3371dd95-7dbe-40e2-80ea-d54f51bb2040" width="150" alt="Product-Category-Region" />
  <img src="https://github.com/user-attachments/assets/3cfa948a-d518-4b30-bbaa-5d398d0d853a" width="150" alt="" />
  <img src="https://github.com/user-attachments/assets/3483e5b5-c5db-4f80-8ebe-b7b452a3662b" width="150" alt="" />
</p>
























<img width="495" height="212" alt="image" src="https://github.com/user-attachments/assets/89e36c5b-9439-449b-b1f5-ca415f33322f" />



Part 3 Creating Auto-Generated Visuals 
--

**Step 1: Quick Visualization**
1. Drag Sales into canvas
2. Power BI automatically creates a visual

<img width="568" height="407" alt="image" src="https://github.com/user-attachments/assets/c369ba9f-4fd9-453e-9aa2-d89a9dda95ac" />


Question:
- What type of chart was created? **Answer: Stacked Column Chart**
- What does it show? **Answer : Sum of Sales**

**Step 2: Create a Sales by Region Chart**
1. Click blank canvas
2. Select Clustered Column Chart
3. Drag:
○ Region → X-axis
○ Sales → Values

<img width="543" height="423" alt="image" src="https://github.com/user-attachments/assets/9c151ea5-12ed-4fdc-bc34-9f4fa1ebda01" />


Question:
- Which region has highest sales? **Answer : West**

**Step 3: Sales by Category**

1. Insert a Pie Chart
2. Drag:
○ Category → Legend
○ Sales → Values

<img width="566" height="466" alt="image" src="https://github.com/user-attachments/assets/36ed793c-050d-42ee-91b7-609b85b5a9f5" />


Question:

- Which category dominates? **Answer : Electronics**
- Is the distribution balanced? **Answer : No**


**Step 4: Sales Over Time**
1. Insert Line Chart
2. Drag:
○ Date → X-axis
○ Sales → Values

<img width="528" height="419" alt="image" src="https://github.com/user-attachments/assets/91d7233f-a73c-48c0-a8b7-ad78e513fb32" />


Question:
- Is there growth? **Answer : No**
- Any noticeable trend? **Answer : Consistent Decreasing overtime**


PART 4: Basic Data Insight Interpretation
Students must now interpret visuals.
Question:
- Which region contributes most revenue? **Answer : West**
- Which product category performs best?  **Electronics**
- Are sales consistent across dates? **Not consistent**
- What business recommendation can you suggest? **Focus on lowest revenue region**

LABORATORY QUESTIONS
Part A – Technical Questions
1. What are the five columns in the dataset? **Answers: Category, Date, Product, Region, Sales**
2. What data type is assigned to the “Sales” column? **Answer: Whole Number**
3. Which Power BI view allows you to see raw data? **Answer: Table View**
4. What chart type is best for showing trends over time? **Answer : Line Chart**
5. What aggregation is automatically applied to Sales? **Answer: Stacked Column Chart**

Part B – Analytical Questions
6. Which region has the highest total sales?  **Answer: West**
7. Which category has the lowest performance? **North**
8. Are sales increasing, decreasing, or stable? **Answer : The sales are decreasing**
9. If you were a manager, which region would you prioritize? **Answer : I would prioritize in the most profitable region and focus on the category that are most purchased, leverage on strong market**
10. Provide one actionable recommendation based on the data. **Answer: understand the data, determine what the cause of declining sales and take preventive notion for it, and also focus on what category and region has most profitable and those other must put other examine**






