Project: Analyzing the Impact of Car Features on Price and Profitability

Raw Dataset Link: 
Project 7 Dataset.xlsx

Problem Statement:

The automotive industry has been rapidly evolving over the past few decades, with a growing focus on fuel efficiency, environmental sustainability, and technological innovation. With increasing competition among manufacturers and a changing consumer landscape, it has become more important than ever to understand the factors that drive consumer demand for cars.

In recent years, there has been a growing trend towards electric and hybrid vehicles and increased interest in alternative fuel sources such as hydrogen and natural gas. At the same time, traditional gasoline-powered cars remain dominant in the market, with varying fuel types and grades available to consumers.

For the given dataset, as a Data Analyst, the client has asked How can a car manufacturer optimize pricing and product development decisions to maximize profitability while meeting consumer demand?

This problem could be approached by analyzing the relationship between a car's features, market category, and pricing, and identifying which features and categories are most popular among consumers and most profitable for the manufacturer. By using data analysis techniques such as regression analysis and market segmentation, the manufacturer could develop a pricing strategy that balances consumer demand with profitability, and identify which product features to focus on in future product development efforts. This could help the manufacturer improve its competitiveness in the market and increase its profitability over time.
Dataset Description:
The dataset contains information on various car models and their specifications, and is titled "Car Features and MSRP". It was collected and made available on Kaggle by Cooper Union, a private college located in New York City.

Here is a brief overview of the dataset:

Number of observations: 11,159
Number of variables: 16
File type: CSV (Comma Separated Values)

The variables in the dataset are:

Make: the make or brand of the car
Model: the specific model of the car
Year: the year the car was released
Engine Fuel Type: the type of fuel used by the car (gasoline, diesel, etc.)
Engine HP: the horsepower of the car's engine
Engine Cylinders: the number of cylinders in the car's engine
Transmission Type: the type of transmission (automatic or manual)
Driven_Wheels: the type of wheels driven by the car (front, rear, all)
Number of Doors: the number of doors the car has
Market Category: the market category the car belongs to (Luxury, Performance, etc.)
Vehicle Size: the size of the car 
Vehicle Style: the style of the car (Sedan, Coupe, etc.)
Highway MPG: the estimated miles per gallon the car gets on the highway
City MPG: the estimated miles per gallon the car gets in the city
Popularity: a ranking of the popularity of the car (based on the number of times it has been viewed on Edmunds.com)
MSRP: the manufacturer's suggested retail price of the car

This dataset could be useful for a variety of data analysis tasks, such as:

Exploring trends in car features and pricing over time
Comparing the fuel efficiency of different types of cars
Investigating the relationship between a car's features and its popularity
Predicting the price of a car based on its features and market category

However, it's important to note that the dataset was last updated in 2017, so it may not reflect current trends or prices in the automotive industry.
Understanding the Dataset:

The dataset contains information on over 11,000 car models and their specifications, including details on the car's make, model, year, fuel type, engine power, transmission, wheels, number of doors, market category, size, style, estimated miles per gallon, popularity, and manufacturer's suggested retail price (MSRP).

A data analyst could use this dataset to gain insights into various aspects of the automotive industry, such as:

Analyzing trends in car features and pricing over time: By examining the variables in the dataset, a data analyst could identify how car features and prices have changed over time, which could help manufacturers make informed decisions about product development and pricing.

Comparing the fuel efficiency of different types of cars: By looking at the MPG variables in the dataset, a data analyst could compare the fuel efficiency of different types of cars and identify which types are the most efficient. This could help consumers make informed decisions about which car to purchase.

Investigating the relationship between a car's features and its popularity: By examining the popularity variable in the dataset, a data analyst could identify which features are most popular among consumers and how they affect a car's popularity. This could help manufacturers make informed decisions about product development and marketing.

Predicting the price of a car based on its features and market category: By using the various features and market category variables in the dataset, a data analyst could develop a model to predict the price of a car. This could help manufacturers and consumers understand how different features affect the price of a car and make informed decisions about pricing and purchasing.

Overall, this dataset could be a valuable resource for data analysts interested in exploring various aspects of the automotive industry and could provide insights that could inform decisions related to product development, marketing, and pricing.

Business and Data Analytics Skills:

The given tasks below based on the business problem would require advanced Excel skills and knowledge of data analysis techniques such as regression analysis, pivot tables, sensitivity analysis, optimization, and time series analysis. 

