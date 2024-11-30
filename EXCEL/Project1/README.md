# Project 1: Basic Sales Tracker

**Description**:  
In this project, you will create a simple tracker to record daily sales for a small business. The tracker will calculate total sales, average sales, and display the data neatly. You will either use a provided dataset or create your own data.

---

### **Approach 1: Dataset Provided**

1. **Download the Dataset**:
   - Use the provided dataset (`Sales_Tracker_Data.xlsx`).
   - Open the file in Excel.

2. **Understand the Data**:
   - Look at the provided columns: `Date`, `Product Name`, `Quantity`, `Price per Unit`.
   - Familiarize yourself with the values in each row.

3. **Follow the Steps**:
   - Perform the same steps as mentioned previously:
     - Add the `Total Sales` column using the formula `=C2*D2`.
     - Summarize total and average sales.
     - Format the table and apply styling.

---

### **Approach 2: Learners Create Their Own Dataset**

1. **Set Up the Workbook**:
   - Open a new Excel workbook.
   - Rename the first sheet as `Sales Tracker`.

2. **Create the Table**:
   - In row 1, type the column headers:  
     - `Date`, `Product Name`, `Quantity`, `Price per Unit`.

3. **Enter Sample Data**:
   - Add 10 rows of data manually. Example:
     - `Date`: 01-Nov-2024
     - `Product Name`: Notebook
     - `Quantity`: 5
     - `Price per Unit`: 50
   - Enter varied data for each row to reflect different products and quantities.

4. **Perform the Steps**:
   - Follow the same steps as in Approach 1:
     - Calculate `Total Sales`, summarize data, format, and style.

---

### **Learning Objectives**

1. For **Approach 1**:
   - Focus on applying Excel functions and formatting skills.
   - Learn how to work with pre-existing datasets.

2. For **Approach 2**:
   - Understand the importance of proper data structure.
   - Practice creating clean, well-organized datasets from scratch.

---

### **Data Dictionary**

| **Column Name**   | **Description**                                   | **Example**           |
|--------------------|---------------------------------------------------|-----------------------|
| **Date**           | The date when the sales occurred.                | `01-Nov-2024`         |
| **Product Name**   | The name of the product sold.                    | `Notebook`            |
| **Quantity**       | The number of units sold.                        | `5`                   |
| **Price per Unit** | The price of a single unit of the product.        | `50`                  |
| **Total Sales**    | The total sales amount for that product on the given day (`Quantity * Price per Unit`). | `250` |

---

## Steps to Execute

### **Step 1: Choose Your Data Source**

#### **Option 1: Use Provided Data**
1. Download the dataset named `Sales_Tracker_Data.xlsx` from the link or folder provided.
2. Open the file in Excel and look at the data. It contains columns: `Date`, `Product Name`, `Quantity`, and `Price per Unit`.  
   Take a moment to review the values.

#### **Option 2: Create Your Own Data**
1. Open a new Excel workbook and rename the first sheet as `Sales Tracker`.
2. In row 1, type these headers:  
   - `Date`, `Product Name`, `Quantity`, `Price per Unit`.  
3. Enter 10 rows of data manually. Be creative! Use today’s date or any recent dates, add products like “Notebook” or “Pen,” and choose realistic quantities and prices. For example:  
   - Date: 01-Nov-2024  
   - Product Name: Notebook  
   - Quantity: 5  
   - Price per Unit: 50  

---

### **Step 2: Add the Total Sales Column**

1. Add a new column header in cell E1: `Total Sales`.
2. In cell E2, type this formula:  
   `=C2*D2`  
   (This multiplies Quantity and Price per Unit).  
3. Press **Enter**, then drag the formula down for all rows in the `Total Sales` column.

---

### **Step 3: Summarize Your Data**

1. **Total Sales**:  
   - Below your table, type `Total Sales` in column D (e.g., D12).  
   - In the cell next to it (E12), type the formula:  
     `=SUM(E2:E11)`  
   - This will add up all the values in the `Total Sales` column.

2. **Average Sales**:  
   - Below the Total Sales row, type `Average Sales` in column D (e.g., D13).  
   - In the cell next to it (E13), type the formula:  
     `=AVERAGE(E2:E11)`  
   - This will calculate the average sales amount.

---

### **Step 4: Format Your Data**

1. Highlight the `Date` column.  
   - Go to the Home tab, click on `Number Format`, and choose `Short Date`.  
2. Highlight the `Price per Unit` and `Total Sales` columns.  
   - Apply the currency format to display prices properly.

---

### **Step 5: Style Your Table**

1. Highlight the entire table (including headers).  
2. Click `Format as Table` in the Home tab.  
3. Choose any style you like and ensure the `My table has headers` box is checked.  
4. Your table is now styled for easy reading.

---

### **Step 6: Save Your Work**

1. Save your file as `Sales_Tracker.xlsx`.
2. Review your work to ensure it looks clean and professional.

---

### **Step 7: Share Your Work on GitHub**

Congratulations on completing your project! Now, let’s follow an important practice: documenting and sharing your work on GitHub. This will not only help you build a professional portfolio but also develop good habits as a data professional.

---

### **Steps to Create a GitHub Repository**

1. **Sign In to GitHub**  
   - Go to [GitHub](https://github.com) and log in to your account.  
   - If you don’t have an account, sign up for free.  

2. **Create a New Repository**  
   - Click on the green `New` button in the top right corner.  
   - Fill in the repository details:  
     - Repository Name: `Basic_Sales_Tracker`  
     - Description: `A simple sales tracker project using Excel.`  
     - Make it **public** so others can view your work.  
   - Check the box for `Add a README file`.  
   - Click `Create Repository`.

3. **Upload Your Work**  
   - Open your repository and click on `Add File > Upload Files`.  
   - Upload:  
     - Your Excel file (`Sales_Tracker.xlsx`).  
     - Screenshots of your work (e.g., showing the table, summary, and formulas used).  

4. **Update the README File**  
   - Open the `README.md` file in your repository.  
   - Add the following details:  
     ```markdown
     # Basic Sales Tracker  
     This project is part of the Data Science Mastermind program. It demonstrates how to create a sales tracker in Excel with the following features:  
     - Calculating total and average sales.  
     - Formatting and styling data for readability.  
     - Using basic formulas like `SUM`, `AVERAGE`, and `*`.  

     ## Methodology  
     1. Data Setup: Entered sample sales data with columns - Date, Product Name, Quantity, Price per Unit.  
     2. Calculations: Used formulas to calculate Total Sales, Total Amount, and Average Sales.  
     3. Formatting: Applied date and currency formats, and styled the table.  
     4. Summary: Created total and average sales summaries.  

     ## Screenshots  
     ![Sales Tracker Table](<URL to the screenshot>)  
     ![Summary Section](<URL to the screenshot>)  

     ## Tools Used  
     - Microsoft Excel  
     - GitHub for version control.  
     ```  

5. **Commit Your Changes**  
   - After editing, click `Commit changes` to save the updates to your README file.  

---

### **Practice for Every Project**

Repeat this process for every project you complete during the Data Science Mastermind program. By the end, you’ll have a GitHub portfolio showcasing your skills and progress—a valuable asset for job interviews and networking!

---

### **Congratulations Again!**
Your work is now live on GitHub for others to see. Share the repository link with your peers or mentors to get feedback!