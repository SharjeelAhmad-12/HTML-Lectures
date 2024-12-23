## Multimedia Tags in HTML

HTML provides several tags for embedding multimedia content such as audio, video, and images. These tags help create richer, more interactive experiences on the web. Below are some key multimedia tags in HTML.


## 1. `<img>` - Image Tag

The `<img>` tag is used to embed images in an HTML document.

***Common Attributes:***

- `**src**(Required)`: Specifies the image file's URL or path.
- `**alt**(Required for accessibility)`: Provides alternative text if the image cannot load.
- `**width and height**`:Define the size of the image (in pixels or percentage).

## **Example**:

```html
<img src="example-image.jpg" alt="A beautiful landscape" width="600px" height="400px">
```
In this example:

- `**src**`="example-image.jpg" points to the image file.
- `**alt**`="A beautiful landscape" provides descriptive text for users who cannot see the image.
- `**width**`="600px" and  `**height**`="400px" control the image's display size.


## 2. `<audio>` - Audio Tag
The `<audio>` tag is used to embed audio files such as MP3s or other audio formats.

```html
<audio controls>
  <source src="audio.mp3" type="audio/mp3">
</audio>
```

`**controls**`: Adds play, pause, and volume control buttons.
`**<source>**`: Specifies the audio file and its format.

You can add multiple `<source>` tags for different audio formats.

## 3. `<video>` - Video Tag
The `<video>` tag is used to embed video content.

```html
<video width="640" height="360" controls>
  <source src="video.mp4" type="video/mp4">
  <source src="video.ogv" type="video/ogg">
</video>
```

- `**controls**`: Adds play, pause, and volume control buttons.
- `**width and height**`: Define the dimensions of the video.
- `<source>`: Specifies different video formats (e.g., MP4, WebM, Ogg).


## 4. `<iframe>` - Embedding External Content
The `<iframe>` tag is used to embed external content such as videos from YouTube or Google Maps.

```html
<iframe src="https://www.youtube.com/embed/dQw4w9WgXcQ" width="560" height="315" frameborder="0" allowfullscreen></iframe>
```

- `**src**`: Specifies the URL of the external content.
- `**width**` and `**height**`: Define the dimensions of the iframe.
- `**frameborder**`: Controls the border of the iframe (set to "0" to remove the border).
- `**allowfullscreen**`: Allows the embedded content (such as video) to go full-screen.


- `<iframe>` is used to embed external content like websites or media from other sources.

- `<video>` is specifically used to display video files hosted locally or remotely on the same website.

- In short, if you want to embed external content like a YouTube video or a website, use `<iframe>`. If you want to display a video file on your website, use `<video>`.

## Conclusion
These multimedia tags allow web developers to enhance their websites by embedding images, videos, audio, and even external content in various formats. By using these tags effectively, you can create richer and more interactive web experiences.