```sql
SELECT  /* select property , selects a column , when sitted to (*) it means all */
FROM /* from a table name */

/* conditions ******* conditions */
WHERE column_name < 1; /* less than 1 */
WHERE column_name = 'good'; /* value of good */
WHERE age BETWEEN 9 AND 10; /* numeric between */
WHERE name_list LIKE 'a%'; /* a% means anything starts with a */
WHERE name_list LIKE '%a'; /* %a means anything ends with a */
WHERE name_list LIKE '%a%';/* %a% means anything has a in it's name */
ON table1.id = table2.id;

/* SQL JOINS ************** SQL JOINS */
SELECT table1 AS T1
INNER JOIN table2 AS T2
ON T1.id = T2.id;

/* BASIC SYNTAX **** BASIC SYNTAX */
SELECT * FROM love WHERE loved_people LIKE 'mo%' OR LIKE 'mu%' OR LIKE 'ma%';




```

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="description" content="freeCodeCamp Accessibility Quiz practice project" />
    <title>Accessibility Quiz</title>
    <link rel="stylesheet" href="styles.css" type="styles.css" />
  </head>

  <body>
    <header>
        <!-- Header , title and navigation bar -->
        <nav></nav>
    </header>

    <main>
      <!-- Main content bro -->
      <form action="" method="post" > <!-- Form action to a weburl , and here is a post request -->

        <section role="region" aria-labelledby=""> <!-- Role must have an aria-labelledby --> 


        </section>          
        <select required> <!-- Dropdown select -->
          <option value="" selected>Select an Option</option>
          <option></option>
          <option></option>

        </select>
        <textarea placeholder="good" rows="30" cols="20">
          <!-- Text area with rows and columns -->
          </textarea>
      </form>

    </main>
    
    
    
    <footer> <!-- fOOTer , it's descriptive  -->
      <address> <!-- Contact Information -->
          <br /> <!-- break line -->
      </address>
    </footer>

  </body>


</html>

<!-- Tables -->
<table>
  <caption>Table's caption</caption>
  
  <thead>
    <tr>
      <td>table cell or element</td>
      <td> another table cell </td>
      <th>A header cell</th>

    </tr>
  </thead>

  <tbody>


  </tbody>

  <tfoot>

  </tfoot>
</table>

```
/* HTML Famous attributes ***************** HTML Famous attributes */
```HTML
  <i  lang="" role="" cols="" rows="" href="" rel="" type="" content="" value="" name="" id="" class="" aria-hidden="true-false" colspan="" rowspan="" width="" height="" border="" ><i>
```

```css
/* CSS FUNCTIONS ********* CSS FUNCTIONS */
.class{
  padding: calc(1.25rem+2px);
  !important /* overwrite anything with !important  to make it const*/
  /* Gradient Applied in CSS background property */
  gradient-type(
  color1,
  color2
  );
}

```
```css
/* variables *** variables */
:root{ /* the root cascade */
  --variable-name: value;
  background: var(--variable-name , fallback-value);
}


