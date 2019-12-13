
<!-- README.md is generated from README.Rmd. Please edit that file -->

# smoky

<!-- badges: start -->

<!-- badges: end -->

The goal of smoky group was to pull together air quality data into a
site akin to [isithotrightnow](https://isithotrightnow.com/).

We wanted to pull air quality data from authorities across Australia and
present it in a way that would allow the public to see how recent air
quality events relate to historical data. We also wanted to include
information to guide decision making.

# Things we worked on…

## deciding where to get data from

We ended up settling on NSW gov data, although this data is not ideal.
The site will only let us download daily average AQI.

## making a shiny app

The shiny app starts with a pulldown for site choice and tells you
whether air quality is very good, good, poor, very poor, or hazardous.
That text is also colour coded.

## grid plot

We have been working on replicating plot 3 on the
[isithotrightnow](https://isithotrightnow.com/) site.

![heatmap grid](https://isithotrightnow.com/output/066062/heatmap.png)

## gganimated historical change plot
