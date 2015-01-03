# GeeMail 

GeeMail is a coding exercise meant to simulate an e-mail web application inbox.

* **Author**: [FVCproductions][]
* **Source Code**: [GitHub][]

---

## Description

* coding challenge done for [DevLeague](http://devleague.com)
* simple simulation of a little known current e-mail web application

---

## Pre-Requisites

I needed the following tools:
* [Personal GitHub Account](http://github.com/fvcproductions)
* [Sublime Text 3 ](http://www.sublimetext.com/3)
* [Git](http://githubformac.com)

---

## Objectives

1. Fork repository to own GitHub profile and clone to local machine.

2. Create basic page layout via HTML/CSS with top header section with name of application and content section where messages will be displayed.

3. When page loads, via JavaScript access our pre-populated data stored in the `window.geemails` variable. Each object in the array has following properties:
	* `date` - The date message was sent
	* `subject` - The subject of the message
	* `sender` - The sender of the message
	* `body` - The GeeMail message content

4. With this data, make a visual list of mail messages on the page with following minimum requirements:
	* Each message should have it's own row showing:
		* Date
		* Sender
		* Subject
	* When clicking on a message, provide some method of showing message for that row.

5. Show an inbox count somewhere on page to show current number of messages in inbox.

6. Set recurring function to via JavaScript `setInterval` function that will call existing `getNewMessage` function that was already created that will return a newly created message with same properties as previous messages.

6. All CSS styles should be created in `css\style.css` file included in project. 

7. All JavaScript should be created in `<head>` element in included `index.html` file inside of `window.onload` function already created in `<head>` section.

---

## Dates

* January 2015

[FVCProductions]: http://fvcproductions.com
[Github]: https://github.com/fvcproductions