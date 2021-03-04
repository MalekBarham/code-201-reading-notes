Code in a Content Management System

If you are working with a content management system, blogging platform, or e-commerce application, you will probably log into a special administration
section of the website to control it. The tools provided in the administration sections of these sites usually allow you to edit parts of the page rather than the entire page, 

Looking at How Other sites are Built

simply go to the
sample code for this chapter, at
www.htmlandcssbook.com/ code/ and click on the link called "View Source."
Once you have opened this page, you can look for the View menu in your browser, and select the option that says Source or View source

Text :- When creating a web page, you add tags
(known as markup) to the contents of the page

Structural markup: the elements that you can use to describe both headings and paragraphs

Semantic markup: which provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation (and who said it), the meaning of acronyms, and so on

Headings

HTML has six "levels" of
headings:
h1 tag  is used for main headings
h2 tag  is used for subheadings If there are further sections under the subheadings then the h3 element is used, and so on.
  
  Paragraphs To create a paragraph, surround the words that make up the paragraph with an opening p
tag and closing p tag.

Bold & Italic  
The <b> element also represents a section of text that would be presented in a visually different way (for example key words in a paragraph) although the use of the <b> 

By enclosing words in the tags i and i tags we can make
characters appear italic.
The i element also represents a section of text that would be said in a different way from surrounding content — such as technical terms

Superscript & Subscrip

The <sup> element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like raising a number to a power such

White Space 

In order to make code easier to read, web page authors often add extra spaces or start some elements on new lines.

Line Breaks & Horizontal Rules  As you have already seen, the browser will automatically show each new paragraph or heading on a new line. But if you wanted to add a line break inside the middle of a paragraph you can use the line break tag 

Visual Editors & Their Code views
Visual editors often resemble word processors. Although each editor will differ slightly,

Code views show you the code created by the visual editor so you can manually edit it

Semantic Markup :- There are some text elements that are not intended to affect the
structure of your web pages, but they do add extra information to the
pages — they are known as semantic markup.

Strong & Emphasis :- The use of the <strong>
element indicates that its content has strong importance. For example, the words contained in this element might be said with strong emphasis.

The em element indicates emphasis that subtly changes the meaning of a sentence.

Abbreviations & Acronyms

If you use an abbreviation or an acronym, then the <abbr> element can be used. A title attribute on the opening tag is used to specify the full term.
  
  Citations & Definitions
  
  When you are referencing a piece of work such as a book, film or research paper, the cite element can be used to indicate where the citation is from

The first time you explain some
new terminology (perhaps an academic concept or some jargon) in a document, it is known as the defining instance of it.



pages 226 - 245

HTML5: Adding HTML5 Audio to Your Pages

HTML5 introduced the <audio>
element to include audio files in your pages. As with HTML5 video, browsers expect different formats for the audio.
  
  src
This attribute specifies the path to the audio file.

loop
This attribute specifies that the audio track should play again once it has finished.

preload
This attribute indicates what the browser should do if the player is not set to autoplay. It can have the same values we saw on page 214 for the video element

Multiple Audio Sources

It is possible to specify more than one audio file using the <source> element between the opening <audio> and closing audio tags
  
  FLASH, VIDEO & AUDIO
X Flash allows you to add animations, video and audio to
the web.
Flash is not supported on iPhone or iPad.

HTML5 introduces new <video> and <audio>
elements for adding video and audio to web pages, but these are only supported in the latest browsers
  
  Browsers that support the HTML5 elements do not all support the same video and audio formats
  
  Introducing CSS
  In this section, we will look at how to make your web pages more attractive controlling the design of them using CSS.
  
  Introduce you to how CSS works
 Teach you how to write CSS rules
 Show you how CSS rules apply to HTML pages
 
 Understanding CSS:
 Thinking Inside the Box The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.
  
  BLOCK & INLINE ELEMENTS
  You may remember from pages 185-186 that in there is a difference between block level  CSS Associates Style rules with HTML elements

Selectors indicate which
element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.
example 
p  font-family: Arial

CSS Properties Affect How Elements Are Displayed

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon

Here you can see a simple web page that is styled using CSS

Using External CSS  :-  you can using external css using herf tag and type tag and also rel tag.
using internal css :- You can also include CSS rules within an HTML page by placing them inside a style element.

CSS Selectors 

There are many different types of CSS selector that allow you to target rules to specific elements in an HTML document. 

How Css Rules Cascade 

