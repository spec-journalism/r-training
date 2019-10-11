# R Training Prerequisites

If you haven't already, make an account on GitHub and text me your username so I can add you to our organization. GitHub is where most of your future coding, data analysis, and data visualization will live.

Read and follow the instructions in the first six pages of [A (very) short introduction to R](https://cran.r-project.org/doc/contrib/Torfs+Brauer-Short-R-Intro.pdf). I will assume that you will come into the workshop knowing the basics of R and RStudio.

Now that you've installed R and RStudio, you'll need to install the tidyverse library. (The tidyverse is a collection of R packages designed for data analysis). In the console, run `install.packages(c("tidyverse", "jsonlite))` to download and install the tidyverse and a JSON reader. Every time you open RStudio, you have to run `library(tidyverse)`, either in the console or a script, to be able to use these packages.

That's it! See you at the workshop.

## Setup

1. Clone this repository by running the following command in the terminal:
```
git clone https://github.com/spec-journalism/r-training
```

2. Open RStudio. Go to `File > New Project... > Existing Directory`. Make the project working directory the `r-training` directory you just made. Then click "Create Project".

3. Make a new RMarkdown file (`File > New File > RMarkdown...`). Set the title to "Week 4 Workshop", then click OK.
