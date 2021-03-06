---
output: 
  html_document: 
    keep_md: yes
---



<style type="text/css">
body, td {
   font-size: 16px;
}
.table { width: auto; }
</style>



View the output version of this [template file] (https://qubeshub.org/groups/birdd/nabt2018template)  
![](https://qubeshub.org/groups/birdd/File:birdd.JPG)

## BIRDD Activity: Exploring Finch Morphology Data

### Put your title here. 

#### Put author names here

***

## Exercise 1 - Taking a quick look at the data
In the "Data" area you can use the "Manage" and "View" tabs to learn a little bit about the dataset. Please record the following information.  
  
Dataset Name:  
Number of Records:  
Number of Columns:  
Share an oberservation or question about the dataset:  

## Exercise 2 - Initial visualization
The box plot below shows wing length data for each of the 5 finch genera included in the Sato dataset. If you haven't worked with this kind of graph before you can [learn more about box plots here] (http://vita.had.co.nz/papers/boxplots.pdf).  


> Please replace this text with a brief interpretive statement about some of the information in the graph above.  
  
Now use the "Visualize" tab of the Data area to try to recreate this graph. Once you have done that choose a different visualization of the data and include the graph below.  

> When you have prepared your graph click the "report button" to save the visualization into this report. The code to recreate the graph will be saved to the end of this report and you can just copy and paste it to replace these instructions. When copying and pasting bits of code remember to grab everyting includung the beginning and ending triple apostropies (''').  

> Replace this text with a brief description of your graph and a question that it has helped you formulate.  
  
## Exercise 3 - Data manipulation 
This dataset contains morphological, island, and taxonomic information about a lot of birds. Sometimes the data is not in the proper format to directly answer a question. For example, **how many distinct species are on each island?** This is shown in the following pivot table.


```r
# result <- pivotr(dataset = "Sato", cvars = "IslandID", nvar = "SpeciesL69", fun = "n_distinct", nr = 28)
# summary(result)
# plot(result, flip = TRUE)
```

Now use the "Pivot", "Explore", or "Transform" tabs of the Data area to try to recreate these results. Once this is done, ask a different question that requires some data processing and include your results below.

> Replace this text with your data manipulation code and visualization(s) - be sure to include a brief interpretive description for each graph. 

See the information on the [BIRDD NABT 2018 Session Page] (https://qubeshub.org/community/groups/birdd/workshops/nabt2018). 
