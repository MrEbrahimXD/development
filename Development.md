```sql
/* SQL ********* SQL */
CREATE DATABASE name;

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
LEFT JOIN table3 AS T3
RIGHT JOIN table4 AS T4
ON T1.id = T2.id;

/* BASIC SYNTAX **** BASIC SYNTAX */
SELECT * FROM love WHERE loved_people LIKE 'mo%' OR LIKE 'mu%' OR LIKE 'ma%';

/* Variables *** Variables */
VARCHAR p = "";
INT s = 0;
FLOAT x = 0.2;
DOUBLE q = 0.00000000001;
TEXT name = "";
CHAR a = "A";

```

```html
<!-- Basic HTML Page -->
<!DOCTYPE html> <!-- Document type is html 5 , cause html is based on xml langauge , not case sensitive-->

<html> <!--HTML element is the start of every html code -->

  <head> <!-- Inside any html element , there is a head and a body , head is the things you can't see in the page , like infos about the page or even the page title-->

  </head> <!-- Closing tag of the head-->

  <body> <!-- Body is the element inside the html which is going to be rendered in the browser -->

  </body> <!-- Closing tags for the body-->

</html> <!-- Closing tag of the html element -->


```

```html
<!DOCTYPE html> <!-- Document type is html 5 , cause html is based on xml langauge -->
<html lang="en"> <!--HTML element is the start of every html code -->
  <head> <!-- Head is the element that shows some data for search engines and title and for linking files-->
    <title>Accessibility Quiz</title> <!-- Page's title -->
    <meta charset="UTF-8" /> <!--char encoding which is mostly in utf-8 -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0" /> <!--viewport for scaling-->
    <meta name="description" content="Good webpage xd" /> <!--Page description-->
    <link rel="stylesheet" href="styles.css" type="styles.css" /> <!-- Linking our css file for designing-->
    <script href="script.js"></script> <!-- Linking our javascript file -->
  </head>

  <body> <!-- body element is responsible of showing stuff in your webpage-->
    <header> <!-- Header , title and navigation bar -->

        <nav> <!-- Usually we link nav with ul (unordered list) -->

        </nav>
    </header>

    <main> <!-- Main content bro , It's useful for SEO (search engine optimizations) -->
      <form action="" method="post" > <!-- Form action to a weburl , and here is a HTTP post request -->
        <section role="region" aria-labelledby=""> <!-- Role must have an aria-labelledby -->  
          <select required> <!-- Dropdown select -->
            <option value="" selected>Select an Option</option>
            <option value="1">I'm option 1</option>
            <option value="2">I'm option 2</option>
          </select>
          <textarea placeholder="good" rows="30" cols="20">
            <!-- Text area with rows and columns -->
          </textarea>
        </section>
      </form>
    </main>
    
    
    
    <footer> <!-- fOOTer , it's descriptive  -->
      <address> <!-- Contact Information -->
          <br /> <!-- break line -->
          <hr /> <!-- Horizontal line -->
      </address>
    </footer>
  
  </body>
</html>



<!-- Tables -->
<table>
  <caption>Table's caption</caption> <!--Table's caption-->
  
  <thead> <!--Table head (first row)-->
    <tr>
      <td>table cell or element</td>
      <td> another table data cell </td>
      <th>A header cell</th>
    </tr>
  </thead>

  <tbody> <!--Table body (elements)-->

  </tbody>

  <tfoot> <!--Table footer or foot (last row)-->

  </tfoot>

</table>




<!-- Lists -->
<ul> <!-- Unordered list -->
  <li> </li> <!-- List item -->
  <li> </li> <!-- List item -->
  <li> </li> <!-- List item -->
</ul>

<ol> <!-- Ordered list -->
  <li> </li> <!-- List item -->
  <li> </li> <!-- List item -->
  <li> </li> <!-- List item -->
</ol>

<dl> <!-- Descriptive list -->
  <li> </li> <!-- List item -->
  <li> </li> <!-- List item -->
  <li> </li> <!-- List item -->
</dl>


<!-- Block quote -->
<blockquote cite=""> <!-- a BlockQuote , cite="" attribute specifies the website we quoted from -->
  <q> <!--  Short quote -->
    I love quotes
  </q>
</blockquote>



<!-- Emphasising some text -->
<em></em> <!--For a word-->
<strong></strong> <!--For a text-->



<!-- abbreviation --->
<abbr title="laugh out loud">LOL</abbr> <!-- title="" attribute text should have the description -->



<!-- Img with source and alt and loading lazy means loads when needed or viewed and width and height in pixels -->
<img src="" alt="" loading="lazy" width="3840" height="2160" />


<!-- anchor , A way to link to different url or page -->

<a href="#id or url" ></a>

<!-- Italic text -->
<i></i>

<!-- Bold text , to give a strong meaning -->
<b></b>

<!--
  A self containing element or a self closing element means it doesn't need a closing tag
  like the img tag or the link tag , we usually close them by adding / at the end of it 
  but it's not required.
  <link />
  <img />
-->


<!-- Field sets (nice field for inputting infos) , we usually nest <fieldset> within a <form>-->
<fieldset>
  <legend></legend> <!-- The caption of that field -->
  <!--
    here we usually add <input /> elements 
  -->
</fieldset>


<!-- Div , or division , it's an element for creating designs usually because it has no meaning to the page , you can nest as many divs inside that div as u want -->
<div></div>


<!-- Article , is probably something like div , but it has a meaning that it's creating an article -->
<article>
  <!--
    Text and stuff here 
  -->
</article>

<!-- adding aside element , When I want to explain something aside what was written -->
<aside></aside>


<!-- Span element for seperating piece of text from the other -->
<span> </span>
<p>Hi<span class="span1">Mohamed</span></p>








```

