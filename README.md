# UnderlineJS

a **pixel-perfect** javascript library for drawing text underline, and maybe `animate` it, `data-viz` it, and more

The goal of this project is not to succeed, but fail. 

If one day there is absolutely no reason to use this third party js library to render underline, I would be very happy. That means the browser has supported  this feature natively. And that is my goal, to push the W3C further in a pixel-perfect, designer-friendly route.

## Example
[**http://wentin.github.io/underlineJS/article.htm**](http://wentin.github.io/underlineJS/article.htm)
(paragraph "What we’ve got …" text underline is canvas rendered!
example designed by Wenting Zhang(me) in huffpost labs, article by Katelyn Bogucki from huffpostcode 

## Logs
##### Dec 2, 2014
* start proof of concept
* it now works on chrome/safari!

## To do list

- firefox bug
  - ctx.textBaseline="top”; render just like hanging

- detect and deal with line break word `done`

- make canvas width precise, 5px offset has to go `done`

- css like setting options.

- dynamic getting font styles `done`
  - maybe add font rendering styles and kern

- round posY to .5 px `done`

- underline stroke according to font stroke width `done`

##Contact
* Follow [@DesignJokes](http://twitter.com/DesignJokes) on Twitter
* Email <zhangwenting111@gmail.com>
* Visit [wentin.co](http://wentin.co)