# Tool Learning Log

Tool: **Aframe**

---
**Using Src can make any shape the image you presented**
**ONLY WAY U CAN USE SRC IS WHEN YOU UPLOADED AN IMAGE**
#### Positioning:
* -X makes the shape go to the left
* X makes the shape go to the right
* -Y makes the shape go down
* Y makes the shape go up
* -Z makes the shape go forward
* Z makes the shape go backward
*
#### Shapes (will add more soon)
* Cone
* Sphere
* Cylinder
* Plane (the "floor")
* Box
* Triangle
* Curvedimage
* Circle
#### Functions:
* There is different parts of aframe you could use to make backgrounds. After installing the part you could
* The a-sky repersents the background so you could make the background whatever color you want.
* Putting components like sphere cylinder inside an `<a-entity></a-entity>` could be used to add a css element to every component that is in the `<a-entity></a-entity>`.
* Using `<a-camera></a-camera>` you can use the x y and z in postioning to choose where the user will see your website from.
* Putting visible with an a-entity could make the components in the a-entity appear or dissapear. Example of the code `<a-entity visible=true/false> </a-entity>`
* When using wasd controls you have to connect the camera function for the component to work. Example of the code `<a-entity camera look-controls wasd-controls="acceleration:25" position="0 1 0"></a-entity>`
* To add text in a 3D image you have to position anchor size and add an value to add text to your liking. You also can change the color of the text. Example of the code
```
<a-entity position="41 2 -3" text="anchor: right; width: 45; color: blue; value: Hi name" </a-entity>
```
Things I tried:
* changing colors, increasing/decreasing the sizes of the shape,
* The shapes are called entities
* trying out different shapes that are not given to you when you paste in the code to tinker with aframe
* Using Src to make really funny things to show my friends
* Making shapes disappear or appear
* Make the user start below or above the aframe and make the movement fast or slow
* Adding text
Links:

* [AFrame](https://aframe.io/docs/1.5.0/introduction/html-and-primitives.html)
* [Workshop Slides](https://docs.google.com/presentation/d/1nsptrTVH5fI2NpvmmE3PffaUNODlpyxpB-LgH4Eko5A/edit#slide=id.g84acedc9de_0_70)
* [Forked a replit from workshop slides](https://replit.com/@keithh32/EscapingRealityS1WinterWonderlandv1-Tinkering)
* [Visible](https://aframe.io/docs/1.5.0/components/visible.html)
* [Controling wasd](https://aframe.io/docs/1.5.0/components/wasd-controls.html)
* [Preview on how text on 3d works](https://aframe.io/aframe/examples/test/text/index.html)
* [Example code I tinkered with](https://github.com/aframevr/aframe/blob/master/examples/test/text/index.html)
<!--
* Links you used today (websites, videos, etc)
* Things you tried, progress you made, etc
* Challenges, a-ha moments, etc
* Questions you still have
* What you're going to try next
-->
