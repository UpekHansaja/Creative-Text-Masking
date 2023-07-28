# Creative-Text-Masking-in-Web-Design

Explore the art of creative text masking in web design with this stunning code example. The combination of SVG, video, and CSS transforms ordinary text into an eye-catching visual masterpiece. Discover how this technique can add depth and uniqueness to your web projects. 💻🎨

#WebDesign #SVG #CSS #CreativeCoding

https://github.com/UpekHansaja/Creative-Text-Masking-in-Web-Design/assets/109482062/d808403d-8302-4203-b527-e6bfd3c8d0c6

<br/>
<hr>
<br/>

## HTML  <img src="./res/html.svg" alt="html" title="HTML5"/>  👇

```html
<svg height="100%" width="100%">
  <clipPath id="text-mask">
    <text x="50%" y="50%" fill="red" text-anchor="middle">WEMIXT</text>
  </clipPath>
</svg>

<video src="res/ink.mp4" autoplay loop muted></video>
```

<br/>
<hr>
<br/>

## CSS 👇

```css
@import url("https://fonts.googleapis.com/css2?family=Titillium+Web:wght@900&display=swap");

video {
  width: 100%;
  height: 100vh;
  clip-path: url(#text-mask);
}

svg {
  font-size: 11em;
  font-family: "Titillium Web", sans-serif;
  position: absolute;
  top: 0;
  left: 0;
}
```
