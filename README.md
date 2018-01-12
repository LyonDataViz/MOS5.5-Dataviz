# Interactive Data Visualization (ECL MOS 5.5)

[Romain Vuillemot](http://www.ec-lyon.fr/contacts/romain-vuillemot), *LIRS/MI École Centrale de Lyon*, [Site Web](http://romain.vuillemot.net/),  [Twitter](https://twitter.com/romsson).

  Contact or questions: romain.vuillemot@ec-lyon.fr

## Reading

<table border="0">
  <tr>
    <td>
      <img src="img/book-cover-interactive-data-visulization-murray.png" style="width: 100px;">
    </td>
    <td>
      <a href="http://chimera.labs.oreilly.com/books/1230000000345">Interactive Data Visualization for the Web</a><br>by Scott Murray
    </td>
  </tr>
</table>

## Grading

* 40% Final exam
* 40% Final projects
* 20% Homeworks/Submitted assignments (pass/fail policy)

## **Lecture 1 - Introduction to Data Visualization** 

*Friday 12/01/2018 13:30-15:30*

* Overview: Class organization, learning paths ([slides](https://docs.google.com/presentation/d/1YaPshJZLDj6M0XBMtmHqANeH17JINdB3Ie5G8RdC74U/edit#slide=id.p))
* Basics of Data Visualization: Perception, cognition, Visual mapping, Standard charts ([slides](https://docs.google.com/presentation/d/1YY8h1wjfaAv172LVa8kVAnxCyEB547HRL43JlEOvCH0/edit#slide=id.p))
* Authoring visualizations: Libraries, Tools, Tableau Software ([slides](https://docs.google.com/presentation/d/18b-B9wAYpq93nbROxRe9u6-7xexuBLM7T-yapqGoYdo/edit#slide=id.g2f7ee94efd_0_45))

## **Tutorial 1 - Tableau Software**
Friday 12/01/2018 15:45-17:45

*Tableau Tutorial* 

1. The goal is to have a first experience with Tableau and build standard charts using a simple dataset.
2. Download and install [Tableau Public](https://public.tableau.com/) (Free) on your machine
3. (Simple) alternative to Tableau: [Polestar](http://vega.github.io/polestar/)

*Iris flowers visualization*

1. Download the [`iris.csv`](data/iris.csv) and load it in Tableau; convert data types (if needed)
2. Plot a **scatterplot** with X:sepal_length, Y:sepal_width, color:species and a trend line 
3. Save as a tab and save the workbook

*Elections map*

1. Download the [`us-elections-history.csv`](data/us-elections-history.csv)` and load it in Tableau; convert data types (if needed)
2. Plot a grid plot with `Year` as columns, `State` as rows and `State Winner` as color/marks.
3. Save as a tab
4. Plot a **geo-map** with colors winning party in 2012 `Latitude (generated)` et `Longitude (generated)`, with `State` as shapes and color `ATTR([State Winner])`
5. Save as a tab and save the workbook

*Stock markets visualizations*

1. Download the [`stocks.csv`](data/stocks.csv) and load it in Tableau; convert data types (if needed)
2. Plot a **multiple line chart** over time, for all stocks in a different color, grouped by company
3. Plot a **grouped bar chart** (companies as categories, grouped by year or by companies)
4. **Your own chart**!
5. Save as a tab and save the workbook

*Bonus*

* For each previous dataset, provide an alternative visualization.
* Find a more complex stock dataset with OHLC attributes (Open, High, Low, Close) and visualize intra-day variations
* Find more time points and companies and re-produce the previous charts; adapt accordingly.
* Use other markets data (e.g. BitCoin)
* Use other tools, e.g. Vega Lite to visualize the above or your dataset

📅 **For next class (19/01)**

* Submit your Tableau workbook [in this document](https://docs.google.com/spreadsheets/d/15R4NmF-Ript1vW8m15fs0rmOV2ag85M30gkaBQx0uy4/edit#gid=0),
* Reading: [Chapter 1. Introduction
](http://chimera.labs.oreilly.com/books/1230000000345/ch01.html), [Chapter 2. Introducing D3](http://chimera.labs.oreilly.com/books/1230000000345/ch02.html) and [Chapter 3. Technology Fundamentals](http://chimera.labs.oreilly.com/books/1230000000345/ch03.html)
* Create a GitHub account and learn how to use it (bottom of the page)
* Pick a chart type [in this document](https://docs.google.com/spreadsheets/d/15R4NmF-Ript1vW8m15fs0rmOV2ag85M30gkaBQx0uy4/edit#gid=0), and find online:
  * Historical examples
  * Recent most famous ones
  * Comments: possible variations, different names
  * Document your sources, credits and write a summary report
  * Create a github page and put all examples in a `Readme.md` document
  * Add the link to your summary [in this document](https://docs.google.com/spreadsheets/d/15R4NmF-Ript1vW8m15fs0rmOV2ag85M30gkaBQx0uy4/edit#gid=0) **before Thursday 19/01/2018 12h00 Lyon Time** *

## **Lecture 2 - Introduction to D3.js** 

<small>Friday 19/01/2018 13:30-15:30</small>

* Advanced data visualization concepts: Animation, Interaction, Multiple Views (slides)
* D3.js: Principles, Codes, Web Development (slides)
* Introduction to projects

## **Tutorial 2: D3.js** 
Friday 19/01/2018	16:15-18:15

We will use Block Builder http://blockbuilder.org/ (requires a GitHub account to save code, but no local install)

📅 **For next class (26/01)**

* Reading: [Chapter 4. Setup](http://chimera.labs.oreilly.com/books/1230000000345/ch04.html), [Chapter 5. Data](http://chimera.labs.oreilly.com/books/1230000000345/ch05.html), [Chapter 6. Drawing with Data](http://chimera.labs.oreilly.com/books/1230000000345/ch06.html), [Chapter 7. Scales](http://chimera.labs.oreilly.com/books/1230000000345/ch07.html).
* Build a chart using Block Builder and submit it to the following Google Form
* Project teams, datasets and projects descriptions proposal

## **Lecture 3 - Advanced D3.js and Design Methods**
Friday 26/01/2018 13:30-15:30

* 
* Sketching, Rapid Prototyping, Development cycles (slides)
* Projects proposal discussion/validation

## Tutorial Design
Friday 26/01/2018 16:15-18:15

📅 **For next class (02/02)**

* Each team submits their project design proposition

## Lecture 4 - Advanced Design and Reseach 
Friday 02/02/2018 13:30-15:30

* Complex data types, layouts (slides)
* Research areas, open challenges (slides)

## Tutorial (1/2): Advanced layouts in D3.js
Friday 02/02/2018 16:15-18:15

📅 **For next class (09/02)**

* Peer review of other groups' projects proposal
* Web page setup of each team's project
* Submit URL

## Tutorial (2/2): Advanced layouts in D3.js
Friday 09/02/2018 13:30-15:30

## Projects (1/5)
Friday 09/02/2018 16:15-18:15

📅 **For next class (16/02)**

* Keep working on the project!

## Projects (2/5)
Friday 16/02/2018 13:30-15:30

## Projects (3/5)
Friday 16/02/2018 16:15-18:15

📅 **For next class (02/03)**

* URL of final project
* Project technical and design report

## Projects (4/5): Pesentations & demos
Friday 02/03/2018 13:30-15:30

## Projects (5/5): Presentations & demos
Friday 02/03/2018 16:15-18:15

## Online resources

Tableau

* [FAQ:  How to learn Tableau](https://community.tableau.com/thread/151389)
* [Build standard charts with Tableau](http://onlinehelp.tableau.com/current/pro/desktop/en-us/dataview_examples.html)

D3.js

* [Gallery of examples](https://github.com/d3/d3/wiki/gallery)

Git/GitHub

* Git and GitHub (e.g. [Try GitHub](https://try.github.io/levels/1/challenges/1))
* https://agripongit.vincenttunru.com/
* https://onlywei.github.io/explain-git-with-d3/#freeplay
* https://learngitbranching.js.org/

JavaScript

* Learn JavaScript (e.g. [learnxinyminutes](https://learnxinyminutes.com/docs/javascript/), [learnjsdata](http://learnjsdata.com/index.html))
* JSON (e.g. [learnxinyminutes](https://learnxinyminutes.com/docs/json/))

Data Visualization Classes

* http://dataviz.media.mit.edu/
* [Visual Analytics Ecole Centrale Paris](http://aviz.fr/wiki/pmwiki.php/TeachingVA2017/Schedule) 
* Dataviz resources http://www.cs.ubc.ca/group/infovis/resources.shtml

Blogs

* http://www.thefunctionalart.com/
* http://eagereyes.org/
* http://visualisingdata.com/

Graphics/Journals

* http://www.bloomberg.com/visual-data/
* http://data.huffingtonpost.com/
