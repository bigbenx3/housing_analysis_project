Overview of README content:


-README.md- 
This file was created as an overview of the contents within this repo.


movies_genres_dfs: 

    This folder houses excel files: all the data frames for each of the 22 unique genres from 
    df_for_genre_rating_plot data frame, exported as excel files.


.gitignore: 
       
    This file helps avoid creating an ipynb.checkpoint file every occurence of a git add, commit,
    and push. Ignores the extra porject files that includes caches and checkpoints.


aaa_df_for_genre_rating_plot_visual.xlsx: 
                   
    This file creates a pivot table in excel for df_for_genre_rating_plot.  
    Displays genres vs ratings data of movies in 2018 and 2019 years.


aaa_df_good_margins.xlsx: 
                   
    This file houses all the budget data relating to genres and the
    corresponding domestic and worldwide margins.


aaa_movie_analysis_project_notebook.ipynb: 

    This jupyter notebook displays the project code for the various functions, data acquistion,
    and cleaning processes. 


movie_analysis_presentation.pdf: 

    This is the pdf of the jupyter notebook derived from the powerpoint
    presentation.


project_jupyter_notebook.pdf: 

    This is the pdf of the jupyter notebook for the movie analysis project.


!["dodge charger with sunset background"](project_images/thumb-1920-1036030.jpg)

# Microsoft Movie Studio Analysis

**Author**: [Benny Zhu]

## Overview

This project analyzes movie production specs of [Microsoft Studios], a new movie studio looking at what kind of movie to produce. Our investigation has found that among the Top 3 highest rated genres in the box office are Drama providing the most movies with the highest ratings (6.9 - 7.3), followed by Comedy, and lastly Documentary. Microsoft Studios can use this analysis to adjust their intended production time frame, projected ROI and budget, and other resource allocation.

## Business Problem

![img](./images/animals.png)

Microsoft Studios may be able to improve their resource allocation to both reduce costs and ensure that the center has staff and space to care for the animals brought to them. Doing so will allow the Austin Animal Shelter to better serve its clients while also freeing up resources to expand the scope of services they can offer.

## Data

Microsoft Studios wanted to look into the best performing movies in the box office. has the longest running public dataset of animal rescues in the country. Every animal has a unique ID associated with both their [intake](https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Intakes/wter-evkm) and [outcome](https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Outcomes/9t4d-g238) data. The data files provide the dates and types of each event, as well as other animal characteristics (e.g. type, sex).

## Methods

This project uses descriptive analysis, including description of trends over time. This provides a useful overview of AAC's typical intakes and outcomes to identify resource needs.

## Results

Most animals have short stays at AAC (under 15 days) but some have long stays (over 180 days), and most of these are dogs.

![stay_lengths_by_type](./images/stay_lengths_by_type.png)

The total number of sheltered animals typically peaks in May of each year and then hits its lowest point around January. There is often a secondary peak sometime after May before the number of sheltered animals drops rapidly. The number of sheltered animals has dropped precipitously in 2020, likely as a result of COVID-19.

![sheltered_by_month.png](./images/sheltered_by_month.png)

## Conclusions

This analysis leads to three recommendations for improving operations of the Austin Animal Center:

- **Engage in targeted outreach campaigns for dogs that have been sheltered at AAC for more than 30 days.** While most dogs will have been placed after 30 days, this may help reduce the number of dogs that end up having extended stays, potentially requiring many more months of care.
- **Reduce current spending until the numbers of intakes and sheltered animals return to normal.** Given the reduced activity during this period, AAC should consider ways to temporarily reduce costs by changing space utilization or staffing.
- **Hire seasonal staff and rent temporary space for May through December.** To accommodate the high volume of intakes and number of sheltered animals in the spring and fall, AAC should leverage seasonal resources, rather than full-year ones. This will allow AAC to cut back on expenditures during the months when there is lower

### Next Steps

Further analyses could yield additional insights to further improve operations at AAC:

- **Better prediction of animals that are likely to have long stays.** This modeling could use already available data, such as breed and intake condition.
- **Model need for medical support.** This modeling could predict the need for specialized personnel to address animals' medical needs, including neutering, using intake condition and sex data.
- **Predicting undesirable outcomes.** This modeling could identify animals that are more likely to have undesirable outcomes (e.g. Euthanasia) for targeted medical support or outreach.

## For More Information

See the full analysis in the [Jupyter Notebook](./animal-shelter-needs-analysis.ipynb) or review this [presentation](./Animal_Shelter_Needs_Presentation.pdf).

For additional info, contact Alison Peebles Madigan at [alison.peeblesmadigan@flatironschool.com](mailto:alison.peeblesmadigan@flatironschool.com)

![logo](./images/aac_logo_tall.jpg)

## Repository Structure