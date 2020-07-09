
<!-- README.md is generated from README.Rmd. Please edit that file -->

# Third workshop module: Shiny and AWS AI Services

In the third module of the **AWS AI Services for R users** workshop you
will see how quickly and easy you can add sophisticated deep learning
capabilities to your Shiny applications.

We will deploy a Shiny application which makes calls to several AWS AI
services. The Shiny application leverages the AWS API calls you already
know and used in the second workshop module.

<center>

<img src="images/lab_scenario.png" width="40%" />

</center>

Our Shiny application is a [Shiny
document](https://bookdown.org/yihui/rmarkdown/shiny-documents.html)
based on a R Markdown file. Check out the source code in the
[GoT\_shiny\_ai\_services\_app.Rmd
file](/GoT_shiny_ai_services_app.Rmd). We also deployed the app to
[]()<https://shinyapps.io> and you can access it
[here](https://alexlemm.shinyapps.io/got_ai_services_lab/). In this
module you will deploy your version of the app.

## Installation

### Modify the app-specific `.Renviron` file

You will find another `.Renviron` file in the folder of the third
workshop module. This file will be deployed with the rest of the app
components. It allows the Shiny app to access the AWS AI Services via
the API.

If you trust [](https:shinyapps.io) you can copy & paste the three
environment variables from your user-specific `.Renviron` file to the
app-specific `.Renviron` file. Just open your user `.Renviron` file
using `usethis::edit_r_environ()`
