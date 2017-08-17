Apolo   
=============================

Personal project

## CSS nameing convention 
I am using a combination of SCSS OOCSS and BEM. The file structure follows SCSS with additional files for utility classes and custom utility classes. 

BEM 
Block = header-position
Element header-postion__
Modifiyer  = header-position--

Be carefull with the use of the atomic selectors as they will apply to the global scope of the inital media quirey and will have to be overwritten 

The layout of the page has to be done in index.html. In the index.html file create place holders for the pug includes files. this is also where the reponsive flexbox action takes place. 

## How to develop a website with a templating lang 

The first step is to create the layout using index.html. Block out all the content to indicate where components will go and build the reponsive functionality. 


## Changing the width of the header. 

To change the width of the header you have to adjust the container in (layouts) _home-wrap.scss and in (3-includes)_header.scss. Adjust both the width and flex bassis, the Width is to reposition due to the fixed property. 

## @media 

```css

@media (min-width: 600px){ }

@media (min-width: 799px){ }

@media (min-width: 1049px){ }

@media (min-width: 1200px){ }


```