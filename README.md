# 01 HTML, CSS, and Git: Code Refactor - John Mabie

In order to do this challenge, I had to take apart the original index and CSS, step by step.
First issue I ran into was not being able to get the first "div" under "header" to retain the same styling when switching the name to nav and applying the ".header nav", ".header nav ul", ".header nav li" to the CSS. Unsure as to exactly how I could have done this to clarify the "nav" separation rather than leaving it as a "div".
Kept the original CSS styling and the initial "div" break for the navigation hyperlinks at the top of the page.

Kept the "Hero", "Content", and "Benefits" CSS styling and HTML.
However, in order to improve the legibility of the semantic HTML, I reduced the number of "div" separations by utilizing "header", "section", "article", "aside" and "footer" instead. This way, it is clear what each separation is doing within the index, and it allowed for some serious condensing of CSS styling by using these greater classes to apply style once rather than having sequences of 3 identical styling classes for each h2/h3 in a "div" and each img in a "div". This condensed the CSS by about 60 lines of redundant styling.

Added the "ID" identicator to the first of the articles in order to make the navigation hyperlinks work across the board. Also added a consise "Horiseon Website" title to the page.

Added comments/notes to every major change I made to the HTML, as well as to the CSS, to make sure anyone reviewing the code and the styling could understand what I was doing

Added alt descriptions to all section images, shy of the main background image in the ".hero" class. Not sure where I would have added an alt description to that image when there wasn't an "img=" in the HTML where I could add an "alt=" to go along with it. I tried a couple things to try and integrate the background image in the ".hero" class directly into the HTML instead of by way of the CSS, but they weren't working as intended.

A screenshot of how the HTML index was showing in Google Chrome can be found at the following location:
![Screenshot of My Horiseon Website](assets/screenshot-for-12-8-22-homework-challenge.png)

A link to the deployed application can be found below:
https://jmabie94.github.io/12-8-22-Homework-Challenge/

