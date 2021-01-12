# Forms
## Traditionally, the term 'form' has referred to a printed document that contains spaces for you to fill in the information

## Why Forms?
### The best-known form on the web is probably the search box that sits right in the middle of Google's homepage.

## Form Controls
- Text input
- password
- text-area

# How Forms Work
## A user fills in a form and then presses a button to submit the information to the server.

# Form Structure
- <form>
- <input>


# Button & hidden Controls
## The <button> element was introduced to allow users more control over how their buttons appear, and to allow other elements to appear inside the button.

### Labelling Form Controls
### Grouping Form Elements


## Form Validation
- Email
- Date
- Url
- Search 

# Lists, Tables, and Forms in CSS
## There are several CSS properties that were created to work with specific types of HTML elements, such as lists, tables, and forms.

## Buttle point style
- list-style-type
- list-style-image
- list-style-position
- list-style
- empty-cells

## Cursor Styles
- cursor

# Web Developer Toolbar
- outline
- structure
- CSS styles

# Events 
## When you browse the web, your browser registers different types of events. It's the browser's way of saying, "Hey, this just happened." Your script can then respond to these events.
- interactions create events
- events trigger code
- code responds to users

## DIFFERENT EVENT TYPES
- load
- unload
- scroll 
- error
- keydown
- click
- mousemove
- input
- select

# HOW EVENTS TRIGGER JAVASCRIPT CODE
## When the user interacts with the HTML on a web page, there are three steps involved in getting it to trigger some JavaScript code. Together these steps are known as event handling.
- Select element 
- specify event
-  call code

## TRADITIONAL DOM EVENT HANDLERS 
### All modern browsers understand this way of creating an event handler, but you can only attach one function to each event handler.

## EVENT LISTENERS
### Event listeners are a more recent approach to handling events. They can deal with more than one function at a time but they are not supported in older browsers.

## Event Flow 
### HTML element nest inside other element 

# THE EVENT OBJECT
## When an event occurs, the event object tells you information about the event, and the element it happened upon

# EVENT DELEGATION
## Creating event listeners for a lot of elements can slow down a page, but event flow allows you to listen for an event on a parent element.

# USER INTERFACE EVENTS
### User interface CUI) events occur as a result of interaction with the browser window rather than the HTML page contained within it, e.g., a page having loaded or the browser window is resized.


