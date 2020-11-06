
Here are the details for part 2 of the textbook. 

# Part II 

## 3. Programming in R (suggested new title: R and the tidyverse)

 - intro: exact copy from data 8
 - 3.1 exact copy from data 8
 - 3.2 exact copy from data 8
 - 3.3 few original additions about R and tidyvese, but otherwise a exact copy from data 8.
 - 3.4 datasets and most of descriptions are original, but section titles and flow 
       are a copy from data 8; probably some light rearranging and renaming of sections is all 
       that is needed
       
more notes: I think an addition of a section about the tidyverse can be good here, to separate this chapter more from data 8. The section can give a very high-level discussion of the main packages that we will be using from the tidyverse, of which there is a bunch. Important to note that each works together in unison with the other pieces like unix commands and pipes. 

- tibble: "modern re-imagining of the data frame"; makes working with data frames nicer,
             complains more often when problems occur so better debugging, 
             big thing is that it prints very nicely to the console 
- dplyr: for data manipulation, sorting, adding/deleting columns, filtering rows, slicing
- tidyr: tidying your data 
- ggplot2: visualization
- purrr: maps, which we use for iteration; appears when we need to do simulations 
- stringr: string manipulation functions
- readr: reading datasets like CSV and returns a tibble 
- link to tidyverse: https://www.tidyverse.org
  
 
## 4. Data Types

- intro: exact copy from data 8
- 4.1 mostly original content, but some parts are exact copies: introductory paragraphs, paragraph that starts with "when a double value is combined with an integer value using some arithmetic operator," and subsection 4.1.1
- 4.2 exact copy from data 8
- 4.3 exact copy from data 8

## 5. Vectors

- intro: exact copy from data 8
- 5.1: everything up to the tables is an exact copy from data 8. 
- 5.2: this section is original work
- 5.3: not completed 
- 5.4: not completed 

Here is the data 8 chapter: 
https://www.inferentialthinking.com/chapters/05/Sequences.html


## 6. Tables

not completed. This chapter should be a merging of 6 and 8 from the data 8 text. I think there are too many topics to cover here for one chapter, so a route we can take is have two separate chapters that are broadly on "Data transformations" and the idea of "Tidy Data", borrowing a bit from Hadley's "R for Data science" textbook. This is my idea for each. 

### Data transformations chapter

My plan is to devote a section to each of the main dplyr verbs, select(), arrange(), filter(), group_by(), summarize(), and of course the pipe operator "%>%". Possible outline: 

- intro: importance of data frames and data transformation; importance of dplyr and how dplyr verbs recycle many redundant tasks in data science work (selecting columns, splitting a column into two new ones, filtering rows by some criteria, adding new columns, summarizing groups present in the data like "what is the average flight delay for each month")
- 6.1: selecting columns (select)
- 6.2: arranging rows (arrange)
- 6.3: creating new columns (mutate, transmute)
- 6.4: grouped summaries (summarize)

Relevant chapter from Hadley's textbook: 
https://r4ds.had.co.nz/transform.html

Relevant chapter from data 8:
https://www.inferentialthinking.com/chapters/06/Tables.html

### Tidy data chapter 

This chapter should focus on what tidy data is and why we need tidy data in data science (possibly following the principles from Hadley's text)

- intro
- 6.1: Introduction to functions, maps, and purrr. Applying functions to columns using map. Now that we have this, we can apply conversions to columns (say temperature or weight) 
- 6.2: Handling missing values 
- 6.3: Pivot tables (pivot_longer, pivot_wider); seems pointless but is necessary for R workflows 
- 6.4: Separating and uniting columns 
- 6.5: case study to bring everything together 

Relevant chapter from Hadley's textbook:
https://r4ds.had.co.nz/tidy-data.html

Relevant chapter from data 8:
https://www.inferentialthinking.com/chapters/08/Functions_and_Tables.html

## 7. Visualization

- intro: exact copy from data 8
- 7.1: this one treads a little too closely to Hadley's textbook, which has the same licensing restrictions as data 8. The writing is all original, but the plots and discussion points are more or less identical to the textbook. What I have included is what I think needs to be discussed in some form in this section. See here for the corresponding section in the text:
  - https://r4ds.had.co.nz/data-visualisation.html
- 7.2: similar problem as 7.1, and introductory figures are copied from the textbook; note that 7.2.4 and onward is original work. 
- 7.3: dataset is original but content is an exact copy from data 8 


## 8. Functions and Tables 

not completed; see plan for chapter 6 



