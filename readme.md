### Project: **Personal Website**
#### Author: **Christopher Huber**

### Github page: https://chuber42.github.io/portfolio/
#### Github repo: You're standing on it.
##### Copyright Christopher Huber 2020

&nbsp;
     
&nbsp;
     
         
##### Components: 
This website was built using HTML 5.0 and CSS + Bootstrap. 
No special files should be necessary to load this file, all
dependencies are bundled.
##### **Warning: some CSS/Bootstrap clauses may not be supported by IE8 or below!**

##### File layout:
Files are written out - essentially - in the order in which the visual elements occur.
The first div family encountered will be the side bar, after which the main container for the remainder of the page is initialized.
Within the container (the entirety of the page besides the left sidebar) elements are listed in visual order:
Top/Title bar Div   
Spacer Bar Div   
Main component Div   
Child-of-main-component divs
bottom bar/copyright div.

This behavior holds for the styles.css rules as well; Global rules are published first (html and body), followed by sidebar, and then   
other components in top-->bottom visual order as they would be encountered on the page. I have tried to keep styles-families close to  
  each other, but cascading, inheritance, and forks (ex: .project-box and .main-text occupy the same visual space on different pages)
make this difficult to guarantee.

##### _Contact_:

CHuber42.Gmail.com
