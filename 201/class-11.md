# Reading Notes Class 11

<br>

## Video and Audio Content

**Explain how the ability to use video and audio on the web has evolved since the early 2000s.**

- Technologies like Flash and Silverlight were the popular plug-in technologoies at the time. It gave the ability to embed video and audio on the web

**Describe the use of the src and controls attributes in the <code>video</code> element.**

- It contains the the path of the video (just like img) that is to be embeded

**Why is it important to have fallback content inside the <code>video</code> element?**

- This is useful to provide a fallback for people using older browsers. An example would be to provide a link instead to the user to the location of the original video

**Write a very short story where <code>audio</code> and <code>video</code> are characters.**

- One day there was a student named HTML who was getting ready to give a presentation to his school. HTML really wanted to show the crowd a cool website that would be fun and interactive with moving images and sound. Two of his best friends, Audio and Video, said that they knew of a guy named Flash that could help put the presentation together for them

<br>

## A Complete Guide To Grid

**How does Grid layout differ from Flex?**

- Grid works on a 2-D interface while Flex only had a one directional flow, grid solves that problem

**Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.**

- Grid container:The elements where <code>display: grid</code> is applied
- Grid item: A child of the grid container
- Grid line: Dividing lines that make up the grids structure. They can be verticle or horizontal

<br>

## Responsive Images

**Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**

- Responsive images help when images may be too big when moving to a device that is smaller or more narrow. This can help ease the user in seeing images at a corrected size

**Define the following <code>img</code> attributes <code>srcset</code> and <code>sizes</code>. Write an example of how they are used.**

- <code>img</code>: Only points the broswer to a single source file. Just places the picture directly as it is, original size and all
- <code>srcset</code>: Defines a set of images that allows the browser to decide the size of each image
- <code>sizes</code>: Defines a ser of media conditions and indicates what image size would be best to choose when certain media co'nditions are true

**How is <code>srcset</code> more helpful for responsive images than CSS or JavaScript?**

- When a browser laods a page it starts to pre-load images. This helps in reducing load times, but not with responsive images. Without <code>srcset</code> the image would load both the original image and the re-sized image as well.

<br>

## Things I want to know more about