```HTML
  <!-- HTML Famous attributes ***************** HTML Famous attributes -->
  <i dir="ltr-rtl" title="" loading="lazy" target="_blank" lang="" role="" cols="" rows="" href="" rel="stylesheet-Referer-noreferrer" type="" content="" value="" name="" id="" class="" aria-hidden="true-false" colspan="" rowspan="" width="" height="" border="1" style=""><i>
```

```css
/* CSS FUNCTIONS ********* CSS FUNCTIONS */
.class{
  padding: calc(1.25rem+2px);
  !important /* overwrite anything with !important  to make it const*/
  /* Gradient Applied in CSS background property */
  transparent /* color transparent */
  minmax(minvalue,maxvalue); /* to make the page responsive */
  gradient-type(
  color1,
  color2
  );
  repeating-linear-gradient( /* Repeats the linear-gradient*/
    var(--color1) 0%,
    var(--color1) 10%,
    var(--color2) 90%,
    var(--color2) 100%
  );
  linear-gradient( /*  circular gradient to the background */
    var(--color1) 0%,
    var(--color1) 10%,
    var(--color2) 90%,
    var(--color2) 100%
  ),
  radial-gradient(
    circle closest-corner at 15% 15%,
    #ffcf33,
    #ffcf33 20%,
    #ffff66 21%,
    #bbeeff 100%
  );
}

```
```css
/* variables *** variables */
:root{ /* the root cascade */
  --variable-name: value; /* to declare a variable you have to add (--) before the variable name and give it any value u want , usually we use them to store colors */
  --variable-name2: value2; 
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
/* Media *********** Media = more like if (condition) { do something }*/
@media (max-width: 199px) {#id{someting: 10px;}}
@media (prefers-reduced-motion: no-preference){ scroll-behavior: smooth; }

/* Colors ********************* Colors */

background-color: rgb(0-255,0-255,0-255);
background-color: rgba(0-255,0-255,0-255, {Opacity} )
background-color: #000000;
background-color: hsl(0-360,0-100%,0-100%); 
/* 0 to 360 for hue, a percentage from 0 to 100 for saturation, and a percentage from 0 to 100 for lightness. */
background: linear-gradient(deg,color1,color2, ..);
background : repeating-linear-gradient(deg,color1,color2, ..);

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
  /* it's so beauty , when it's 75% of the first color , transition to the next one */
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
    filter: blur(2px) grayscale() opacity() ; /* filter = blur , descriptive bruh */
    overflow: hidden; /* No element will overflow when overflow set to hidden */
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

  flex-grow: 1 or 0; /* 1 is true , 0 is false */

  flex-shrink: 1 or 0 /* 1 is true , 0 is false */

  flex: 0 1 50px; /* flex: (flex-grow) (flex-shrink) (flex-basis or width) */

  justify-content: center; /* positioning in the main axis = x axis */

  align-items: center; /* positioning in the cross axis = y axis */
  
  object-fit: cover - fit - contain; /* fixing the aspect ratio of all photos = cropping to fit*/


}
```

```css
.css-grid{
  display: grid; /* To start a grid , this is applied for the parent */
  grid-template-columns: 1fr 95rem 1fr .. ; /* To create an X number of columns , parent property*/

  
  
}
```


