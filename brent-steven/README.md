# Project Name

**Author**: Brent Williams, Steve Starwalt
**Version**: 1.0.0 

## Overview
Build a web page that will to be able to filter articles so that the user can selectively view articles by author or by category, preview each article so that the user can easily view the results and select the one they want to read further.
In addition the site needs tab-based navigation so that the user can easily visit other sections of the site.
Finally, I want my code to be thoughtfully organized, easy to read, and executing efficiently.


## Getting Started
If you wish to build this site you will need to organized your HTML to be able to be populated by JWQuery and use a SMACSS style CSS.  Your JS files need will to use JQuery for accessing the DOM and you will need to have the blog articles formatted with the proper HTML elements in the body so they will display correctly. Finally you will need to understand evemt listners and how to use them on multiple parts of your DOM.

## Architecture
First we used a starter code from Allie that had the HTML formated in a simple matter so the details of the page were made with the JS files using JQuery.  The CSS uses a SMACSS format. The articles are displayed by using JQuery to acess and modify the DOM and insert the content which is stored in a serperate js file.  Each article is truncated with by a JQuery .hide and be be fullassesed using an event listner atached the the article tht will invove a function to display the entire article.  Finally, the tabs will hide all the elements in the main section of the DOM and only diplay the information associated with the tab selected.     

## Change Log
0900 - 09030 reviewed existing code
0930 - 0945 TODO on HTML and article.js
0945 - 1030 TODO made filters work on articleView.js
1030 - swapped navigator driver
1100 - got the main nave working
1150 - got the teasers working


## Credits and Collaborations
Allie Grampa provided the starter code.  We used the oscarotero.com JQuery cheat sheet which is linkewd to JQuery.com. We used some of the cose from the demo to help solve some problems as well.  Finally MDN was used as a reference throughout.
-->