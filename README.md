Boxed-css-theme-for-reddit
==========================

A subreddit theme to be used by subreddit owners on www.reddit.com 

upload sprite-icon-16.png before saving the stylesheet.



# CSS basics
Before I start, I'll go into the css basics. The reason for this is simple, 99% of the people using a theme want to adjust it to their own needs. I am providing the theme and am more than willing to help out. **But** I am only willing to do so if you grasp the basics of CSS. Because it really isn't doable for me to explain the basics every single time and I don't have the time either to write the adjustments for every individual out there. With that out of the way, lets get started. 

In its core css is build up of two parts 

1. Selectors 
2. Properties inside those selector 

Whenever you see css the selector is the part before the curly bracket and its most simple form you can directly address html elements. To give you an example, to change something that affects all urls it would look like this 

    a {
         property: propertyvalue;
    }

This of course isn't that very useful if you want to change more specific elements. To target specific elements there are a whole host of options available but at its most basic you are looking at two kinds: 

1. IDs 
2. Classes  

IDs are supposed to be unique to one element and in css always start with #, in html you can also spot them rather easily 

    <a id="thisThing">I am an url!</a>

So in css you can do something like this 

    #thisThing {
         property: propertyvalue;
    }

And target that specific element with that ID. Sometimes someone messes up and you end up with two elements with the same ID, but if one is an url and the other is something else (a div for example) you can be more specific with 

    a#thisThing {
         property: propertyvalue;
    }

Classes are not unique to single elements but can be seen as a category of elements. They too are easy to spot in html

    <a class="theseThings">I am an url!</a>

And you target them with a dot like this 

    .theseThings {
         property: propertyvalue;
    }

or once again if you need the specific kind of element 

    a.theseThings {
         property: propertyvalue;
    }

You can read more about it here if you want: http://www.w3schools.com/css/css_syntax.asp 
CSS Cheat Sheet - Learn CSS(Basic to Advanced Concepts): https://www.interviewbit.com/css-cheat-sheet/
And this video nicely shows how you can use the chrome inspector tools (similar available in firefox) to try out and tweak css: 
https://www.youtube.com/watch?v=sdLxvD23uhY


# Installing the thing. 

1. go to the following address: https://github.com/creesch/Boxed-css-theme-for-reddit/blob/master/sprites-05.png
2. right click on the "raw" button and select "Download as" and save the image to a directory you will easily find again. Do NOT rename it. 
3. go to the following address: 
https://github.com/creesch/Boxed-css-theme-for-reddit/blob/master/boxed_base.css 
4. left click "raw" .
5. select the entire page/text and copy it. 
6. Go the your subreddit but add the following to address /about/stylesheet . So for http://www.reddit.com/r/boxed it would become http://www.reddit.com/r/boxed/about/stylesheet
7. Paste the text you just copied into the large text field. 
8. Don't click save yet! 
9. Under "images" select the browse button. This will open up a file selection dialog. 
10. Go to the directory where you saved sprites-05.png earlier, select the file and click "open". 
11. Make sure that in the "new image name" field it says "sprites-05" 
12. Click upload and wait until it says "saved" .
13. Click the "save" button under the big text field. 
14. Theme installed! 

In order to also get the announcement bar you have to do the following: 

1. Go to subreddit settings (about/edit/ so for boxed http://www.reddit.com/r/boxed/about/edit/)
2. Go to the text field with the "Sidebar" header. 
3. Enter something that looks like this: 

         ### My announcement text here 
4. Click "Save options" 
5. Done! Your subreddit is now styled with /r/boxed! 


