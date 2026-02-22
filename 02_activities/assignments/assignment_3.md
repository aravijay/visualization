# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

VISUALIZATION 1: PYTHON

    > What software did you use to create your data visualization?
    I used Python for my first visualization.

    > Who is your intended audience?
    The intended audience for this visualization is anyone who has interest in construction factors that can contribute to poorer road quality. This could be general laypeople who are frustrated with road quality, construction contractors, or government personnel looking for factors to target in order to fix this problem. 
    
    > What information or message are you trying to convey with your visualization?
    I am attempting to draw a correlation between average PCI scores (Pavement Condition Index) and their construction materials. A better or worse score can therefore be connected to a specific material used in the construction of said road. 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
    I felt I needed to split up the road types as the data does, from long-distance roads like freeways to shorter ones like local roads. For this, I created subplots placed close to each other so that they would be easy to compare. I also made the bar plots I used into a percentage stacked format, and coloured it proportionally with the percentage share of each road quality score it got along its measured segments. This is to show that roads have differing average qualities in an easy to understand, visual way. Because readding a chart this way with no numerical indicator is difficult, I also added little labels with the percentage values for anything above 5% on top of each bar for readability. 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    I ensured it was reproducible by inputting a seed for the code to follow with np.random.seed(). 
    
    > How did you ensure that your data visualization is accessible?
    I used bright, contrasting colours to ensure that the colourblind can easily pick out differing bar lengths, as well as add clear delineations between bars for types of colourblindness that this palette cannot account for.  
    
    > Who are the individuals and communities who might be impacted by your visualization? 
    If the data is taken to enact some reparatory action, the people most affected in a positive way would be those who live by local roads with poorer than average road quality, as my visualization suggests that local roads should be the target of renovation by far. 
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    I could not include roads in the visualization with too much omitted data, so I made sure that any road picked would be of a minimum recorded continuous length of 25km to work with.  
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    There was a degree of annoyance with rewriting some categorical variables for better audience readability, needing me to remap a lot of terms to more readable ones (such as paving type).


VISUALIZATION 2: TABLEAU

    > What software did you use to create your data visualization?
    I used Tableau for my second visualization.

    > Who is your intended audience?
    My intended audience here is a more general layperson, who is interested in overall trends in road quality across a large variety of roads.
    
    > What information or message are you trying to convey with your visualization? 
    I am attempting to impart an idea of average road health in Ontario, in order for more curious people new to the topic to be motivated to research further.
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    I had to make the general idea of some roads being better or worse in overall quality flow easily in the visual sense. This means that I had to use the element of recency bias to convey that local roads are typically the worst treated roads in terms of maintenance and upkeep. As such, I had to show a general trend of worsening road quality, starting with freeways as the best quality, then arterial highways, then collectors, then finally local roads.
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
    Tableau does not easily make reproducible results, so I had to pick proportionally fair slices of each of the pavement types (labelled as Func Class Display) to display as close to a normal distribution as I could make for each road type. 
    
    > How did you ensure that your data visualization is accessible?
    Even for the colorblind, data is arranged in such a way that the roads with the best score in the selected slice are always at the top of each slice, and are organized from best to worst. Context absent, this visually shows a downward trend that is easy to pick up on.   
    
    > Who are the individuals and communities who might be impacted by your visualization?
    This is meant to impact people looking at general results of road health, whether out of curiosity or from research motivated from negative sentiments about road quality in their vicinity. It is meant to be a general look at road health, to motivate interested viewers to hard data or community outreach groups that seek to fix issues like these.  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization?
    I had to select data from specific slices of each road type that did not have too much omitted data to be reliable. 
    
    > What ‘underwater labour’ contributed to your final data visualization product?
    Tableau had a bad habit of over-selecting for roads that counted as multiple categories, so I had to decouple said road scores from each other with filters.

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
* Submission Due Date: `23:59 - 02/23/2026`
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
