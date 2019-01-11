# Interactive Data Visualization (ECL MOS 5.5)

[Romain Vuillemot](http://www.ec-lyon.fr/contacts/romain-vuillemot), *LIRIS, École Centrale de Lyon/Département Math-Info*, [Website](http://romain.vuillemot.net/),  [Twitter](https://twitter.com/romsson).

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

Other books

* [Visualization Analysis and Design](https://www.cs.ubc.ca/~tmm/vadbook/) by Tamara Munzner
* [Design for Information](http://isabelmeirelles.com/book-design-for-information/) by Isabel Meirelles
* [Making Data Visual: A Practical Guide to Using Visualization for Insight](http://shop.oreilly.com/product/0636920041320.do) by Danyel Fisher & Miriah Meyer

## Grading

* 30% Final exam
* 60% Final projects
* 10% Homeworks/Submitted assignments (pass/fail policy)
* 10% Bonus (class participation, best homeworks/assignments)

---
## Submissions

All homeworks/assignements/reports are due the day before the class at 23.59pm Lyon Time (GMT+1). Using [this document](https://docs.google.com/spreadsheets/d/15R4NmF-Ript1vW8m15fs0rmOV2ag85M30gkaBQx0uy4/edit#gid=0).
---

## **Lecture 1 - Introduction to Data Visualization** 
*Friday 11/01/2019 13:30-15:30*

* Overview: Class organization, learning paths ([slides](https://docs.google.com/presentation/d/1YaPshJZLDj6M0XBMtmHqANeH17JINdB3Ie5G8RdC74U/edit#slide=id.p))
* Basics of Data Visualization: Perception, cognition, Visual mapping, Standard charts ([slides](https://docs.google.com/presentation/d/1YY8h1wjfaAv172LVa8kVAnxCyEB547HRL43JlEOvCH0/edit#slide=id.p))
* Authoring visualizations: Libraries, Tools, Tableau Software ([slides](https://docs.google.com/presentation/d/18b-B9wAYpq93nbROxRe9u6-7xexuBLM7T-yapqGoYdo/edit#slide=id.g2f7ee94efd_0_45))

## **Tutorial 1 - Tableau Software**
*Friday 11/01/2019 15:45-17:45*

*Tableau Tutorial* 

1. The goal is to have a first experience with Tableau and build standard charts using a simple dataset.
2. Download and install [Tableau Public](https://public.tableau.com/) (Free) on your machine
3. (Simple) alternative to Tableau: [Polestar](http://vega.github.io/polestar/)

*Iris flowers visualization*

1. Download the [`iris.csv`](data/iris.csv) and load it in Tableau; convert data types (if needed)
2. Plot a **scatterplot** with X:sepal_length, Y:sepal_width, color:species and a trend line 
3. Save as a tab and save the workbook

*Elections map*

1. Download the [`us-elections-history.csv`](data/us-elections-history.csv) and load it in Tableau; convert data types (if needed)
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

*Global Superstore Dataset*

1. Download the [`us-elections-history.csv`](data/Global Superstore Orders 2016.xlsx) and load it in Tableau; join datasets (if needed)


📅 **For next class (20/01)**

✍ Assignments

* Submit your Tableau workbook on Global Superstore dataset
* Propose a project topic (2-page): what is the question you want to answer? which data do you need? how do you plan to collect your data? what are the main risk in collecting/visualizing it? what are the privacy/ethical issues?
* Create a GitHub account and learn how to use it (bottom of the page)

📖 Readings

* Interactive Data Visualization for the Web [Chapter 1. Introduction
](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch01.html), [Chapter 2. Introducing D3](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch02.html) and [Chapter 3. Technology Fundamentals](https://web.archive.org/web/20160307043159/http://chimera.labs.oreilly.com/books/1230000000345/ch03.html)

* JavaScript Tutorials

* [Inside look at modern web browser](https://developers.google.com/web/updates/2018/09/inside-browser-part1)

## **Lecture 2 - Introduction to D3.js** 
*Friday 18/01/2019 13:30-15:30*

## **Tutorial 2: D3.js** 
*Friday 18/01/2019 15:45-17:45*

## **Lecture 3 - Advanced D3.js and Design Methods**
*Friday 25/01/2019 13:30-15:30*

## Tutorial 3: Design Methods & more D3.js 
*Friday 25/01/2019 15:45-17:45*

## Lecture 4 - Advanced Design Method and Reseach in DataViz
*Friday 01/02/2019 13:30-15:30*

## Tutorial (1/2): Advanced layouts in D3.js
*Friday 01/02/2019 15:45-17:45*

## Tutorial (2/2): Advanced layouts in D3.js
*Friday 08/02/2019 13:30-15:30*

## Projects (1/5)
*Friday 08/02/2019 15:45-17:45*

## Projects (2/5)
*Friday 15/02/2019 13:30-15:30*

## Projects (3/5)
*Friday 15/02/2019 15:45-17:45*

## Projects (autonomie)
*Friday 01/03/2019 13:30-15:30*

## Projects (autonomie)
*Friday 01/03/2019 15:45-17:45*

## Projects (4/5): Final projects presentations & demos
*Friday 08/03/2019 13:30-15:30*

## Projects (5/5): Final projects presentations & demos
*Friday 08/03/2019 15:45-17:45*


## Exam
*TBD*

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


