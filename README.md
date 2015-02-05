# Chart.js 

[![Build Status](https://travis-ci.org/nnnick/Chart.js.svg?branch=master)](https://travis-ci.org/nnnick/Chart.js) [![Code Climate](https://codeclimate.com/github/nnnick/Chart.js/badges/gpa.svg)](https://codeclimate.com/github/nnnick/Chart.js)


##New Features In This Fork
 - labelsFilter to filter x-axis labels based on user provided function [http://jsfiddle.net/leighking2/mea767ss](http://jsfiddle.net/leighking2/mea767ss/)
 - Template interpolator can be changed from default `<%` `%>` to what ever you want [http://jsfiddle.net/leighking2/d5yq9x32](http://fiddle.jshell.net/leighking2/d5yq9x32/)
 - New chart - overlay chart - for combing both bar and line charts on the same chart [http://jsfiddle.net/leighking2/y58n7m3z](http://fiddle.jshell.net/leighking2/y58n7m3z/)
 - new chart options for pie and dougnut to allow the creation of semi circle (or any size) charts drawn at user defined starting angle [http://jsfiddle.net/leighking2/f62Lghy1](http://fiddle.jshell.net/leighking2/f62Lghy1/)
 - line and overlay charts can handle sparse datasets, just include null in the dataset where no data is avaliable, this can be seen in the samples [http://jsfiddle.net/leighking2/ntuwuk5v](http://fiddle.jshell.net/leighking2/ntuwuk5v/)
 - line,bar and overlay charts can have the tooltip display finely tuned. For each dataset an option called showTooltip can be passed to turn off the displaying off tooltips for that one dataset but not the whole chart [http://jsfiddle.net/leighking2/at3w2aej](http://fiddle.jshell.net/leighking2/at3w2aej/)
 - bar (and overlay) chart can have an option passed to stack bars (draw on top of each other), just pass the option 'stacked:true' when creating the chart [http://jsfiddle.net/leighking2/h2f7rs8d/](http://jsfiddle.net/leighking2/h2f7rs8d/)
 - line (and overlay) chart can have an option passed to populate sparse data sets. When this is passed the chart will connect any blank values in the chart so that the line is continous (starts at the first data poitn entered and goes untill the last data point), just pass the option 'populateSparseData:true' when creating the chart. [http://jsfiddle.net/leighking2/uhs6rbt8/](http://jsfiddle.net/leighking2/uhs6rbt8/)

All new features are documented in the forks docs section or follow the links to the fiddles to see a working example.
## Documentation


*Simple HTML5 Charts using the canvas element* [chartjs.org](http://www.chartjs.org)

## Documentation

You can find documentation at [chartjs.org/docs](http://www.chartjs.org/docs/). The markdown files that build the site are available under `/docs`. Please note - in some of the json examples of configuration you might notice some liquid tags - this is just for the generating the site html, please disregard.

## Bugs, issues and contributing

Before submitting an issue or a pull request to the project, please take a moment to look over the [contributing guidelines](https://github.com/nnnick/Chart.js/blob/master/CONTRIBUTING.md) first.

For support using Chart.js, please post questions with the [`chartjs` tag on Stack Overflow](http://stackoverflow.com/questions/tagged/chartjs).

## License


Chart.js is available under the [MIT license](http://opensource.org/licenses/MIT).

