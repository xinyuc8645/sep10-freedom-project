# Entry 5: More In-depth Tinkering for my tool Aframe Along With Code Snippets
##### 4/11/25

# Context Before Diving in
As you may already know, base on the last blog entry 4,(if you haven't read it yet [read entry 4 here](entry04.md)) I mentioned and talked about tinkering with my tool Aframe and why I choose Aframe as my tool for the whole Freedom Project. But one thing  I didn't do was talk in-depth about the tinkering. I only talk about the basics, to which in this blog 5 I want to really go in deeper with my tinkering, and some codes I tried out and evidences of me coding by providing code snippets and syntax. So let's now deep straight into the tinkering section.
# Tinkering In-depth with Aframe
<em>Just a heads up most of the content in this section will be mostly from my learning log, because that is where I kept all my tinkering with my Aframe tool</em>
To start off, as you may know if you want to tinker firstly, you want to have the code link already implied in whatever coding system you use. In my case, it was the Cs50.dev. You also want to make sure that what you're tinkering with your tool, its inside the <a-scene> and the </a-scene> code. Following by the outside out of <html> <body> and etc. If you do not put the code in the scene code, your code/object you created will not appear and will appear blank. In order to preview what you have created if you are using Cs50.dev type http-server and open it up, naming your file at the end with html, anything other than that name will not open and work. With the basics, for the first 1-2 videos I watch on the tutorial for Aframe I were taught shapes. I know I know this may seems simple stuff, but think of it as a review. There shapes to the following:

                <a-box>, <-a-box> (box) <a-cylinder>,</a-cylinder> (cylinder), and etc. 
of course there are many other shapes, but those are the simple basic ones you want to use. After I type 

                                <html>
                                <head>
                                        <script src="https://aframe.io/releases/1.6.0/aframe.min.js"></script>
                                    </head>
                                  <body>
                              <a-scene>
                              <!--box>
                              <a-box>
                              </a-box>
                              </a-scene>
                              </body>
                              </html>
I opened up http-server and preview it, it was an <em>box</em>with with plain white color, nothing special at all. However I didn't want it to be simply just be white and colorless. So I used some CSS skill from some couples of lesson back, and changed the box color, changing the color of your shape is easy. Simply add the following:

                             <a-scene>
                              <!--box>
                              <a-box color="red">           
                              </a-box>
                              </a-scene>
Simple right? Just add the color="(color)" code to the shape. Now when I refreshed the page the box will look red! The same goes for other shape. Moving on to positioning and relative positioning. Basically for this video I watch, it just talks about changing the positioning of your shape and some basic rules to the positioning. For example there are three coordinate to change for positioning. The x, y, and the z. Basically think about an graphic label with the x and y axis. And with the z think of the like combining the both together a sort. (The x being like the thumb and the y being the pointy finger, and the z being the third finger.) In order to use this to full advantage, I tested it out with my guinea pig, my good old friend box shape. 

                           <a-box color= "black"
                          height="3"
                            position="0 10 0"
                            width="2"
                          length="1.5">

                          </a-box>
                      <a-cone color="blue">

                        </a-cone>
                          and
                       <a-box color= "red"
                          height="3"
                        position="20 0 0"
                        width="2"
                        length="1.5">

                        </a-box>
                    <a-cone color="skyblue">

                    </a-cone>
From the first example, when I tested in my IDE, when I changed the box with the black color position of y value, the positioning went up, as in like upwards towards an imaginary sky. Then from the red box, when I changed the x value, the box seems to go in front. The changes may not seem drastic but the more you changed the x and y value the more it goes in their certain direction. Now the reason I didn't include the z positioning is because, when I tested with the z position because, its some of a mix between both the x and y value. I often think of the z value as a combination of both.                 
# Part 2 Of Tinkering
I know for before, I explained about the position, simply because basically its all about x, y and z positioning. But apart from that there is also something called the relative positioning and rotations. This one focuses more on rotations. Like you know how the clock can rotate to an certain degree an angle, well think of that as an example. From my understanding when I watched the video, it goes something like this for the x positioning rotation<em> if you do changed the x value of the rotation; like rotation="10 0 0" it changed the item/object like slanted</em> for the y positioning rotation<em>if you do changed the y value of the rotation; like rotation="0 10 0" it changes like also slanted like the x value changes but different way</em> and lastly for the z value, its basic the same stuff all over again with the positioning because when I tested out on my IDE:

                                  rotation="20 30 10" --> (shape turning side) rotation="20 30 40" --> (turning more)rotation="20 30 70" -->(I thought it                                               completely flip itself over but apparently not?
Overall, just is that z value for some reason it just keeps turning its side over and over, I don't know if that's because of the x and y rotations I put.          The next video I watch was scale, relative scale and reflection. Once again the code is the same exact format as the other 2 before, but different functions. There are some rules you have to remember when you are doing the scale function. For the scale to function, as for me if my y of the scale, stayed at 0, the shape would of appeared flat, and it was so thin to the point where you basically can't see it at all. So you have to put an number that is apart from 0, you can put like 0.5, 1, 2 and etc. And apparently, for the x value, it doubles the shape sizes? Because thats what happen when I was testing out my shape multiple times. But I swear it's always the z values that always confuse me because, for z the more bigger number I input the bigger the shape becomes?? along with the thickness of it.

                             <a-cylinder color="brown"
                              height="3"
                            radius="1"
                              segments-radial="5"
                                open-ended="true"
                                side="double"
                              position="0 1 0"
                            rotation="0 -90 90"
                          scale="2 1 0">
                        </a-cylinder>
This is a flat bed of an cylinder. 

                          <a-cylinder color="brown"
                              height="3"
                            radius="1"
                              segements-radial="5"
                                open-ended="true"
                                side="double"
                              position="0 1 0"
                            rotation="0 -90 90"
                          scale="5 1 0">
                        </a-cylinder>
The flat bed became much longer
# Engineering Designing Process
Base on the last blog 4, I said that I was still in-between the creating and the planning section. But I can confidently said that I'm officially moving out of the territory of the planning section into the creating section. Since planning, I associate that with like learning your tool since you need to watch video and make a plan for yourself of how you want to tinker with those tools. The reason why I'm saying I'm at the creating section is because right now, I tinkered with my tools Aframe to the point where I understand most of it's concept (Maybe except for some concept like NRM maps and etc). I think I can fully stand in the creating section if I watch all the tutorial for Aframe in my playlist over the break. So currently, I am in the creating section of the engineering designing process, but only like 50% of the way of there, so expect the next blog to have fully 100% on the creating section.
# Skills
### Paying Attention To The Details Presented
I think the skill of paying attention to details, even to the smallest detail in code, is one of the greatest skill that you can have for an software engineer, because firstly you want to make sure the code you entered to your project or website is correct and secondly you want to make sure that the code runs smoothly. Which paying attention comes in key play. Because many coders tend to be clumsy with their code, and sometimes they put their code very fast without double checking and paying attention to each code. Sometimes they often end up putting the wrong set of code in the wrong place. Additionally, paying attention to small details can sometimes save your life (metaphorically). Like if you have an code project that is due soon, however you try to speedrun that project and finish it in under 3 days. You might code very fast. Then you turn in that code project, but on the day the teacher checks the homework, and everything end up not working, and everything is not presentable and you end up getting a 0 for that project. But if you pay attention to every code (not saying <em>Every</em>) but some you can at least prevent some silly mistakes that are easy to make. 
### Identifying and Solving An Problem Presented
This skill is also important because, if you are an coder, you need the skill and ability to identify "what is the problem that is occuring for your code" and second "how you can solve that problem in front of you". Without those abilities, coders can't function proper. Like, for example let's say you have a reader, and that reader is given an test, and the test prompt is "identify what is the main idea of this text", and "what evidences can you use to support that this is the main idea of the text" and if the reader cannot identify the main idea among with the evidences then they fail. Think of identify and solving an problem this way. You also cannot be lacking in both areas. Meaning you cannot identify an problem, but you cannot solve it, the same thing goes for the other way around. You cannot solve an problem without identifying the problem first. Both skills are important in this case, especially to an coder, the abilities of coders to identify an problem then to solve an problem is what make coders extremely invested in their time. Meaning they need the patient and the time to identify an problem and solving one, since some code are so long to the point where it takes 1 hour just to solve one problem. All I'm saying is, without identifying the problem of an code, you can't solve it. And solving an problem, doesn't mean you identify the problem. So it's good to have both of those skills.
Text

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
