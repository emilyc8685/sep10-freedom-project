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
    

<!-- 
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
