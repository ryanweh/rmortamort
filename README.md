# Reverse Mortgage Amortization

A learning project for D3.js, this simple page will calculate, chart, and graph mortgage values given initial loan conditions for a reverse mortgage.  Payments into the loan and changes to the loan interest rate can be added yearly.  Hopefully it can help you decide if a reverse mortgage makes sense in your situation.

## Getting Started

Everything is local HTML and Javascript, so you do not need a web server to view.  The d3.js library is included and is a fairly recent version of d3 as of the initial commit.  The three pieces necessary to view the page are the data/amortdata.json file, the d3/d3.js file, and the rmortamort.htm file itself.

You can copy the data/amortdata.json values into data/privatedata.json file.  Since it is gitignored, values in it will be used so that you can load your own initial conditions without them being pushed back into the repository.

### Prerequisites

You can simply download the entire rmortamort project to get the necessary files.

## Deployment

Some changes will be needed to make the project worthy of live deployment.

## Authors

* **Ryan Weh** (https://github.com/ryanweh)


## Acknowledgments

Big thanks to:
* https://www.d3-graph-gallery.com/line.html
* https://www.tutorialsteacher.com/d3js

...for helping to learn D3 and providing usable examples to work from