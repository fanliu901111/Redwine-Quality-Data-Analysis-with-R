# Udacity_Project5
# Red Wine Data Anlaysis by Fan Liu
## About
In this project, I will explore a data set on red wine quality and physicochemical properties. The objective is to explore which chemical properties influence the quality of red wines. This dataset is public available for research.

```{r echo=FALSE, message=FALSE, warning=FALSE}
#Reading the file
rw <- read.csv('wineQualityReds.csv')
```

```{r echo=FALSE, message=FALSE, warning=FALSE}
#Loading all packages
library(ggplot2)
library(gridExtra)
library(GGally)
library(scales)
library(reshape)
```

### Summary of data
Let's check the basic information for the statistics
```{r echo=FALSE, message=FALSE, warning=FALSE}
head(rw)
str(rw)
summary(rw)
```
