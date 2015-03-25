#Practice Interview Questions

The master list of questions that we've asked students in mock interviews and group interview practice sessions. **If you are a student and want to contribute answers, please make a pull request**

##Character Questions

Do you think anyone can learn to code?

What is the most important thing you learned at gSchool?

Do you have any pet projects?

What is your dream job?

What books are on your reading list?

If you could master one technology this year, what would it be?

Do you prefer to work on a team or alone?

Who are your favorite developers/bloggers that you follow?

Who are your heroes?

What open source-contributions have you made?

What did you learn this week?

***

##Short-Answer Technical Questions

What’s the difference between Bignum and Fixnum?

How do symbols differ from strings?

What is convention over configuration?  

What's the function of garbage collection in ruby?

What are the 3 worst defects of your favorite programming language?

What's the difference between render and redirect in Rails?

Describe the Rails Asset Pipeline and how it handles assets(such as JS and CSS files)

What is an ORM?

What is the database.yml file?

What are the 3 data sources that the params hash is compiled from?

What are the different rails environments?  Why do they exist?  What are the differences between them?

Write code to produce a `stack level too deep` error

What are data-attributes and why are they useful?

In as much detail as possible, explain what happens when I type 'google.com' into my navbar and hit enter.

What is a typical use case for anonymous functions?

Name 2 ways to define a global variable in Javascript

What does AJAX stand for?  Explain how it works in as much detail as possible

What’s the difference between `==` and `===` in JS?

In Ruby, what’s the value of x: `x = 10 + '20' `

In Javascript, what’s the value of x: `var x = 10 + '20' `


What does the following JS code return:

```
var a = [1,2,3]
var b = [1,2,3]
return a === b

```

What's the differnce between Primitive and Refernce types in Javascript?

What is the result of running following JS code:

```
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```

Explain this ruby idiom: `a ||= b`

Order the following CSS selectors by specificity

```
p
#special
.selected
div p
.red .green .blah

```

What does CSS Stand for and what does its name mean?

How is CSS Specificity calculated?

Give me an example of a function that cannot be rewritten recursively

What is z-index in CSS?

Name 3 color systems in CSS

Name 4 different media queries in CSS

How do you go about testing your JavaScript?

What is a relational database and how does it differ from a non-relational database?  Give examples

WTF is REST?

What does `git bisect` do?

How would you design a URL shortener similar to bit.ly?


***


##Whiteboard Questions

Write a method to check if 2 given words are anagrams.

```
anagram_checker("Dictionary", "Indicatory")
#=> true

anagram_checker("Dictionary", "blahblah")
#=> false

```

Write code to convert a numeric string like “543” and convert it to the integer version 543. Assume numbers will be whole integers.

What is 595 in binary?

Convert 101101 to base 10

Whiteboard the schema for zappos.com

Shoes Table: columns could include "Color", "Size", "Gender", "Price", "Style"

Write FizzBuzz with as few if statements as possible. It's possible without any conditionals at all.

Implement a function which calculates the n-th item of Fibonacci sequence

def fib(n)
  if n<2
  return n
  end
  return fib(n-1) + fib(n-2)
end  

Find largest prime palindrome less than 1000

Implement an algorithm to reverse a singly linked list

Count the number of nodes in a binary tree

Write your own getElementById function