However, by answering these questions and building an interactive dashboard, a data analyst could provide valuable insights to a car manufacturer and help them optimize their pricing and product development decisions to maximize profitability while meeting consumer demand.

Tasks: Analysis 
Before diving into the analysis of the given dataset, it is important to perform thorough data cleaning to ensure accurate and reliable results. You need to build an interactive dashboard in Excel from the tasks given below:

Insight Required: How does the popularity of a car model vary across different market categories?
Task 1.A: Create a pivot table that shows the number of car models in each market category and their corresponding popularity scores.
Task 1.B: Create a combo chart that visualizes the relationship between market category and popularity.

Insight Required: What is the relationship between a car's engine power and its price?
Task 2:  Create a scatter chart that plots engine power on the x-axis and price on the y-axis. Add a trendline to the chart to visualize the relationship between these variables.

Insight Required: Which car features are most important in determining a car's price? 
Task 3: Use regression analysis to identify the variables that have the strongest relationship with a car's price. Then create a bar chart that shows the coefficient values for each variable to visualize their relative importance.

Insight Required: How does the average price of a car vary across different manufacturers?
Task 4.A: Create a pivot table that shows the average price of cars for each manufacturer. 
Task 4.B: Create a bar chart or a horizontal stacked bar chart that visualizes the relationship between manufacturer and average price.

Insight Required: What is the relationship between fuel efficiency and the number of cylinders in a car's engine?
Task 5.A: Create a scatter plot with the number of cylinders on the x-axis and highway MPG on the y-axis. Then create a trendline on the scatter plot to visually estimate the slope of the relationship and assess its significance.
Task 5.B: Calculate the correlation coefficient between the number of cylinders and highway MPG to quantify the strength and direction of the relationship.
Building the Dashboard:

Now for the Next portion of the Project, you need to create the Interactive Dashboard. 
Use filters and slicers to make the chart interactive. The client has requested these questions given below:

Task 1: How does the distribution of car prices vary by brand and body style?
Hints: Stacked column chart to show the distribution of car prices by brand and body style. Use filters and slicers to make the chart interactive. Calculate the total MSRP for each brand and body style using SUMIF or Pivot Tables.

 
Task 2: Which car brands have the highest and lowest average MSRPs, and how does this vary by body style?
Hints: Clustered column chart to compare the average MSRPs across different car brands and body styles. Calculate the average MSRP for each brand and body style using AVERAGEIF or Pivot Tables.


Task 3: How do the different feature such as transmission type affect the MSRP, and how does this vary by body style?
Hints: Scatter plot chart to visualize the relationship between MSRP and transmission type, with different symbols for each body style. Calculate the average MSRP for each combination of transmission type and body style using AVERAGEIFS or Pivot Tables.

Task 4: How does the fuel efficiency of cars vary across different body styles and model years? 
Hints: Line chart to show the trend of fuel efficiency (MPG) over time for each body style. Calculate the average MPG for each combination of body style and model year using AVERAGEIFS or Pivot Tables.

Task 5: How does the car's horsepower, MPG, and price vary across different Brands?
Hints: Bubble chart to visualize the relationship between horsepower, MPG, and price across different car brands. Assign different colors to each brand and label the bubbles with the car model name. Calculate the average horsepower, MPG, and MSRP for each car brand using AVERAGEIFS or Pivot Tables.
How to do this Project? 

Download the dataset: You are supposed to download the dataset and perform the analysis using Excel for Dashboard Building.

Perform Analysis: Specific Tool Requirement is already mentioned above. Kindly follow them strictly. 

Submit a Report: Make a report (PDF/PPT) to be presented to the Client and the Stakeholders. 

Data Analytics Report: Format/Structure

The report should/can contain the following details:

Project Description:
Give a brief about your project description. Points to Remember:

Overview of the project and its purpose.
Business problem or question that the project aims to address.
Description of the data sources used in the project.
Description of the data cleaning and preprocessing steps performed on the data.
Any assumptions made during the project.

Approach:

Description of the analytical methods used in the project, such as descriptive statistics, visualization, machine learning, or optimization.
Explanation of the reasoning behind the choice of analytical methods.
Description of the modeling techniques used, if applicable.
Any challenges or limitations encountered during the project.

Tech-Stack Used:

