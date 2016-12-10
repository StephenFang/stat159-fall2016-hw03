# Multiple Regression Analysis

## Project Description
This project is to perform multiple regression analysis to reproduce the data analysis in the book "An Introduction to Statistical Learning" (By James et al), for the content in section 3.2 (From page 71 to 82). In addition to regression analysis, we are also writing some of our own R functions as well as some unit tests. 

## File Structure
```
stat159-fall2016-hw03/
    .gitignore
    README.md
    LICENSE
    Makefile
    session-info.txt                     # produced by session-info-script.R
    code/
      README.md
      test-that.R
      functions/
        regression-functions.R
      scripts/
        eda-script.R
        regression-script.R
        session-info-script.R
      tests/
        test-regression.R
    data/
      README.md
      Advertising.csv
      eda-output.txt                      # produced by eda-script.R
      correlation-matrix.RData            # produced by eda-script.R
      regression.RData                    # produced by regression-script.R
    images/
        histogram-sales.png                # produced by eda-script.R
        histogram-tv.png                   # produced by eda-script.R
        histogram-radio.png                # produced by eda-script.R
        histogram-newspaper.png            # produced by eda-script.R
        scatterplot-matrix.png             # produced by eda-script.R
        scatterplot-tv-sales.png           # produced by regression-script.R
        scatterplot-radio-sales.png        # produced by regression-script.R
        scatterplot-newspaper-sales.png    # produced by regression-script.R
        residual-plot.png                  # produced by regression-script.R
        scale-location-plot.png            # produced by regression-script.R
        normal-qq-plot.png                 # produced by regression-script.R
    report/
        report.Rmd
        report.pdf
```
## Instructions to Reproduce Results

## Author Info

Name: Stephen (Mingtao) Fang

The project's content is licensed under MIT License and [Creative Commons License](https://creativecommons.org/licenses/by-sa/4.0/)
