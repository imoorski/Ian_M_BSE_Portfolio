# Midi Controller
For this project, I built an Arduino MIDI Controller. A MIDI controller is a tool that allows for the interactive creation of music. I chose to make this project because I really enjoy making music and I wanted to build something I could use in a meaningful way.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Ian Moore | Los Gatos High School | Electrical Engineering | Rising Senior

![IMG_5987](https://user-images.githubusercontent.com/86970592/126803887-d78d956e-3c88-4b66-94eb-772f20781c62.jpg)

# Demo Night
Reflection: Overall, I feel that I really got to experience the trial and error nature of engineering firsthand during this project. I ran into a lot of roadblocks along the way, so I had to spend a lot of time debugging and brainstorming other potential solutions. I think I've picked up valuable problem solving skills, as well as engineering specific skills like soldering.

<iframe width="560" height="315" src="https://www.youtube.com/embed/etMTezY4xrc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Final Milestone


For my final milestone, I finished the midi controller. I soldering a ground wire between the buttons and individual wires from each button to a pin on the Arduino. For the potentiometers, I soldering a ground wire, a power wire connecting to the 5V pin on the Arduino, and individual wires connecting to the analog Arduino pins. Once everything was soldered, I wrapped the connections with electrical tape for insulation. After the physical midi controller was finished, I had to make sure it was working properly. The hairless-midiserial app was registering inconsistent inputs from the midi controller, but after changing a few lines of code, it worked properly. Finally, I tested the midi controller with Ableton and was able to map everything correctly.

<iframe width="560" height="315" src="https://www.youtube.com/embed/JmAzzM2Iua0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Second Milestone


My second milestone was getting a button and a potentiometer to work simultaneously in Ableton, as well as preparing to assemble the actual midi controller. In order to use the button and potentiometer together, I had to use some different code, as well as an application called hairless-midiserial to convert the signals from the Arduino into MIDI information that Ableton can read. For the casing of the controller, I am just using a plastic enclosure, and I had to drill out and sand all the holes for the buttons. I made sure the buttons fit and then I connected a ground wire between them in preparation for soldering and putting the midi controller together.

<iframe width="560" height="315" src="https://www.youtube.com/embed/LFArD90AK3E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# First Milestone
  

My first milestone was building a basic circuit and getting the Arduino Uno set up with the Ableton digital audio workstation. The circuit includes two potentiameters that are connected to two of the analog pins on the Arduino. I used the standard Firmata code in the Arduino IDE to get it to connect with Ableton. Ableton has a plugin specifically designed for Arduino, so it was very straightforward once they were connected. I created a simple midi synth instrument in Ableton and mapped the two analog pins to different parameters of the synth. This allowed me to control the synth parameters with the potentiameters. Initially, I was trying to connect the Arduino with the Logic Pro X digital audio workstation, but I had a lot of difficulties with that. After some research, I found out that Ableton is actually much more compatible and optimized for the Arduino, so I switched over. For this milestone, I also created a diagram plan for my midi controller. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/cQkooa2bY04" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
