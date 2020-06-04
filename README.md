## HTML / CSS Layout Test
The CSS for this solution has been built with standard CSS and not SCSS or LESS. This is to avoid having an additional build step. I would usually write CSS in SCSS / LESS with either Webpack or Gulp handling the build step.

I have built the layout using Flexbox as I don't think there is a need to use Grid in this instance. The solution to the problem can be fulfilled without having to implement additional fallbacks for IE11 support, which would have been required had I chosen to use Grid.

I've taken a mobile-first approach, thus setting the base column width to 100% and adjusting the column sizes when reaching larger breakpoints.

CSS namespacing has been implemented with BEM (Block, Element, Modifier) syntax.

Some browser resets have been added to handle base margin, padding and font size on the body element to maintain consistency across browsers.

Although the CSS could have been added in a style tag in the index.html file, I've decided to keep it separate in it's own CSS file, as it would be done in a larger project.
