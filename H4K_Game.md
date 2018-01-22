# Juggling 

<b> This is a simple guide on how to program your own juggling minigame with Scratch </b>  
<b> Note: While doing this, make sure to save your project often to prevent dataloss! </b>  
<b> There will be checkboxes in front of every step. This doesn't mean that every step has something to do.   
    Sometimes it's just an explanation of the previous step for example. In that case, only check the box if you have truly understood the explanation.</b>

![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Introduction_Screen.png)

## Chapter 1: First steps

<b>Step 1: Setting up a background</b>  
The first step will teach you how you use a sprite as a platform to juggle the ball
    
   <b>Activity Checklist</b>
   - [ ]  Start a new Scratch and delete the cat sprite so that your project is empty. Right click the cat sprite in the sprite area below the project area
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Del_Cat_en.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Del_Cat_franc.png)


   - [ ]  Change the background of the stage to black. In order to do this, click on the stage to the left of the sprite area.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Stage_en.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Stage_fr.png)

   - [ ] Next, pick the bucket tool in the backdrop area.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Palette.png)

   - [ ] Make sure that black is chosen as colour. You have a colour palette below the area you're working in right now.
 
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Colours.png)

   - [ ] Now, with the bucket tool and black as colour selected, simply click into the big white area that you see on the right side of your screen. The result should look like this.  
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Backdrop.png)

<b>Step 2: Creating the platform</b>
   
   - [ ] The juggling game needs a platform to bounce the ball off of. In this step  we're creating this platform, which in our case simply consists of the letter D. This letter, when the game starts, will go into position and act as platform! 
 
   - [ ] Create a new sprite by clicking on the brush symbol above the sprite area.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/New_Sprite_en.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/New_Sprite_fr.png)

   - [ ] Now in the backdrop area on the right (The same area, where you painted the background black), you want to select the Text tool.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Backdrop_Text.png)

   - [ ] Select white as coulour in the colour palette. (Both squares on the left of the colour palette are white)
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Colour_White.png)

   - [ ] Now click into the area in the middle to open a text box. Enter a capital D. You do this by holding shift and then pressing the letter D. 
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Keyboard.png)
   
   - [ ] Since the D sprite is white it may seem invisible at first but it's there. Now, unselect the D sprite by clicking anywhere else in this area. If you do this, a bunch of rectangles and dots are going to appear on the D sprite.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/D_Grid.png)

   - [ ]  Select, the diagonal rectangles and drag them to make the D sprite bigger. Should you accidently unselect the D sprite or you're unsatisfied with the size, click on the little undo arrow that is pointing to the left, at the top part of this area.  
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Undo.png)
   
   - [ ]  If you're satisfied with the size of the D sprite, click anywhere in the area again to unselect it and make it appear in your project area on the left side.
   
   - [ ] Your project should now look like this.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Project1.png)

<b>Step 3: Creating the Ball</b>

   - [ ] The game obviously needs a ball which we are going to create now. Create a new sprite, just like you did with the letter D.  
   
   - [ ] Before, we used the bucket and the text tool. This time we are going to use the circle tool.  
   
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Select_Ball.png)

   - [ ] Select a green colour in the colour palette. To the left of the colour palette you also want to select the "fill" option for the ball. This means that we aren't just drawing the outlines, but the full ball.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Ball_Fill.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Colour_Green.png)

   - [ ] Now, inside the area on the right, hold shift and the left mouse button, then drag the mouse to create a ball. The reason why you want to hold shift, is because it forces a perfectly round ball, without shift it may turn into an egg!
   
   - [ ] From here on out it's the same as with the D sprite, release the mouse button and click somewhere in this area to finish the creation of the ball, just like with the D sprite, the ball should appear inside the project area on the right as well.
   
   - [ ] Your project should look similar to this.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Project2.png)

   - [ ] Before we move on to the programing, there's one more step required later on, that we should configure now.
  
