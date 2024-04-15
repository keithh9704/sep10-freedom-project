# Entry 5
##### 4/8/24
### Context
I continued to learn my tool (aframe) and found some interesting things that I could do since aframe is a VR world.
#### Learning my tool
From what I left off in [Blog4](entry04.md) I went to research what else aframe can do than just create shapes and be able to move them. I would find out that you can input pictures of your own to the whole aframe space or a part of the aframe space. An example of the code is
```<a-scene>
      <a-assets>
      <img id="logo" src="54AFCF4A-4F9C-4E78-A984-C5BD91A48BEE.jpg">
        <img id="logo2" src="A4599694-8BB9-4EEA-A778-B60542C89CC2.jpg">
      </a-assets>
      <a-curvedimage src="#logo" position="0 0.5 -3" radius="5.5" height="1"> </a-curvedimage>
      <a-plane src="#logo" position="0 0 -4" rotation="-90 0 0" width="10" height="10" color="green"></a-plane>
      <a-circle src="#logo2" position="0 0 6" rotation="-90 0 0" radius="5"></a-circle>
      <a-sky src="#logo" color="#ECECEC"></a-sky>
      <a-camera scr="#logo" position="0 10 0"></a-camera>
    </a-scene>
```


 I found this helpful because you could add what background you need that fits when the theme of what you are creating in the aframe space.
 There is also camera speed, meaning you can control how fast the viewer can go and where they are positioned. An example of the code is
 `<a-entity camera look-controls wasd-controls="acceleration:25" position="0 1 0"></a-entity>` This could be helpful in what you want your viewer to see in your aframe space.
 ### How I Learned My Tool
 From the previous [Blog4](entry04.md) I used a [slideshow](https://docs.google.com/presentation/d/1nsptrTVH5fI2NpvmmE3PffaUNODlpyxpB-LgH4Eko5A/edit#slide=id.g84acedc9de_0_70) and [jsbin](https://jsbin.com/?html,css,output) to test out what I learned the sildeshow. After that week I would go on the official [aframe](https://aframe.io/docs/1.5.0/introduction/) and look at most of the components I would like to use to make for my freedom project. Some of these components I can't use with jsbin because they don't support downloading things from my computer so I use [replit](https://replit.com) and I could use these components perfectly and see what I can use this for.    
 Sometimes when I try to tinker with the codes on the Aframe website I get stuck and need clarification. I solved this problem by using an inspect element like on [putting text on a 3D Space](https://aframe.io/aframe/examples/test/text/index.html). I would also use previous [freedom project examples](https://andyc6074.github.io/sep10-freedom-project/aframe/lifespan.html) to help me expand my aframe knowledge. **I would add the images and shapes that I want to use for my freedom project to get a glimpse of how this is presented.**
 ### Skills
 I have extended my knowledge of researching and grabbing different parts of readings to test them out to better understand the topic at hand. I also learned how to understand codes with my twist so I would increase my knowledge of the topic at hand.
 #### Researching
 Since I mostly used the Aframe official website, they would write a lot of things about different components and I would take parts of the readings and test them out which makes me understand how the components work.
 #### Creativity
 I use inspect elements a lot and sometimes I don't know even given the code how it works and how this code does what it does. Most to all the time I input my ideas for a component I immediately understand what the code is doing.
 ### Next Steps
 I will be creating my website for animation which would be exciting but I have one more thing to learn inputting blender to aframe before I can start doing my aframe part of the freedom project.

[Previous](entry04.md) | [Next](entry06.md)


[Home](../README.md)
