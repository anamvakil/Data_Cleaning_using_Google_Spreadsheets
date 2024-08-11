# Data Cleaning using Google Spreadsheets

In this project, I have used two datasets named as International Logistics Association Memberships and Cosmetics.Inc to perform data cleaning process using some of these tools in google spreadsheets listed below:

### ***Conditional Formatting***

Conditional formatting is a spreadsheet tool that changes how cells appear when values meet specific conditions. Likewise, it can let you know when a cell does not meet the conditions you've set. Visual cues like this are very useful for data analysts, especially when we're working on a large spreadsheet with lots of data. Making certain data points stand out makes the information easier to understand and analyze. One of the ways we can use conditional formatting is to remove the blank cells from the dataset. 

Considering the below-mentioned example, we will select all the columns except column F and column H. 

![image](https://github.com/user-attachments/assets/cb0d9398-d125-4321-b427-5e80cf368101)

Performing conditional formatting to highlight the cells with blank values.

![image](https://github.com/user-attachments/assets/e683a514-e0f4-45ae-91ce-9a30e6e6c2cf)

As seen in the image below we get blank cells highlighted in pink.

![image](https://github.com/user-attachments/assets/1785548b-2c6a-4452-9785-1a4279dac631)

### ***Remove Duplicates***

A tool that automatically searches for and eliminates duplicate entries from a spreadsheet and it can be done in these simple steps.

![image](https://github.com/user-attachments/assets/78329053-2456-4e9b-8d05-2e91cabeb2b1)

To use this tool we need to select the option from the drop-down menu. Since we want to remove the duplicate values from the entire dataset we will select all and act.

![image](https://github.com/user-attachments/assets/4f3febeb-27aa-4c06-8e46-3be9d041bf80)

This is how we remove the duplicate values in 3 easy steps.

![image](https://github.com/user-attachments/assets/c8def101-5a69-472c-85ea-0d0893dd454e)

### ***Formatting Dates***

Coming across datasets with dates in different formats can be challenging. To fix this we can use Format Dates to make the data look more consistent and easy to manipulate.

 ![image](https://github.com/user-attachments/assets/3a2ad673-a84c-4f20-b9a9-eb3bed082b7c)

From the menu, select Format, then Number, then Date.

 ![4](https://github.com/user-attachments/assets/16fa0525-0515-4728-b928-0283441118bf)

Now, all of our dates have a consistent format.

 ![image](https://github.com/user-attachments/assets/518108ec-700e-41f7-9d6e-aa0f8fe46913)

### ***Using Split Function***

Split is useful when we have more than one data in a cell. When we have a string and a substring together in a cell and we want to split them into two different cells. For eg: when we have a person's first name and last name together in a cell and we want each of them in their column.
Let's go ahead and explore this tool further.

![image](https://github.com/user-attachments/assets/9c2ef50d-b109-46b1-bd31-8640ffe58d44)

As we can see in column L the certifications are separated by commas but we want to split these certifications into two different columns.

![5](https://github.com/user-attachments/assets/29ce8dbe-3e1b-4213-ba76-264693912bb6)

![image](https://github.com/user-attachments/assets/494624e0-e3ff-4737-a5f8-bd8f97f96fef)

This spreadsheet already knew that the comma was the delimiter but sometimes we need to specify what the delimiter should be and for that, we need to select the parameter from the drop-down list. 

There are times when copying and pasting the data from one sheet to another the numbers get stored as text or if the formatting is done. To explain this further let's go ahead and see another dataset named as Cosmetics-Inc.

![6](https://github.com/user-attachments/assets/1d1fed24-f76b-44f8-9d0e-dd1663990cd1)

As we can see there is an error in this spreadsheet in column F. The reason behind it is that the spreadsheet is not able to calculate the total as the number 707 in column E seems to be a text and cannot be changed to a number. In such a scenario we select the column we need to correct the error in and perform the following step.

![image](https://github.com/user-attachments/assets/df0baf8e-b90a-49d6-8fa8-a5d53b9cb591)

![image](https://github.com/user-attachments/assets/7520eb50-40fe-4295-a04c-d2df0629c1f7)

These were the few tools that can be used in spreadsheets for data cleaning. However, Google spreadsheets also offer various functions that can be used in data cleaning which I have explained in my next project. 
