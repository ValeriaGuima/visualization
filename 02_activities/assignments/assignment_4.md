# Data Visualization

## Assignment 4: Final Project by Valeria Guimaraes

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

Data Source: https://open.toronto.ca/dataset/earlyon-child-and-family-centres/

EarlyON Child and family centres offer free programs to parents/caregivers and their children from birth to six years of age. These centres welcome all families to participate in quality programs that help strengthen adult-child relationships, support parent education, and foster healthy child development.

1. Visualization 1
![Alt text](r'C:\Users\user\Projects\visualization\02_activities\assignments\image004.png)

For this first visualization, I creted a 3D map using Excel to displays the localization of the Early Years centres throughout Toronto. This resource is primarely for professionals in the sector who may need to refer families to these centres. By hoovering over each point on the map, users can view details such as the program name, full address and website of each centre.

The goal of this visualization is to highlight the availability of Child and Family Centres in Toronto.
I followed aesthetic design principles, using different fonts of diferent, sizes, and colors that are pleasing but not overwhelming. Eachpoint on the map represents a unique centre, and the information provided includes details for each centre. 

The data used in this visualization is publicly available and has been saved in an Excel file. The file includes notes detailing the data cleaning process. However, a downside of using Excel for this purpose is that the embeded tour feature can be challenging for recipients undamiliar with this tool.  For future mapping projects, I may consider using a different tool based on the learning obtained in this course.

This visualization could be added to a webpage for easier access and viewing. It could be particularly beneficial for families with children aged 0-6 lving in Toronto, as it may help them find suitable centres for visits and referrals.

To determine which features of the dataset to include in the visualization, I categorized the variables into three levels: "Good," "Nice to have," and "Not required." This helped me focus on the most relevant data for the general population, excluding variables such as staff and contact details, which were unnecessary for this exercise.

The process of creating the final data visualization involved significant "underwater labor." Selecting the dataset was challenging due to the many ideas that emerged during the data visualization program. Given time constraints, I opted for a theme familiar to me, which is part of my work as a data analyst for a social services agency. This choice allowed me to efficiently manage the project and produce a meaningful visualization.

2. Visualization 

Using the same data source in Python, I created two visualizations of the Early Years centres, grouped by city wards. The first visualization highlights the ward with the maximum number of centres, while the second shows all centres distributed across the wards. You can find these visualizations in the Jupyter notebook.

Initially, my goal was to display the number of centres per ward. However, the chart became overly crowded and visually unappealing. To address this, I created a bar chart showing the top 10 wards by the number of centres, using a gradient color scheme ranging from dark purple to light green. The second visualization is a pairplot that visualizes the location of centres by wards, also using gradient colors.

- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
