Many websites contain a variety of different media, like images and videos. When a website contains such media, 
it’s important to make sure that it is scaled proportionally so that users can correctly view it.
In the example above, .container represents a container div. 
It is set to a width of 50% (half of the browser’s width, in this example) and a height of 200 pixels. 
Setting overflow to hidden ensures that any content with dimensions larger than the container will be hidden from view.
The second CSS rule ensures that images scale with the width of the container. 
The height property is set to auto, meaning an image’s height will automatically scale proportionally with the width. 
Finally, the last line will display images as block level elements (rather than inline-block, their default state). 
This will prevent images from attempting to align with other content on the page (like text), which can add unintended margin to the images.
