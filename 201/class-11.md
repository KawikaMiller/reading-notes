# Reading - Class 11

These notes will explain audio and video elements within HTML, how Gridbox works in CSS, as well as how to implement responsive designs within our webpages.

## Video and Audio Content

1. **Explain how the ability to use video and audio on the web has evolved since the early 2000s.** Originally, videos and audio was made possible by plugin-based technologies like Flash and Silverlight but now HTML offers its own video and audio elements along with JavaScript APIs to control them.

2. **Describe the use of the `src` and `controls` attributes in the `<video>` element.** The `src` attribute is similar to that of the `src` attribute of an image - it gives the `<video>` element a path to the video we want to display. The `controls` attribute gives us the ability to do things like pause, play, and change the audio levels.

3. **Why is it important to have fallback content inside the `<video>` element?** Similarly to that 'alt' text of an image, the fallback content of a video is displayed if the browser cannot display the video for some reason - for example, like if the video format is not supported. We can even provide a direct link to the video file so that the user can access it even if the browser cannot display it.

4. **Write a very short story where `<audio>` and `<video>` are characters.** Video loved to entertain and put on a show. Video was always the center of attention as they were able to really showcase their talents of singing and dancing. Audio the songbird loved to sing their songs but remain unseen as they didn't really know how to dance. Together, they made the town of Webpage a great place to live.

## Grid

1. **How does Grid layout differ from Flex?** Grid is essentially a way to create a kind of 'table' but with your web page layout. Elements are arranged in a series of rows and columns that are proportionate to one another whereas Flex elements can change their spacing and shape.

2. **Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.** If we think of a grid as a series of smaller boxes all lined up and stacked on each other, the `grid container` is the outer-most box that holds them all together. The `grid items` would be the smaller boxes inside of the `grid container` while the `grid lines` would be the borders between the columns and rows of `grid items`.

## Responsive Images

1. **Besides making a site visually appealing across different screen sizes, why should developers make images responsive?** Bandwith / data useage would be one reason as people on mobile devices typically don't want to have to download the larger assets that are intended for desktop use. Additionally, depending on the type of image being used and the resolution of them they might also appear grainy and unreadable in the wrong context.

2. **Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used.** `srcset` allows us to specify multiple image source paths which the browswer will then choose depending on the context / size of the screen. `sizes` defines these specific screen widths where we want these changes to happen and which image would be best to choose. When creating an `<img>` attribute we would need to include the `src` and `alt` attributes as usual, and then we also include the `srcset` attribute with the additional image source paths & screen widths, and then the `sizes` attribute with the  conditions upon which we want the images to change.

3. **How is `srcset` more helpful for responsive images than CSS or JavaScript?** Because of the way that the HTML is loaded and the CSS is then parsed. The images are preloaded before the main parser has a chance to load and interpret the page's CSS

## Things I Want To Know More About

n/a