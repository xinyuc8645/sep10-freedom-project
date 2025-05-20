# Entry 6:MVP Of My Freedom Project Website (Not Beyond MVP)
##### 5/5/25
# Context As Usual
Base on the last entry; 5 in that entry I included how I tinker with my Aframe tool. As for this blog, I want to dive in on how I created my website for Freedom Project for MVP(Minimum Viable Product). And yea that's basically all for the context. Just do note that this entry may get a little bit of lengthy depending on how much information I put, but I do want to keep this entry short as possible.So, I guess sit back and relax?..
# Content Part 1
Alright, so for my website I wouldn't say its really "special" I would much rather call it "normal" I think my website is just simple and not too complicated. I also did not use any bootstrap templates for my website; the reason being that one if you use a bootstrap template, there are many codes you could change, but at the same time you wouldn't understand any of them. And two I want to start my website off base off of scratch instead of an pre-existing template, so I don't rely too much on other's existing codes. Now there were 4 components I used, it was navbar, cards, carousel and accordion. Of course, most of these key functions are from the bootstrap websites. However I did adjust and modify them to my liking. Which I'll show later. As for my entirely of my website, I planned to have an blue background, but it would be too boring. So instead, I use linear gradient. This code actually saved me because I remember using this code back for one of the presentation we had to do, and my section was base off of linear gradient. The linear gradient code I used for my background were:

                  body {

                    background: linear-gradient(to right, lightblue, blue, darkblue);
                      height: 100vh;
                        margin: 0;
                            }
Base off of this code, if you copy and paste it into jsbin, you should be able to see that from the right, it shifts from white-> to lightblue-> then to blue-> then lastly to darkblue. This made my website's background a whole lot more interesting and not plain. Once again the color shift's from right to left. As for the navbar it's nothing to special:

                    *CSS*
                          .navbar {
                      position: fixed;
                        width: 100%;
                        top: 0;
                      z-index: 1000;
                    font-family: monospace;
Okay, so I'm just only going to show the CSS section because the navbar is just an code but different color for navbar from the bootstrap website. Some of the stuff that I modify were I made the navbar fixed top, meaning if you scroll down the navbar is still at the top of the screen and still be able to function and navigate like usual. And some normal width and top, with z-index making so that it fits the whole screen. Also needing to emphasize something that the navbar is in an container fluid I believe. And lastly font-family monospace so it wouldn't be too plain.
# Part 2
I covered about the navbar and the background, now I wanted to focus more sort of on the paragraphs for my introduction, as you can see for my informations for my website, you notice how it was side by side. The question is how did I do that? Well:

                          <div class="section-content row">
                            <div class="col-lg-4 mb-4">
                              <p>
                            The website URL does not seem to end with typical extensions like .com, .edu, .gov, but instead ends with .html, so its reliability is                               uncertain.
                            Upon visiting the site, it appears very clean and easy to navigate, offering a family-friendly experience with no inappropriate content.
                          The site provides a basic overview of the software, explaining how it can be animated. The site is divided into sections, with the first                               explaining how you can animate in real-time using your device's webcam. Essentially, it's a website telling you about the software                             that hosts another site. At the bottom of the page, there’s a payment bundle labeled “Creative Cloud All Apps.”
                          </p>
                          </div>
From this code you can see, when on large size screen the paragraphs only takes 4 columns. I know that in total its 12 column's. Meaning since I had 3 paragraphs side by side, I basically did the same for the other two paragraphs. And that's all pretty much to it. Since I gave it a class and made the text white. Nothing that special. For the last set of code I want to cover is:

                           <div class="col-6">
                        <img src="./img-texture-folder/zoetrope.jpeg" alt="Adobe" class="img-fluid w-100">
                          </div>
                      <div class="col-6">
                    <img src="./img-texture-folder/working.jpeg" alt="Working" class="img-fluid w-100">
This set of code is for the two preview image that is side by side. If you don't know I got the image to work and where I got it from basically, I created my own set of image folder, however I'm currently in index html, meaning I have to go back by ./ then it will lead me to the img folder. And once again you see that I used col-6 meaning it takes up 6/12 columns. Meaning they get to share half and half. And overall giving them lastly a class to make them fluid.
                          
# Engineering Design Process
As for this entry, I wanna still say that I'm more leaning towards the creating type. The reason is because, if you don't know the whole reason that we're even doing a website for Freedom Project is for the FP fair thats upcoming. And since I create an website, that is MVP I think its pretty decent. I wouldn't say its super good, because there are still bugs, organization stuff I have to fix and etc. But I definitely want to shift towards away from the planning side. And lean towards more of creating. And hopefully by next entry I'll be on testing for my <em>Beyond MVP</em> website.
# Skills
### The ability to use HTML codes, CSS, and other outside resources like bootstrap to strengthen your website
I consider this skill easily one of the most important skill because, without the use of the knowledge of basic html code and css codes, many of the website's element won't be possible. The ability to also use outside code source like bootstrap is also important because, you don't want your website to look plain and boring and old right? That's when bootstrap comes in to play. Think of bootstrap as an upgrade to your website. Not only does bootstrap have highly advanced component that you can fit into your website, it makes your website looks a whole lot more modernized. And let me be honest, getting an bootstrap code from the bootstrap website isn't hard at all. All you have to do is copy the code, unless you want to create the code yourself, and paste it into your html. And then from there on you just change/add stuff you need into the bootstrap. It's just that simple.
### Design/Planning/Wireframe of your website
I think this is also an important skill, the reason being that, some people may think that you do not need an overall layout or an planning of what your website is going to be look like, and where the content is going to be, but in reality you NEED an overall gist, whether it be wireframe, planning of your website before you ACTUALLY start coding your website. Not only does planning and making an wireframe makes your life more easier, it also makes it so that its more organized. Because you do not want to procrastinate when you are coding, and wondering to yourself "Where should I put this content? If I place it here then it won't fit, and it will collide with other section.." that would make you lose time instead of using them sufficiently. Additionally, from my own personal experience speaking, in an non-bias and honest perspective, when our teacher told us before you start coding, "make an planning/wireframe FIRST" I honestly didn't even want to make one. Because I thought it would make me waste my time figuring one what goes where and where. But after I spend some time on writing and designing my wireframe layout for my website. I finally realized how EASY it was. On the day of actually creating my website, all I had to do was just look at my planning and my wireframe then copy and paste my content into sections I planned how, without having to waste my time on thinking where to put them. Basically TLDR; don't go in blind to create an website, from scratch without an planning/wireframe layout of what your website is going to look like.
Text

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)
