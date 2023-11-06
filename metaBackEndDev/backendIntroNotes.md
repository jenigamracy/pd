# Introduction to Back-End Developement

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

## Core internet technologies

### Introduction to internet protocols

- IPv4 vs IPv6
    - xxx.xxx.xxx.xxx vs xxx:xxx:xxx:xxx:xxx:xxx:xxx:xxx

- IP packets include a header and data

- TCP 
    - prevents the out-of-order delivery of data
        - reassembles packets in order or requests re-transmission of out-of-order packets
- UDP - does not guarantee that packets will arrive in order

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

