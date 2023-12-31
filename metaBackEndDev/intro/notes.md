# Introduction to Back-End Developement

# Week 1

## Introduction to the professional certificate

Web developer

- front-end
    - user side
    - what users interact with
    - HTML, CSS, JS

- back-end 
    - what end users don't see
        - ie. DB, architecture, webserver, etc
    - knowledge of back-end languages,  DB, API, webserver, etc
        - also setup, config, resources, IT knowledge

- full-stack
    - both FE and BE
    - knowledge in planning, architecture, design, development, deployment, maintenance

## How the web works

- HTML, CSS, JS -> building, decorations, people

- browser sends request, servers send response

- web hosting
    - shared
        - $
        - physical server
        - serves small websites
    - virtual private server 
        - $$
        - involves physical server to serve multiple VPS
    - dedicated
        - $$$
        - yours and yours alone!

    - cloud
        - includes both physical and virtual servers
        - no hardware limits
        - scalable
        - pay based on resources used

### Additional Resources

[What is a Web Server? (NGINX)](https://www.nginx.com/resources/glossary/web-server/)

[What is a Web Browser? (Mozilla)](https://www.mozilla.org/en-US/firefox/browsers/what-is-a-browser/)

[Who invented the Internet? And why? (Kurzgesagt)](https://youtu.be/21eFwbb48sE)

[What is Cloud Computing? (Amazon)](https://youtu.be/mxT233EdY5c)

[Browser Engines (Wikipedia)](https://en.wikipedia.org/wiki/Browser_engine)

## Core internet technologies

### Introduction to internet protocols

- IPv4 vs IPv6
    - xxx.xxx.xxx.xxx vs xxx:xxx:xxx:xxx:xxx:xxx:xxx:xxx

- IP packets include a header and data

- TCP 
    - prevents the out-of-order delivery of data
        - reassembles packets in order or requests re-transmission of out-of-order packets
    - suitable for text content such as HTML documents
- UDP 
    - does not guarantee that packets will arrive in order or at all
    - prevents data corruption
    - suitable for streaming 

### Introduction to HTTP

- HTTP used to transfer HTML documents, images, files

- request-response
    - request:
        - format: method, path, version, headers
        - methods: GET, POST, PUT, DELETE
            - GET - retrieve a resource
            - POST - send
            - PUT - update
            - DELETE - remove
            - PATCH
    - response:
        - format: header, message body
        - codes
            - grouped by purpose
            - 100-199 - informational
            - 200-299 - successful
            - 300-399 - redirection

                - 302 - temporary
                - 301 - permanent

            - 400-499 - client error

                - 400 - bad data submitted
                - 401 - log-in required
                - 403 - insufficient permissions
                - 404 - response not found

            - 500-599 - server error

                - 500 - internal server error

- versions 1.1 and 2.0 are most used

- HTTPS - secures communications, transmitted info is protected/encrypter

### Other protocols

- DCHP - used to assign a computer an IP address
- DNS - provides a way to know which IP adderss to communicate when visiting a website
- FTP - a way to transfer files from computer to server (insecurely)
- IMAP - a way to DL emains and manage your inbox on the server storing your emails
- POP - older protocol used to DL emails to email client
    - deletes copy on device 
- SFTP - secure transfer over FTP
- SSH - used when you need to log-in and interactive remotely with a computer
    - all data sent is encrypted
- SMTP - a way to send emails

### Webpages, websites, and web apps

- webpage
    - single page using HTML, CSS, JS
- websites
    - multiple webpages under the same domain
    - more informative than web apps
- web apps
    - dynamically update content, personalized content
    - high level of interactivity compared to websites

### Developer tools

- browser tool - inspect
    - elements - lets you inspect the different elements on a page
    - console - outputs js logs
    - sources - content resolved for page
    - network - inspect time and details of http request
    - performance - pinpoints functions that are taking up most time
    - memory - what's consuming the most resources

### Frameworks and libraries

- compare to using a hammer
    - you wouldn't use a new hammer - you'd reuse the hammer you have

- libraries 
    - reusable pieces of code
    - specific functionality
    - time saving
    - ie. email validation 
    - pros
        - can be replaced
    - cons
        - selecting library set
        - compatibility with other libraries

- frameworks
    - provide a structure for developers to build with
        - to build a chair, you'd need a blueprint
    - ie. framworks for developing applications
        - express, django, asp.net, rails, spring
    - pros
        - time saving
        - enforces structure
        - follows best practices
    - cons
        - structure constraints
        - compatibility with libraries you want to use

- frameworks contain libraries

- when?
    - frameworks - opinionated
    - libraries - un-opinionated

### APIs and services

- API
    - set of functions to access features
    - aka gateway or middleware
    - act as bridge between systems
    - ie.
        - REST
            - provides data for web/mobile apps
            - aka webservers
            - set of principles
            - provides response to request
        - sensor-based
            - what IoT is based on
            - actual physicals sensors tha can communicate with each other
        - DOM - html to tree of nodes
        - geolocation
        - fetch
        - canvas
        - history
        - web storage
    - APIs use REST principles
        - use endpoints (ie. stuff after / in the URL)


### IDEs

- can be specific to a programming language
- set of tools a dev uses (much like a carpenter and their toolbox)
- features
    - error/syntax highlighting
    - auto-completion
    - refactoring
    - debugger

### Additional Resources 

[HTTP Overview (Mozilla)](https://developer.mozilla.org/en-US/docs/Web/HTTP/Overview)

[Introduction to Networking by Dr.Charles R Severance](https://www.amazon.com/Introduction-Networking-How-Internet-Works/dp/1511654945/)

[Chrome Developer Tools Overview (Google)](https://developer.chrome.com/docs/devtools/overview/)

[Firefox Developer Tools User Docs  (Mozilla)](https://firefox-source-docs.mozilla.org/devtools-user/index.html)

[Getting Started with Visual Studio Code  (Microsoft)](https://code.visualstudio.com/docs)

## Glossary

**CSS** - cascading style sheets

**DNS** - domain name system 

**DHCP** - dynamic host configuration protocol

**FTP** - file transfer protocol

**HTML** - hypertext markup language

**HTTP** - hypertext transfer protocol

**IDE** - integrated development environment

**IMAP** - internet message access protocol

**POP** - post office protocol

**REST** - representation state transfer

**SFTP** - SSH file transfer protocol

**SMTP** - simple mail transfer protocol

**SSH** - secure shell protocol

**TCP** - transmission control protocol

**UDP** - user datagram protocol

**URL** - uniform resource locator

# Week 2

## Getting Started with HTML

- HyperText Markup Language
- hyptertext - text which contains links to other text
- markup - tags/elements used in a document

- W3C maintains HTML
- HTML5 current version 
- use CSS to pretty up a webpage

- HTML doc begings with DOCTYPE declaration
- DOM to represent the HTML doc in JS

### WAI

- Web Accessibility Initiative
- improves web accessibility for people with disabilities
- done so by:
    - correct HTML structure
    - ARIA techniques (Accessible Rich Internet Application)
    - appropriate use of HTML elements

### Additional Resources

[HTML Elements Reference (Mozilla)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

[The Form Element (Mozilla)](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form)

[What is the DOM? (W3C)](https://www.w3.org/TR/WD-DOM/introduction.html)

[ARIA in HTML](https://w3c.github.io/html-aria/)

[ARIA Authoring Practices (W3C)](https://www.w3.org/TR/wai-aria-practices-1.2/)

## CSS Basics

### Box Model

- 4 parts:
    - content - you
    - padding - your clothes 
    - border - your silhoutte or outline
    - margin - personal space between you and the next person

### Block vs Inline

- block
    - stack upon each each other and begin a new linec
    - p, div, etc
- inline
    - continuous flow
    - occupy the width and height of their content and do not appear on a new line
    - a, span

- use CSS to change from block to inline and vice-versa

### Syntax

- consists of:
    - selector (ie. h1)
    - declaration block (ie. {})
        - properties
            - `propertyName: propertyValue`
            - `color: blue;`
- Elements: `h1 { color: blue; }`
- Classes: `.className { } `
- Elements with IDs: `.idName { }`
- Child Elements: `parent > child { } `

### Additional Resources

[CSS Reference (Mozilla)](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

[HTML and CSS: Design and build websites by Jon Duckett](https://www.amazon.com/HTML-CSS-Design-Build-Websites/dp/1118008189/)

[CSS Definitive Guide  by Eric Meyer](https://www.amazon.com/CSS-Definitive-Guide-Visual-Presentation/dp/1449393195/)

# Week 3

## Intro to UI and Frameworks and Libraries

### Working with Libraries

- bootstrap css
    - `<link href="[link]" rel="stylesheet">`
- js
    - `<script src=""></script>`

- dependency tree
    - where you have libraries that can depend on other libraries

- package manager
    - allows you to handle the dependencies given a version

- npm (node package manager)
    - most common

- include all your dependencies in your html using a bundler (ie. gulp, webpack)

### Introduction to responsive design

- allows the website to automatically stretch or shrink depending on the screen it is displayed on

- set of 3 practices:
    - flexible grids
        - columns
        - gutters (space between columns)
        - margins (space between content and L and R edges of screen)

        - defined in percentage values
    - fluid images
        - set css max width property of images to 100%
        - images will scale down smaller if containing columns becomes narrower
            - will not grow larger and become pixelated if column becomes wider than image
    - media queries
        - query the display size, orientation, aspect ratio

- breakpoint (pixed value specified)
    - the point which a website's content and layout will adapt to provide the best possible experience
    - can function in different ways across different grids
        - fixed grid
            - fixed width columns and flexible margins
        - fluid grid
            - full-width grids
            - fluid-width columns, fixed gutters and margins
            - flexible content
        - hybrid
            - has both fluid-width and fixed-width components

### Bootstrap

- library of CSS and JS code

- modern web dev all about components
- bootstrap comes with multiple components

- responsive grids are also important
- bootstrap comes with pre-made set of CSS rules

#### Bootstrap Styles

- bootstrap modifiers add a CSS class to change the visual style of components
- use an infix to indicate the breakpoint

| Breakpoint | Class infix | Dimensions |
| -------- | -------- | ------------- |
| Extra small |  | < 576 px |
| Small | sm | >= 576 px |
| Medium | md | >= 768 px |
| Large | lg | >= 992 px |
| Extra large | xl | >= 1200 px | 
| Extra extra large | xxl | >= 1400 px |

- bootstrap is mobile first, so no infix for extra small

#### Bootstrap Grid

- grid
    - 12-column grid system
    - can be fluid or fixed
- elements
    - container
        - root `<div class="container"></div>`
        - always start with this
        - contains pads and aligns content
        - width determined by responsive breakpoint
    - row
        - `<div class="row"></div>"`
        - in each row you can add columns
    - column
        - `<div class="col-12 col-lg-6"></div>`
            - `col-12` no infix so for mobile, span the full width (12 columns)
            - `col-lg-6` so for large screens, half-width

#### Bootstrap Components

- pre-made set of UI elements and styles
- ie. ramge from alert message to navigation menus

- ones used in video:
    - badge
    - alert, alert-info
    - card, card-img, card-title, card-body

### Other CSS frameworks and libraries

[Foundation](https://get.foundation/)
- similar to Bootstrap
- used by Pixar, Polar, Sonos, etc
- can be used to style content for sending via email

[Pure.css](https://purecss.io/)
- building UI
- not as many features as Bootstrap
- designed to be minimal
    - ie. smaller size improves loading time

[Tailwind](https://purecss.io/)
- utility approach for CSS rules
- many CSS classes with a single purpose

[UIKit](https://getuikit.com/)
- small set of responsive commponents
- simple design

[MVP.css](https://andybrewer.github.io/mvp/)
- small CSS library that automatically styles HTML elements without needing to apply CSS classes
- aims to allow to quickly prototype a UI without worrying about the final design
- MVP comes from "minimal viable product"

### Additional Resources

[Bootstrap Official Website](https://getbootstrap.com/)

[Bootstrap 5 Foundations by Daniel Foreman](https://www.amazon.com/Bootstrap-Foundations-Mr-Daniel-Foreman/dp/B0948GRS8W/)

[Responsive Web Design with HTML5 and CSS by Ben Frain](https://www.amazon.com/Responsive-Web-Design-HTML5-CSS/dp/1839211563/)

[Bootstrap Themes](https://themes.getbootstrap.com/)

## Introduction to React

### Static and dynamic content

- static content
    - doesn't change
    - sent directly from the server
    - faster to generate than dynamic content

- dynamic content
    - changes based on interaction with user
    - must be generated by an application server before the web server sends the content in an HTTP response
        - thus, slower to generate than static content

browser -> web server -> application server
        <-            <-

application server
- used for every type of content
- limited capacity for requests per second
- cache stores dynamic content so the web server doesn't need to hit the app server constantly

### Single page applications

Traditional websites
- multiple pages

SPA (single-page applications)
- doesn't mean one page, but one HTML page and the content is updated
- responses from the web server are in JSON format
- 2 approaches to delivering resources
    - bundling
        - everything is loaded
    - lazy loading / code splitting
        - minimum resources are loaded
        - retrieve others as required

### What is React?

- focused on working with components
- can be used with other JS libs
- benefits
    - write less code to implement functionality
    - maintain code
    - re-use components
    - simplify testing

### How React Works

- react element 1:1 HTML element
- reconciliation
    1. virtual DOM (vDOM) updated
    1. vDOM compared to previous version of vDOM
    1. changed elements updated in browswer DOM (bDOM)
    1. website is updated to match bDOM
- only updates when necessary
    - what if there are a lot of updates?
        - can be expensive and slow
        - solution?
            - React Fiber Architecture
                - incrementally render web page "over time"
                - priority updates done on elements that are visible
                - visible elements (ones current on screen) are more important than non-visible ones

### Component Hierarchy

- contains at least one component (app or root component)
- components added to root to build out a tree structure
- components are reusable!
    - multiple instances of the same component would just have different properties
        - ie. in a menu
            - two food item components
                - one chicken dish
                - one beef dish

- example: blog website
    - root component
        - navigation bar component
            - title
            - navigation links component
            - search component
        - page component
            - main feature component
            - small feature component x2

### React and complementary libraries

[Lodash](https://lodash.com/)
- utility library
- common logic

[Luxon](https://moment.github.io/luxon/#/)
- helps with date and time formatting

[Redux](https://redux.js.org/)
- manages application state
    - ie. tracks items in shopping cart

[Axios](https://axios-http.com/)
- simplifies sending of HTTP requests and processing of responses

[Jest](https://jestjs.io/)
- js testing framework
- focus on simplicity
- provides reporting utilities

### Additional Resources

[React Official Website](https://reactjs.org/)

[Choosing between Traditional Web Apps and Single Page Apps (Microsoft)](https://docs.microsoft.com/en-us/dotnet/architecture/modern-web-apps-azure/choose-between-traditional-web-and-single-page-apps)

[React Source Code (Github)](https://github.com/facebook/react)

[Introduction to React.js](https://youtu.be/XxVg_s8xAms)

