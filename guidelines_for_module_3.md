# Guidelines for Module (3)

The folder “spreadsheets” contains several files with data about diverse international conferences that were important events for the Third World movement in the 1950s and early 1960s. Spreadsheets are divided by event, and each of them contains data about organizations and/or individuals that took part of these events.

Choose a certain number of files and use them to create network data in the form of a nodes file and an edges file. Then, visualize the data on Gephi.

Do do that, you have to ask yourself the following questions:

* How could you analyze these data as network data? What do you exactly want to know, or prove?
* What are the entities that you are interested in studying? What are your nodes? Do you have only one type of node (one-mode network) or more (bi- or tri-partite network)?
* What kind of relations do you seek to analyze: co-attendance, affiliation, common origin, etc.?

## Note on data and data cleaning
Before you start creating your files, please bear in mind that these spreadsheets consist of what is known as *messy data*: columns and categories may not be the same across all files; some rows may be empty; data may be duplicated, etc. 

When you create your files, make sure your data is clean and readable by humans and computers. Follow these five principles:

### 1. One Value Per Cell
Never combine multiple pieces of information into a single box. 

### 2. Use a Single, Clean Header Row
Your dataset should have exactly **one row of column names** at the very top (Row 1).

### 3. Stick to Safe, Machine-Readable Names
Keep column headers short, descriptive, and free of special characters.

### 4. Never Use Formatting to Convey Meaning
In a raw CSV, all visual styling (such as cell background colors, bold text, borders, or highlights) is completely stripped out.

### 5. Handle Missing Data Consistently
Blank cells can be ambiguous. It is often unclear if a blank cell means a value is zero, unknown, or if the person entering data simply skipped it.
Choose **one standard** for missing values and stick to it throughout the entire project: for example, leave the cell completely empty or even better, use something like 'NULL' or 'NA'.

 
