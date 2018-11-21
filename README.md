# XPath Challenge

## Setup
* If `git` is installed: `git clone git@github.com:wizenoze/xpath_challenge.git`
* If not, [click here](https://github.com/wizenoze/xpath_challenge/archive/master.zip) to download a `.zip` file with repository's content.


## Part 1
Open `easy.html`.  
It's a pretty simple html page which follows the [Open Graph protocol](http://ogp.me/).
Which `XPath` expression can we use to extract `Open Graph title`?

## Part 2
Open `hard.html`.  
We want to extract the same property as in `easy.html` but it doesn't exist.  
In this case (if opengraph title doesn't exist), extracted text should be just `Doe`. 

Tip: [This post](https://stackoverflow.com/questions/4489976/xpath-to-return-default-value-if-node-not-present/) might help

Validation: XPath expression for Part 1 should return: `John` and the same expression should return `Doe` for Part 2.


