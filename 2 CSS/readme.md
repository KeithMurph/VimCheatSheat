# CSS
Cascading style sheets
<br>
A stylesheet language used to describe the look and presentation of a HTML document.
<br>
<strong><h2>HOW WE ADD STYLE<h2></strong>




<hr>
The building blocks of a modern website includes HTML which provides structure to what the user sees, CSS to style what the user sees and JavaScript which adds interaction for the user.
<hr>

# 3 Ways to add CSS
<hr>

## Inline
Style within a HTML element 
<br>

    `<h1 style="color:blue;text-align:center;"> This is blue and centered </h1>`
<br>

## Style Element
Internal CSS file.
<br>
Usable only on the page that contains the style tag

` <style> Full CSS format within single HTML tag </style>` `

<br>

## External CSS File ⭐
-recommended method-
<br>
Use ` <link> ` element to link a CSS file

` <link rel="stytlesheet>" href="styles.css"/> `

The 'rel' is the relationship attribute thats telling the file it's linking a CSS file.
<br>
"href" is the file or pointer to a file 

<br>
<hr>

# Selectors


In CSS we describe the styling through selectors.
<br>

selector {
    property1: value;
    property2: value;
}
<br>
Selectors can also have unique properties with values of their own 


Specificity wins out!
<br>
High Priority to Low ⬇
<br>
    
## Inline 
-Style Inside the HTML element-
<br>

The least recommended of the selectors but the easiest way of testing the styling of specific HTML elements.
<br>

`<h1 style="color:blue;text-align:center;"> This is blue and centered </h1>`

 
## Element tags
h1{

}
<hr> 
<br>

HTML tags can be assigned styles
<br>
div, h1, header, strong, etc...

## Classes ⭐
-Used 90% of the time-
<br>
  .classname{

}
<hr>  
<br>
elements can have multiple classes 

## Id
#id_name {


} 
<hr>
# Box Model
Box Model

![boxModel](https://user-images.githubusercontent.com/85463607/156156853-dc22af79-c3be-4bed-bdbd-ff7d8cea9b43.jpg)
