Create a web-page according to provided responsive designs using twitter bootstrap framework and scss style preprocessing.

The whole page is build with using of bootstrap components:
- navbar;
- page-header;
- responsive grid;
The only custom module on page is the 'related-class' module, it should have its own separate css rules for inner styles, but it's width and position should be managed by bootstrap grid.

First steps on this project:
 - download the latest version of twitter bootstrap framework
 - project requires only bootstrap.min.css, bootstrap.min.js files from downloaded pack. 
 - Also note that all bootstrap plugins depend on jQuery. This means that the latest version of jQuery.js must be downloaded form official site, stored in /js folder and included in html page before bootstrap plugin files.
 - Note: navbar plugin's toggle button will not work without plugin setup correctly. There is no need to write any javascript for it, just make sure that all required javascript plugins are in /js folder and included in the right order in page html markup.
 - Include links to bootstrap.min.css and to compiled style.css files into page, no other styles should be included.

Scss preprocessing should be used in this project. You can choose any app you want for compiling scss files to css. Preprocessing part of home-task should include:
- using of variables,
- using of scss nesting syntax
Since there in not a lot of custom styling in current home-task, there is no need to break source styles into a separate files for variables, bootstrap styles overrides and custom styles, all styling can be stored in a single styles.scss file. But if you want to try you can split styles to files listed above.

Bootstrap source files shouldn't be touched at all. The only place where customization is required is active navbar element. Overriding of styles could be done inside styles.scss file using the same css selector for customized element which is used by bootstrap itself.

Colors, used in this project:
$blue:   #2A74BF;
$red:    #D7514C;
$green:  #4D944B;
$orange: #D8C11D;
$grey:   #666;



