**3D Printer Journal**

Hello again, welcome to the 3D printer Journal. This time, me and my partner (Kano) are working on programming a 3D printer and I am thrilled to share our progress.


**The Materials**

You might ask: "building a 3D Printer is so complicated, how can high school students do this stuff, and what do you guys even use?" Well I have an answer: we have awesome mentors
like Dr. Dzula and Mr. Raus. The materials? We currently have an arduino, breadboard, some wires, a distance/voltage sensor...That's about it for now actually.

![IMG_4487](https://github.com/user-attachments/assets/5fdb9984-43ae-40a6-bbd7-18dd139f0417)


**Problems+Progress**

1) Currently we have a running code that detects voltage and bits, but it cannot detect distances. I realized that neither me or my partner really knows how to code, so we are currently relying on WebbGPT and Mr. Raus. We did have some trouble connecting the distance sensor to the breadboard, then to the arduino. You need to really focus on cutting your unstripped wires so you don't cut off the entire tip of the wire. That was a problem we ran into a few times. Another issue we ran into was attaching the wires to the breadboard. (first you have to connect the wires to the sensor, then to the breadboard, then to the arduino, then to the computer, then do your code)We realized that we need to have the tip of the wires about 0.5 cm long in order to attach it properly into the breadboard. 


2) Breadboard Intro: there are two sides that are red and blue, this means that the currents can run through the whole entire column, but the center where there is not a blue or red  
line, it just means that each mini row of 5 are connected, for our 3D printer we need connect the black and red wire into any random row of 5 on the breadboard, seperate ofcourse,
the white wire will be used to measure voltage then connected into the Arduino, I mean the rest of the wires will be too, but that is more or less important)

<img width="541" height="320" alt="Screenshot 2025-11-12 at 19 50 39" src="https://github.com/user-attachments/assets/7ca9bb03-9ed3-4497-8d6c-f534d9354b97" />


3) The next step would be to measure accurate distances, I already have a graph for approximately what it should look like above. Also a code that I am not completely sure would work
   but I guess that's part of the process.

   <img width="711" height="504" alt="Screenshot 2025-11-12 at 19 51 55" src="https://github.com/user-attachments/assets/2f2617c0-722b-485e-8680-2db27f7f7bcf" />
   <img width="703" height="533" alt="Screenshot 2025-11-12 at 19 53 12" src="https://github.com/user-attachments/assets/993c4899-37ef-423f-9cf8-27a39141be0e" />

4) After the distance measuring, we need to think about how we can get the servos and steppers moving. Servos and Steppers allow movement of the sensor on the X,
   Y, and Z axes. This means you can measure/scan the object before printing.
   ![IMG_4604](https://github.com/user-attachments/assets/89f834aa-99a1-45c5-8b1d-6105b005ed8a)
**Goals**

1) To completely finish measuring distance and add it to the code (by next class)
2) have smooth (rotational)  movement of sensor moving in X, Y, and Z axes.

3) get parts to assemble printer (my favorite)
4) present to audience/inform Webb and classmates (end of semester)



**Current Conclusion+Future Plans**

The progress made so far has laid the groundwork for the eventual assembly of the 3D printer. Moving forward, the focus will shift from data detection experiments to the integration of mechanical and electronic components. This will involve selecting and installing appropriate sensors for precise distance measurement, designing the frame and motion system, and connecting stepper motors for controlled movement. Once the hardware is assembled, the next stage will be refining the software to synchronize sensor inputs with motor outputs, ensuring accurate calibration and reliable printing. By steadily combining these elements, the project will transition from a series of experiments into a fully functioning 3D printer, demonstrating the practical application of innovation and persistence.



**Timeline Overall**


I really think that I'm completely new to developing any software so I am definitley one of the people who are struggling more, what motivates me every day is thinking about drinking boba at the end of the week and having a completed 3D printer soon.


🛠 Roadmap to Assembly
1.	Sensor Integration
o	Add sensors to measure distances and voltge accurately.
- make sure that servos and steppers are spinning
- testing to make sure that object detection is possible in X,Y, and Z axes.
3.	Frame Construction (should be after step 4)
o	Build or source a sturdy frame to hold all components.
o	Ensure alignment for smooth movement along X, Y, and Z axes.
4.	Motion System Setup
o	Install stepper motors and drivers.
o	Connect belts, pulleys, or lead screws for precise axis control.
5.	Electronics Assembly
o	Mount the Arduino (or upgrade to a more powerful controller).
o	Wire sensors, motors, and power supply neatly onto the breadboard or PCB.
6.	Software Development
o	Write or adapt firmware to control motors based on sensor input.
o	Test calibration routines for accuracy in movement and extrusion.
7.	Extruder & Print Bed Installation
o	Attach the extruder for filament feeding.
o	Set up a heated bed or platform for stable prints.
8.	Testing & Calibration
o	Run test prints to check accuracy.
o	Adjust motor steps, bed leveling, and sensor thresholds.
9.	Final Assembly & Refinement
o	Secure all components.
o	Document the build process and improvements for future iterations.



**REFLECTION**
The personal, emotional journey:

**How did you feel**
Since I am pretty new to building with more advanced parts like arduino. I think being scared and ashamed  is how people feel when they step out of their box, but
sometimes I feel like I'm not always seen in the class due to my lack of knowledge on some parts of the class, but I'm trying to adapt
because I can't make everyone adapt to me.


**How did these feelings change as you encountered challenges and made progress?**
As I started making some progress, I think I tried my best to feel that I made a bit of progress. It's hard tp convince myself that I'm a lot
better than I started off with.I guess the reason why I feel this way is because I haven't started building because that's the only part I feel comfortable with. But, stepping out into the open is also very cool and I am learning to go with the flow even though the river is flowing really fast.


**How do these feelings relate to your journey of discovery?**
These feeling are building up... and stepping out of the norm means instant discovery, so I'm nervous but excited! Every time I feel stressed or uncomfortable, I usually end up with really good results and something new to add to my story.

Yay so that's it for now, I will continue adding all my progress I promise!!

Journal Entry 1: November 12, 2025

thanks for reading.
<img width="515" height="248" alt="Screenshot 2025-11-16 at 10 50 48" src="https://github.com/user-attachments/assets/4d8bf984-ed8e-4143-b6cb-d83640c591a3" />


