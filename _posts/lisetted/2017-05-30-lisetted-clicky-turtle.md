---
layout: post
author: lisetted
title: "Lisette's Clicky Turtle"
---

trinket
<iframe src="https://trinket.io/embed/python/47fd051be1" width="100%" height="600" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen></iframe>

Reflection:

I wanted to create a guessing game where the user tries to guess what randomly generated shape will appear next. Instead, I have 3 boxes that the user must draw some shapes in, and one box where the shape is randomly generated. In the first 3 boxes, there are unique colors for the shape if drawn in the box, and red if it is out of the box. 

I ran into a bunch of issues that I couldn't fix in this. First, I wanted to send an error if the user drew a shape outside of the randomly generated shape box, but the random function didn't seem to work correctly with that. Instead, I have the color be red outside if the shape is drawn outside fo the first 3 boxes. This means that any shape drawn in the random box will be red too. I also tried to create a helper function to change the turtle color, but I couldn't get the variable to correctly call the tina.color. If I had more time to play with it, I could have probably gotten it to work. I also would like to fix that a message is shown to draw inside the box even when the user is drawing in the  random box.

My other big problem is that I can't figure out how to move on to the next shape after one. I used an input statement, but then the user has to click enter and I was hoping to make them be able to get a new shape on the second click.

Even though I didn't get to do everything I wanted to in this exercise, I feel pretty good about it. I solved a lot of problems along the way (most of which I cannot remember to write here, maybe I should take more notes while I'm working on it). If I were to start again now, I think I could probably create the guessing game I had originally wanted to do. 

Update  5/31/2017
I was able to fix a bunch of my issues (mostly simple mistakes) after I had a chance to step away from the turtle. One of my stupid mistakes was along the lines of -45<= tina.ycor() <=-145, which by definition would always be false since -45 is larger than -145! Now the clicky turtle changes colors depending on where it is in the x,y coordinates.
