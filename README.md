# Design Research: Elaine de Kooning's 'Untitled Bull'

## Part 1: Imaging Technique Inspiration

![Jordan Kim Collage 1](https://www.creativeboom.com/upload/articles/64/64d506e5238807f700c16296d2a7bcb17c15a8c3_944.jpg)
![Jordan Kim Collage 2](https://www.creativeboom.com/upload/articles/03/03444548e7c55a374f9190b49d09e793e69bd760_944.jpg)

Jordan Kim’s layered collage technique inspires me to approach [*Untitled Bull*](https://uploads6.wikiart.org/images/elaine-de-kooning/untitled-bull-1973.jpg) by Elaine de Kooning not through direct realism, but through compositional assembly. Her use of distinct paper textures and shaped fragments echoes the painterly segmentation in de Kooning’s work. For our code-based representation, I want to simulate a similar fragmented visual language—cutting the form of the bull into abstract, class-based geometric regions that can be animated independently. This collage-inspired structure fits our project’s focus on abstraction, modularity, and form reconstruction.

## Part 2: Coding Technique Exploration

### Canvas API with Polygon Clipping

The HTML5 Canvas API combined with polygon clipping algorithms could effectively recreate de Kooning's distinctive style. This technique would allow for creating irregular, overlapping color regions with precise boundaries similar to the 1973 'Untitled Bull'. By defining clipping paths that follow the dynamic contours of the bull and filling these with bold colors, we can achieve the vibrant, expressive quality of the original artwork. The Canvas API's compositing operations further enable the creation of complex color interactions where shapes intersect.

**Example Implementation**: [Canvas Clipping Techniques](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Compositing)

### Paper.js Path Manipulation

Paper.js offers sophisticated vector graphics manipulation that could effectively capture de Kooning's abstract expressionism. Its path operations and boolean functions allow for creating complex, overlapping shapes with the bold outlines characteristic of the 1973 'Untitled Bull'. The library's handling of path segments enables precise control over the dynamic, angular lines while maintaining fluid composition. Additionally, Paper.js's color management system makes it ideal for implementing the vibrant color blocks that define de Kooning's work.

**Example Implementation**: [Paper.js Path Tutorials](https://paperjs.org/tutorials/paths/) 
