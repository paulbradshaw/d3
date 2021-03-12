# Notes from Victoria Oliveres: 

Don't use D3 every day but only in circumstances:

* Where you want to be creative or innovative a custom visualisation that you can't do with Flourish etc.
* Where it's an ongoing/reusable resources like a dashboard where the investment of time will be justified
* Where speed is a problem with third party tools because of the size of data etc.
* High impact stories

# Notes from D3 course

Two courses on LinkedIn Learning:
https://www.linkedin.com/learning/learning-data-visualization-with-d3-js/using-d3-selections?u=42288921
https://www.linkedin.com/learning/d3-js-essential-training-for-data-scientists/explaining-d3?u=42288921

Use [Gulp](https://developers.google.com/web/ilt/pwa/introduction-to-gulp) to provide a server

## Using CSS selectors

`d3.select("p").text("hello")` will select the *first* `p` tag and fill the text specified.

`d3.selectAll("p").text("hello")` will select *all* `p` tags and fill the text specified.

`tr:nth-child(1)` would select the first `tr` item - note it's a 1-based index for selectors.


