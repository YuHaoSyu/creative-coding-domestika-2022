coding-course-2.0
=================
Resources and notes for students of the course [Creative Coding: Making Visuals with JavaScript 2.0]() at Domestika.


## General Resources

#### New to JavaScript
The course is focused on creating visuals using JavaScript. In case you are new to the language, it's better to start with some of the fundamentals first:

- [JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [JavaScript First Steps](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps)
- [The Modern JavaScript Tutorial](https://javascript.info/)
- [Creative Coding: Making Visuals with JavaScript](https://www.domestika.org/en/courses/2729-creative-coding-making-visuals-with-javascript/bruno_imbrizi)

#### CanvasRenderingContext2D
> The CanvasRenderingContext2D interface, part of the [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API), provides the 2D rendering context for the drawing surface of a `<canvas>` element. It is used for drawing shapes, text, images, and other objects.

- [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- [CanvasRenderingContext2D](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D)

#### canvas-sketch
> `canvas-sketch` is a loose collection of tools, modules and resources for creating generative art in JavaScript and the browser using the `<canvas>` tag. It is designed to help create artworks and images with code, randomness, algorithms, and emergent systems.

- [canvas-sketch API Docs](https://github.com/mattdesl/canvas-sketch/blob/master/docs/api.md)
- [canvas-sketch CLI Docs](https://github.com/mattdesl/canvas-sketch/blob/master/docs/cli.md)

#### Online templates

- [StackBlitz template](https://stackblitz.com/edit/js-ph9w9y)
- [CodeSandbox template](https://codesandbox.io/s/canvas-sketch-default-uz11b)


## UNIT 2 - Setup

#### L01 - JavaScript Recap
- [JavaScript basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [JavaScript First Steps](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps)
- [The Modern JavaScript Tutorial](https://javascript.info/)
- [Creative Coding: Making Visuals with JavaScript](https://www.domestika.org/en/courses/2729-creative-coding-making-visuals-with-javascript/bruno_imbrizi)
- [Lorem Picsum](https://picsum.photos/)
- [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)

#### L02 - Online Setup
- [StackBlitz](https://stackblitz.com/)
- [CodeSandbox](https://codesandbox.io/)
- [canvas-sketch-cli default template](https://github.com/mattdesl/canvas-sketch-cli/blob/master/src/templates/default.js)
- [Fork StackBlitz template](https://stackblitz.com/edit/js-ph9w9y)
- [Fork CodeSandbox template](https://codesandbox.io/s/canvas-sketch-default-uz11b)

#### L03 - Offline Setup
- Editors:
	- [Sublime Text](https://www.sublimetext.com/)
	- [Visual Studio Code](https://code.visualstudio.com/)
- Browsers:
	- [Google Chrome](https://www.google.com/chrome/)
	- [Mozilla Firefox](https://www.mozilla.org/firefox/new/)
	- [Microsoft Edge](https://www.microsoft.com/edge)
- Terminal (Windows):
	- [Git for Windows](https://gitforwindows.org/)
	- [Cmder](https://cmder.net/)
	- [ConEmu](https://conemu.github.io/)
- Runtime:
	- [Node.js](https://nodejs.org/)
	- [NPM](https://www.npmjs.com/)

#### L04 - Canvas-Sketch
- [Canvas API](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
- [CanvasRenderingContext2D (code snippet to draw a house)](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D)
- [canvas-sketch API Docs](https://github.com/mattdesl/canvas-sketch/blob/master/docs/api.md)
- [canvas-sketch CLI Docs](https://github.com/mattdesl/canvas-sketch/blob/master/docs/cli.md)


## UNIT 3 - SKEW

#### L01 - Rectangle
- [The drawing state](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/save#drawing_state)

#### L02 - Skewed Rectangle
- [canvas-sketch-util/math](https://github.com/mattdesl/canvas-sketch-util/blob/master/docs/math.md)

#### L03 - Distribution
- [canvas-sketch-util/random](https://github.com/mattdesl/canvas-sketch-util/blob/master/docs/math.md)

#### L04 - Colors
- [canvas-sketch-util/color](https://github.com/mattdesl/canvas-sketch-util/blob/master/docs/color.md)
- [Riso Ink Colors](https://www.stencil.wiki/colors)
- [riso-colors](https://github.com/mattdesl/riso-colors)
- [globalCompositeOperation](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/globalCompositeOperation)

#### L05 - Clipping Mask
- [CanvasRenderingContext2D.clip()](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/clip)

#### L06 - Random Seed
- [canvas-sketch-util/random](https://github.com/mattdesl/canvas-sketch-util/blob/master/docs/math.md)


## UNIT 4 - CURVES

#### L01 - Quadratic
- [bezierCurveTo](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/bezierCurveTo)
- [quadraticCurveTo](https://developer.mozilla.org/en-US/docs/Web/API/CanvasRenderingContext2D/quadraticCurveTo)

#### L02 - Cursor Interaction
- [addEventListener](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/addEventListener)
- [removeEventListener](https://developer.mozilla.org/en-US/docs/Web/API/EventTarget/removeEventListener)
- [MouseEvent](https://developer.mozilla.org/en-US/docs/Web/API/MouseEvent)

#### L03 - Multi-point
- [Erik Natzke](https://natzkestore.com/)

#### L04 - Grid
- [canvas-sketch-util](https://github.com/mattdesl/canvas-sketch-util)
- [Perlin Noise](http://web.archive.org/web/20160530124230/http://freespace.virgin.net/hugo.elias/models/m_perlin.htm)

#### L05 - Segments
- [colormap](https://github.com/bpostlethwaite/colormap)

#### L06 - Animation
- [Exporting Animations](https://github.com/mattdesl/canvas-sketch/blob/master/docs/exporting-artwork.md)
- [ffmpeg-installer](https://www.npmjs.com/package/@ffmpeg-installer/ffmpeg)


## UNIT 5 - AUDIO

#### L01 - Press Play
- [Artlist](https://artlist.io/)
- [MP3 - ikoliks - Big City Lights](https://cdn.artlist.io/artlist-watermarkmp3/396812_396811__ikoliks_-_Big_City_Lights_-_100920_-_EXT_-_X_-_2444.mp3)
- [Audio codecs](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Audio_codecs)
- [Autoplay guide](https://developer.mozilla.org/en-US/docs/Web/Media/Autoplay_guide)

#### L02 - Analyser
- [Web Audio API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
- [frequencyBinCount](https://developer.mozilla.org/en-US/docs/Web/API/AnalyserNode/frequencyBinCount)
- [SketchManager](https://github.com/mattdesl/canvas-sketch/blob/master/docs/api.md#sketchmanager)

#### L03 - Frequencies
- [getFloatFrequencyData](https://developer.mozilla.org/en-US/docs/Web/API/AnalyserNode/getFloatFrequencyData)
- [Notes are logarithmically spaced](https://stackoverflow.com/a/43369065/461048)
- [Why 44,100 Hz?](https://intelligentsoundengineering.wordpress.com/2016/01/04/why-44-1-khz/)

#### L04 - Arcs
- [Jessica Svendsen : 100 Days : Müller-Brockmann](http://a-mushtaq1114-dc.blogspot.com/2013/09/jessica-svendsen-100-days-muller.html)
- [cubic-beizer](https://cubic-bezier.com/#0,0,1,1)
- [Robert Penner's Easing Functions](http://robertpenner.com/easing/)
- [eases](https://www.npmjs.com/package/eases)

#### L05 - Müller-Brockmann
- [Josef Müller-Brockmann](http://www.designishistory.com/1940/joseph-mueller-brockmann/)