```



```css
.style , .yea{
  text-align: center; /* to align the text to the center , or the left , or the right*/
  background-color: rgb(0-255,0-255,0-255); /* to set a background color */
  background-image: url(https://google.com/); /* to set a background-img */
  aspect-ratio: 35/4; /* the aspect-ratio of svg lol */
  opacity: 0-1; /* the transparent from 0 to 1 */
  color: red; /* to set the font color */
  font-family: monospace; /* to set the font */
  font-style: italic; /* set font style to italic */
  font-size: 20px; /* adjust the font size */
  margin: 20px; /* margin is spaces in CSS */
  margin-left: auto; /* to always fix the margin from the left */
  margin-right: auto;  /* to always fix the margin from the right */
  margin-top: auto; /* margin top */
  margin-bottom: auto; /* margin bottom */
  width: 20%; /* 20% it was gonna be 20% of the width of it's parent tag */
  max-width: 500px; /* to add a max width to prevent making big wide screen */
  height: 20px; /* create a height or fix the height to 20px */
  display: inline-block; /* to make the block in the same line lol */
  padding-left: 20px;/* to add some spaces between objects {20px} */
  padding-right: 20px; /* spaces between objects {20px} */
  padding-top: 20px;
  padding-bottom: 20px;
  padding: 20px; /* to make the left-right-top-bottom all 20px */
  border-color: brown; /*  to change the border color */
  border-width: 20px; /* to change the border width */
  border-height: 20px; /* to change the border height */
  list-style: none; /* remove the list styling , easy peasy */
  
}
/* pseudo-selectors *********** pseudo-selector */
a:visited{ } /* Anchor link , when it's visited */
a:hover{ } /* Anchor Link , When you hover on it */
a:active{ } /* Anchor Link , While clicking */
a:not(.class); /* Anchors that aren't targeted by this .class class */
/* pseudo-element ******************* pseudo-elements */
p::before{ content: "Text #"; } /* before the p put those content */
p::after{content: "Text after lol";} /* after this p put those text */
 
 
 /* Hacks and stuff ******* Hacks and stuff */
 /* text and the background of a heading should be at least 4.5:1 */
 /* this is basically the same things */
 nav > ul > li{


 }
 
 nav li{


 }
 
/* positions ********** positions */
.class{
  position: static; /* normal default shit */
  position: relative; /* just like static but can use top and bottom , right and left */
  position: absolute; /* start from the beggining point 0 of the page if parent was static*/
  position: fixed; /* start from the fking beggining point 0 an it's ignoring anyone */
  position: sticky; /* it loves you , won't leave you , she's humble */
  top: 50%;
  bottom: 50%;
  left: 50%;
  right: 50%;
  caption-side: ; /* position table caption */

}


 /* Colors ********************* Colors */

background-color: rgb();
background-color: #000000;
background-color: hsl(0-360,0-100%,0-100%) 
/* 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness. */

/* Progress till 2022/5/26 */ All basic CSS has been finished */
.style , .yea{
  text-align: center; /* to align the text to the center , or the left , or the right*/
  background-color: rgb(0-255,0-255,0-255); /* to set a background color */
  background-image: url(https://google.com/); /* to set a background-img */ 
  opacity: 0-1; /* the transparent from 0 to 1 */
  color: red; /* to set the font color */
  font-family: monospace; /* to set the font */
  font-style: italic; /* set font style to italic */
  font-size: 20px; /* adjust the font size */
  font-weight: bold; /* or 300 to 1000 */
  margin: 20px; /* margin is spaces in CSS */
  margin-left: auto; /* to always fix the margin from the left */
  margin-right: auto;  /* to always fix the margin from the right */
  margin-top: auto; /* margin top */
  margin-bottom: auto; /* margin bottom */
  width: 20%; /* 20% it was gonna be 20% of the width of it's parent tag */
  max-width: 500px; /* to add a max width to prevent making big wide screen */
  height: 20px; /* create a height or fix the height to 20px */
  display: inline-block; /* to make the block in the same line lol */
  padding-left: 20px;/* to add some spaces between objects {20px} */
  padding-right: 20px; /* spaces between objects {20px} */
  padding-top: 20px;
  padding-bottom: 20px;
  padding: 20px; /* to make the left-right-top-bottom all 20px */
  border-color: brown; /*  to change the border color */
  border-width: 20px; /* to change the border width */
}
/* pseudo-selectors *********** pseudo-selector */
a:visited{ } /* Anchor link , when it's visited */
a:hover{ } /* Anchor Link , When you hover on it */
a:active{ } /* Anchor Link , While clicking */
a:not(#example){ } /* select all elements without the id #example */
element[class~="something"] { color: red; } /* select all something class in element */


/* access key *********** access key */
``
<element accesskey="s" /> /* when clicked s it is gonna go to the section that has accesskey="s"; */

``
/* Media *********** Media */
@media (max-width: 199px) {#id{someting: 10px;}}
@media (prefers-reduced-motion: no-preference){ scroll-behavior: smooth; }

/* Colors ********************* Colors */

background-color: rgb();
background-color: #000000;
background-color: hsl(0-360,0-100%,0-100%); 
/* 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness. */
background: linear-gradient(blue , red);

/* Progress till 2022/5/26 All basic CSS has been finished */


```css
.additional_classes{
  border-left-width: 10px; /* to change the width of the left border */
  border-right-width: 10px;
  border-top-width: 10px;
  border-bottom-width: 10px;
  border-width: 10px; /* sets all left,right,top,bottom width at the same time */
  border-left-style: solid;
  border-right-style: solid;
  border-top-style: solid;
  border-bottom-style: solid;
  border-style: solid;
  border-left-color: black;
  border-right-color: black;
  border-top-color: black;
  border-bottom-color: black;
  border-color: black;
  vertical-align: middle - top;
  scroll-behavior: smooth; /* adjust the scrolling behavior to be smooth and amazing */
  


}
.Additional_Colors{
  background: linear-gradient(gradientDirection, color1 {75%}, color2, ...);
  /* it's so beautiful , when it's 75% of the first color , transition to the next one */
  background: rgba() , hsla();
  /* RGB ALPHA = (r,g,b,opacity) hsla */
  box-shadow: offsetX offsetY blurRadius spreadRadius color; /* apply shadows for anything */
  

}
```




```css
/* Descriptive CSS ****************** Descriptive CSS */
.class{

    margin: 10px; /* all 4 values */
    margin: 10px 10px; /* top and bottom , right and left */
    margin: 10px 20px 10px; /* top , right and left , bottom */
    box-shadow: 10px 10px; /* horizontal offset , vertical offset */
    box-shadow: 10px 10px 20px; /* horizontal offset , vertical offset , blur*/
    box-shadow: 10px 10px 20px -10px; /* horizontal offset , vertical offset ,blur , spread = "how many pixel till start the blur"*/
    box-shadow: 10px 10px 20px -10px currentcolor; /* horizontal offset , vertical offset , blur , spread ,  */
    box-shadow: inset 10px 10px 2px -19rem currentcolor; /* inset , horizontal offset , vertical offset , blur , spread , color */
    border-radius: 8px 10px; /* think about it as a rictangle , top-left and bottom-right , top-right and bottom-left */
    border-radius: 10px 10px 20px 20px /* top-right,top-left, bottom-right,bottom-left */

}

```



```css
.class{
    transform: rotate(0.6deg);
    filter: blur(2px); /* filter = blur , descriptive bruh */
    overflow: hidden; /* to show the full width and height without adjusting any pixel */
    box-shadow: 10px 10px; /* horizontal offset , vertical offset */
    box-sizing: border-box; /* sets the size of the box to be it's size only without padding or margin */
    text-indent: -8px; /* indent text */
}

```





```css
.flexbox{
  display: flex; /* to display the flexbox , items are spaced and aligned within a container.
  it has two axis , main axis = x and determined by flex-direction: row; row-reverse; is horizontal if flex-direction: column; column-reverse; is vertical , */
  
  flex-direction: row, column , -reverse;

  flex-wrap: wrap; /* wrap to the next row/column , nowrap; */

  justify-content: center; /* positioning in the main axis = x axis */

  align-items: center; /* positioning in the cross axis = y axis */
  
  object-fit: cover; /* fixing the aspect ratio of all photos = cropping to fit*/


}


```css
/* typography selectors */
.class{
  letter-spacing: 0.15px; /* adjust space between each character of text */
  float: right or left; /* place an element on the left or right , with <span> actually*/
  clear: right or left; /* clearing the float property */
  overflow: hidden; /* to avoid overflow , easy lol*/




}


```css

.unknown_yet{
  clip: rect(1px,1px,1px,1px);
  clip-path: inset(50%);
  -webkit-clip-path: inset(50%);
  white-space: nowrap;
  gap: 1rem;
  z-index: 0;
  border-collapse: collapse;
}
/* unknown pseudo selectors ******  unknown pseudo selectors */
:first-of-type{} /* targets the first element that matches the selector */
:last-of-type{} /* targets the last element that matches the selcetor */
:nth-of-type(number) /* targets the (number) that matches the selector */

```css
start any css file with ******** start any css file with 
*,*::before,*::after{ /* ::after and ::before pseudo elements select before or after the element*/
  box-sizing: inherit;
}
html{
  box-sizing: border-box; /* border-box box-sizing : means box will have the same width and height no mater padding or margin or border i put */
  
}


```






