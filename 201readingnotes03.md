# HTML book:

## Chapter 3: “Lists” (pp.62-73)
* HTML provide 3 types of list: Ordered lists; Unordered lists; Definition lists.
* Use as < ol >, < li >, < ul > 
* Definition list open and close with < dl >. Inside < dl >, < dt > contain the term and < dd > contain the definition
* Nested lists: user can creat a < li > inside a < li > as sublist


## Chapter 13: “Boxes” (pp.300-329)
* BOX dimensions: css can adjust the dimensions of a specific area on the page
* Limiting width & height: css can min & max width or height for different content
* Overflow: can hidden or scroll content if it's too large to put inside the box
* From outside to inside: Border-->margin-->padding
* By adjusting border, margin and padding can change the layout or appreance of content
* Centering text by " text-align: center "
* Display: inline; block; inline-block; none
* Visibility: hidden. This can hide the box or show a hidden element

# JS book:

## Review Chapter 2: “Basic JavaScript Instructions” (p70-73)
* Arrays: stores a list of values
* Creating an Array:
  * var colors;    
    colors = ['white', 'black', 'custom'];
* Values in Arrays can be accessed with number sequence, starts at 0 (not 1)


## Chapter 4: “Decisions and Loops” from switch statements on (p162-182)
* If..else statement: return different result to users depending on what value they put in.
  * ex: if (lowercaseX === 'yes' || lowercaseSpace === 'y') {
    alert('Good morning');
  } else if (lowercaseX === 'ok') {
    alert('Good afternoon');
  }
  else {
    alert('Good day');
  }
* Switch statements: similar to if...else.., but list the variables user can pick up then proceed to the next step
* Javascript will try to figure out if user put unclear data type
  * string, number, boolean, null, undefined
* Truthy and Falsy values
* Three types of loop: for, while, and do...while

[<--Back>](README.md)