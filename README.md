# moody-food-pixel-perfect

# Purpose

Create a pixel-perfect website based off of a .psd file with no additional information from 'client'.

# Process

I started by using Adobe Photoshop to examine the .psd file and collect all the relevant spec information that I needed. Before jumping straight into the HTML, I took a moment to determine semantic elements (such as which headers should be h1, h2, h3, etc) and made an initial list of classes I knew would be needed. Then I typed up all of the text for the page, adding new classes as appropriate. Before I can be distracted by visuals I loaded the HTML file and checked the text for any typos. At that point I was able to start tackling the aesthetics of the page! Because of how blocky this design is, I decided to code the CSS section-by-section. Once all the CSS was done I compared the web page to the design comp file to check for any errors.

**Next steps:**

- JavaScript?
- Refactor code (clean up any extraneous classes, make sure any necessary notes are included, add metadata information).
- Run Lighthouse audit to optimize website - resize images and follow any other suggestions from the report.
- 508 Accessibility?
- Test web page on various browser devices and mobile sizes
- On a real project, confirm that typos are not intentional

## Gathering Information

1. I checked the canvas size to determine that the design layout is 1440 pixels wide.
2. I inspected all image and 'design' layers to determine the height and width of all graphic elements.
3. I extracted all the images as .png files via `Export -> Layers to Files`.
4. I inspected all text elements to determine font style, size, weight, and tracking.
5. I used the Eyedropper tool to gather all the necessary hex color codes.
6. I utilized the Ruler tool to determine the margins and padding for various elements.

### Challenges

- Group 2 orange box
- Getting double spacing to work (unicode characters)
- Group 4 background image opacity without affecting child elements!!!

# Preview

( deployed link here )

## Design Comp

![Design Comp Preview](images/design-comp-preview.jpg)

### Credits

The .psd design comp was created by Freepik and is being used under their Premium license.
