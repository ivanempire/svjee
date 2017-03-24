# SVJee
Will slowly be building up a collection of SVG animations made with D3 and other tools. Doing this to create (and build up) my Dribbble portfolio. Profile is [here](https://dribbble.com/ivanempire).

## Glow
This one is the debut shot - yay! It was my first attempt at a bare bones SVG animation. Basic text glow effect with a changing amount. Everything from the container initialization to text to filter additions is done with D3. The text alignment in SVG is a pain, I only used text-anchor and alignment-baseline. Documentation for those can be found here:

 - [text-anchor](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/text-anchor)
 - [alignment-baseline](https://developer.mozilla.org/en-US/docs/Web/SVG/Attribute/alignment-baseline)

The glow is applied to the text through the use of a GaussianBlur filter in SVG. The animation is done using an (what I read on some sites/forums) outdated technique - SMIL. I don't know, JS and CSS keyframes seemed a bit too messy for this one. D3 handled it just fine - some of my sources:

 - [D3JS glow](http://www.visualcinnamon.com/2016/06/glow-filter-d3-visualization.html)
 - [SVG filters](https://developer.mozilla.org/en-US/docs/Web/SVG/Element/filter)

## Bubbles
This is my second shot for Dribbble. There have been several in the works for a while now, but I had a very clear picture of what I wanted this one to look like. The resources used for this shot:

 - [linear gradient](https://developer.mozilla.org/en-US/docs/Web/CSS/linear-gradient)
 - [radial gradient](https://developer.mozilla.org/en-US/docs/Web/CSS/radial-gradient)
