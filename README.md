S Q U A R E S . J S
=========

A small javascript library for creating tiled effects.

SquaresJS is a small( < 2KB) javascript library that allows you to create some interesting effects with squared tiles.


How to Use
==========

Download the squares.min.js file and insert as a script tag in your HTML
    `<script src="squares.js"></script>`


Then, you create a canvas like so:
    `<canvas id="canvas" width="2000" height="1000"></canvas>`

And then insert the following after the body:
    
		var squares = new squaresjs(width,height,square_size);
		squares.draw();
		
		
where width and height are the size of the canvas and the square size is any size you like.





