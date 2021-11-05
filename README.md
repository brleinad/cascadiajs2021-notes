# Notes from [CascadiaJs 2021](https://2021.cascadiajs.com/)

| | |
--|--
Day 1 (link doesn't work in Canada anymore) | https://www.youtube.com/watch?v=vFhJceJffwE
Day 2 | https://www.youtube.com/watch?v=ePDqanmVm1Y

## Presentations I liked on Day 1:

### [Responsive components: Present & Future](https://jdsteinbach.com/responsive-components/#/6)

**TL;DR:**  Responsive designs are hard, even with media queries, 
but now we have modern tools that make it easier like `flex-wrap`, `flex-basis` and grids. 
In the future we will also have [containers](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Container_Queries) 
which are way cooler because  Instead of looking at the viewport size (like media queries), 
we can look at the container size and make our layout adjustments according to the space in the container. 

### [So you think you know `window.open`](https://cascadiajs-window-open.netlify.app/act-i)

**TL;DR:** You can do all sorts of things with `window.open`. 
For example when that your users use many tabs of your app. 
You can have the browser refocus one of their already open tabs instead of opening a new tab.

### [Let's go Fast! Creating a culture of frontend performance](https://speakerdeck.com/andrewhao/cascadiajs-2021-creating-a-culture-of-frontend-performance)

**TL;DR:**  Create a community of practice. A group of people who regularly do things do improve something they care about.
A task force is way to do this. They can be in charge of tooling, sharing knowledge through docs and presentations.

### [Enter the Sandbox - JavaScript on WebAssembly](https://drive.google.com/file/d/13XdyUEkQ5Z_G2ead7_aMsHTzUHbsLWc-/view)

**TL;DR:** WebAssembly is an exciting new technology!
WebAssembly and JavaScript are different tools best suited for different jobs.
[Wasm](https://wasi.dev/) is a system interface for WebAssembly.
Wasm in JS is a great way to speed up, or architect performant JS Applications!
JS in Wasm is an exciting new space that allows exciting new use cases, like running untrusted code!


### [I need you to create with code](https://github.com/romellogoodman/library/blob/main/slides/I%20Need%20You%20to%20Create%20with%20Code.pdf)

**TL;DR:** Code can be more than just a way to create monetary value. 
The explosion of web technologies in the 2010s was a community lead and reshaped modern web development.
Every week there was a new javascript library testing a new idea for how to create websites.
The "creative coding" field can go through the same transformation and needs your help.

## Presentations I liked on Day 2:

### [hands-free coding with Gaze control in javascript](https://docs.google.com/presentation/d/1x9PKw_LRGUQQQjPcaUFPUZkZtdd-Sr4r8kkmzbIoiZs/edit#slide=id.p)
https://youtu.be/ePDqanmVm1Y?t=2989

**TL;DR:** Charlie built a JavaScript library using iris tracking to predict the direction of a user's gaze, 
to experiment with gaze-controlled interfaces. Built using TensorFlow.js
Then she extended that idea into an Electron app, paired with a VScode extension for React to be able to code hands-free.

![demo](https://github.com/charliegerard/gaze-detection/blob/main/gaze-demo.gif)

Related resources:
* https://www.joshwcomeau.com/blog/hands-free-coding
* https://charliegerard.dev/project/gaze-detection
* https://github.com/charliegerard/gaze-detection

### [DX for Internal Teams](https://github.com/brleinad/cascadiajs2021-notes/files/7486557/DX_for_Internal_Teams_-_Ian_Sutherland_CascadiaJS_2021.pdf)
https://youtu.be/ePDqanmVm1Y?t=9931

**TL;DR:** Good Developer experience is important because productivity = happiness.
Good DX it can be made up of different parts like: good docs, tooling, CIs, APIs, sandbox environments, CLIs, etc.
Treat internal tools like production software.

### [The Fellowship of the Strings](https://www.betaorbust.com/presentations/The_Fellowship_of_the_String__Jacques_Favreau__CascadiaJS2021.pdf)
* https://youtu.be/ePDqanmVm1Y?t=11273

**TL;DR:**  The story of a big refactoring, of a function that sometimes failed without errors, at Netflix.
They made sure to talk with all the teams who would be affected before changing any code (from devs to marketing).
Then they used codemods to automate the refactoring and put in place ESlint rules so that devs would stop using 
the deprecated function.

Related resources:
* https://www.manning.com/books/the-mikado-method
* https://astexplorer.net/
* https://egghead.io/blog/codemods-with-babel-plugins	
* https://www.compilersforhumans.com/


## Misc
* New (for me) JS framework: [RedwoodJs](https://redwoodjs.com/)
* [CryptoKitties](https://www.cryptokitties.co/)

![image](https://user-images.githubusercontent.com/12233785/140425112-9dcc7d60-e330-42d1-83cb-9ccd88615f48.png)

