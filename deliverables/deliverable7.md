# Deliverable 7

In Deliverable 7, you'll continue working on your Etch-A-Sketch mode with the aim of having it completed, meaning it achieves all of the requested functionality outlined in the [README](../README.md) and [Deliverable 6](deliverable6.md) adequately. You'll also begin your power supply design, another electrical engineering element to this project. Details for both below.

## Finish Designing, Building, Testing, and Documenting Etch-A-Sketch Mode (D)

This week you should be close to finishing your Etch-A-Sketch mode. It's important to remember that these milestones are not strict deadlines, however you should have at least some functionality working for the Etch-A-Sketch mode, and you should not move on to the rest of the project until you've completed the Etch-A-Sketch mode. 

**D**: As part of this deliverable we ask you to bring your plotter into class to demonstrate the work you've done so far. This is so we can get a feel for how well the functionality has been implemented. As mentioned in the Project Specifications section of the readme, you should have your code [launch on startup](setup/launch-on-startup.md) (when you power on the Pi) to reduce the setup time/equipment needed for your demo. While this is not strictly required for this demonstration (as this was a late addition), it will be required for future ones.

**D**: In addition to the in-class demo, you'll also need to submit a video of the work you've completed for your Etch-A-Sketch mode. It should be short and to the point, while showing each of the pieces of functionality that you've completed. This is primarily a fallback option for us to grade, in case hardware issues arise in class. This video can be more than 30 seconds.  Try to keep it at 90 seconds or less. Make sure you given commentary during the video so we know what you are doing.  Follow the order below in your video.

Show the following in your video: 1) draw a horizontal line, 2) draw vertical line, 3) draw diagonal line, 4) show pen up/down with "y" button press, 5) show slow/fast speed with "x" button press, 6) With pen up of course, show your pen will not go beyond mechanical limits of plotter. This means the limit switches will stop the stepper motors for each axis when pressed. Based on the location of this point (where the gantry is when the limit switches are encountered), you should characterize your x and y stepper motors so that the the plotter cannot go beyond the opposite x and y limits of the plotter's gantry. In other words, the switches give you one extreme limit. You have to calculate the other. Show in your video that it captures and prevents all cases. 7) show simultaneous button press puts plotter in a wait mode for further input from user with prompt on LCD. And, will ignore x/y inputs because no longer in Etch-a-sketch mode.

For the in class checkpoint, we will go through each of the 7 "video" steps plus we want to see the system come up cleanly without major acrobatics to get things working.

> Note: This deliverable grade is NOT the grade for etch-a-sketch mode. It is simply a checkpoint grade to encourage you and your team to stay on track for this project. It will be a factor of your final grade, but your "minimum to be considered for" is evaluated at the END of the semester, based on the modes your team was able to implement. With that in mind, if you have not completed etch-a-sketch mode to this point, showcase the work you have done, and aim to complete it as soon as possible so you can move on to Math Mode.

## Begin Power Supply Design (P)

To supplement this project with a bit more electrical engineering, we've assigned you a routine design of a power supply for your plotter! The final design will be due as part of Deliverable 9. Below are some electrical specifications and design requirements for your power supply, as well as the requirements for submission.

### Design Specifications

- Your power supply will take in 120 VAC from the wall, and supply 12V 5A DC typical, with +25% peak output capability (should be able to output up to (12V\*5A) + (12V\*5A)\*0.25 = 60W + 15W = 75W Maximum Output) and +/- 5% allowable tolerance.

- less than or equal to 10% peak-to-peak ripple/noise on output (at full load)

- You must use [active components](https://en.wikipedia.org/wiki/Electronic_component#Active_components) (i.e. not just transformers, capacitors, inductors, resistors, diodes, etc.)

- Your design should optimize for efficiency and cost

### Submission Requirements 

- You must submit a complete schematic and fabrication-ready board layout made with [Autodesk Eagle](https://www.autodesk.com/products/eagle/free-download).

- You must also submit a MultiSim simulation demonstrating the functionality, stability, and accuracy/quality of your design. Your simulation should measure the output characteristics of your design with and without a load, including measurements such as voltage, current, and [ripple/noise](https://knowledge.ni.com/KnowledgeArticleDetails?id=kA03q000000YG05CAG&l=en-US).

- In addition to your design and simulation, you'll also need to provide a [Bill of Materials](https://en.wikipedia.org/wiki/Bill_of_materials) which should include DigiKey prices and part numbers for every electrical component.

**P**: With the above information in mind, as part of your deliverables for this week, you should submit an early design for your power supply. It can be anything from just an idea for your design, all the way up to an initial schematic. **Do Not Stress** about this deliverable, it is simply to make sure you have started thinking about your power supply design. Design files can include a description (with pictures) of the design, schematics, breadboard pictures, etc.

# Summary

In summary, for this week you need to:

1. Submit your **D** deliverables (Etch-A-Sketch video) to the Design Deliverables 7 assignment folder on ELC. You do not need to submit code on ELC, just make sure your GitHub repository is up to date and contains the needed scripts.

2. Prepare for your in-person demonstration.

3. Submit your **P** deliverable (early power supply design) to the Progress Deliverables 7 assignment folder on ELC.

4. Update your User Manual and Technical Documentation with your findings.

5. Submit your Weekly Project Management Report to the Deliverable 7 assignment folder on ELC.
