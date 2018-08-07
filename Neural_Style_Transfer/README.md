# neural-style-pt

This is a PyTorch implementation of the paper [A Neural Algorithm of Artistic Style](http://arxiv.org/abs/1508.06576)
by Leon A. Gatys, Alexander S. Ecker, and Matthias Bethge. The code is based on Justin Johnson's [Neural-Style](https://github.com/jcjohnson/neural-style).

The paper presents an algorithm for combining the content of one image with the style of another image using
convolutional neural networks. Here's an example that maps the artistic style of
[The Starry Night](https://en.wikipedia.org/wiki/The_Starry_Night)
onto a night-time photograph of the Stanford campus:

<div align="center">
 <img src="https://raw.githubusercontent.com/ProGamerGov/neural-style-pt/master/examples/inputs/starry_night_google.jpg" height="223px">
 <img src="https://preview.ibb.co/hhA2ke/Ashoka_University.jpg" height="223px">
 <img src="https://image.ibb.co/hHpjyz/ashoka_starry.jpg" width="710px">
</div> 


