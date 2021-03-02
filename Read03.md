#read03.md
 Changes to Content

ins tag :-    element can be used to show content that has been inserted into a document.
<del>  tags :- element can show text that has been deleted from it.

<s> tag :- The <s> element indicates something that is no longer accurate or relevant (but that should not be deleted).



There are lots of occasions when we need to use lists. HTML provides us with three different types:

Ordered lists are lists where each item in the list is
numbered. For example, the list might be a set of steps for
a recipe that must be performed in order, or a legal contract
where each point needs to be identified by a section
number.
● Unordered lists are lists that begin with a bullet point (rather than characters that indicate order).
● Definition lists are made up of a set of terms along with the definitions for each of those terms.



This example combines many of the techniques shown in this chapter.

By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the height and width properties. 

333.png  

The most popular ways to specify the size of a box are to use pixels



limiting hight 

In the same way that you might want to limit the width of a box on a page, you may also want to limit the height of it.



Overflowing Content  ;-  The overflow property tells the
browser what to do if the content contained within a box is larger than the box itself.

hidden :- This property simply hides any extra content that does not fit in the box.

scroll :- This property adds a scrollbar to the box so that users can scroll to see the missing content.



Border, Margin & Padding :- 

Every box has three available properties that can be adjusted to control its appearance: 

the porder :- Every box has a border (even if
it is not visible or is specified to be 0 pixels wide )

the margin :- Margins sit outside the edge of the border.

the padding :- Padding is the space between the border of a box and any content contained within it.



White space & Vertical Margin ;-

The padding and margin properties are very helpful in adding space between various items on the page.



Border Style :- 

You can control the style of a border using the border-style property.

solid  : is a single solid line 

dotted a series of square dots (if your border is 2px wide, then the dots are 2px squared with a 2px gap between each do.



Border Color ;- You can specify the color of a border using either RGB values, hex codes or CSS color names.

Shorthand border :- The border property allows you
to specify the width, style and color of a border in one property (and the values should be coded in that specific order).

---------------------------------------------------------------------------------

padding ;- The padding property allows you to specify how much space should appear between the content of an element and its border.  

margin :- The margin property controls the gap between boxes.

Centering Content  :- If you want to center a box on
the page (or center it inside the element that it sits in), you can set the left-margin and right-margin to auto.


IE6 Box Model  :- When you specify the width of
a box, any padding or margin should be added to the width of it. Internet Explorer 6, however, has a quirk whereby it includes the padding and margins in the width of the box.



Change Inline/Block  :- 

 

The display property allows you to turn an inline element into a block-level element or vice versa, and can also be used to hide an element from the page. 



Hiding Boxes  :- The visibility property allows you to hide boxes from users but It leaves a space where the element would have been.

border-image :- The border-image property applies an image to the border of any box. It takes a background image and slices it into nine pieces.

 



JS Box Model :-
USING QUOTES INSIDE A STRING :- If you just want to use single
quotes in the string, you could surround the string in double quotes.

You can also use a technique called escaping the quotation characters. This is done by using a backwards slash (or "backslash") before .



USING A VARIABLE TO STORE A BOOLEAN  :-

 

First, Booleans are used when the value can only be true/ fa 1 se. You could also think of Tthese values as on/off or 0/1:
true is equivalent to on or 1,



SHORTHAND FOR CREATING VARIABLES ;- 

1. Variables are declared and values assigned in the same statement.

2- Three variables are declared on the same line.

3- Two variables are declared and assigned values on the same line. 



CHANGING THE VALUE OF A VARIABLE  :- 

Once you have assigned a value to a variable, you can then change what is stored in the variable later in the same script.

For example, the value of a shipping variable might start out as being false. Then something in the code might change the ability to ship the item and you could therefore change the value to true.



What is jQURY ?

is to make it much easier to use JavaScript on your website.

A BASIC JQUERY EXAMPLE 

44-1.png  



WHY USE JQUERY?  

jQuery doesn't do anything you cannot achieve with pure JavaScript.
It is just a JavaScript file but estimates show it has been used on over a
quarter of the sites on the web, because it makes coding simpler

1: SIMPLE SELECTORS  

Older browsers do not support the latest methods for selecting elements.

IE does not treat whitespace between elements as text nodes, while other browsers do.

2: COMMON TASKS IN LESS CODE  

There are some tasks that front-end developers need to do regularly, such as loop through the elements that have been selected.

3: CROSS-BROWSER COMPATIBILITY   

jQuery automatically handles the inconsistent ways in which browsers select elements and handle events.



FINDING ELEMENTS  

Using jQuery, you usually select elements using CSS-style selectors. It also offers some extra selectors, noted below with a 'jQ'.

BASIC SELECTORS  :-

*    ------------ > All elements  

element -------------------->    All elements with that element name  

  # ---------------------> Elements whose id attribute has the value specified  

.class  -------------->  Elements whose cl ass attribute has the value specified 

selector l, selector2   ---------- >  Elements that match more than one selector (see also the .add() method, which is more efficient when combining selections) 



HIERARCHY 

ancestor descendant   An element that is a descendant of another element (e.g., 1 i a)  

parent > child   An element that is a direct child of another element (you can use* in  

previous + next    Adjacent sibling selector only selects elements that are immediately  

previous -  Sibling selector will select any elements that are a sibling of the
previous element


BASIC FILTERS   

: not (selector)  ------------->  All elements except the one in the selector (e.g., div: not ('#summary')) 

:first  --------------------> The first element from the selection  

: last   ------------------> The last element from the selection  

:even   ----------------> Elements with an even index number in the selection  :eq(index)   ------------ >  Elements with an index number equal to the one in the parameter  

CONTENT FILTERS  

:contains('text ')  --------------> Elements that contain the specified text as a parameter  

:empty   -------------------->  All elements that have no children  

:parent  ------------------> All elements that have a child node (can be text or element)  



LOOPING   

In plain JavaScript, if you wanted to do the same thing to several elements, you would need to write code to loop through all of the elements you selected. 



CHAINING  :- If you want to use more than one jQuery method on the same selection of elements, you can list several methods at a time using dot notation to separate each one,   

. html() :- When this method is used to retrieve information from a jQuery selection, it retrieves only the HTML inside the first element in the matched set, along with any of its descendants.



. text()
When this method is used to retrieve the text from a jQuery selection, it returns the content from every element in the jQuery selection, along with the text from any descendants. 



GETTING AT CONTENT  

Use the  . html() and . text() methods are used on the same list (depending on whether

or elements are used in the selector).
and how to update elements 
66.png 

 

 

CHANGING CONTENT : 

In this example, you can see three met hods that allow you to update the content of the page.

INSERTING ELEMENTS   ;- 

1: Create the new elements in a jQuery object
2: Use a method to insert the content into the page 


 

 

 

 

 
