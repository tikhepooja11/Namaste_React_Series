Namaste React Notes -

1.	Emmet command - Type in vs code file for boiler plate code
	html:5			- for html boiler plate code

2.	CDN react - get react library from CDN and inject into your file
	why 2 files of React -> React file - Just contains core of react used for UI building
						React DOM - contains React code necessary to modify DOM elements
						

3.	React gives a super powerful helper functions to manipulate the DOM using JS library, as 
	adding & removing html elements(nodes of a DOM tree) from a DOM used to be a very costly operation,
 
	Philosophy behind building React - Manipulate DOM using Javasccript


4.	React.development.js & React.production.js diff
	In a typical development workflow, you would use the react.development.js version during development to take
	advantage of the additional debugging and warning features. When deploying your application to a production environment,
	you would switch to using the react.production.js version to optimize file size and runtime performance.
	
5. 	Module vs Package
	Module is single JS file while package contains folders of various modules ( JS files ) along with package.json
	
6.  Library vs Framework -
	Library is previously (predefined) written code so that developers can directly include it in their code and use to perform specific tasks
	while framework is basically used to build entire application so acts as skeleton of an application. 
	It states the overall architecture, control flow & how components interact with each other.
	
7. Why react named as React ->
	beacuse its capability to react to data changes on updating the UI.

8. CrossOrigin ->
	Its an attribute in script or link tag which determines whether the browser should allow data to be fetched from different origins or domains
	Cross-origin requests occur when a web application requests a resource from a different domain, protocol, or port than the one from which the current page originated. 
	It has two values -> anonymous & use-credentials
	anonymous -> we dont passes any cookie or http authentication. Used for such requests which does not requires authentication
	use - credentials -> passes credentials require to proceed with the successful response from a request. such as cookie or authentication data