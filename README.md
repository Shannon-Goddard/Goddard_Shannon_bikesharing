![Header](/pics/header.png)

#### Table of Contents

[Project Overview](#project-overview)  
[Resources](#resources)  
[Objectives](#objectives)  
[Summary](#summary)   
[Challenge Overview](#challenge-overview)  
[Challenge Objectives](#challenge-objectives)
[Challenge Summary](#challenge-summary)  
[Limitations](#limitations)

## Project Overview
In this module, we worked with data visualization software called Tableau to present a business proposal for a bike-sharing company. First, we learned how to import, style, and portray data accurately. Then, we created worksheets, dashboards, and stories to visualize key data from a New York Citi Bike dataset.

## Resources  
For this project, we used data from the Citi Bike program in New York City. The data we downloaded was contained in a flat file, a CSV. 
We went to the [Citi Bike System Data](https://www.citibikenyc.com/system-data) page. This link took us to an index of trip data, [Download Citi Bike trip history data](https://s3.amazonaws.com/tripdata/index.html). We scrolled down the list to **201908-citibike-tripdata.csv.zip**, then downloaded and saved on our computer.  

- **Data Source:** 201908-citibike-tripdata.csv, [Des Moines Census Data](https://www.census.gov/quickfacts/desmoinescityiowa), [Des Moines Tourism Website](https://www.catchdesmoines.com/things-to-do/)
- **Software:** Tableau, VS Code

## Objectives
- Import data into Tableau.
- Create and style worksheets, dashboards, and stories in Tableau.
- Use Tableau worksheets to display data in a professional way.
- Portray data accurately using Tableau dashboards.

## Summary
#### Import data into Tableau
In Tableau, we have a variety of different options when it comes to data sources. We can have flat files such as CSV, PDF, and TXT files, as well as other data sources like databases and data streams. (These will mostly be SQL databases.)  

There are two primary ways that Tableau connects to the data we provide: through live data or extract data. Both have their benefits and uses:  

**Live data** is primarily databases such as MySQL and Microsoft SQL Server. Live data is just what it sounds like: live data. This type of data is updated every time we view the dashboard, since it’s possible that the data has changed in our database.  

**Extract data** is primarily when we use files such as CSV, TXT, or PDF. These files remain unchanged unless we pull a new extract of the data. For example, if we update the file, we would have to update it in Tableau as well.
For our analysis, we imported the CSV file, which contains all the data we needed for this project. Therefore, we technically worked with extracted data for our project.  

#### Create and style worksheets, dashboards, and stories in Tableau.<br/>  
Worksheet
<img align="left" width="250" src="/pics/worksheet.png"><br/>  
Story
<img align="left" width="250" src="/pics/story.png"><br/>  
Dashboard
<img align="left" width="250" src="/pics/dashboard.png"><br/>
<br/>
<br/>
<br/>
<br/>
#### Use Tableau worksheets to display data in a professional way.  
The best visualizations have a clear purpose and work for their intended audience. What will we be trying to say with this dashboard? Are we presenting a conclusion or a key question?  

In addition to knowing what we're trying to say, it's important to know who we're saying it to. Does our audience know this subject matter extremely well or will it be new to them? What kind of cues will they need? Thinking about these questions before we head into the design phase can help us create a successful dashboard.  

Designing data visualizations is a huge field within the data industry, with some jobs devoted to making visualizations look better. While we don’t need to know everything about designing worksheets, we should be familiar with some best practices. The [Tableau website](https://help.tableau.com/current/pro/desktop/en-us/dashboards_best_practices.htm) provides information about best practices for effective dashboards. 
 
#### Portray data accurately using Tableau dashboards.  



## Challenge Overview  
In this challenge, we put together our final presentation and analysis for investors. We selected the questions we wanted to answer, conducted independent research, crafted our story in Tableau, and then created our written analysis.

## Challenge Objectives  
- Display data professionally and accurately.
- Professionally style a Tableau story.
- Utilize previously created Tableau worksheets to create a new story.
- Create a Tableau story based on starting a bike-sharing company in Des Moines.  

## Challenge Summary  
For this portion of the presentation, we worked with a team that is trying to answer core questions about opening a bike-sharing business in Des Moines.  

Our goal is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. So we wanted to format our story so it was persuasive. We also wanted to include information about both New York City and Des Moines—after all, the investors will need to understand how the Citi Bike data for New York City applies to our proposal.

## Limitations  
One thing to note about Tableau Desktop is that it does cost money every month. However, you can choose to do a [14-day free trial](https://www.tableau.com/products/desktop/download), which allowed us to complete the work in this module without being charged.

#### Background
The moment has come to put together the final presentation for the investors. You've asked your data a lot of questions: the who, what, where, and how long. The Citi Bike data is ready to help you tell a story, but it's up to you and the team to deliver a compelling story. Your final deliverable might look different from a peer's deliverable, and that's okay.  

To craft this narrative for the investors, you'll do the following:
- Select your questions. During this step, you'll consider which results you want to share with your audience. What do they want to see? How can we use that information to make their decision making process easier?
- Execute independent research. You'll need to look at other relevant pieces of information to build a bigger picture. Search other sources to find information that will make your visualization more powerful.
- Craft your Tableau story. This is when you create your story, primarily from worksheets and other visuals, with descriptions for each of them.
- Create a written analysis. The written analysis is intended to provide additional insight into what we're trying to convey to our audience. This is a good place to add extra detail so that everyone can get on the same page.  
#### Instructions
The tasks for this challenge are broken up into four key steps: select your questions, do independent research, craft your story, and write an analysis.
#### Step 1: Select Your Questions
When putting together an analysis, the first thing to consider is what question you will try to answer. To select your question, consider the analysis you have done on the NYC Citi Bike data and consider what investors might want to know about Des Moines in order to decide whether a bike-sharing program would work there. The questions your team has landed on are below. Choose one to focus on in your analysis.
- What is the population of Des Moines? How does its population compare to the population of New York City? Does the population affect the number of people who will use the bike-sharing program?
- What is the gender diversity of Des Moines? How does it compare to the gender diversity of New York City? What effect does it have on possible business in Des Moines?
- What is the density of McDonald's in New York City versus Des Moines? Does this affect where people go in the city? If so, how?
#### Step 2: Execute Independent Research
The next critical step is conducting independent research. In this case, consult various resources to help you get a better picture of what a bike-sharing business would look like in Des Moines.
The goal is to find key pieces of information that are relevant to the question you selected and that will help investors arrive at a decision more easily. Here are a few resources you might look at:
- [Des Moines Census Data](https://www.census.gov/quickfacts/desmoinescityiowa)
- [Des Moines Tourism Website](https://www.catchdesmoines.com/things-to-do/)
- New York and Des Moines McDonald's dataset: 
  - Download ny_mcdonalds.csv
  - Download ia_mcdonalds.csv
#### Step 3: Craft Your Tableau Story
Create a Tableau story answering the question you selected. Use story points and arrows to describe your findings.
If you would like more specifics for creating a great story, see Tableau's Best Practices for Creating Great Stories
 (Links to an external site.)
.
Then publish your Tableau story and dashboards to Tableau Public. Tableau Public is a way to share dashboards or stories that you have created online.
Note
Tableau Public should not be used for dashboards containing potentially private data; for this you should use Tableau Server. Private data is generally data that would have an impact on a business or person if it were released into the public. Since the data you're using is not considered private data, you can use Tableau Public.
You can publish your analysis to Tableau Public through the Tableau app. Follow these steps:
- Go to the Server dropdown menu and select Tableau Public.
- Click "Save to Tableau Public."
- To publish your analysis, log in to your Tableau account.
*For more information, see Tableau's documentation on saving workbooks to Tableau Public*
- Next, copy the link to use in your written analysis.
#### Step 4: Create a Written Analysis
The goal of your written analysis is to share additional thoughts with your audience, expanding on details and clarifying points that they may not understand. Stories in Tableau can be fairly open-ended, so a written analysis allows you to further share your insights and interpretation of the data in order to help your case.
**Length**
There is no official guideline for how long a written analysis should be, but you should write enough to convey your points.
**Content**
Your written analysis can include all or some of the following:
- A summary of your analysis
- A summary of each page in the Tableau story
- Clarifying any data that is unclear or complex
**Format**
Write your analysis in a markdown file named citibike_analysis.md, using VS Code. Your document should include a title. There are different sizes, or levels, of headings that correspond to the number of "#" signs preceding the title. For example:
# NYC Citi Bike Analysis