```css
/* typography selectors */
.class{
  font-size: 10px;
  font-family: 10px;
  font-weight: bold - 100 - 1200;
  text-align: center; /* aligning the text to the center */
  letter-spacing: 0.15px; /* adjust space between each character of text */
  float: right or left; /* place an element on the left or right , with <span> actually*/
  clear: right or left; /* clearing the float property */
  overflow: hidden; /* to avoid overflow , easy lol*/
}
```

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
/* start any css file with ******** start any css file with */
*,*::before,*::after{ /* ::after and ::before pseudo elements select before or after the element*/
  box-sizing: inherit;
}
html{
  box-sizing: border-box; /* border-box box-sizing : means box will have the same width and height no mater padding or margin or border i put */
  
}

```

```css
.display{
  display: inline; /* inline elements = in the same line like <em> <strong> ,no width and height */
  display: inline-block; /* more like inline but takes width and height if needed like <img /> */
  display: block; /* takes the whole line in their parent like the heading elements and <p> */ 
  display: flex; /* display flexbox , also I have explained it */
  display: grid; /* display grid , also I have explained it */
}
```

```css
.position{
  position: absolute; /*start from the overflow of the page point (0,0) */
  position: relative; /*start from the overflow of the parent point(0,0) relativly */
  position: fixed; /* fixed position , Stays the same whatever happened */
  position: sticky; /* Won't leave you ever */
  position: static; /* Normal positioning or default */

  /*
    Note you can use top , bottom , right , left properties to move
    objects in all positioning statement unless it's default (static)
  */
  top: ;
  right: ;
  bottom: ;
  left: ;
}
```

```css
.box-model{
/* Margin
      ______________________________________________________ -> border
     |                                                      |
     |  padding                                             |
     |      ________________________________________        |
     |     |                                        |       |
     |     |      Content like a heading <h1-h6>    |       |
     |     |________________________________________|       |
     |                                                      |
      ------------------------------------------------------
  */
  --margin{ /* is the space outside of anything , think of anything as a box */
    margin-top: ; /* space on the top of the box */
    margin-bottom: ; /* space at the bottom of the box */
    margin-right: ; /* space in ur right my boi */
    margin-left: ; /* space in ur left my boi */

    --COOL ABBR *************** COOL ABBR--

    margin: 1px 1px 1px 1px; /* margin (top , right , bottom , left) */
    margin: 20px 20px 10px; /* margin top , (right and left) , bottom */
    margin: 1px 1px; /* when it is 2 values = [top and bottom] , [right and left] */
    margin: 1px; /* all 4 sides has a margin of 1 px */
  }

  --padding{ /* space inside the box , the same properties like margin */ 
    padding-top: ; /* space on the top of the content */
    padding-bottom: ; /* space at the bottom of the content */
    padding-right: ; /* space in ur right my boi */
    padding-left: ; /* space in ur left my boi */

    --COOL ABBR *************** COOL ABBR--

    padding: 1px 1px 1px 1px; /* padding (top , right , bottom , left) */
    padding: 20px 20px 10px; /* padding top , (right and left) , bottom */
    padding: 1px 1px; /* when it is 2 values = [top and bottom] , [right and left] */
    padding: 1px; /* all 4 sides has a padding of 1 px */
  }
  --border{ /* borders surrounding your content {padding} */
    border-{DIRECTION}-color: red; /* Obviously the color */
    border-{DIRECTION}-{DIRECTION}-radius: 50%; /* radius of the direction */
    border-{DIRECTION}-width: 10px ;  /* Width of the border in the {DIRECTION} */
    border-{DIRECTION}-style: dashed; /*Style of the border in the {DIRECTION} is dashed {means it's cutted like a group of dashes } */
    border-{DIRECTION}-style: solid; /* solid color among the selected {DIRECTION} */
    border-{DIRECTION}-style: double; /* double border color among the selected {DIRECTION} */
    border-collapse: collapse; /* useful in tables , you can collapse the border {shrink it} */

    --COOL ABBR *************** COOL ABBR--
   
    border-color: red; /* Color of all 4 borders combined is red */  
    border-width: 50%; /* Width of all 4 borders is 50% each the width of the parent */
    border-radius: 200px; /* the radius of all borders are 200px each */
    border-style: double - dashed - solid; /* Style of all 4 borders combined */
    
    --time saving ABBR ************* time saving ABBR--

    border: 10px; /* when 1 value , write a width */
    border: 10px solid; /* when two values write a color and a width */
    border: 10px double red; /* when 3 values , write width , style , color */

  }

  
  
}
```
