# Entry 4
##### 3/15/26

# Context
Out of my top 3 tools to use for my freedom project, I decided to pick A-frame, I was deciding between A-frame, Jekyll and Bulma but ended up picking Aframe since I like the idea of creating the models of my Part B Future technologies and maybe even make them function properly,I started my tinkering progress by grabbing [starter code ](https://aframe.io/docs/1.7.0/introduction/) from Aframe website and pasting it into my IDE.

My start code I'll be using is:
``` html
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
```
I first tinkered around by adjusting the plate size via height and width
 ```html
 <html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-sphere position="0 1.25 -5" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="100" height="67" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
```
This only made the plate a  lot bigger

Then I tried to put the sphere onto the cylinder to create a tree shape.
```html
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.1/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-box position="-1 0.5 -3" rotation="0 45 0" color="#4CC3D9"></a-box>
      <a-sphere position="1.5  2.5 -3.5" radius="1.25" color="#EF2D5E"></a-sphere>
      <a-cylinder position="1 0.75 -3" radius="0.5" height="1.5" color="#FFC65D"></a-cylinder>
      <a-plane position="0 0 -4" rotation="-90 0 0" width="100" height="67" color="#7BC8A4"></a-plane>
      <a-sky color="#ECECEC"></a-sky>
    </a-scene>
  </body>
</html>
```
I tried my best, the Z value was hard to control since even a small change of 0.5 can sometimes change it's position by a lot which made it impossible to put the sphere exactly where you wanted it

[Previous](entry03.md) | [Next](entry05.md)

[Home](../README.md)
