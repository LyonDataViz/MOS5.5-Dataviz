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
      <a href="https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345">Interactive Data Visualization for the Web</a><br>by Scott Murray
    </td>
  </tr>
</table>

## Grading

* 30% Final exam
* 60% Final projects
* 10% Homeworks/Submitted assignments (pass/fail policy)
* 10% Bonus (class participation, best homeworks/assignments)
 
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
](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch01.html), [Chapter 2. Introducing D3](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch02.html) and [Chapter 3. Technology Fundamentals](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch03.html)
* Create a GitHub account and learn how to use it (bottom of the page)
* Pick a chart type [in this document](https://docs.google.com/spreadsheets/d/15R4NmF-Ript1vW8m15fs0rmOV2ag85M30gkaBQx0uy4/edit#gid=0), and find online:
  * Historical examples, recent and/or most famous ones for your category
  * Comments: what you like or not in it (design critic like in class), possible visual variations, different names, different look and feel, tools used to create it, .. Minimul 10 charts with detailed analysis, but you are welcome to add more examples.
  * Document your sources; **always** give credits (e.g. link to orginal image, article and authors)
  * Create a github page and write your summary as a `Readme.md` document, put images in a `/img/` folder. Add classic elements in your summary such as your name, etc.. and also the chart type you picked.
  * Add the link to your summary [in this document](https://docs.google.com/spreadsheets/d/15R4NmF-Ript1vW8m15fs0rmOV2ag85M30gkaBQx0uy4/edit#gid=0) **before Thursday 18/01/2018 12h00 Lyon Time**

## **Lecture 2 - Introduction to D3.js** 

<small>Friday 19/01/2018 13:30-15:30</small>

* Introduction to projects ([slides](https://docs.google.com/presentation/d/1r96OLz_yDkkAsq6segP360Vnr_PJrboO5XEJb0lHgw4/edit?usp=sharing))
* Feedback/discussion from homework #1
* Advanced data visualization concepts: Animation, Interaction, Multiple Views ([slides](https://docs.google.com/presentation/d/1g2ZT3LHUnCSmEUIrxow_4APTlnuiMGgID8XxMyt8mz4/edit#slide=id.p))
* D3.js: Principles, Codes, Web Development ([slides](https://docs.google.com/presentation/d/1BtnZZoSmrafigZLbsFqPGwBlhPZHee19SJpUtcHKuCU/edit#slide=id.p))

## **Tutorial 2: D3.js** 
Friday 19/01/2018	16:15-18:15

We will use Block Builder http://blockbuilder.org/ (requires a GitHub account to save code, but no local install)

* Let's build a [bar chart using SVG only](http://blockbuilder.org/romsson/36b1cdc599e8f341a33892f143cf087f) (without D3)
* Let's build a [bar chart with D3 *without* data binding](http://blockbuilder.org/romsson/f865e7c5c05c805759486a3cf435a548)
* Let's build a [bar chart with D3 *using* data binding](http://blockbuilder.org/romsson/e7aeedeb03300f4cdfd54531e33e9b68)
* Let's build an interactive bar chart
* Let's build an interactive bar chart using a dataset
* Let's build an [interactive line chart using a dataset](http://bl.ocks.org/romsson/4fab85668c5cbed4fe0c070fa56d7a77)

* Class example of [combining rects and circles and interaction](http://blockbuilder.org/romsson/0eaefaea7d95e302c5d7aafbd63813f6)

📅 **For next class (26/01)**

* Build a scatterplot using the [`iris.csv`](data/iris.csv) dataset and Block Builder ([submission form](https://goo.gl/forms/1X6Gdt4CCuSxNlFl2)) using a [different symbol](https://bl.ocks.org/mbostock/6d9d75ee13abbcfea6e0) for each species; and a [regression line](https://bl.ocks.org/ctufts/298bfe4b11989960eeeecc9394e9f118). **Submit before Friday 26/01/2018 13h59 Lyon Time** ([solution](http://blockbuilder.org/romsson/5c6d0c7d20ed65798ff42e792204a7e9))
* BONUS: build a scatterplot *matrix* 
* BONUS: add a histogram in the matrix diagonal showing distribution for each dimension 
* BONUS: add interaction: brushing on scatterplot, selection on histogram (or brushing too) 
* Reading: [Chapter 4. Setup](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch04.html), [Chapter 5. Data](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch05.html), [Chapter 6. Drawing with Data](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch06.html), [Chapter 7. Scales](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch07.html).
* Project teams, datasets and projects descriptions proposal [in this document](https://docs.google.com/spreadsheets/d/15R4NmF-Ript1vW8m15fs0rmOV2ag85M30gkaBQx0uy4/edit#gid=637889820)
  * Project ID (e.g. TennisVis) + link to GitHub repository (using this ID)
  * Project full name, project description and members names
  * Data you plan to use, does it exist, if not how you collect it?
  * 3-5 questions you want to answer using your project
  * **Wait for validation by instructor before any coding**

## **Lecture 3 - Advanced D3.js and Design Methods**
Friday 26/01/2018 13:30-15:30

* Advanced D3.js: complex layouts, coordinated chart, animated transitions ([slides](https://docs.google.com/presentation/d/14pYKK2dYGnPS6iZ9l1gw1vuiPOGXjjCfeJlArMYRLBs/edit#slide=id.p))

* Sketching, Rapid Prototyping, Development cycles ([slides](https://docs.google.com/presentation/d/11kEkZK12C893qzyEDvkIjgFKPmRKFf-KDDOKiwGw6ys/edit#slide=id.p)) and using the [Five Design Sheet](http://fds.design/) methodology

## Tutorial 3: Design & more D3.js 
Friday 26/01/2018 16:15-18:15

* Class exercises:
  * Filter this [line chart](http://blockbuilder.org/romsson/57eb273e01761b829aaa95b28c8193c1) with click on legend ([solution for scatterplot](http://blockbuilder.org/romsson/e390441cd93082cc9cc159590977114a))
  * Build multiple, coordinated scatterplot using the [`iris.csv`](data/iris.csv) dataset ([solutions](http://blockbuilder.org/romsson/62e8a09545b701f813488021c74bc915))
  * Build[grouped bar chart](http://blockbuilder.org/romsson/2f94c1913b81f7fd20c530236934433a) and a [stacked bar chart](http://blockbuilder.org/romsson/8aea86fddcf01380eb96a341509f394f) using the [`stocks.csv`](data/stocks.csv) market data; and add an animated transition between both.

* Projects proposal discussion (group by group) & validation by instructor

📅 **For next class (02/02)**

* Add another transition to the grouped/bar chart example. Choose which one you think is relevant (e.g. better staggering, a third chart, use of color/opacity, etc.). Submit it as block **making sure it is a secrete block!** (submission link) **Submit before Friday 26/01/2018 13h59 Lyon Time** ([solution](http://blockbuilder.org/romsson/5c6d0c7d20ed65798ff42e792204a7e9))

* Each team submits their project design proposition ([submission link](https://docs.google.com/forms/d/1i7D3sgpdmUBd37PGg2y3JZwTYkpYXD5eqjlXq2V0xFw/edit))
  * Create a repository with projet ID
  * `README.MD` file that is a summary of the project
  * `PROPOSAL.MD` that is the project proposal that includes pictures `img/` of the 5-design sheets
  * `DATA.MD` that contains the list of data sources, samples of datasets, data model, data pre-processing methods `data/`
  * `index.html` that is a hello world of your project
  * Add URL to the hello world [in this document](https://docs.google.com/spreadsheets/d/15R4NmF-Ript1vW8m15fs0rmOV2ag85M30gkaBQx0uy4/edit#gid=637889820)

* Reading: [Chapter 8. Axes](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch08.html), [Chapter 9. Updates, Transitions, and Motion
](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch09.html), [Chapter 10. Interactivity](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch10.html), [Chapter 11. Layouts](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch11.html).

## Lecture 4 - Advanced Design and Reseach 
Friday 02/02/2018 13:30-15:30

* Feedback and solution from previous homework 3
* Complex data types, data structures ([slides](https://docs.google.com/presentation/d/1a79MLat-ftU25Uk7uM2JYfDSlKS-9hp94EnmegvcLg0/edit#slide=id.g327e636b06_0_540))
* Exercise: [build a geo-map](https://lyondataviz.github.io/teaching/lyon1-m2/2017/tp4.html) ([credits](http://www.tabard.fr/))

## Tutorial (1/2): Advanced layouts in D3.js
Friday 02/02/2018 16:15-18:15

* Modern web development tools: local server, package managers ([slides](https://docs.google.com/presentation/d/1Uz3ZjX1f9DJgH73VOrJwi7cgVqwlKIwFPmM4eubUIb8/edit#slide=id.g32bdb64449_0_18))
* Introduction to [data cleaning tools and methods](http://romain.vuillemot.net/publis/slides-daquata-workshop-data-cleaning-dataviz.pdf)
* Feedback on projects, work on data cleaning and structure

📅 **For next class (09/02)**

* Submit the link to the GitHub repository you have created during the class and which contains your geo-map ([submission link](https://docs.google.com/forms/d/1i7D3sgpdmUBd37PGg2y3JZwTYkpYXD5eqjlXq2V0xFw/edit)). Link should [look like this one](https://romsson.github.io/boilerplate-d3-chart/chart2.html).
* Each project does a peer review of another groups' projects proposal (pick the one below you in [this document](https://docs.google.com/spreadsheets/d/15R4NmF-Ript1vW8m15fs0rmOV2ag85M30gkaBQx0uy4/edit#gid=1407328880)) and write your review as a `REVIEW.MD`  file in your project repository **before Friday 09/02/2018 12h00 Lyon Time**
* Each project write details on their dataset in their repository:
  * `DATA.MD` lists all the datasources and details (e.g. volume of the data, how the dataset was created, copyright, etc.)
  * `PROCESSING.MD` describes the cleaning and preparation process to clean and shape your date
  * create a `index.html` that loads in d3 (e.g. `d3.csv`, ..) a first dataset (or sample of the dataset or an exepected dataset you create yourself). This will push you to have a first 

## Tutorial (2/2): Advanced layouts in D3.js
Friday 09/02/2018 13:30-15:30 

* Brief intro to D3 and Canvas ([example](https://bl.ocks.org/mbostock/31ce330646fa8bcb7289ff3b97aab3f5))
* Class exercises: fork [this repository](https://github.com/LyonDataViz/MOS5.5-Dataviz) and focus on the sub-folder `tp-node-links` and the file `index.html`. The current version separates nodes in three random groups and highlight closest node to the mouse pointer. Add the following:
  - Group nodes by their group attribute (`d.group`).
  - Organize groups as a 2D grid ([example](http://blockbuilder.org/romsson/ba9181f7de7715022e166d3227087951)) by adding a `y` scale.
  - Link nodes nodes using `<line>` element ([example](https://bl.ocks.org/mbostock/4062045)) by adding data to the `graph.links` array. Look at the links drawing function for the expected data structure.
  - Highlight links connected to the current node, and the target nodes.
  - Adjust the `d3-force` parameters ([documentation](https://github.com/d3/d3-force/blob/master/README.md)) ([example](https://bl.ocks.org/mbostock/6526445e2b44303eebf21da3b6627320)).
  - BONUS
    - Load [The Miserable dataset](https://bl.ocks.org/mbostock/4062045) instead of fake data
    - Group nodes by binning them using the `d3.histogram()` function


* Feedback on projets proposals & reviews


## Projects (1/5)
Friday 09/02/2018 16:15-18:15

* Work on projects

📅 **For next class (16/02)**

* Submit the link your graph ([submission link](https://docs.google.com/forms/d/1i7D3sgpdmUBd37PGg2y3JZwTYkpYXD5eqjlXq2V0xFw/edit))
* Keep working on the project
  -  

## Projects (2/5)
Friday 16/02/2018 13:30-15:30

* Work on projects

## Projects (3/5)
Friday 16/02/2018 16:15-18:15

* Work on projects

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
* [Code examples and references for the course "D3.js in Motion"](https://github.com/curran/d3-in-motion)
* [Relearning D3.js](http://www.cagrimmett.com/til/2016/08/07/relearning-d3.html)
* [D3 in depth](http://d3indepth.com/)
* [Awesome D3](https://github.com/wbkd/awesome-d3)
* http://vadim.ogievetsky.com/IntroD3/#1
* https://github.com/arnicas/d3-faq
* [Changes in D3 4.0](https://github.com/d3/d3/blob/master/CHANGES.md)
* [D3 V4 - What's new?](https://iros.github.io/d3-v4-whats-new/#1)
* [Wide vs. Long Data in D3](http://jonathansoma.com/tutorials/d3/wide-vs-long-data/)

SVG 

* [SVG2D3](http://billautomata.github.io/svg2d3/)

Git/GitHub

* Git and GitHub (e.g. [Try GitHub](https://try.github.io/levels/1/challenges/1))
* https://agripongit.vincenttunru.com/
* https://onlywei.github.io/explain-git-with-d3/#freeplay
* https://learngitbranching.js.org/

JavaScript

* [Mozilla Developers Network's Javascript reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* Learn JavaScript (e.g. [learnxinyminutes](https://learnxinyminutes.com/docs/javascript/), [learnjsdata](http://learnjsdata.com/index.html))
* JSON (e.g. [learnxinyminutes](https://learnxinyminutes.com/docs/json/))
* [Eloquent JavaScript](http://eloquentjavascript.net/Eloquent_JavaScript.pdf)
* (Notes on Douglas Crockford's Javascript the Good Parts 🚀
)[https://github.com/iteles/Javascript-the-Good-Parts-notes]

Data Visualization Classes

* http://dataviz.media.mit.edu/
* [Visual Analytics Ecole Centrale Paris](http://aviz.fr/wiki/pmwiki.php/TeachingVA2017/Schedule) 
* Dataviz resources http://www.cs.ubc.ca/group/infovis/resources.shtml
* https://curran.github.io/dataviz-course-archive/
* https://github.com/Ecohen4/data-viz
* https://github.com/arnicas/interactive-vis-course

Blogs

* http://www.thefunctionalart.com/
* http://eagereyes.org/
* http://visualisingdata.com/

Graphics/Journals

* http://www.bloomberg.com/visual-data/
* http://data.huffingtonpost.com/

Misc

* [Command line tutorial](https://www.learnenough.com/command-line-tutorial)
* https://egghead.io/lessons/debugging-with-dev-tools
* Design essay: [Picturing the Great Migration](https://medium.com/info-we-trust/picturing-the-great-migration-9e4b5a3eca8a)


