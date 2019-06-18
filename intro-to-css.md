## Introduction to cascading style sheets (CSS)
At this point, you probably have a site with random colors and no layout. Your content just goes straight down the page. Don't worry, it will get better. We just put random colors to as a fast way of letting us see where the divs are. You can do so much more to make your website look decent with css (Cascading Style Sheets). 

### How do HTML and CSS work together?
Like I mentioned earlier, you already put a little bit of css in your code by putting in the atrribute style= in your html tag. 

Let's look at an example: 
```html
<h1 style="color:blue">I love Pacman</h1>
```
This is called an "inline style" or "local style" because it is placed within the HTML. Although this does the job, if you are making a big site where you need consistency, this is an extremely inefficient way of writing your styles. Imagine that I had h1 tags throughout my page and in different pages throughout my website and I wanted them all blue. I would have to copy, paste ```style="color:blue"``` after every h1 tag. If you're doing mundane tasks like that in coding, you are not doing it right. We will get more efficient as the lesson goes on because we're working our way up to coding like the pros! 

### Doing it right: Ways to organize your CSS
* Internal style sheets
We are going to start with internal style sheets just so you can see the difference. Internal style sheet means that all your style code will be between ```<style></style>``` tags inside the ```<head></head>``` tags. Like this: 

```html
<!DOCTYPE html>
<html>
   <head>
      <title>
       Pacman Tribute
      </title>
      <style>
        h1 {
          color:blue;
        }
      </style>
   </head>
   <body>
```

* External Style sheets 
Later, we will move all our styles to an external style sheet and link it to the html file. We will code like this from now on because it's cleaner. 

### How to spot/write CSS: Syntax, code structure, comments
It's helpful to know what the different parts of the css code is called because it helps with searching when you are trying to do more complex things later on. The Internet is your friend. But a lot of the times, you can't find what you need because you don't know how to search. 

```css
h1 /*Selector*/ {
  /*Your styles go inside of the curly braces*/
 color: blue; /*property:value;*/
}
```
One the code above, we are doing a lot of different things. We have our code for the h1 tage styles and we wrote the different parts of the css code in comments. We mentioned comments in html. There are comments for every language and they all serve the same purpose. In css, you have to open comments with /* and close them with */. 

<b>Parts of css</b> 
1. Selector- The selector is the part that tells the css what to style. This selector is selecting the element h1 in the html to style. The selector must be written into the html in order for this to work. 
2. { - Open curly brace, this is the start of the style code. 
3. Property- This is how you want the selector to change. A property can be color, font, rotation, border, etc. It's any design element you want to add to your selector. 
4. : - Colon, this comes after the property. 
5. Value - This is the specifics about how you want the property to change. This can be in the form of font names, color names, and numbers. 
6. ; - Semi-colon, goes at the end of every property:value pair. 
7. } - Closing curly brace, end of style code for the selector. 

```
selector {
 property:value;
 property:value;
}
```
This is the basic structure and syntax of css. Somewhere along the way, we will run into new little things like how to reference specific types of selectors and making variables- for now this is it. 

### Check if styles are working 
Delete the style attribute from your h1 tag so that your code looks like this: 
```<h1>I love Pacman</h1>```
Because of your internal style sheet, it will still be blue! Now, put a different title with an h1 tag on your site. All h1 tags will now be blue! 

## Using External Style Sheets


### Link to your sheet in HTML
### Classes, IDs, Elements
*Color on the Web*
 Constructing CSS selectors
 Interesting...
 https://www.geeksforgeeks.org/css-attribute-selector/

# Working with images
## CSS pseudoclasses
# Text and link color

