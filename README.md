# Big Data in R with Arrow

**posit::conf 2023**

by Steph Hazlitt & Nic Crane

------------------------------------------------------------------------

:spiral_calendar: September 17th, 2023\
:alarm_clock: 09:00 - 17:00\
:hotel: ROOM TBD\
:writing_hand: [pos.it/conf](http://pos.it/conf)

------------------------------------------------------------------------

### Workshop Website

This repository contains materials for the 1-day **Big Data in R with Arrow** workshop at Posit::conf(2023). See <https://posit-conf-2023.github.io/arrow/> for rendered workshop materials, including slides and exercises.

### Workshop Overview

Data analysis pipelines with larger-than-memory data are becoming more and more commonplace. In this workshop you will learn how to use Apache Arrow, a multi-language toolbox for working with larger-than-memory tabular data, to create seamless "big" data analysis pipelines with R.

The workshop will focus on using the the arrow R package---a mature R interface to Apache Arrow---to process larger-than-memory files and multi-file data sets with arrow using familiar dplyr syntax. You'll learn to create and use interoperable data file formats like Parquet for efficient data storage and access, with data stored both on disk and in the cloud, and also how to exercise fine control over data types to avoid common large data pipeline problems. This workshop will provide a foundation for using Arrow, giving you access to a powerful suite of tools for performant analysis of larger-than-memory data in R.

*This course is for you if you:*

-   want to learn how to work with tabular data that is too large to fit in memory using existing R and tidyverse syntax implemented in Arrow
-   want to learn about Parquet and other file formats that are powerful alternatives to CSV files
-   want to learn how to engineer your tabular data storage for more performant access and analysis with Apache Arrow

### Instructors

**Steph Hazlitt** is a data scientist, researcher and R enthusiast. She has spent the better part of her career wrangling data with R and supporting people and teams in learning, creating and sharing data science-related products and open source software.

**Nic Crane** is a software engineer with a background in data science, and has a lot of enthusiasm for open source and learning and teaching all things R. Nic is part of the core team who maintain the Arrow R package.

### Acknowledgements

Some of the `Big Data in R with Arrow` workshop materials draw on other open-licensed teaching content which we would like to acknowledge:

-   [useR!2022 virtual Larger-Than-Memory Data Workflows with Apache Arrow tutorial](https://github.com/djnavarro/arrow-user2022) authored by Danielle Navarro
-   [R for Data Science (2e)](https://r4ds.hadley.nz/) written by Hadley Wickham, Mine Çetinkaya-Rundel, and Garrett Grolemund---with thanks to Danielle Navarro who contributed the initial version of the [Arrow chapter](https://r4ds.hadley.nz/arrow)
-   [How to use Arrow to work with large CSV files? blog post](https://francoismichonneau.net/2022/10/import-big-csv/) by François Michonneau, which introduces the single vs multi-file API models for learning/teaching Arrow

------------------------------------------------------------------------

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
