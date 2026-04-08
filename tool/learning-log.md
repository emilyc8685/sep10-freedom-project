# Tool Learning Log

## Tool: **SASS**

---

### 3/16/26:
* I learned how to use **@include and @mixin** with this [Sass Crash Course](https://www.youtube.com/watch?v=Zz6eOVaaelI).
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
---

### 3/23/26:
* I learned about **SASS Nesting** by watching [Sass in 100 Seconds](https://www.youtube.com/watch?v=akDIJa0AP5c&t=14s)
  * SASS Nesting: allows us to organize code that are related
    
SASS:
   ```` CSS
      font: {
        family: Arial, sans-serif;
        size: 20px;
      }
   ````
CSS: 
````CSS
   font-family: Arial, sans-serif;
   font-size: 20px;
````


* SASS Functions 
  * **SASS Strings**: get information about strings.
    ```` HTML
      to-lower-case("HEY!")
      result: "hey!"

      quote(hey!)
      result("hey!")
    ````
---    
### 3/30/26:
* SASS **@extend**: allows me to use CSS i already used for new CSS

SASS:
```` CSS
   .class1 {
      color: red;
}

   .class2 {
      @extend .class1
}
````

CSS:
````CSS
   .class1, .class2 {
      color: red;
}
````

* SASS **variables** allows you to store information and re-use it later
   * Sass uses the $ symbol to declare a varible
   * video: [SASS Tutorial - Variables](https://www.youtube.com/watch?v=LXx_oE6IBWs&list=PL4cUxeGkcC9jxJX7vojNVK-o8ubDZEcNb&index=3) 

SASS:
````CSS
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

<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
