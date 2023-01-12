# Reading - Class 05

These notes cover how to use different media tags like `<img>` and `<figure>` along with different image file types such as `.png`s and why they are preferrable. Additionally, it covers basic information about fonts and color rules in CSS, how to apply them and manipulate them to create a better user experience.

## HTML - Media

1. **What is a real world use case for the `alt` attribute being used in a website?** The `alt` tag is useful for people who use screen readers to access the internet. It gives the user a kind of "caption" that can be used to describe the picture. 

2. **How can you improve accessibility of images in an HTML document?** By using the `alt` tag on any and all of your images and abiding by the WCAG standards.

3. **Provide an example of when the `figure` element would be useful in an HTML document.** A `figure` could be useful if we wanted to display some kind of table of information for a business, such as various information pertaining to their sales performance.

4. **Describe the difference between a `gif` image and an `svg` image, pretend you are explaining to an elder in your community.** A `gif` can either be a picture or a small snippet of a video/animation wheras an `svg` is a special kind of picture that will look crystal clear no matter what size you stretch or shrink it down to.

5. **What image type would you use to display a screenshot on your website and why?** `.PNG` are usually the most common because it uses lossless compression and is supported by all major browsers.  `.WebP` would be another great alternative that offers even better compression but it is not as widely supported across older brower versions.

## CSS - Color & Styling HTML Text Elements

1. **Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.** If we use a standard newspaper as an example, the background color would be what the color of the actual paper (grey) is while the foreground color would be the color of the ink (black).

2. **Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?** By creating CSS rulesets that would target the `background-color` and `color` properties of his HTML elements and maybe even the `border` property as well.

3. **What should you consider when choosing fonts for an HTML document?** We should consider if we are using web safe fonts or not, because if they are *not* web safe then we will have to import the desired font from somewhere. Additionally, we should also consider what kind of font style we're going to use, `serif`, `sans-serif`, `monospace`, `cursive`, or `fantasy` which can greatly impact the feel / vibe of the website and the readability of the text.

4. **What do `font-size`, `font-weight`, and `font-style` do to HTML text elements?** `font-size` changes how big or small the text will be, usually defined in pixels `px`. `font-weight` describes how thin or thick the font is, with values that can range from 100 - 900 where 100 is thinnest and 900 is boldest. `font-style` is used to to essentially put the text at a slant, like you would see with `italic`.

5. **Describe two ways you could add spacing around the characters displayed in an `h1` element.** We can either use the properties `font-kerning` or `letter-spacing` which both essentially increase the space between the letters of a specified text element.

## Things I Want To Know
- What would be the preferred use case for using <img> vs <figure> if our goal is to display a picture?
- What is the preferred use case for monospace fonts besides just aesthetic reasons?
