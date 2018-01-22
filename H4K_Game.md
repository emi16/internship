# Juggling 

<b> This is a simple guide on how to program your own juggling minigame with Scratch </b>  
<b> Note: While doing this, make sure to save your project often to prevent dataloss! </b>

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Introduction_Screen.png)

## Chapter 1: First steps

<b>Step 1: Animating a platform and a ball</b>  
The first step will teach you how you use a sprite as a platform to juggle the ball
    
   <b>Activity Checklist</b>
   - [ ]  Start a new Scratch and delete the cat sprite so that your project is empty. Right click the cat sprite in the sprite area below the project area
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Del_Cat_en.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Del_Cat_franc.png)


   - [ ]  Change the background of the stage to black. In order to do this, click on the stage to the left of the sprite area.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Stage_en.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Stageg_fr.png)
   
   Then, add a Platform, a ball and the lava floor. (The Platform is just a D letter). This is what the stage should look like:
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Base_Screen.png)

   - [ ] Next, we have to set the costume center. Click on the ball sprite and select the costumes tab. Click on the cross in the top right corner of the costumes screen. A cross will appear.  
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Cross_Select.png)
   
   - [ ] Put the center of the cross right in the middle of the ball and then do the same with the D letter, but here, put the cross in the bottom right corner of the letter.
   
   - [ ] Add the following code to your D sprite:
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/D_Start.png)

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/D_Glide.png)

   - [ ] In order to completely write this code, a new variable has to be made. Click on Make a Variable under the Data option and call it "Degrees".
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Variable.png)

   - [ ] If you now click on the green flag above the project, the D should turn sideways and glide a little bit torwards the bottom of the screen and turn into a platform!
   - [ ] We have a platform so the next thing to do is, make a ball. Select the previously created ball sprite and add this script:
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Ball_Bounce.png)

   - [ ] Now, if you click on the green flag, once the D has become the platform, the ball should start bouncing around in the project window.
   
<b>Step 2: Moving the platform and juggling the ball</b>

   <b>Activity checklist</b>
   - [ ] The next step will implement some code, which, once the D has become the platform, lets you control it with the right and left arrow keys.  
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/D_move.png)

   - [ ] The bouncing ball will just go straight through our platform. What we want to do is add a solid area on top of the platform that the ball can bounce off of.
   
   - [ ] Add a new sprite. This new sprite should be a yellow line that should be about 1 pixel wide and 7 pixel long. Pixels are shown as grey/white rectangles in the costumes window if you zoom in as shown in the picture below.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Yellow_Bar.png)

   - [ ] Next, do the same as above, but this time make it a blue bar. For both, set the costume center cross to their bottom right just like you did with the D letter.
   
   - [ ] Now, we want to add some code to those bars. Add the following code to the blue bar.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Blue_Bar_Position.png)

   - [ ] You probably noticed that this code is similar to the one that lets the D turn and float down, this code essentially does the same with the blue bar, just that the bar is first invisible and appears once the platform is in position.
   
   - [ ]  Now you want to add the same code to the yellow bar, since this bar isn't at the exact same position, we have to change the output position slightly as shown here:

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Yellow_Bar_Position.png)

   - [ ] The juggling is almost playable now, we just have to program the ball, so that it bounces off of the yellow and blue bar and the angle it bounces off should be determined by whether the left or right side of the platform is being hit.
   
   - [ ] We're going into the script of the ball and program a colour detection, since the yellow bar will be on the right and the blue bar on the left of the platform, we add the following lines to the previously programed code:
   
   <b>Previous ball code</b>  
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Ball_Bounce.png)

   <b>New ball code</b>
   
![title](https://github.com/JeyAl/internship/blob/master/Ball_Propper_novar.png)
   
- [ ] The game should be playable now. Click on the green flag and give it a try!  

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/demo.png)
  
<b>Step 3: Additional features</b>  
There is no real goal yet, so let's implement a timer, a game over screen and a scoreboard.  

- [ ] First, we are going to declare a time, score and top score variable to show us our playtime countdown, our current score and the top score. Just like before, go to the Data Menu, click on Make new Variable and create these variables:  

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Vars.png)

- [ ] Make sure, the check box next to those 3 new variables are checked. This means that they appear on screen. They also can be dragged around freely. I positioned them at the top, as shown in the first picture.  

- [ ] We are going back to the ball code we previously added. The one that lets the ball bounce differently depending on the colour it's hitting. Here we want to add some "score increase by 1" and "speed increase by 0.2" code. For the speed part, you want to add a new variable called speed obviously, this variable can be left unchecked.

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Score_Up.png)

- [ ] Every time the platform is being hit, the ball will move slightly faster and you get a point. Give it a try and see if the score goes up, as it hits the platform.  

- [ ] We now want to add some variable initiators. In other words, we make sure that every time the game is replayed, specific variables will be reset to their initial state. We add 3 initiators to the beginning of the ball code we programmed earlier. This is what the full code looks like:

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Ball_Full.png)  

- [ ] Every game must come to an end, so let's add some code that determines when the game is ending.  

- [ ] The game is ending one of 2 ways: When the bottom part (the lava) is being hit or when the timer reaches 0. In order to do this we are broadcasting a bunch of variables that initiate the game over screen when either the timer hits 0 or the ball is touching "red" as in the colour of the lava. This code is pretty big and a bit confusing, but easy to understand if you go through it step-by-step.

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Game_Over.png)

- [ ] The code is almost done, just missing a few last parts, this is where thee variables that we declared before are being used.  

- [ ] This code will stop the player from moving the platform after the game ends.  

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/D_reset.png)

- [ ] We do the same with the ball and at the same time, we are updating the top score, if it was beaten.  

![title](https://github.com/JeyAl/internship/blob/master/Ball_reset.png)

- [ ] Now, we want to make the two bars invisible again, just like they were in the beginning. Simply add this to their respective sprites:

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Yellow_reset.png)

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Blue_reset.png)

- [ ] Create a new sprite and make it a simple Game Over text and put it where you want it to pop up. Then simply add this code, to let it appear disappear at the right time.

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/GO_screen.png)

- [ ] A Game Over should look like this.  

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Done.png)

- [ ] There you go. Your own juggling mini game is done!









   
   
   



   
   
   
