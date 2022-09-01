# computing-for-public-policy
 Summer 2022 Computing Bootcamp - Georgia Tech SPP



##Day 1 computing bootcamp 

1. Intro to class, goals, agenda for day
    1. Prep for ARM I,II
    2. Prep for your own projects
2. Why learn scientific computing?
    1. Applications to empirical and theoretical social science
3. Good enough practices 
    1. Data management
        1. Raw and intermediate data
        2. Documentation of preprocessing
        3. Output into plug and play data — i.e. easy to analyze
    2. Software
        1. Comment!
        2. Decompose into functions and refactor 
        3. Naming things
        4. Unit tests
    3. Collaboration
        1. To do lists
        2. Decide on how to communicate with collaborators
    4. Project organization
        1. Organize projects into directories
            1. Split different parts of the work in different subdirectories
                1. e.g. src, doc
                2. Name to reflect content/functions
    5. Keeping track of changes
        1. Back up everything asap.  ( and create helper functions to do so)
        2. Small changes, frequent updates
        3. Use local git + GitHub to track changes.  GitHub desktop is very user friendly
    6. Manuscripts
        1. Recommend latex + bibtex for writing, change tracking and reference management

Git tutorial https://www.youtube.com/watch?v=2sjqTHE0zok&list=PLyzOVJj3bHQuloKGG59rS43e29ro7I57J&index=6


## Day 2 computing bootcamp 

1. Intro to RStudio
    1. Where are things at
    2. Installing packages
2. Introduction to R syntax

Questions
* What data types are available in R?
* What is an object?
* How can values be initially assigned to variables of different data types?
* What arithmetic and logical operators can be used?
* How can subsets be extracted from vectors?
* How does R treat missing values?
* How can we deal with missing values in R?

Objectives
* Define the following terms as they relate to R: object, assign, call, function, arguments, options.
* Assign values to objects in R.
* Learn how to name objects.
* Use comments to inform script.
* Solve simple arithmetic operations in R.
* Call functions and use arguments to change their default options.
* Inspect the content of vectors and manipulate their content.
* Subset and extract values from vectors.
* Analyze vectors with missing data.

For reference: https://datacarpentry.org/r-socialsci/01-intro-to-r/index.html 



## Day 3-4: Starting with Data

Data for today: https://figshare.com/articles/dataset/SAFI_Survey_Results/6262019



1. Files and folders/directories
2. Loading and playing around with tabular data

Questions
* What is a data.frame?
* How can I read a complete csv file into R?
* How can I get basic summary information about my dataset?
* How can I change the way R treats strings in my dataset?
* Why would I want strings to be treated differently?
* How are dates represented in R and how can I change the format?

Objectives
* Describe what a data frame is.
* Load external data from a .csv file into a data frame.
* Summarize the contents of a data frame.
* Subset and extract values from data frames.
* Describe the difference between a factor and a string.
* Convert between strings and factors.
* Reorder and rename factors.
* Change how character strings are handled in a data frame.
* Examine and change date formats.


For extra practice and notes:
- https://r4ds.had.co.nz/
- also check out LinkedIn learning / Lynda for R tutorials.  You get free premium access through Georgia Tech!


## Day 4-6: Data wrangling

Questions
* How can I select specific rows and/or columns from a dataframe?
* How can I combine multiple commands into a single command?
* How can I create new columns or remove existing columns from a dataframe?
* How can I reformat a dataframe to meet my needs?

Objectives
* Describe the purpose of an R package and the dplyr and tidyr packages.
* Select certain columns in a dataframe with the dplyr function select.
* Select certain rows in a dataframe according to filtering conditions with the dplyr function filter.
* Link the output of one dplyr function to the input of another function with the ‘pipe’ operator %>%.
* Add new columns to a dataframe that are functions of existing columns with mutate.
* Use the split-apply-combine concept for data analysis.
* Use summarize, group_by, and count to split a dataframe into groups of observations, apply a summary statistics for each group, and then combine the results.
* Describe the concept of a wide and a long table format and for which purpose those formats are useful.
* Describe the roles of variable names and their associated values when a table is reshaped.
* Reshape a dataframe from long to wide format and back with the pivot_wider and pivot_longer commands from the tidyr package.
* Export a dataframe to a csv file.

## Day 7: Data Visualisation with ggplot2 and Review


* What are the components of a ggplot?
* How do I create scatterplots, boxplots, and barplots?
* How can I change the aesthetics (ex. colour, transparency) of my plot?
* How can I create multiple plots at once?

Objectives
* Produce scatter plots, boxplots, and barplots using ggplot.
* Set universal plot settings.
* Describe what faceting is and apply faceting in ggplot.
* Modify the aesthetics of an existing ggplot plot (including axis labels and colour).
* Build complex and customized plots from data in a data frame.


