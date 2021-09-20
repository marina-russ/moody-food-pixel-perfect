# 📑 Table of Contents

1. [Purpose](#purpose)
2. [Live Page](#webpage)
3. [Process](#process)
4. [Challenges](#challenges)
5. [Design Comp](#designcomp)

# ⭐ Purpose <a name="purpose"></a>

Create a 'pixel-perfect' website based off of a .psd file with no additional information from a client.

This demonstrates the ability to correctly implement a design as well as attention to detail. Instead of creating a vague approximation of the design, the design is brought to life on the page as closely as code will allow.

# 💻 Live Page <a name="webpage"></a>

[Deployed Web Page](https://marina-russ.github.io/moody-food-pixel-perfect/)

# 📐 Process <a name="process"></a>

I started by using Adobe Photoshop to examine the .psd file and collect all the relevant spec information that I needed. Before jumping straight into the HTML, I took a moment to determine semantic elements (such as which headers should be h1, h2, h3, etc) and made an initial list of classes I knew would be needed. Then I typed up all of the text for the page, adding new classes as appropriate. Before I can be distracted by visuals I loaded the HTML file and checked the text for any typos. At that point I was able to start tackling the aesthetics of the page! Because of how blocky this design is, I decided to code the CSS section-by-section. Once all the CSS was done I compared the web page to the design comp file to check for any errors.

## Gathering Information

1. I checked the canvas size to determine that the static design layout is 1440 pixels wide.
2. I inspected all image and 'design' layers to determine the height and width of all graphic elements.
3. I extracted all the images as .png files via `Export -> Layers to Files`.
4. I inspected all text elements to determine font style, size, weight, and tracking.
5. I used the Eyedropper tool to gather all the necessary hex color codes.
6. I utilized the Ruler tool to determine the margins and padding for various elements.

# 🚀 Challenges <a name="challenges"></a>

The "What's new?" section directly underneath the hero image was a little tricky. 
* I had never done vertical and horizontal text in the same section before. I solved that issue for the decorative vertical text by using `transform` to rotate it 270° and then `position: relative` to place it where I wanted it. 
* The decorative yellow box background was also smaller than the section of text on that area of the page. I used `background: linear-gradient` with the top and bottom sections at zero opacity in order to have only part of the `<div>` with a colored background.
* For the list of items underneath the header, there was a large gap between the pipebar and the text. I couldn't just throw in a `margin-left` on the text elements because when an item goes on multiple lines the additional lines of text line up with the pipebar. I ended up using the `:before` pseudoclass to add the pipebar with spaces. The `:before` element wouldn't allow for a string that ended in multiple spaces `"|   "` however, so I hardcoded the spaces in via Unicode characters: `content: "\007C \00a0 \00a0 \00a0";`

- Group 2 orange box
- Getting double spacing to work (unicode characters)
- Group 4 background image opacity without affecting child elements!!!

# 🎨 Design Comp <a name="designcomp"></a>

![Design Comp Preview](images/design-comp-preview.jpg)

## Credits

- The .psd design comp was created by Freepik and is being used under their Premium license.
- Social media icons were made at iconfinder.com
