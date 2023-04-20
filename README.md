# AngelHack - Data Story
Submission for AngelHack April 2023 Challenge
Submitted by Angelica Casuela

## Background

Innovation drives the economy, and of the main contributors are those that reside in the academe. 

This data story aims to seek the understand the influence of educational institutions that are part of the Times Higher Education World University Rankings in the innovation index. The Global Innovation Index of 2022 is primarily scored based on the innovation input index and the innovation output index. 

The following questions will be answered throughout the exploration on data given by the Times Higher Education World University Rankings and the Global Innovation Index:
- How many universities are present in each country found in the THE World University Rankings?
- Is the median score of all of the universities in one country correlated with the country' ranking in the Global Innovation Index, focusing on the following criteria:
    - scores_teaching: Teaching score - learning environment score
    - scores_research: Research score - volume, incode and reputation of University
    - scores_citations: Citations score - research influence of University
    
The following scores from the dataset were chosen for data exploration since this are activities related to innovation output. 


## Methodology

This data story will make use of two datasets: 
- uni_rank.csv - Shows the THE World University Rankings
- inno_index.csv - Shows the Global Innovation Ranking of each country observed

Universities of the same country will be also analyzed by the median so that it takes into consideration that data is asymmetric. These values will be compared against their respective country's rank to see if there is a correlation present. 

## Conclusion

The teaching score can improve by country which can lead to an improve ranking in the Global Innovation Index. Providing students and researchers the space needed for innovation is a crucial as it fosters a culture pushing for national development as well. The same can be said with the research score of each country. Research outputs is a relevant indicator for a country's participation in innovation. Therefore, countries, especially those who reside in developing countries must look into a more active participation in research and development to improve their innovation ranking. 

Moreover, the citation score shows no correlation with the innovation ranking of a country which can suggest that the participation of knowledge transfer is an activity that is already expected of each country or academic institution. Making use of that knowledge does not translate in this criteria. 

A country's rate of innovation is dependent on the active participation of its education system. 

## Recommendations

It would be intersting to incorporate socio-economic factors such as income group in future analysis. This may uncover suggestions for developing countries to create policies that places an emphasis on research and development towards innovation. 
