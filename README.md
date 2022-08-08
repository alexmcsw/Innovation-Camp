# Innovation Camp
Coding demo and challenge for the 2022 Innovation Camp

## Description
This repository was created for an interactive coding demo + exercise for the 2022 Innovation Camp Pilot. The purpose is to expose participants to different analytical, visualization, and collaborative techniques that are available in open source software such as Rmarkdown.

There are two versions of the coding challenge, one with examples and hints (challenge.Rmd) and the other a minimalist version for those looking to challenge themselves (challenge-no-hints.Rmd).

## Adding this repo to your AAW
1. Within this repository, click the download button in the upper right.

 ![Step 1](/images/step1.jpg)

2. Save the zip file to somewhere you can easily locate it.

![Step 2](/images/step2.jpg)

3. In your AAW Kubeflow RStudio server locate the upload files button at the top of the lower right box.

![Step 3](/images/step3a.jpg)

4. Leave the target directory as ~ and click choose file.

![Step 4](/images/step4.jpg)

5. Locate and select the zipped folder we saved earlier. Click open.

![Step 5](/images/step5.jpg)

6. Click OK.

![Step 6](/images/step6.jpg)

7. Note that you should now have a folder called innovation-camp-main containing all the files of this directory.

![Step 7](/images/step7a.jpg)
![Step 7](/images/step7b.jpg)

## Installation
If you are working in AAW, all packages are readily available to you. Otherwise, the following packages will need to be installed:

```
library(cansim) # read in CODR/NDM tables
library(dplyr) # for data manipulation
library(tidyr) # for shaping the data
library(plotly) # for creating plots
library(lubridate) # for manipulating date-time objects
```
## The Assignment
In this workshop we will be exploring [Stocks of specified dairy products](https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=3210000101#tables). 

We will learn and practice how to load, clean, analyze and visualize data using Rmarkdown.

## References 
- [RPUG R Resources](https://rpug.pages.cloud.statcan.ca/en/resources/r/)
- [Plotly basics](https://plotly.com/r/creating-and-updating-figures/)
- [dplyr](https://dplyr.tidyverse.org/)
- [tidyr](https://tidyr.tidyverse.org/)


## Support
Contact the workshop organizers in chat or the [innovation surge team](mailto:statcan.innovationsurgeteam-equipedappointdelinnovation.statcan@statcan.gc.ca) after the workshop.

## Contributing
If you'd like to showcase your solution there will be opportunity at the end of the workshop.

## Authors and acknowledgment
Created by Alexandra McSween for the 2022 Innovation Camp Pilot. Contributions and support from Tabitha Wiliams, Kate Burnett-Isaacs, Brittny Vongdara and Philippe Bisaillon.
