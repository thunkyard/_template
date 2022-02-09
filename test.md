---
marp: true
title: Marp Test Playground
description: Experiment with different slide deck properties
theme: uncover
class: invert
math: katex
---

# Your slide deck

Start writing!

---

# Test

```js
console.log(`W. T. Fusc? ${window.location}`);
```

---

## katex

block form:
$$
\Gamma(z) = \int_0^\infty t^{z-1}e^{-t}dt\,.
$$

and inline: `->>` $ax^2+bc+c$

<!-- This is a presenter note for this page. -->

---

## bg

deckset-style split backgrounds:

![bg right](https://camo.githubusercontent.com/96806a6fcb4512833c561bb22288a087d0629dbc8f9521a330b84a4b207ce02a/68747470733a2f2f696d616765732e756e73706c6173682e636f6d2f70686f746f2d313536383438383738393534342d6533376564663930656236373f63726f703d656e74726f70792663733d74696e7973726762266669743d63726f7026666d3d6a706726683d3732302669786c69623d72622d312e322e3126713d383026773d363430)

---

## advanced bg

![bg blur:1px](https://fakeimg.pl/800x600/fff/ccc/?text=A)
![bg blur:3px](https://fakeimg.pl/800x600/eee/ccc/?text=B)
![bg blur:5px](https://fakeimg.pl/800x600/ddd/ccc/?text=C)

---

## Split backgrounds with specified size

![bg left:33%](https://picsum.photos/720?image=27)

---
<style scoped>
  iframe.desmos {
    border: 0;
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
  }
  nav.desmos {
    z-index: 1;
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 50px;
    background: #1c1d1e;
    color: #eee;
    font-size: 0.75rem;
  }
  nav.desmos a {
    color: #eee;
    text-decoration: underline;
  }
</style>


<nav class="desmos"><a href="https://www.desmos.com/calculator/ujhr8ir0vl">https://www.desmos.com/calculator/ujhr8ir0vl</a></nav>
<iframe class="desmos" src="https://www.desmos.com/calculator/ujhr8ir0vl">
  Hyperbinary Numbers
</iframe>

<!-- this should be an iframe loading a desmos embed -->

---
<!-- _class: other -->
# Bullet list

- One
- Two
- Three

---

# Fragmented list

* One
* Two
* Three

---
<!-- _transition: cover -->
# video
Click to toggle playback

---
<!-- _backgroundSize: cover -->
Click to play

<video html muted class="bg" onclick="this.paused ? this.play() : this.pause(); this.blur()" onpause=""><source src="https://download.samplelib.com/mp4/sample-5s.mp4" type="video/mp4"></video>

---
<!-- _backgroundImage: "linear-gradient(to bottom, #67b8e3, #0288d1)" -->
## bg colors

Gradient background

---
<!--
_backgroundColor: black
_color: white
-->
Black background + White text

---
<!-- _class: -->
## img filters
![sepia:0.3 drop-shadow:0,5px,10px,rgba(0,0,0,.4)](https://picsum.photos/500?image=27)

---
<!-- _transition: reveal -->
![bg sepia:0.2](https://picsum.photos/500?image=27)
![bg sepia:0.6](https://picsum.photos/500?image=27)
![bg sepia:1.0](https://picsum.photos/500?image=27)

---
## more filters

![sepia:0.2 brightness:200%](https://picsum.photos/500?image=25)

---
![bg right](https://picsum.photos/720?image=3)
![bg](https://picsum.photos/720?image=20)
# Split + Multiple BGs

The space of a slide content will shrink to the left side.

---

# <!-- fit --> fin

