# Challenge-sass

# The following concepts. 

1. Being able to explain what a CSS-Preprocessor is?
2. Generate some CSS from your CSS preprocessor (SASS)
3. Being able to minify your CSS output
4. Knowledge of the following SASS features:
5. Variables
6. Mixins (Functions)
7. Nesting
8. Partials & Import
9. Extend/Inheritance
10. Operators (Math)

---
# What is a CSS preprocessor????


-A CSS preprocessor is a scripting language that extends CSS and is compiled into regular CSS syntax.

-A CSS preprocessor is a program that lets you generate CSS from the preprocessor's own unique syntax. There are many CSS preprocessors to choose from, however most CSS preprocessors will add some features that don't exist in pure CSS, such as mixin, nesting selector, inheritance selector, and so on.

---
# How to use SASS??

## Steps to use Sass.

-Create a /Demo folder anywhere on your drive. Like this: ...
-Inside that folder create two sub folders: /css and /scss. Like this: ...
-Create a .scss file. ...
-Go back to the CMD line for a minute. ...
-Make Sass “watch” your /scss and /css folders. ...
-Edit the .scss file and watch Sass compile it into a .css file.

---

 ## How do I minify my CSS?

-Go to minifycode.com and click the CSS minifier tab. Then paste the CSS code into the input box and click the Minify CSS button. After the new minified code is generated, copy the code. Then go back to the css file of your website and replace the code with the new minified version.

[link](https://blog.logrocket.com/the-complete-best-practices-for-minifying-css/
) 

---

# What are Variables???? 
# I'm going to explain this to myself. 


Custom properties (sometimes referred to as CSS variables or cascading variables) are entities defined by CSS authors that contain specific values to be reused throughout a document

# How do Variables work ?


-When you declare a CSS variable, you also give that variable a scope. A variable's scope determines where that variable will work, based on where you declare it. CSS variables can have either local or global scope. Local CSS variables only work in the selector they're created inside

# What are Mixins functions?

-Functions allow you to define complex operations on SassScript values that you can re-use throughout your stylesheet. They make it easy to abstract out common formulas and behaviors in a readable way.

---

## Here is an example of functions .

@function invert($color, $amount: 100%) {
  $inverse: change-color($color, $hue: hue($color) + 180);
  @return mix($inverse, $color, $amount);
}

$primary-color: #036;
.header {
  background-color: invert($primary-color, 80%);
}
[link](https://sass-lang.com/guide)

