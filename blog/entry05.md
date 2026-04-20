# Entry 5
##### 4/20/26

## Content
  The tool I chose was SASS and some things I learned about my tool was SASS varibles. SASS varibles allows the user to store information and re-use it later.
  
Sass uses the $ symbol to declare a varible:

SASS:
````SASS
  $color1: red;
  $fontsize1: 20px;

p {
   color: $color1;
   font-size: $fontsize1;
}  
````

CSS: 
````CSS
 p {
   color: red;
   font-size: 20px;
}   
````

  I leanred how to use my tools with videos and websites that gave me informtion about how to use SASS. A video i used to learn about @include and @mixin in SASS was this [Sass Crash Course](https://www.youtube.com/watch?v=Zz6eOVaaelI). 

*  @mixin: makes CSS codes reuseable.
  ```` CSS
   @mixin text {
      color: red;
      text-align: center;
      font-size: 20px; 
  }
  ````
* @include: used to include a mixin

```` CSS
     h1 {
      @include text ();
   }
````

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
