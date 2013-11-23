### Abigail's Convention-Over-Configuration Guidelines

So, there's lots of ways of writing code.  And lots of opinions on how to go about it.  Here is one opinion on an approach that has worked very well for me in creating dozens of applets, and which produces extremely clean and concise code; allows for code reuse; and which created very straightforward and understandable Meteor code.  

#### File Naming  
- All files are given names using Binomial Nomenclature, using a contextualizing prefix.  For example: ``contextualizer.file.js``.



#### Model View Controller
- The Model is encoded in the Document Object Model, using .html files.
- The View is encoded with cascading Style Sheets, using .css or .less files.
- The Controller is encoded with Javascript, using .js files.

Which suggests a basic directory structure like this....  
````sh
/.scrap
/client
/client/views/cascading.stylesheet.css
/client/models/document.templates.html
/client/controllers/javascript.libraries.js
/packages
/public/images
/server
````

#### Code Naming Conventions  
- Inputs given id containing ``Input`` suffix.
- Pages given id containing ``Page`` suffix, and ``page`` class.
 
#### Standard Packages  
- All apps get Bootstrap-3 and Less packages.
- All apps get Iron-Router.
