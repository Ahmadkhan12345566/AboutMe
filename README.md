# AboutMe
Basic Front-end develpment

## Browser Defaults vs. resetting vs. normalizing CSS
The final topic we want to briefly touch on in this reading is the issue of browser style defaults, and how developers use CSS resets or CSS normalization to ensure a consistent experience across browsers.

As we saw earlier in this unit, your browser has default styling for many elements. For instance, if you use ``<h1>`` and ``<h2>`` elements on a page but don't add any custom CSS, your browser will still render the ``<h1>`` as larger than the ``<h2>``. This is a good thing in that you can view HTML without writing CSS, but it's a bad thing in that you may not want the defaults. Furthermore, browsers differ in their defaults, which means your end users might get a different experience when they're using Chrome than when they're using Firefox.

There are two common solutions to this problem. The first strategy is to use a CSS reset, the [most popular of which is the Meyer reset](http://meyerweb.com/eric/tools/css/reset/reset.css). By linking to this file in your HTML (above your other style sheets, so it sets a base that they add to), you can guarantee cross-browser consistency for default styles.

Another option is [normalize.css](https://necolas.github.io/normalize.css/), which is a CSS library that normalizes a subset of browser elements to be consistent between browsers.

## Web Detective 201: CSS Power Mode with Dev Tools
Now that we're dealing with CSS, we're going to start seeing the power of Developer Tools. Developer Tools allows you to instantly change how everything about a webpage looks. You can inspect the CSS applied to any element, locate the source code (that is, the original file that was downloaded that contains a set of style rules), change, delete, and add attributes, visualize the overall dimensions of an element, and see an element's computed styles.

This interface is perfect for CSS detective work on existing sites, brainstorming style changes, and solving styling bugs.

When you're working on the styles for a project, you can preview your page in the browser, experiment with different settings in Developer Tools, then save the changes you like back in your source code, using your text editor. Getting into this habit puts you on the path to a powerful workflow.
for more [visit](https://courses.thinkful.com/gh-studentv2/assignment/1.3.2).
