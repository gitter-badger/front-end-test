# Front-end test

You'll have few days to integrate a single page with HTML, CSS and JavaScript.
(You can download the [PSD on Wetransfert](http://bit.ly/1W5gaDB)).

### Task List Syntax

1. Create a [Github](http://github.com) account
	* Personalize your profite with an avatar and all personal information.
	* Send to me ([diasd@proximity.bbdo.fr](mailto:diasd@proximity.bbdo.fr)) your username by email.
2. Open the PSD into Photoshop or [Gimp](https://www.gimp.org/).
3. Create a project called "my-awesome-app" and start to develop on a new branch called **develop**.
4. You'll build a responsive web site with 12 columns (even without mobile PSD, the website needs to be responsive).
	- You'll use SASS to code your CSS.
	- You'll use Boostrap (SASS) or Foundation 6.
	- You'll create a simple JavaScript files with one or two functions or plugins, to show us how you are struturing your JavaScript files. 
5. You can develop in HTML or use Jade (recommended).
6. Commit your work regularly adding an explicit message.
7. You'll check your work at least one one mobile device (IOS or Android) and on all modern brower (Chrome, Firefox, IE 10+)
8. Check the quality of your development using the Front-end checklist.
9. When you work is done, push you develop branch into the master.

## Front-end checklist

Your single HTML page needs to respect all the standards rules you'll find below. Take time to insure the quality of your development. If you don't have time to do all the tests, prioritize what could be the most importante.

### Head

* The Doctype is HTML5 and present in all pages
* The lang of your website is specified
* Direction of lecture specified
* Charset declared (UTF-8)
* X-UA-Compatible meta tag
* Title tag is used in all pages - No more than 65 characters
* The viewport was declared correctly
* CSS is linked before JavaScript files in the <head>

### CSS

* The CSS was tested and pertinents errors were corrected (http://jigsaw.w3.org/css-validator/)
* SASS was used as CSS preprocessor
* ID are not used (only if needed for the JavaScript).
* A CSS normalize is used and up to date.
* All classes (or id- used in JavaScript files begin by js- are not styled into the Sass files
* CSS files are concatened
* CSS files are minified
* Remove unused CSS
* Use CSS vendor prefixes
* Pages were tested with DebugCSS http://yahoo.github.io/debugCSS/ (you can use the bookmarklet)
* Pages are close to Pixel perfect (https://chrome.google.com/webstore/detail/perfectpixel-by-welldonec/dkaagdgjmgdmbnecmcefdhjekcoceebi?hl=en)

### HTML

* A label is associated with each input form element
* A print stylesheet is provided and is correct on each page
* Pages are W3C compliant (in a logical way)
* Clean up commented / unnecessary code
* Specific HTML5 input types are used
* Pages respect the accessibility standards http://wave.webaim.org/
* All images are optimized (PNG and JPEG)
* Each image have an alt and it is not empty (except design element)
* All images have height and width and alt.
* Small images are in a sprite or a webfont

### JavaScript

* JavaScript files ars concatened
* avaScript files are minified
* No JavaScript errors detected with ESLINT
* The modernizr is custom