If there are two or more rules that apply to the same element, it is important to understand which will take precedence

LAST RULE
If the two selectors are identical,
the latter of the two will take precedence. Here you can see the second i selector takes precedence over the first.

Why use External Style Sheets?

When building a website there are several advantages to placing your CSS rules in a separate style sheet.

All of your web pages can share the same style sheet. This is achieved by using the link element on each HTML page of your site to link to the same CSS document. This means that the same code does not need to be repeated in every page (which )results in less code and smaller  ( HTML pages). 

how to use object and methods 
dociment.write('goodagfternoon'!);

and you can use java script while you use it in html between scipt tags 

THE LANGUAGE:
SYNTAX AND GRAMMAR
like any new language, there are new words to learn (the vocabulary) and rules for how these can be put together (the grammar and syntax of the language)

A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon. 

COMMENTS  ;- You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. 

WHAT IS A VARIABLE? 
When you write JavaScript, you have to tell the
interpreter every individual step that you want it to
perform. This sometimes involves more detail than
you might expect. 

A variable is a good name for this
concept because the data stored in a variable can change (or vary) each time a script runs.

DATA TYPES 
JavaScript distinguishes between numbers,
strings, and true or false values known as
Booleans. 

 fisrt NUMERIC DATA TYPE 
 0.75 

STRING DATA TYPE 
'H.
1 ' Ivy! 1

BOOLEAN DATA TYPE 
Boolean data types can have one
of two values: true or false. 
true

USING A VARIABLE TO STORE A NUMBER
price holds the price of an individual tile

 quantity holds the number of tiles a customer wants
 
 Note that the numbers are not written inside quotation marks.
 
 USING A VARIABLE TO STORE A STRING
 For the moment, concentrate on the first four lines of JavaScript. Two variables are declared (username and message), and they are used to hold strings (the user's name and a message for that user).
 
 USING QUOTES INSIDE A STRING
 Sometimes you will want to use a double or single quote mark within a string. 
 You can also use a technique called escaping the quotation characters. This is done by using a backwards slash (or"backslash") before
 
USING A VARIABLE TO STORE A BOOLEAN 
A Boolean variable can only have a value of true or fa 1 se, but this data type is very helpful. 

SHORTHAND FOR CREATING VARIABLES 
Variables are declared and values assigned in the same statement. 

CHANGING THE VALUE OF A VARIABLE

RULES FOR NAMING VARIABLES is css :- 

Here are six rules you must always follow when giving a variable a name: 

The name must begin with a letter, dollar sign ($),or an underscore (_). It must not start with a number. 
The name can contain letters, numbers, dollar sign ($), or an underscore (_). Note that you must not use a dash(-) or a period (.) in a variable name
You cannot use keywords or reserved words. Keywords are special words that tell the interpreter to do something.
All variables are case sensitive,
so score and Score would be different variable names, but it is bad practice to create two variables that have the same name using different cases.

Use a name that describes the kind of information that the variable stores. For example,fi rstName might be used to store a person's first name, l astNarne for their last name, and age for their age. 
If your variable name is made up of more than one word, use a capital letter for the first letter of every word after the first word. For example, f i rstName rather than fi rstnarne (this is referred to as camel case). Y

ARRAYS An array is a special type of variable. It doesn't just store one value; it stores a list of values. 

ARITHMETI C OPERATORS 
JavaScript contains the following mathematical operators, which you can use with numbers. You may remember some from math class

USING ARITHMETIC OPERATORS.
This example demonstrates how mathematical operators are used with numbers to calculate the combined values of two costs. 

CREATING A DATE OBJECT 
1. In this example, a new Date object is created using the Date {) object constructor It is called today
2. If you do not specify a date when creating a Date object, it will contain the date and time when the JavaScript interpreter encounters that line of code

WORKING WITH DATES & TIMES 
1. In this example, you can see a date being set in the past.
2. If you try to find the difference
between two dates, you will end up with a result in milliseconds. 
3. To get the difference in days/weeks/years, you divide this number by the number of milliseconds in a day/week/year.
 
 EXAMPLE FUNCTIONS, METHODS & OBJECTS
 Functions allow you to group a set of related Functions can take parameters (informatiorJ required to do their job) and may return a value. 
An object is a series of variables and functions that represent something from the world around you. 

In an object, variables are known as properties of the object; functions are known as methods of the object.

USING COMPARISON OPERATORS
At the most basic level, you can
evaluate two variables using a comparison operator to return a true or f al se value. 




