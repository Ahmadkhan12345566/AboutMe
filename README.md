# AboutMe
Basic Front-end develpment

## Browser Defaults vs. resetting vs. normalizing CSS
The final topic we want to briefly touch on in this reading is the issue of browser style defaults, and how developers use CSS resets or CSS normalization to ensure a consistent experience across browsers.

As we saw earlier in this unit, your browser has default styling for many elements. For instance, if you use <h1> and <h2> elements on a page but don't add any custom CSS, your browser will still render the <h1> as larger than the <h2>. This is a good thing in that you can view HTML without writing CSS, but it's a bad thing in that you may not want the defaults. Furthermore, browsers differ in their defaults, which means your end users might get a different experience when they're using Chrome than when they're using Firefox.

There are two common solutions to this problem. The first strategy is to use a CSS reset, the [most popular of which is the Meyer reset](http://meyerweb.com/eric/tools/css/reset/reset.css). By linking to this file in your HTML (above your other style sheets, so it sets a base that they add to), you can guarantee cross-browser consistency for default styles.

Another option is [normalize.css](https://necolas.github.io/normalize.css/), which is a CSS library that normalizes a subset of browser elements to be consistent between browsers.
