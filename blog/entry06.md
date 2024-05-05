# Entry 6
##### 5/1/24

### Context
After learning my tool I made my freedom project website that has all the mvp. The website is functioning but doesn't look like a really nice website that would make people think that I put a lot of time on the website.


### Deciding on how I should format my website
When I created my wireframe for [computer](https://wireframe.cc/XtriJU) and [phone](https://wireframe.cc/GJKGb) I thought this would be easy with a template to start with. After I inputted the template I was overwhelmed with the amount of css code that I was afraid to change any of the existing code because I could have ruined the template. So I decided after the 3rd day of making my freedom project website that I should start from scratch and try to take inspiration from that website.
### Making the [Website](https://keithh9704.github.io/sep10-freedom-project/)/Challenge 1
When I first started I tried importing background image and adding text. It was working until the whole image was getting cropped out when I expanded the pixel size of the website. I tried doing `width: 100%;` but it didn't work so I was just confused and then I realized I had to use `background-size` to make the image go along with the text. Even though everything was working with the text over the Image, the image was repeating itself so I looked back at the template I was originally going to use and used inspect element to see how they inputted there background image. I found you have to use these codes to make the background image work.
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
After this was inputted in the website I realized that I had to make my text bigger so the whole Image would pop up. Alongside having a problem with my background image, everything was fairly easy making the rows and columns to present my Information in a way that looked like my wireframe.
### Adding Images and Aframe to my website
When I was done using my components on the website I went to add images. One of my Images was too small and one of my images was too big. I was so confused on how to change the size since I tried using `width: 100%;`. I Asked my friend Johnny if he knew anything and showed me that I had to resize the image from the file in my computer to make the website more responsive. Although It doesn't fit the whole box I am planning to fix that when I am working beyond mvp.


### Engineering Design Process
I am at the 8th step of the EDP which is Communicating the results because I made a website communicating my prototype. On the other hand I feel like I need to go back a step to step 7 which is improving as needed since I want to work beyond mvp on my website to make it more responsive and not look like I put really low effort on my freedom project.


### Skills
Between Blog 5 and Blog 6 I haven't really learned anything new skills but I have enhanced on skimming lines of code and grabbing the information I need and tinkering with the code with my own images and text on my website. I also worked on time management because I knew that working on this website in just one day would be really bad, especially on the last day before going back to school.


### Grabbing information from lines of code to tinker with
When I was struggling making my background image I used inspect element on the template I was going to use and there were a lot of lines of code so I looked for the css code under the id or class that the image was connected to and got my information I needed. Every website is different so instead of just leaving the code as it is saying I did it I tinkered with the sizing to my own liking.


### Time Management
Since I had to finish this website over the spring break I didn't want to procrastinate until the last day to finish the website so I gave myself 3-4 days to do parts of the website which made me feel stress free since I had other homeworks to do.


### Next Step
I look forward to working beyond MVP and presenting my website in the expo on what I worked on during the past year taking the sep course.

 

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
