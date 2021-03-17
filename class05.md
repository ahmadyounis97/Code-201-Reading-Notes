# HTML Images; CSS Color & Texts
There are many explanations that an image should be shown on a website. You may have a logo, a snapshot, a picture, a diagram, or a illustration.

```
<!DOCTYPE html>
<html lang="en">

<head>
  <title>Images</title>
</head>

<body>
  <img src="./img/profile.jpg" alt="My Profile">
</body>

</html>
```

`<img>` The`<img>` element is used to insert an image into the page. This is a non-existent function (which means there is no closing tag). It must exhibit the following two characteristics: `src` This instructs the browser about where to search for the image file. This is typically a relative URL to a picture on your own website. `alt` This gives you a text summary of the picture, which you can read if you can't see it.

[Back to Content](#content)

### Color

## Color
The pages would also be more vibrant if they were colored.
The color property can be used to adjust the color of text within an element. You can assign any color using CSS in one of three ways:


### RGB values:
```css
p {
	color: rgb(100,100,90)
}
```
or
```css
p {
	color: rgba(100,100,90,1)
}
```
RGB stands for red, green, and blue. and RGBA stands for alpha. (opacity).


### HEX codes:

```css
p {
	color: #ee3e80
}
```
HEX stands for a hexadecimal number.


### Color name:

```css
p {
	color: red
}
```


## Background Color

for changing background color for the webpage, heading, div... you'll use:

```css
body {
	background-color: red
}
```


## Opacity

As I previously said, RGBA stands for RGBA, and A stands for alpha(opacity). Another method it's HSL, which stands for hue, saturation, and lightness. HSL also has HSLA, and you guessed it A stands for alpha(opacity).
### Text

## HTML

### Text

The Text is the contents of what you are displaying or presenting on your website.

To show texts we have elements:

Headings

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

Paragraphs

```html
<p>Paragraph</p>
```

the definite between headings and paragraphs, it's important, the main title of webpage element `<h1>`, if the web has subheadings we use `<h2>` until you arrive `<h6>`, in HTML, you can be using some element according to its position in the text and the meaning it, like `<b>Bold</b>` for bold text, `<i>italic</i>` for italic text, `<sup>Superscript</sup>` for Superscript text, `<sub>Subscript</sub>` for Subscript text, `<p>Paragraph</p>` in this element, The size of the space or the number of lines does not count, to achieve that you need to use an extra element, this call white space, we have element work like the previous elements but have a definite meaning this `<strong></strong>`, `<em></em>`, `<strong>` work like `<b>`, but mean indicates that the knowledge stored inside it is important, `<em>` work like `<i>`, but mean indicates subtly shifting the context of a sentence by stressing it, if you When you're writing an article, book, or another kind of document, you can find yourself quoting from other sources in HTML you can use `<blockquote>` or `<q>` elements for Quotations. when writing a science or instructional post, abbreviations are often used and to simplify in your web page we use `<abbr>HTML</abbr>`, but to show the abbreviation u need to use the title attribute `<abbr title="Hypertext Markup Language">HTML</abbr>`, we have a lot of element in HTML for text `<cite>`, `<dfn>`, `<address>`, `<ins>` or `<del>`, `<s>` etc... but you don't see them constantly or some of these elements are no longer supported.



## JPEG vs PNG vs GIF

The content below is an excerpt from the article. [1](#001)

Only the three most widely used image formats in websites and smartphone apps will be discussed in this article. Together, these three formats account for more than 95% of all photographs loaded on websites. Each of them differs significantly from the others, making each one ideal for a particular use case.


### Compression

The size of an image is largely determined by the format and encoding used. There are two types of compression: lossless and lossy. It is possible to restore the original image from the compressed image using lossless compression. Lossy compression causes permanent data loss at the expense of decreased consistency. Compression artifact refers to the apparent loss of image clarity or distortion.


#### JPEG Compression

JPG compression operates by averaging out the colors of pixels in close proximity. It can achieve compression ratios of 1:10 with no discernible output loss. It works well in portraits and drawings of natural scenes with seamless color and intensity variations.


#### PNG Compression

PNG (Portable Network Graphics) is a lossless image format that uses the DEFLATE compression algorithm. There are no data losses or compression artifacts in the image during compression. PNG is not a reasonable option for saving or transferring high-resolution digital images.


#### GIF Compression

If the image incorporates animations, gif images are typically used. The encoding of PNG files is around 5–25% better than that of GIF files. GIF is also available on all big smartphones.


### Transparency

The term "transparency" refers to something that is absolutely imperceptible. Logos and icons are commonly expected to be placed on backgrounds of different colors. The of these logos should be desired.


#### JPEG Transparency

Since photographs don't endorse accountability, they can't be included in these circumstances.


#### PNG Transparency

Transparency can be achieved in photographs in two ways: by adding an alpha channel that makes partial transparency or by declaring a single color clear (index transparency). The edges fade seamlessly into the background thanks to partial clarity. Only index transparency is supported by PNG8 images (discussed in the "Colours" section below), while alpha channel transparency is supported by PNG24 images.


#### GIF Transparency

Transparency is allowed in photographs by declaring a single color in the color palette as transparent (index transparency). The edges (especially rounded or over-detailed edges) suffer from a poor jagged effect due to the lack of partial transparency. Though this can be mitigated to some degree with dithering, GIF is unsuitable for images with transparent backgrounds, particularly with improved PNG support.


### Colours

JPEG pictures have a color range of about 16 million. This is what makes them perfect for preserving natural-scene images. PNG files are divided into two types: PNG8 and PNG24. PNG8 can store up to 256 colors, while PNG24 can store up to 16 million. The number of colors in a GIF image is limited to 256. If index transparency is used, one of these 256 colors is rendered translucent, while the other 255 remain opaque.


### Animation

Only GIF supports animation within these three formats. Because of this, the GIF format is ideal for delivering entertaining advertisements and banners. The use of GIF format for memes has increased recently, thanks to companies including Tumblr, 9Gag, and Giphy. These are some of the main distinctions between JPEG, PNG, and GIF, the three most common image formats for the web.



