
> This document contains JavaScript Best Practies

#### Basics
> These are JavaScript basics to be aware of.

  1. `===` vs `==`
  
      Lorem ipsum
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
      
#### Worst Practices
> These are coding practices to avoid and habits that you should unlearn.

#### Obsolete Practices
> These are coding practices that were once good but have become dated and should be avoided.

  1. Overusing jQuery
      
      Most modern applications use jQuery as an ancillary library, opting for a js framework with features that jQuery doesn't provide (data-binding, routing, etc.) as the primary front-end framework. As such, methods and functions provided by the primary framework should be used before jQuery usage is considered.  Additionally:
      -  Avoid making duplicate jQuery calls.  Instead, store the result of the initial call in a variable. 
      
      
      Bad Practice
      ```javascript
      $('.descriptionDiv').find('').val();
      ```
     
      
     Good Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
      
      -  Ensure that the most efficient jQuery call is used
      
      
      
      Bad Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
     
      
     Good Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
  2. Relying on Comments to Clarify Overly Complex or Confusing Code
      
      
      
      
      Bad Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
     
      
     Good Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
  3. Storing JavaScript Code in One File
      
      Here's where the explanation goes.
     
  4. Manipulating Globals
      
      Here's where the explanation goes.
      
      
      Bad Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
     
      
     Good Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
  5. Manipulating Prototypes (manually or in frameworks like date.js)
      
      Here's where the explanation goes.
      
      
      Bad Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
     
      
     Good Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
  6. Using Browser Detection Instead of Feature Detection
      
      Here's where the explanation goes.
      
      
      Bad Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```
     
      
     Good Practice
      ```javascript
      function test() {
       console.log("look ma`, no spaces");
      }
      ```

#### Good Practices
> Universally applicaple and common sense coding and software development practices.

Lorem ipsum

#### Agile Engineering 
> These are Agile Engineering best practices

  1. Test Driven Development (TDD)
    
    **Why should you do it?** Because it's awesome.
    1. Unit Testing
    
    Lorem ipsum
    > **Recommended Tool** `jasmine`
  1. SOLID
  
  Lorem ipsum
  1. Clean Code
  
  Lorem ipsum
  
#### Industry Practices
> Here are some notable examples of what successful tech companies use and do. Pick what best works for you.

Lorem ipsum 

#### Tooling
> These are easy to learn and use tools.

Lorem ipsum