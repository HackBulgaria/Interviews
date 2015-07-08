# A web application for learning list

Implement a web application, which makes organizing learning resources easy:

* Have a login / register functionality. You can use OAuth, if you want (and can)
* Once logged in, have an interface in which you should be able to create a **Learning Track**

## Learning Tracks and Groups

One learning track should have:

* A name
* A description
* A list of online resources, organizded in different groups of the learning track.

One resource can be just a URL to somewhere else. Nothing more.

The user should be able to organize a learning track by creating new groups and adding resources to a given group.

Once created, the learning track should be able to:

* Be shared with a unique URL to everyone, withour requiring a login to see it.
* Be edited by the user that created it.


## Example

In a markdown, here is how one learning track should look like:

```markdown
# Track for JavaScript

Description - some resources to learn JavaScript

## Group 1 - Getting your way arround

* https://www.javascript.com/
* https://www.codeschool.com/paths/javascript 

## Group 2 - HackBulgaria's JS Courses

* https://github.com/HackBulgaria/Frontend-JavaScript-1
* https://github.com/HackBulgaria/Frontend-JavaScript-2

## Group 3 - Backend JavaScript

* https://nodejs.org/
* https://github.com/HackBulgaria/NodeJS-1
```

Once created, the track should be able to be shared with a link. For example:

```
http://example/tracks/11ffhhj234
```