Description of the tools, languages, and software used in the project, such as Excel.
Explanation of the reasoning behind the choice of tech stack.
Description of any additional libraries or packages used in the project.

Insight:

Key insights or findings discovered during the project.
Explanation of how the insights relate to the business problem or question.
Any recommendations or conclusions are drawn from the insights.

Result:

Visualization of the results obtained from the analysis, such as tables, graphs, or dashboards.
Discussion of the results and their implications.
Any limitations or uncertainties regarding the results.
Possible future directions for the project or additional analysis.

It is important to note that the specific details included in each section may vary depending on the project and its objectives. The report should also be written in a clear and concise manner, with technical jargon and terminology explained for a non-technical audience.

Submission: 

Create a Folder in your Google Drive and name it: Analyzing the Impact of Car Features on Price and Profitability. In this folder, create another two folders and name it: Presentation Files and Analysis Files.

Upload the PDF/PPT and Video Presentation in the Presentation Files. 
Upload the Excel Files in the Analysis Files.

Note: Kindly make sure that you hyperlink the link of the Analysis Folder in your report. If you want to know the steps, read below:

Step 1: Open your Google Drive account and locate the Analysis Folder you want to link to in your presentation. Right-click on the file and select "Get link." Make sure that the sharing settings for the file are set to "Anyone with the link can view" or "Anyone with the link can edit," depending on your preference.

Step 2: In PowerPoint, navigate to the slide where you want to insert the hyperlink. Highlight the text or object that you want to turn into a hyperlink.

Step 3: Click the "Insert" tab in the top menu bar, then select "Hyperlink."

Step 4: In the "Insert Hyperlink" dialog box, paste the Google Drive link you copied in step 1 into the "Address" field.

Step 5: Click "OK" to insert the hyperlink. You should now see that the text or object you selected in step 2 has been turned into a hyperlink.

Step 6: To test the hyperlink, go into presentation mode by pressing F5 or clicking the "Slide Show" tab and selecting "From Beginning." Click on the hyperlink you just created to make sure it takes you to the correct Google Drive file.

Hyperlink any file in PDF: 

Upload the required files on your google drive and then follow the steps below:

Step 1: Open your Google Drive and find the file you want to link to. Right-click on the file and select "Get link".

Step 2: In the "Get link" window, make sure that the link-sharing options are set to "Anyone with the link can view". Copy the link by clicking on the "Copy link" button.

Step 3: Open the Word document and highlight the text you want to use as the hyperlink. Right-click on the highlighted text and select "Hyperlink".

Step 4: In the "Insert Hyperlink" window, select "Existing File or Web Page" from the list of options on the left. Paste the copied link into the "Address" field.

Step 5: Click on "OK" to create the hyperlink. Test the hyperlink by clicking on the linked text to open the Google Drive file.

Guidelines for the Video Presentation:

The candidate has to explain how he/she solved this project and present the excel sheet and the ppt. 
It is mandatory to use a webcam so that we know that it is the candidate who is explaining the project.
How to Submit Your Project:

Step 1: Do your project in PPT/PDF. It’s your choice. For PDF, write your project in MS Word, then save the file in PDF format. You will find the option in the ‘Save As’ Box.

Step 2: Now, upload the file i.e., PPT/PDF on your google drive. It would be wise to create a Single Folder and Name it “Trainity Assignments”. Inside that folder, create another Folder name “<Project Name>”. Upload your assignment there.

Step 3: Right Click on the File, and select ‘Get Link’ under ‘Share’. A Dialog Box will Pop up. Inside the Box, Under General Access, Change ‘Restricted’ to ‘Anyone with the Link’. No need to change anything else.

Step 4: Click on ‘Copy Link’. Now paste the link in the Drive Link box. It is mandatory to submit the video presentation. Fill in all the necessary boxes given on the submission page.

Judgment Criteria:

Data Analytics: Your answers must contain relevant points related to the data analysis and should have real-world case scenarios.

Advanced Excel Understanding: Your spreadsheet must have clear explanations of the processes used, eg, pivot tables, functions used, formulas explained, etc.

Statistics Understanding: Your answers must contain graphs and stats references.

Case study completion: All the questions present must be answered completely having correct answers.

Insights: You need to use your own imagination to answer the case study while improvising it as well.

Plagiarism: The project submitted should not be copied from the internet or anywhere else, it should be your own work. 