<b>Step 4: Sprite Center</b>
   
   - [ ]  We  have to set the costume center. Select the D sprite, then, in the far right corner, you will see a cross symbol. select it.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Costume_Center_en.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Costume_Center_fr.png)

   - [ ] Go into the area with the cross, then hold your left mouse button and drag the cross in the bottom left corner of the D sprite. If you can't see the D sprite well enough or if you're shaking too much, try zooming further in, by clicking on the magnifying glass in the bottom right of this area.
  
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Magn_Glass.png)

   - [ ] You want to put the cross right here.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/D_Cross.png)

   - [ ] Now let go off of the left mouse button, the position of the D will change but that's fine. This happens because you changed where the center of the D sprite is.
   
   - [ ] Remember to use the undo function if something happened (i.e. The D disappeared).
   
   - [ ] Next, do the same with the Ball. The difference here is that you want to put the cross right in the middle of the ball. This should be easier than with the D sprite.
   
   - [ ] Now we got a propper set-up. Let's move on to the programing part shall we?
      
   
## Chapter 2: Basic juggling game

<b>Step 1: Transform the D sprite into a platform</b>

   - [ ] Once the game starts (When you click on the green flag above the project area). We want the D sprite to float torwards the bottom and become the platform we juggle the ball with.
   
   - [ ] We were working in the costume tab of the sprites, now we're changing to the script tab. This is where we put the code.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Tabs_en.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Tabs_fr.png)

   - [ ] The script window should look like this:
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Scripts_en.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Scripts_fr.png)

   - [ ] Now, let's make the code, that will let the D sprite spin and float. Try to copy the following code:
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/D_Turn_Code_fr.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/D_Turn_Code_en.png)

   - [ ] In order to completely write this code, a new variable has to be made. Click on Make a Variable under the Data option and call it "Degrees". Make sure to uncheck the variable after you created it, otherwise we will always see its value on screen and we don't want that.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Variable_en.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Variable_fr.png)

   - [ ] Once you click on the green flag above the project window, the D sprite should float slightly torwards the bottom of the area and at the same time to a 90 degree spin to the right.
   
   - [ ] Explanation of the code: When we click on the green flag, we set the D sprite to a specific x and y position which is somewhere in the middle. The x axis is basically the horizontal axis, where as the y axis is the vertical axis. If you move your mouse through the project area, you can see the axis of your mouse in the bottom right of the project area.
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/axis.png)

   - [ ] The pointing into direction part means it's pointing straight right. 0 would mean it would face straight upwards.
   
   - [ ] Then we set the "Degrees" variable we previously created to 0, meaning we reset it every time we reset the game.
   
   
   - [ ] The big "repeat until" thing that surrounds other code is a loop, meaning whatever is inside is being repeated until the criteria is met. In other words, we repeatedly turn the D sprite by 1 degree to the right and then add 1 to the "Degrees" value until the variable "Degrees" equals 90. Simply put, we turn the D sprite 90 times by 1 degree really fast. After 90 times, the variable "Degrees" has the value 90, so the loop criteria is met and it stops.
   
   
   - [ ] From a seperate starting point we then let the D sprite glide for 3 seconds to a predetermined point closer to the bottom of the project area. This has to be seperate because if we add it to the first block of code it will either turn or glide first, then do the other.  This way it does both at the same time.
   
<b>Step 2: Make a bouncing ball</b>

   - [ ] The following code will let your ball freely jump around: 
   
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Base_Ball_en.png)
![title](https://github.com/JeyAl/internship/blob/master/Scratch_Images/Base_Ball_fr.png)

   - [ ] First, when the flag is being clicked, we set the speed to the base value 8, you probably already guessed that this is a new variable you have to create, just like you did with "Degrees".

   - [ ] Then, just like with the D sprite, you assign a fixed position, that the ball will always return to when clicked on the green flag.
   
   - [ ] We let the ball face a random directon from -30 degrees to +30 degrees, which is basicly a cone facing straight up.
   
   - [ ] Then we wait 3 seconds. We do this so the ball doesn't start bouncing before the D sprite is in position.
   
   - [ ] Inside another loop, simply a loop that lasts forever as it says on it, we let the ball move at "speed" steps, so in other words 8, since we set the "speed" to 8 in the beginning.
   
   - [ ] And of course we let it bounce with the next line of code whenever it hits a wall.








----------------

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









   
   
   



   
   
   
