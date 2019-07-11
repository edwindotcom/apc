# APC - How to build a website

## Background - The Internet
The internet a way computers can connect and transmit text/images to each other.  Sort of like a phone with an agreed upon language and phone number system of area codes and numbers. 

* Phone number (510-555-5555) is like Internet Protocol Address (172.217.0.46)
* Switch board to connect works to IP addresses: Doman Name Service (DNS) www.google.com is 172.217.0.46
* The language two people speak and understand = Hyper Text Transfer Protocol (HTML) and other text/images
* Browser reads HTML and lays it out on the screen

#### Other helpful things

* file extension: letters after the period '.' is an extension that tells computers whats inside the file.  
** JPG = Joint Photographic Experts Group
** GIF = Graphics Interchange Format
** URL = Uniform Resource Locator, it's the text you type to find the site you're looking for: https://www.google.com
** Hyperlink = text that jumps to a different address (URL)
** Browser = Application on a computer that can open a URL and layout HTML it recieves, Chrome, Firefox, Edge, IE, Safari

## Let's Build a site

  1. Goto https://neocities.org
  1. Click 'edit' or 'start building'
  1. Add some text
  1. publish your site and look at it
  1. Add an image
  1. keep doing it till you're happy with it.
  
  
#### Basic HTML Tags

HTML tags are greater and less than symbols surrounding text  `<tag>some text</tag>`. The tag, part in brackets, describes around the text inside it. So `<b>Hello</b>` is **Hello**.
  
* `<html>` tells browser this is HTML format
* `<head>` known as the header, tells it details about the page, but not to display
* `<body>` the body of the document, this is the stuff to display in the browser
* `<h1>...<h6>` heading tags, how big to display this text as a heading
* `<p>` paragraph tag
* `<a>` anchor tag - this is a hyperlink and `href` attribute tells the browser where to go if it's clicked
* `<img>` image tag - this is an image and `src` tells the browser where to load it from
* `<ul><li>` start a group of bulleted lists, and `<li>` is a list item
