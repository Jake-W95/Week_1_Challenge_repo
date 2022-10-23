# Week 1 Refactor Challenge

## Refactoring an existing webpage to improve accessibility and streamline code of both the HTML and CSS.

CONTENTS TABLE WITH LINKS

## The motivation for this project was as follows:
- Use my knowledge of HTML and CSS language to improve and streamline the base code whilst keeping the website functional and identicle to the end user.
- Edit the html code in a way as to improve the page's accessibility to those with visual or aural impairmants.

## My actions
The changes I have made to both the HTML and the CSS files have cut a great deal of unnecessary code, making it easier and quicker to comprehend what is being done within the code itself.
For example, many elements within the index were in seperate classes but having the same CSS attributes, so removing the classes and creating a selector path to those elements uses far less code and makes the CSS easier to understand:

**Note that images to the left are my updated code and images on the right are the original code!**
![CSS Benefits Comparison](/assets/screenshots/CSS_comparison%20_benefits_img.png "CSS Comparison Benefits Images")
### See here that I merged three seperate but identical CSS selectors into one selector. ###

![HTML Navigation Comparison](/assets/screenshots/HTML_Comparison_Nav.png "Comparison of *nav* areas")
### See here that the *div* *ul* and *li* elements were unnecessary, being replaced with just a *nav* element. ###

By adding semantic elements to the index I'm ensuring that the browser will recognise the function of each element and its contents, allowing for that information to be conveyed to the end user, should it be necessary.
This also negates many *div* elements that could be removed, tidying the code further

![HTML Semantics](/assets/screenshots/HTML_Semantics.png "Some of the semantic elements added")
### Above we see **some** of the semantic elements I added, in the original code these were all *div* elements with *class* attributes. ###
Not only does using semantic elements save time and space, it also allows the browser to identify the content, making the site more user-friendly and accessible (*element* openings are in purple and closings in orange).


![CSS Layouts](/assets/screenshots/CSS_Comparison_Layout.png "Comparison in the layout of the original code and my refactored code")
### By re-ordering and classifying selectors in the CSS I have made it incredibly easy to find specific elements, should they need editing in the future. ###
By adding a comment to the CSS I was able to label the groups of selectors together in a way that is instantly recognizeable.
See above that the original code is much longer than my refactored code (shown by the white and yellow lines). After collapsing the *selectors* my code sits comfortably on one screen, the original code is almost twice as long, achieving the same results.

## What I learned
- In working on this project I have realised the importance of semantic elements when creating a webpage; They clearly communicate the purpose of the content within the element to the browser, which can be invaluable to differently abled users.
- I learned the functions of many semantic elements myself and can now use them appropriately and with confidence in my own projects.
- I learned the importance of concise lines of code. keeping the functions clearly understandable to anyone who is working on any given project.


