VisuallyIconic-JS-SVG

Description:

"VisuallyIconic-JS-SVG is a JavaScript/CSS library designed to seamlessly integrate custom SVG icons into web applications. The library introduces a custom mnemonic <VI></VI> to facilitate the implementation of a user-defined set of SVG icons.

Key Features:

Custom `<VI>` Tag Integration: The library enables the use of the `<VI>` tag within HTML documents, allowing developers to easily specify icons for various elements.

Dynamic Icon Replacement: The replaceViTags() JavaScript function dynamically replaces `<VI>` tags with corresponding SVG icons defined within the library.

Flexible Icon Configuration: Icons can be configured using attributes such as icon for specifying the icon name, size, filters, etc.

Class Inheritance: The library supports the inheritance of classes from the `<VI>` tag to the generated SVG element, enabling seamless styling and customization.


Usage: Define your custom SVG names and elements in the `window.icons = { };` found at the top of `vi-icons-live.js`

For each SVG first name it like so `customSVG1` / etc.

Make sure you add the CSS & JS file to your page `<script src="vi-icons-live.js"></script>
<link rel="stylesheet" href="vi-style.css">`

Once you have defined your SVG you can call and manipulate them as you wish. Still has work to be done but solid basis so far, does as explained.

 Like in the example-page.html

 `
 <vi icon="gearIcon" class="bounce" size="width: 60px; height: 60px;" onclick="window.open('https://google.com/', '_blank',)"></vi>
<vi icon="userIcon" class="fade-in" size="width: 60px; height: 60px;"></vi>
<vi icon="gearIcon" class="slide-in-left" size="width: 50px; height: 50px;"></vi>
<vi icon="userIcon" class="rotate" size="width: 50px; height: 50px;"></vi>
<vi icon="gearIcon" class="pulse"></vi>
<vi icon="userIcon" class="color-change"></vi>
<vi icon="userIcon" class="color-shift"></vi>
 `





