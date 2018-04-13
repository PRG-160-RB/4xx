# 4xx
https://4xx.rlbright.com

inside out project version 400.0
added base code to index.html
added initial javascript to app.js page 


inside out project version 401.0
 -created the appData object
 -moved title and tagLine variables into appData
 -refactored the initialize function 
 
 inside out project version 401.1
   -added bootstrap to the index.html file
   -added a DOM injection of the progress bar in the app.js
   -created a display pb function in the app.js 
 
 inside out project version 402.0
   -added style.css and linked in index.html
   -added login form function and call after progress bar is completed
   -added minimal validateLogin function to check for blank strings
   
 inside out version 403.0
  -added the application user interface- sidebar, wrapper, navigation, etc.
  -added the build menu function, which returns the navigation menu and will increase
     in  dynamic navigation building.
  - aded the build main function which returns the primary content area and 
      will evovle to return content dynamically.
  -replaced document.write with 
     call to applicationUserInterface function in the validatelogin  function
 - added the linkClicked function which is called by the click events on anher elemnts
   and returns dynamically driven results.

 inside out version 404.0
 - added the buildMain function which returns the primary content area and will evolve to return content dynamically
     - replaced document write with call to applicationUserInterface function in the validateLogin function
     - added the linkClicked function which is called by click events on anchor elements and returns dynamically driven results
+
+inside out project version 404.0
+- index.html
+    - code changes https://www.diffchecker.com/oybNnzTY
+    - removed comments and cleaned code
+    - added script tag for quotes.js file
+- style.css
+    - code changes https://www.diffchecker.com/114fW8QY
+    - modified the sidebar and sidebar ul classes 
+    - added the auth and infoDiv classes
+- app.js
+     - code changes https://www.diffchecker.com/oKMHtB1u
+     - added the quotArr sort to the initializeApplication function
+     - modified buildMenu function to dynamically build the menu from the array
+     - modified linkClicked function to dynamically populate main content with array content
+- added the assets/data/quotes.js file
+     - code changes https://www.diffchecker.com/YlRCv0UM
 