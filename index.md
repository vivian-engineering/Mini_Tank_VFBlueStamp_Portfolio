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

## Technical Progress
## Challenges
## Future Plan
For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project

# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

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

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
