# Day 10

## Audio, Video, Images

### Video and Audio Content

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

  > The first online videos and audio clips were made possible using plug in technology like Flash and Silverlight. Unfortunately these methods had security and acessinility issues. Now we are able to imbed video and audio clips in HTML using < video > and < audio > tags.

2. Describe the use of the src and controls attributes in the < video > element.

  > SRC is the source of the clip you wish to have. It contains the path of the video you wish to embed. The controls attribute allows you to control video volume, playback seeking and pause/play.

3. Why is it important to have fallback content inside the < video > element?

  > This is important because this is the information displayed if the browser doesnt support the < video > element. You can store a direct video link here.

4. Write a very short story where < audio > and < video > are characters.

  > Once upon a time long ago, our computers used to have plug ins to allow us to watch videos.. but then the future came and showed us a new way... embedding it into our HTML. With this new tool our society thrived and many, many videos are able to be posted online now. The end.

### A Complete Guide to Grid

1. How does Grid layout differ from Flex?

  > With grid you can design a two-dimensional layout vs with Flex it's one dimensional.

2. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

  > Grid container: This is the parent of all grid items. It's the element that display: grid is applied.
  > Grid item: This is the childen/direct descendant of the grid container. This is where the item elements are.
  > Grid line: This is the line that divides the cells, making the structure of the grid.

### Responsive Images

1. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

  > It helps improve the performace of our site across different devices.

2. Define the following < img > attributes srcset and sizes. Write an example of how they are used.

  > srcset: "One or more strings separated by commas, indicating possible image sources for the user agent to use." This contains the URL
  > sizes: "One or more strings separated by commas, indicating a set of source sizes." This is used to specify the display size of the images.

3. How is srcset more helpful for responsive images than CSS or JavaScript?

  > "srcset allows you to define a list of different image resources along with size information so that browser can pick the most appropriate image based on the actual device's resolution."

  #### Sources

1. [imaginekit.io](https://imagekit.io/responsive-images/#:~:text=srcset%20allows%20you%20to%20define,on%20the%20actual%20device's%20resolution.&text=The%20actual%20width%20of%20the,%2C%201.5x%20%2C%202x%20etc.)

2. [developer.mozilla.org](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img#attr-srcset)

Click to return [Home!](../README.md)
