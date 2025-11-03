# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  

Answer: 
        - 1rst Visualization with Python: Please see the Assignment_3.ipynb file (Final Graphic) to see the Image and the process to do the visualization. 
        - 2nd Visualization with tableau, URL: https://public.tableau.com/app/profile/mariluz.lopez/viz/MeanMonthlyNumberofICUPatientswithCOVID-19-RelatedCriticalIllnessvs_ThoseRequiringVentilatorySupportinOntario20202022/Hoja1


- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?
             - 1rst Python Visualization: I used python to explore the Dataset, understand the attributes, the relation between the attributes, and define which columns or atributes I will be used for my graphics and what will be the filters to do it, as a example I observed missed data in an important period of time, also, the peaks of the pandemic was a criteria to define whic years I will be use to the graphic and correlations. 
             - 2nd Tableau Visualization: after explore all the dataset and select the atributes, time line and correlations I used tableau to made an interactive visualization.  

    > Who is your intended audience? 
             - Public health authorities, individuals interested in public health and epidemiology, and people studying or interesting in ICU occupancy trends during the most critical phases of the pandemic in Ontario, 2020, 2021, 2022. 
    
    > What information or message are you trying to convey with your visualization? 
            - The high percentage of patients with COVID-19-related critical illness who required ventilatory support.
            - The evolution of the COVID-19 pandemic in terms of ICU occupancy since the first year, and the health system’s response to increase ICU capacity in a relatively short period of time.
            - The impact of the Alpha variant during the third and most severe peak of the pandemic.
            - The relatively rapid start of the vaccination process in Ontario.
            - To recognize that our intensive care workers made their best effort and went through a very difficult time for almost three years, fighting to save Ontarians from COVID-19.
            - It shows that Ontario’s reopening decision was based on strong epidemiological analysis, and it highlights the importance of data analysts in making big and very important decisions accurately.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
        - Design aspects: Python visualization
            - I used neutral colors, and kept them consistent across both charts.
            - I tried to use the same font style for all labels and titles.
            - I added arrow markers to include relevant annotations and date references, highlighting important events during the pandemic.
            - I aimed to make it comprehensive. For example, I used readable labels and included percentage values.
            - I chose a bar chart to show the timeline evolution during the most critical part of the pandemic.
            - I adjusted the X-axis format to make the timeline easier to understand.
            - I used a neutral background and added horizontal lines to help estimate the height of each bar more easily.
        
    - Design aspects: Tableau visualization
            - I used two neutral colors with similar intensity to make the charts easy to compare, without giving more importance to one over the other.
            - I placed the charts one above the other to make comparison easier.
            - I made it interactive: when hovering over any arrow, you can see the total number of critically ill and ventilated COVID-19 patients and the mean.
            - I used a light background to avoid distracting from the data. I applied the same font to the labels and made the title easy to read.
            
        
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
            - Yes, my data visualization is reproducible because I used a public dataset and included as much relevant information as I could.
            - Also Python language and Tableau are public to use it. 
            - To highlight: reproducing the visualization in Python requires a clean and organized process.
            - I included a jupiter notebook explaining the data exploration and visualization process with comments and Analyst. 
            - To conclude, others can access the same data and follow similar steps to recreate the charts.
    
    > How did you ensure that your data visualization is accessible?  
            - All the tools are free, I include the URL to the free dataset in both (python and tableau)
            - I Upload the Python visualization to my public repository on GitHub.
            - The tableau Visualization is Public as well. 
            
    > Who are the individuals and communities who might be impacted by your visualization?  
            - People who worked in Ontario's ICU during the pandemic COVID-19
            - People interested in Public Health 
            - People Interested in pandemic COVID-19

    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
            - I read the information from the webpage (where I select the dataset) and took notes about how they collected the data, the time period covered, and some annotations about issues they faced during 2023.
            - After selecting the dataset, my first step was to explore it. I analyzed it to understand what each column name meant, what data types were used, and how Ontario’s regions were divided.
            - I created some visualizations to identify the correlations that were most self-explanatory.
            - After the initial exploration, I decided to focus only on the most critical moments of the pandemic and exclude the time period after 2023 due to insufficient data.
            - When I saw the pattern of four pandemic peaks, I searched for specific dates related to events that I believed could have influenced those peaks.
    
    > What ‘underwater labour’ contributed to your final data visualization product?
            - The time that I dedicate to explore and understand the dataset, the correlation and to clean the data was the "underwater labour" of the visualization

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
* Submission Due Date: `23:59 - 11/02/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
