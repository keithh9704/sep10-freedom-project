# Entry 6
##### 5/1/24

### Context
After learning my tool I made my freedom project website that has all the mvp. The website is functioning but doesn't look really nice website that would make people think that I put alot of time on the website.

### Deciding on how I should format my website
When I created my wireframe for [computer](https://wireframe.cc/XtriJU) and [phone](https://wireframe.cc/GJKGb) I thought this would be easy with a template to start with. After when I inputed the template I was overwhelmed with amount of css code that I was afraid to change any of the exist code because I could of ruined the template. So I decided after the 3rd day of making my freedom project website that I should start from scratch and try to take inspiration from that website.
### Making the [Website](https://keithh9704.github.io/sep10-freedom-project/)/Challenge 1
When I first started I tried inporting background image and adding text. It was working until the whole image was getting cropped out when I expanded the pixel size of the website. I tried doing `width: 100%;` but it didn't work so I was just confused and then I realized I had to use `background-size` to make the image go along with the text. Even though everything was working with the text over the Image, the image was repeating itself so I looked back at the template I was orignally going to use and used inspect element to see how they inputed there background image. I found you have to use these codes to make the background image work.
```
#welcome {
background-image: url(Images/animation-image.png);
background-size: cover;
background-position: center;
background-repeat: no-repeat;
text-align: center;
padding-top: 20rem;
padding-bottom: 20rem;
}
```
After this was inputed in the website I realized that I had to make my text bigger so the whole Image would pop up. Alongside having a problem with my background image, everything was fairly easy making the rows and columms to present my Information in a way that looked like my wireframe.
### Adding Images and Aframe to my website
When I was done using my components on the website I went to add images. One of my Images were too small and one of my images were too big. I was so confused on how to change the size since I tried using `width: 100%;`. I Asked my friend johnny if he knew anything and showed me that I had to resize the image from the file in my computer which make the website more responsive. Although It doesn't fit the whole box I am planning to fix that when I am working beyond mvp.


 

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
