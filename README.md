# Chart.js 

[![Build Status](https://travis-ci.org/nnnick/Chart.js.svg?branch=master)](https://travis-ci.org/nnnick/Chart.js) [![Code Climate](https://codeclimate.com/github/nnnick/Chart.js/badges/gpa.svg)](https://codeclimate.com/github/nnnick/Chart.js)


##New Features In This Fork
 - labelsFilter to filter x-axis labels based on user provided function
 - Template interpolator can be changed from default `<%` `%>` to what ever you want
 - New chart - overlay chart - for combing both bar and line charts on the same chart
 - new chart options for pie and dougnut to allow the creation of semi circle (or any size) charts drawn at user defined starting angle ()
 - line and overlay charts can handle sparse datasets, just include null in the dataset where no data is avaliable, this can be seen in the samples.
 - line,bar and overlay charts can have the tooltip display finely tuned. For each dataset an option called showTooltip can be passed to turn off the displaying off tooltips for that one dataset but not the whole chart
 

All new features are all documented the forks docs section.
## Documentation


*Simple HTML5 Charts using the canvas element* [chartjs.org](http://www.chartjs.org)

## Documentation

You can find documentation at [chartjs.org/docs](http://www.chartjs.org/docs/). The markdown files that build the site are available under `/docs`. Please note - in some of the json examples of configuration you might notice some liquid tags - this is just for the generating the site html, please disregard.

## Bugs, issues and contributing

Before submitting an issue or a pull request to the project, please take a moment to look over the [contributing guidelines](https://github.com/nnnick/Chart.js/blob/master/CONTRIBUTING.md) first.

For support using Chart.js, please post questions with the [`chartjs` tag on Stack Overflow](http://stackoverflow.com/questions/tagged/chartjs).

## License


Chart.js is available under the [MIT license](http://opensource.org/licenses/MIT).

