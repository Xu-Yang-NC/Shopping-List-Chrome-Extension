# Shopping-List-Chrome-Extension



This is my first application using JavaScript. This application is a shopping list chrome extension which items can be simply added to or removed from the list.
All the entering data will be saved to the local storage. Therefore, even the extension is closed, all the items in the list will not be lost. 
The "remove purchased" button only removes the items that are checked. The UI used HTML and CSS. SASS is involved to manage all the CSS.


The forEach loop didn't work quit well at beginning when checking which item is checked, only one checked item was removed from the list. The solution is to reverse the array
and then loop through it.
