## Data Analysis Menu in Shiny

This is a data-analysis menu for R using [shiny](http://www.rstudio.com/shiny/). If you would like to see the app in action please visit Rstudio's Glimmer-server at [http://glimmer.rstudio.com/mostlyhrmls/damshiny/](http://glimmer.rstudio.com/mostlyhrmls/damshiny/)

### Todo:
- Add analysis-tools (e.g., conjoint, factor, perceptual maps, MDS, proportions, ANOVA)
- Using knitr to allow logging of analyses
- Create help files
- etc. etc.
		
### To use the damshiny package locally

	install.packages('shiny')
	install.packages('damshiny', repos = c('http://vnijs.rady.ucsd.edu/site_media/R_packages/','http://cran.rtudio.com'))
	library(shiny)
	shiny::runApp(system.file('damshiny',package='damshiny'))

### To use the development version of the marketing app locally

	install.packages('devtools')
	library(devtools)
	install_github('shiny', username = 'rstudio')
	install_github('shiny-incubator', username = 'rstudio')
	install_github('damshiny', username = 'mostly-harmless')
	library(shiny)
	shiny::runApp(system.file('marketing',package='damshiny'))

<!-- ### To use the development version of the finance app locally

	install.packages('devtools')
	library(devtools)
	install_github('shiny', username = 'rstudio')
	install_github('shiny-incubator', username = 'rstudio')
	install_github('damshiny', username = 'mostly-harmless')
	library(shiny)
	shiny::runApp(system.file('finance',package='damshiny'))

 -->
### License
The damshiny package is licensed under the GPLv3. See these files listed below for additional details:

COPYING - damshiny package license (GPLv3)
NOTICE - Copyright notices for additional included software

<!-- install.packages('devtools'); library(devtools)

Installing roxygen2 using install_github doesn't seem to work right now 1/3/2013
install_github('roxygen2')

install_github('damshiny')
library(damshiny)

When installed as a package use: shiny::runApp(system.file('rtut/damshiny/inst/damshiny', package='damshiny'))

Suggestions and input are very welcome. -->	