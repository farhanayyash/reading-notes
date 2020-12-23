# HOW HTML, CSS, & JAVASCRIPT FIT TOGETHER
### 1. HTML ending with .HTML
### 2. Css ending with .css
### 3. Javascript ending with .js

#### Starting with the HTML layer allows you to focus on the most the important thing about your site: it's content. Adding the CSS rules in a the separate file keeps rules regarding how the page looks away from the content itself. The JavaScript is added last and enhances the usability of the page or the experience of interacting with the site.

#### JAVASCRIPT RUNS WHERE IT IS FOUND IN THE HTML When the browser comes across a < script> element, it stops to load the script and then checks to see if it needs to do anything.

## Tips for you when you using Javascript :
> It is best to keep JavaScript code in its own JavaScript
file.
>The HTML < script> element is used in HTML pages
to tell the browser to load the JavaScript file (rather like
the < link> element can be used to load a CSS file).
> If you view the source code of the page in the browser,
the JavaScript will not have changed the HTML,
because the script works with the model of the web
the page that the browser has created.

## Basic Javascript instruction 
### A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon.

## COMMENTS  
### You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code.
- MULTI-LINE COMMENTS /*
- SINGLE-LINE COMMENTS //

# VARIABLE
### A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables. A variable is a good name for this concept because the data stored in a variable can change (or vary) each time a script runs.

## define variable :
### variable key (var) variable name(quantity)
## assign value to variable :
### var name = var value 

# DATA TYPES
### JavaScript distinguishes between numbers, strings, and true or false values known as Booleans.
1. NUMERIC DATA TYPE
2. STRING DATA TYPE
3. BOOLEAN DATA TYPE

## RULES FOR NAMING VARIABLES :
1. The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number.
2. The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name.
3.  You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something. For example, var is a keyword used to declare a variable. Reserved words are ones that may be used in a future version of JavaScript.
4. All variables are case sensitive, so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases.
5. Use a name that describes the kind of information that the
variable stores. For example, fi rstName might be used to store a person's first name, l astNarne for their last name, and age for their age.
6. If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. For example, f i rstName rather than fi rstnarne (this is referred to as camel case). You can also use an underscore between each word (you cannot use a dash).

