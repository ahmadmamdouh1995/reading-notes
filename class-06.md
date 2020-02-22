## An Object 
### The Object is contain multi variables and function to do things in easy way 

### Nodelists look like arrays but not same ,they are a type of object called a collection.
* DOM queries may return one element, or they may return a Nodelist,which is a collection of nodes.

### Nodelists are two type :
* live Nodelist.
* static Nodelist.

### Nodelists have a method called item() which will return an individual node from the Node list.
* Select elements that have a class attribute whose value is hot and store the Nodelist in a variable called e 1 ements.
* Use the 1 ength property to check how many elements were found. If 1 or more are found, run the code in the if tatement.
* Store the first element from the Node List in a variable called fi rstitem. (It says 0 because index numbers start at zero.)


### querySe 1 ector() returns the first element node that matches the CSS-style selector. querySe 1ectorA11 () returns a Nodelist of all of the matches.

### To add aNew content in HTML :
* store new content as string in variable .
* select the element whose content you want to replace .
* set the element's inner HTML property to be the new string .


### DOM manipulation offers another technique to add new content to a page (rather than i nnerHTML). It involves three steps:
* CREATE THE ELEMENT : createEl ement () ,You start by creating a new element node using the createElement() method.
* GIVE IT CONTENT : createTextNode(), createTextNode() creates a new text node. Again, the node is stored in a variable.
* ADD IT TO THE DOM : appendChild(), Now that you have your element you can add it to the DOM tree using the appendChi 1 d () method.


### REMOVING ELEMENTS VIA DOM MANIPULATION:
* STORE THE ELEMENT TO BE REMOVED IN A VARIABLE.
* STORE THE PARENT OF THAT ELEMENT IN A VARIABLE.
* REMOVE THE ELEMENT FROM ITS CONTA INING ELEMENT.


### document.write() :
#### The document object's write () method is a simple way to add content that was not in the original source code to the page, but its use is rarely advised.
#### ADVANTAGES :
* It is a quick and easy way to show beginners how content can be added to a page.
#### DISADVANTAGES :
* It only works when the page initially loads.
* If you use it after the page has loaded it can:
1. Overwrite the whole page
2. Not add the content to the page
3. Create a new page
* It can cause problems with XHTML pages that are strictly validated.
* This method is very rarely used by programmers these days and is genera lly frowned upon.


### element.innerHTML :
#### The i nnerHTML property lets you get/update the entire content of any element (including markup) as a string.
#### ADVANTAGES:
* You can use it to add a lot of new markup using less code than DOM manipulation methods.
*  It can be faster than DOM manipulation when adding a lot of new elements to a web page.
* It is a simple way to remove all of the content from one element (by assigning it a blank string).
#### DISADVANTAGES:
* It should not be used to add content that has come from a user, as it can pose a significant security risk which is discussed over the next four pages.
* It can be difficult to isolate single elements that you want to update within a larger DOM fragment.
* Event handlers may no longer work as intended.

### DOM MANIPULATION
#### DOM manipulation refers to using a set of methods and properties to access, create, and update elements and text nodes.
#### ADVANTAGES : 
* It is suited to changing one element from a DOM fragment where there are many siblings.
* It does not affect event handlers.
* It easily allows a script to add elements incrementally (when you do not want to alter a lot of code at once).
#### DISADVANTAGES
* If you have to make a lot of changes to the content of a page, it is slower than innerHTML.
* You need to write more code to achieve the same thing compared with innerHTML.

