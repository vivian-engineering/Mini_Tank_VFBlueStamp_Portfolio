# Mini Tank: Wilma the WOAHbot
My project is a Mini Tank Robot. Essentially the robot uses a bluetooth to read signals sent from the app and then uses the switch() method in C++ to choose what to do. According to different cases the robot will move in different directions and project the corresponding arrow on the LED board. The hardest part about the build was understanding how the wires connected and operated relative to the board. The arduino runs on digital pins, and I've been using PWM in order to simulate what analog pins would be able to do, namely allowing the robot to move at different speeds. I also editted the code for the robot so that other buttons would allow the robot to turn while moving rather than either going straight or rotating on its own axis. One of the hardest things to build in this project was the CAD for the outside because the arms included a ball-and-socket mechanism and took countless tries to figure out how to fit the ball in the socket without falling out of it. Also, I don't understand C++ so in the beginning it was a bit challenging to code. After taking copious color-coded notes however, I was able to understand what the different functions do relative to the robot. Overall, during this project I learned about various systems and methods like PWM, IIC, and Bluetooth which all allowed me to gain a deeper understanding of how my robot, and other electronics, works.

<!--You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions: -->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Vivian F. | Los Gatos High School | Electrical Engineering | Incoming Senior

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/w1hHq3U6-G4?si=9fnR-Sp6K69DlYNv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

## Components
The components within my robot are the motor system, the ultrasonic sensor that rotates on a swivel, the robot's framework, and the arduino board. For my first milestone I started by building out the motor system which involved several plates that I screwed with the motors themselves, the wheels, and the wheel belts. Afterwards I built the robot's framework, which included the base plate, the LED display, and all the sensors except for the ultrasonic sensor. Next I built the ultrasonic sensor mechanism, or the face of the robot, which involves an ultrasonic sensor attached to a swivel. Finally, I assembled the arduino board itself and connected all the parts together.

## Challenges
One of the challenges I faced when building the robot was just trying to create the wheel mechanism. I made a substituion for a longer screw in the place of a shorter one and later on was unable to use the shorter screw in the longer screw's place. I had to dissassemble the entire structure to redo it. From that I learned that it's best to stick to the right parts as listed in the instructions, and to not just assume I have the resources to use any piece in another's stead. Another issue I had was just with assembling the robot's structure because apparently for a cleaner finish it is best to remove the paper layer on the base plate. Because of that I had to dissassemble and reassemble the entire robot which was very painful. Also, because the breadboards didn't fully combine together I assumed that something was wrong with them but apparently that was just how it fit together.

## Future Plan
In the future I want to add a CAD exterior, and if time permits then the CAD exterior arm would have a ball and socket. Also, I want to paint the exterior of my CAD to make it look more unique, rather than the boring white plastic of the CAD. I also want to work on editing the code so that my robot can move in more complex ways rather than only being able to rotate or turn. I want to enable my robot to turn and move at the same time.

<!-- For your first milestone, describe what your project is and how you plan to build it. You can include: -->
<!-- - An explanation about the different components of your project and how they will all integrate together -->
<!-- - Technical progress you've made so far -->
<!-- - Challenges you're facing and solving in your future milestones -->
<!-- - What your plan is to complete your project -->

# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/JIrFPbK689g?si=9VcRaQSX-hb6To9b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Keyestudio DIY Mini Tank V2.0 (Arduino) | Assembly kit equipped with necesary sensors, motors, circuit boards, and other miscellaneous parts. | $84.00 | <a href="https://www.keyestudio.com/products/keyestudio-diy-mini-tank-v20-smart-robot-car-kit-for-arduino-stem"> Link </a> |
