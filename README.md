# FOTOMATIC Project

The brief was to fix an existing webpage from any bugs, make it responsive, and then style it accordingly to
the [image reference](fotomatic_spec_landing.png).

My first step was to fix any bugs on the HTML index, here the list:

1. The html element was missing the lang attribute.
2. The head section was missing:
    1. The title attribute.
    2. The link to the CSS stylesheet, only the CSS reset was linked.
    3. The viewport meta tag for responsive design.
3. The main body had several issues:
    1. Ten images were missing the alt attribute.
    2. Four images had a wrong relative path.
    3. There were also four minor mistypes on the actual text content.

The second step was to fix the CSS file, which also contained a few errors:

1. A minor issue were the "px" was redundant as the value was set to 0.
2. Six instances were the class selector was missing the dot.
3. The media queries were randomly placed within the CSS file in mix order, creating issues.

After fixing those errors, it was time to finally style the page following the [image reference](fotomatic_spec_landing.png). This was my
first attempt to make a page responsive. Both HTML and CSS files were given, but they needed quite a few adjustments. Also, the final
website, given as an example, was not following the [image reference](fotomatic_spec_landing.png) accurately, so I decided to follow the
image as it was more challenging.

The major adjustments were:

1. Creating an HTML section for the Navbar, when viewed on tablet, the default html had only a desktop and mobile version of it, so when
   resized to medium size like in the case of tablets, it was already stepping on the mobile version, with icons rather than text.
2. Styled the page as described by the [image reference](fotomatic_spec_landing.png).
3. Changes several paddings and margins to make sure the text didn't come to close to the edge of its parent.
4. Changed the "Filter section" in the tablet mode to show four images instead of three, as shown in
   the [image reference](fotomatic_spec_landing.png).
5. Finally, the biggest challenge I found was to fix an issue where the text in the banner was not shrinking down, causing the page to show
   the horizontal scrollbar when resized to very small. At the end, it came out to be a very simple solution though.