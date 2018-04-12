# Filter Constrictions, Spring 2018 Team
#### Thomas Bradford, Jacqueline Dokko, Jonathan Harris
#### April 20, 2018

<div class="alert alert-block alert-danger">
Please do not delete my comments. On the next submission I will use them to see if the issues were addressed and then I will delete them. If you disagree with a comment, just add your own underneath it. Also in the future, denote which report I should grade since there are two similarly named reports.
</div>

## Abstract (first draft done)

The Spring 2018 Filter Constrictions subteam developed and tested an apparatus to mimic floc behavior at constrictions between a filter’s sand particles. The Fall 2017 team developed an apparatus including an acrylic flow cell that contained a wire to constrict flow. Spring 2018 members fabricated three alternative flow cells: the first contained two bent wires; the second contained sand to form multiple constrictions; the third contained a channel cut out of silicone. To better control the system’s flow, members added a needle valve and an adjustable metal arm to the apparatus. The subteam then recorded and analyzed videos of floc accumulation in the new apparatus.

<div class="alert alert-block alert-danger">
Change "has worked" to "is working" in the first sentence to match with the sentence "the team aims to adjust" - Consistent verbs

What information are you trying to get out of your model? Are you only making modifications to the set-up this semester or are you running experiments too?

Model is used in terms of a experimental model and also a theoretical model, consider only calling the theoretical model a model and the experimental model an experimental apparatus.
</div>

## Introduction (First Draft Done)

The Filter Constrictions subteam aimed to evaluate the theory that flocs passing through stacked rapid sand (StaRS) filters deposit preferentially at flow constrictions. According to the Cylindrical Annulus Geometry (CAG) Theory, due to a constriction’s convergent streamlines, particles passing near a pore’s edge progressively draw closer to this edge and deposit through the primary modes of sedimentation and deposition. As particles accumulate, shrinking the constriction, collision frequency increases. The velocity through the constriction increases until the drag force on the deposited particles rotates them through the constriction.

To evaluate the CAG theory, the Filter Constrictions subteam developed a method to model and analyze floc accumulation at a sand filter’s constriction points. This research will be applied to better understand the filtration process in AguaClara’s water treatment plants.

The Fall 2017 subteam built a flow cell comprised of two clear acrylic blocks separated by a layer of silicone. Members cut a rectangular channel out of this silicone layer. A wire lay across the channel, decreasing the area for particles to flow through, thus creating a constriction. The camera recorded what occurred at this single-wire constriction. In order to record a higher quality video to analyze flow and deposition, the subteam used red dye instead of clay to create flocs which allowed for better color contrast in the footages.

<div class="alert alert-block alert-danger">
Consider putting the numbers/details in the methods or manual sections.
</div>

The Spring 2018 subteam determined that this design was insufficient to model constrictions in a sand filter. Since the camera recorded perpendicularly to the flow cell and the wire lay across said cell, the constriction was outside the camera’s plane of view. Also, the constriction was only two-dimensional; when flocs deposited, other flocs could pass around them in a path dissimilar to that in a sand filter. The Spring 2018 subteam aimed to alter the flow cell to contain more realistic constrictions, all visible to the camera.

To determine the most efficient and effective method to model floc accumulation at a filter's constrictions, the subteam tested and captured videos of three new constriction designs: the two-wire constriction; the sand constriction; and the silicone constriction. Each design was named after the material constricting flow.

<div class="alert alert-block alert-danger">
Again consider moving specific numbers into methods section.

The meaning of the last two sentences is unclear.

Give overview of how you will determine the most effective and efficient way to implement these parameters.

Good description of theory.
</div>



## Literature Review and Previous Work (First Draft Done)

When fluid passes through a pipe and encounters a sudden contraction, minor head loss occurs. **The change in flow area causes the streamlines to converge; after passing through the constriction, the streamtube's cross-sectional area becomes smaller than that of the constriction itself.** This creates the vena contracta: the location where the streamtube's cross-sectional area is at a minimum, as shown in Figure 1. After the vena contracta, the streamtube expands **so its cross-sectional area equals that of the pipe** [(Kanpur 2009)]().

<div class="alert alert-block alert-danger">
The sentence "the streamtube becomes smaller than the area it passed through right after the constriction" is unclear.
</div>

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Hydraulic_vena_contracta_275px.png?raw=true"/>
</p>

**Figure 1**: Streamlines gradually converge before passing through a constriction. They converge until the vena contracta, after which they widen.

**According to the CAG theory?** When streamlines converge at the constriction, space decreases between the outermost streamline and the constriction's wall. This increases  the chance that a floc will come into contact with the constriction's wall and deposit. **Floc accumulation at the constriction further decreases the flow area through the constriction, as shown in Figure 2. Due to conservation of flow, as the streamtube's cross-sectional area decreases, the streamtube's velocity through the constriction increases; the rate of floc-collision then increases. The velocity  increases until the fluid's drag on flocs is enough to prevent deposition and to pull the flocs through the constriction** [(Weber-Shirk 2017)](https://courses.cit.cornell.edu/cee4540/pdf/Flow%20Control%20and%20Measurement.pdf).

<div class="alert alert-block alert-danger">
Do the flocs stick to the pipe walls or are they settling out? Saying that "a floc will come into contact with the wall and be captured" sounds like stickiness to me.

Some sentences don't make sense. Revise this paragraph

Why is vena contracta italicized?
</div>

<span style="color:green">
Jonathan - Captured and deposit are the words used in the StaRS Model paper and so we just wanted to be consistent with them and that is why we continued to use those words. However, I did add to the intro the two main processes of deposition in the filter (sedimentation and interception)
</span>

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/ConstrictionsSandGrains.png?raw=true" width="35%"/>
</p>

**Figure 2**: Flow area decreases as flocs collide and accumulate at the constriction.

Both the Milli-Sedimentation and the StaRS Filter Theory subteams provided evidence to support the CAG theory
[(Whiting et. al. 2016)](https://www.overleaf.com/8159891kkzwhhgszwtb#/28827379/) [(Chu et. al. 2016)](https://confluence.cornell.edu/display/AGUACLARA/StaRS+Filter+Theory?preview=/206635878/340897167/StaRSFilterTheoryReportFall2016.pdf). The Fall 2016 Milli-Sedimentation subteam found that when turbid water passed through nonaligned honeycomb structures, flocs deposited where flow was constricted between honeycombs. **The Spring 2016 StaRS Filter Theory subteam conducted experiments on a clogged filter running at different flow rates to find the head loss through the apparatus; the subteam found that the head loss through the filter had a quadratic relationship with __. This suggested that minor losses were present in the clogged filter, and minor losses suggest the presence of constrictions.**  

The CAG was theory was also tested **(By Fall 2017 Filter Constrictions subteam?)** on the Fall 2017 Filter Constrictions subteam's single-wire constriction flow cell. Camera recordings showed flocs depositing at the constriction, though it was unclear at which portion **(whether _ or _ )**. These experiments also demonstrated that, after a sufficiently large volume of flocs deposited on the constriction, the accumulated flocs fell through the constriction as a unit [(Dokko et. al. 2017)](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/). This was hypothesized **by?** to be equivalent to a StaRS filter's failure point [(Li et. al. 2017)](https://www.overleaf.com/6268224jmjfms#/21041070/).

<div class="alert alert-block alert-danger">
Is there a name for the filter constrictions theory detailed in the intro so that referring to it is easier?

Define StaRS acronym
</div>

## Methods
<span style="color:green">
{The Fall 2017 subteam built a flow cell reactor comprised of two clear acrylic blocks that were separated by a specially shaped layer of silicone, creating a channel **[0.5 mm deep]**. A **[0.3 mm diameter]** wire restricted flow, resulting in a **[0.2 mm]** vertical channel for particles to flow through. The camera recorded what occurred at this constriction. In order to record a higher quality video to analyze flow and deposition, the subteam used red dye instead of clay to create flocs.}


{{Since the filter’s sand grains are 0.6 mm in diameter:} due to the geometry of large quantities of sand particles, each constriction should result from a channel **[0.5 mm in diameter and in depth]** and a flow restriction **[of radius 0.3 mm]**. The subteam must determine the most effective and efficient way to implement these parameters.}
</span>
To observe the floc-sand interactions at a constriction, a flow cell was developed to model the microscale occurrence. The flow cell had clear acrylic walls to allow for video recordings of the constriction. Analysis of the footage allows evaluation of the hypothesis.

The system was set up in such a way that flocs would be developed in the flocculator preceding the flow cell; the floc behavior would then be recorded by a close-up camera set at the constriction of the flow cell. These experiments were run for durations up to an hour to observe the short term and long term events at the constriction.

In the past, the constriction was modeled through a 0.5 mm space created by a water-tight silicon spacer between the acrylic pieces where a 0.3 mm diameter wire created a 0.2 mm constriction between the acrylic walls of the cell. Though the flocs have historically been made of coagulant (PACl) and clay, the Filter Constrictions subteam recently chose to switch out the clay for red dye #40. This increased floc visibility, attributed to color contrast in the video footage.
#### Experimental Apparatus Schematic

This semester's team made changes to the system, shown in the system schematic of Figure 3. The system was developed to recreated the portion of the filtration plant where the water is filtered by layers of sand known as the Stacked Rapid Sand Filter (StaRS). As shown in the figure, the actual system apparatus allowed water to flow from the inlet, create flocs with the addition of dye and coagulant (known as polyaluminum chloride - PACl), enter the flow cell and deposit into the waste line. Tap water flowed in from the inlet line which was controlled by the first peristaltic pump. The water then entered the flow accumulator which inhibited the pulsations previously observed in the flow cell later down the line. Coagulant and dye were added by peristaltic pumps and this mixture entered the flocculator of which the G-Theta value had been calculated to create flocs of the desired size. The dye was meant to mimic the dirt particles often found in the dirty water coming into the plant. Then the flocs entered a branched tubing system where most of the water was directed away from the flow cell to prevent high velocities in the flow cell which had a very small volume capacity. Then, the water from both the flow cell and the branched segment were pushed into the waste line. Videos and images of the flow cell were taken with a FlyCap camera which was mounted right next to the flow cell.

 The new schematic highlights the importance of the head loss tubing to the apparatus.  The difference in the height ($\Delta H$) of the head loss tubing and the red waste line in lab dictated the flow rate through the flow cell due to the pressure differences both sides of the flow cell.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Copy%20of%20Schematic.jpg?raw=true" width="70%"/>
</p>

**Figure 3**: The schematic represents the flow apparatus as designed by the Fall 2017 subteam. The changes made highlight the importance of the head loss tubing at the ceiling and its relationship to the laboratory waste line. Adapted and modified from [Dokko et. al. 2017](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/).

Figure 4 shows an image of the actual apparatus used in the laboratory. It followed the exact same flow steps outlined in the schematic of Figure 3.

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Apparatus.jpg?raw=true" width="50%"/>
</p>

**Figure 4**:  The flow apparatus, shown with labeled parts.

<div class="alert alert-block alert-danger">
Describe what else is in the scematic, walk us through the different parts and their importance? What tools do you use for data collections?

Figures are good references but they cannot stand by themselves.
</div>


The apparatus' head loss ($\Delta H$) was manipulated to create the necessary flow rate ($Q$) through the flow cell for different flow cell designs. Head loss was the main driver for the pressure difference on either side of the flow cell which is the direct cause of water flow through the cell. Thus, the ability to control this was crucial in obtaining proper flow velocities in the cell to mimic those seen in the StaRS filters. Previous semesters' Filter Constrictions subteams used various set heights within the laboratory, such as pipes near the ceiling. The Spring 2018 team designed and fabricated a vertically adjustable head loss arm using 80/20. 80/20 is a metal rod with grooves which allow for the easy construction of stable support systems such as the aforementioned head loss arm. This device allowed for more accurate control of the height of the T-connector at the top of the head loss tubing, as shown in Figure 5. The arm's most important component was a lever that allowed easy vertical movement of the 80/20 beam, as shown in Figure 6. This enabled more accurate control of the apparatus' head loss.

<div class="alert alert-block alert-danger">
Did not give background on what the experimental apparatus actually is. Without that, the headloss part does not make sense.

Also why is head loss important?

Describe 80/20
</div>

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/HeadlossAdjuster.jpg?raw=true" width="25%" />
</p>

**Figure 5**: Vertically adjustable head loss arm. The head loss tubing was attached to the top of the arm, as indicated by the red arrow.

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/AdjustablePart.jpg?raw=true" width="25%"/>
</p>

**Figure 6**: Lever that required a 3/4 turn to tighten the arm in place.


#### Flow Cell

The flow cell was developed as a means to observe the minute mechanisms under which the StaRS filters operate. Scaled models or replicates of each constriction in the filter were recreated within the flow cell using various materials and techniques mentioned in the introduction. One example is the single constriction model shown in Figure 7 which only uses silicone. Other models utilized sand particles or wires to model constrictions. Clear material was necessary as sthe outer shell in order to be able to observe and record the filtration model set up inside. Silicone was used as the water-tight borders of the model inside to contain the water and uphold the filtration set-up as shown in Figure 8.

To assemble the flow cell, the Spring 2018 subteam used the same two clear acrylic blocks as the Fall 2017 subteam. The silicon layer between the acrylic blocks was cut to constrict flow, as shown in Figure 7.

<p align="center">
  <img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/BumpConstriction%20Design.png?raw=true" width="40%"/>
</p>

**Figure 7**: The new design of the flow cell models a single constriction column, so that the team can take videos showing where flocs settle on the constriction.

 Two rows along the bottom acrylic block, with five tightened screws each, guaranteed that the cell was watertight, as depicted in Figures 8 and 9.

 <p align="center">
 <img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/flowcellside.jpg?raw=true" width="40%" />

 </p>

 **Figure 8**: This silicone spacer was placed under pressure between two acrylic blocks, which created a watertight seal.

 The flow cell was mounted in the wooden mount as shown in Figure 9. An LED rested in the mount, behind the flow cell, to provide backlighting for high-quality video recordings. The two thin tubes seen coming out of the backside of the mount are the two microtubings that served as the inlet and outlet of the flow cell. The cell was always mounted such that the outlet would be on the bottom to mimic the gravitationally powered movement of flocs downward see in the actual StaRS filter. The inlet was connected to the branched hard-tubing segment and the outlet was connected to the headloss tubing as shown in Figure 4.




<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/newmount.png?raw=true" width="25%"/>
</p>

**Figure 9**: The flow cell contained in the previously created mount.

<div class="alert alert-block alert-danger">
Good figures but not enough description of what they are.

I don't understand how water is flowing through the system.
</div>

#### Flow Cell Iterations

As the team discussed methods to design a new constriction, the first idea was to add a row of sand in the current flow cell. The team considered gluing the sand inside the flow cell; however, the glue was opaque and prevented high-quality video recordings.  The team then decided to use sand grains slightly larger than the gap between the acrylic blocks, large enough to deform when pressed between the tightening blocks. As shown in Figure 10, this design was unsatisfactory for multiple reasons. The sand grains were misaligned, and large gaps arose between some grains. Water preferentially flowed between larger gaps, and the resulting flow patterns were dissimilar to those found in a sand filter.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/SandRowFlowCell2.jpg?raw=true" width = "50%"/>
</p>

**Figure 10**: The row of sand grains inserted at the constriction.

This model inspired the next iteration of the flow cell which was the single-constriction model shown in Figure 7. The single constriction constructed out of silicone was meant to prevent inconsistencies in sand and thus constriction positioning for each experiment by consistently using and testing only a single constriction rather than the multiple seen in the sand model.

<div class="alert alert-block alert-danger">
This section has great content, but is it technically a construction complication? It seems more like a design process.

As an aside, this methods section is a little scattered and might benefit from reorganizing the sections.
</div>



### Procedure
Using the apparatus, flocs were created and run through the flow cell to observe how they behaved in constrictions of StaRS filters. The system would initially be run with just water to push out any air bubbles. Once the system was equilibrated as such, the dye and PACl would begin to be pumped in. As soon as the first floc was seen approaching the flow cell through the flow cell's inlet tubing, the camera was started in order to obtain recordings of the floc behavior at the constriction. Often, the camera would be configured and focused before this in order to be prepared to begin recording at any moment. Once the constriction was clogged, the video would be stopped and the dye and PACl pump would be halted. Water would be allowed to continue running through the system to flush out the remaining flocs before the next recording. The flow cell would be cleaned out and repositioned on the mount to prepare for the next recording. Cleaning was alleviated by the use of the adjustable metal arm to greatly decrease the headloss. Once the arm was dropped to its lowest height, the water owuld flow at very high velocities to enact a rapid cleaning velocity in the flow cell. The arm was placed again in its normal height after the cleaning step.

The system was flushed with bleach every few weeks to prevent bacterial growth within the system.

Further details of the procedure are outlined in the Manual section of this report.

<div class="alert alert-block alert-danger">
This Procedure Section does not actually have a procedure, which would be a set of steps on how to run the experiment. This is a description of your apparatus and should be moved there. In the Procedure Section, provide the How-to on how to run your experiment and how you collected data.
</div>

## Results and Analysis

The head loss equation was used to calculate the arm's appropriate height. $Q$ was calculated to be 27.75 $\mu L / min$, and the diameter $D$ of the microtubing was found to be 0.042 $in$. The length ($L$) of the microtubing is currently 275 $cm$, and the calculated flow rate through one constriction is 27.75 $\mu L / min$. The flow rate through a row of sand particles was calculated to be 555 $\mu L/min$, using the previous team's flow cell measurements, as shown in Figure 11. The length of microtubing contained in one roll is 100 $ft$.

Given these two lengths of microtubing and two flow values, the subteam calculated the head losses corresponding to each possible combination of tubing length and flow rate. The results are shown Table 1.  The following equation was used to calculate the apparatus' head loss:

$$\Delta H = \frac{128L}{\rho g\pi} \frac{\mu Q}{D^4}$$

**Table 1**: The apparatus' calculated head loss at various flow rates and lengths of microtubing.

| Length of tube ($L$) | Flow Rate $\mu L/min$ | Head loss $\Delta H$ (cm) |
|:--------------------:|:-------------------:|:-------------------------:|
|        275cm         |        27.75        |           0.363           |
|         100'         |        27.75        |           4.026           |
|        275cm         |         555         |           7.262           |
|         100'         |         555         |          80.492           |

<div class="alert alert-block alert-danger">
It seems like since you are doing a lot of design, maybe there should be a Design section where these equations should go? If not a design section, then these should be in the methods and manual sections
</div>

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Flowcellsketch.jpg?raw=true" width ="50%" />
</p>

**Figure  11**: The dimensions of the flow cell as designed by the Fall 2017 Filter Constrictions subteam [(Dokko et. al.)](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/).

The current design, corresponding to values in Table 1's first row, has a head loss value less than 1$cm$. The team cannot satisfactorily manipulate the 80/20 arm to produce this precise value, so the team must find an alternative design.

The subteam experimented with using a row of sand particles to act as constrictors; issues arose with keeping the sand in place. The sand also scratched the acrylic blocks. Determining that use of a row of sand particles was unideal, the team decided to use a design matching Table 1's second row of values. It will contain one flow constriction, a flow rate of 27.75 $\mu L/min$, and a microtubing length of 100 ft. The head loss of 4.026 $cm$ is the most feasible to implement.

<div class="alert alert-block alert-danger">
Good analysis of these results.

Results & Analysis is really light right now, and I understand that this is only half way through the semester so there isn't much, but for the next report, add in more analysis of whatever results/design parameters you get.
</div>

## Conclusions
The multiple new models developed by the team brought up a few interesting details for the team to consider. The implementation of a single constriction model required the installment of a long headloss microtube to further discourage flow through the flow cell. The videos recorded showed how the previous flow cell velocity was much greater than the estimated actual velocity through a pore of 2mL/min. The accuracy of the flow velocity as well as the dimensions of the flow cell itself was shown to be vital to the results of the constriction observation. Also, it became apparent that the calculated velocity from the headloss tubing was potentially different from the velocity that was actually created in the flow cell by the apparatus. The team planned to address this discrepancy by measuring the actual flow in the flow cell and manipulating the headloss tubing until the proper velocity was accomplished. In order to avoid this same issue in the future, the team inputted an adjustable headloss tubing apparatus such that the height of the tubing could easily be adjusted. Once the team figures out the relation between the absolute height of the tubing and the flow cell velocity, the height can easily be adjusted in case the flow cell requires a higher velocity (i.e. modeling more than one constriction) than that used for the one constriction model. This would be applicable to the model which uses sand grains in a row since that would model approximately ten constrictions at once. The most accurate model would help the team understand the physics of the occurrences at the constrictions between each sand particle within the sand filter such that these can be optimized for maximum performance within the plant.

<div class="alert alert-block alert-danger">
What videos are you referrig to? You don't talk about collecting any data, only designing changes to your system. You also do not discuss velocity differences.

Additionally, this is the first time you reference "sand grains in a row"

These conclusions don't match up to what you spoke about in your methods/results/analysis portions.

It is also one long paragraph
</div>

## Future Work

In order to optimize the flow cell velocity to that of fluid flowing through one constriction in a StaRS filter, the length of the headloss tubing must be increased. This will greatly increase headloss and allow for a decreased flow cell velocity through the model of the single constriction. The team believes that this can be accomplished by coiling a long microtube around a cylindrical base to decrease the need for an unrealistic height increase. The team must also calculate the proper length of this microtube in order to ensure that the flow velocity is accurate to that of the actual StaRS filter. The accuracy of the flow cell velocity to the calculated one can be tested using ImageJ particle tracking to measure the actual velocity in the flow cell. Alternatively, the outflow from the flow cell can be collected with respect to time to measure the velocity as well. After these are optimized, the team can determine which constriction works best as an accurate model of the flow in a sand filter.

Further, the team is looking to insert a needle valve as part of the apparatus. This would allow for a reduction in the minute pulsation observed in the flow cell. The flow accumulator was implemented in the earlier iterations of the system which seemed to decrease the major pulsation. However, considering the microscale environment of the constriction, diminishing all pulsation in the flow cell is of great importance. This step would have to come after the team figures out the details of the new constriction design.

<div class="alert alert-block alert-danger">
These are gret coherent next steps, but again I don't understand where they are coming from because they weren't mentioned in your results/analysis.I am not sure what the minute pulsation is or the flow accumulator.

In general, you should not be introducing new concepts in the future work or conclusion areas.
</div>


## Bibliography
Logan, B. E., Hermanowicz, S. W., & Parker, A. S. (1987). A Fundamental Model for Trickling Filter Process Design. Journal (Water Pollution Control Federation), 59(12), 1029–1042.

<div class="alert alert-block alert-danger">
Where is the rest of this bibliography? You have at least two or three more sources in your lit review/previous work.
</div>

# Manual
This manual lays out the details of the material and methods used for the aforementioned experiments.

## Fabrication Details
### Flow Cell
* Two 6" x 2.75" clear acrylic sheets
* 1/32" silicone sheet
* 0.3mm diameter wire
* Ten screws
* Ten wingnuts
* Sand


### Model flocculator
* 3.5" diameter cylindrical cardboard tube
* 11.45m long flexible tubing with 1/4" Diameter
* Tape
* Push-to-connects with barbed connections

### Systemic Apparatus
* Two peristaltic pumps
* Model flocculator (described above)
* Four 1L Nalgene bottles
* FlyCapture camera with software
* LED light
* 1/4" hard tubing
* Microtubing
* Polyaluminum Chloride (PACl) coagulant
* Red #40 dye

<div class="alert alert-block alert-danger">
These lists are fantastic.
</div>

## Experimental Methods
### Set-up
1. Turn the valves of the inlet (Blue) and outlet (Red) hoses to the open positions (vertical handle).
  * If the dye and/or coagulant bottles are not connected to the system, replace the water bottles with the correct chemicals. See tube labeling to ensure proper correspondence of microtubing to the chemical.
2. Turn on the pumps and make sure that both the water pump and coagulant/dye pumps are running in the clockwise direction.
3. Ensure both pumps are on "INT" mode.
4. Set the water pump to 38.9 rpm and the dye/coagulant pump to 20 rpm.
5. Set up the camera and connect it to the computer. If it does not show up, click Force IP.

 Setting up the camera
 * Unscrew the caps from both ends of the camera and the camera holding device connected to the computer.
 * Screw the camera onto the holding device
 * Attention: It is very important that no fingerprints are left on any of the lenses of the camera to ensure no disruption in the footage


### Experiment
1. Check that the flow cell is cleared of any old flocs, free of air bubbles and properly set up in its mount with the outlet side down.
2. Turn on both of the pumps.
3. Let the pumps run until flocs begin to form.
4. Keeping the pumps running, start recording a video using the Point Grey FlyCap Software.

### Running FlyCap Software
1. Open the Point Grey FlyCap software.
2. Make sure that the camera is connected to the computer and shows up as the recording device on the screen.
3. Zoom in or out of the footage screen to adjust to the full capacity of the video dimensions.
4. Click record.
5. When the new window opens up check that the file path is directed to the proper folder location.
6. Change the "Image" tab to the "Video" tab and select "MPEG" from the drop-down menu.
7. Click the button on the file type and it should automatically select the appropriate values for the file type.
8. Click "Start Recording" at the bottom of the window.
  * Check that the number of "Corrupted Images" remains low and the number of "Saved Images" increases accordingly.
  * Do not record for too long as the video may not save properly if it is too large.

### Cleaning Procedure
1. Obtain a bucket and fill it with clean, cold water. Place it on a stand to put it at the height of the flow cell mount.
  * Cold water is necessary to minimize dissolved oxygen levels. This will prevent air bubble formation in the flow cell later.
2. Turn the valves of the inlet (Blue) and outlet (Red) hoses to the open positions (vertical handle).
3. Turn on just the water pump to flush out the system of chemicals.
4. Submerge the flow cell in the bucket of cold water and open the flow cell by unscrewing all ten screws.
5. Clean the flow cell using glass cleaner and paper towels.
6. While maintaining the flow cell underwater, reassemble the flow cell with proper silicon and wire orientation. Screw all 10 screws tightly.
    - Check that neither the outlet or inlet holes are covered by the silicone piece. The silicone piece can slide around during this step.
    - Some screws may not slide in easily due to alignment. Loosely attach all ten screw, then tighten for better alignment. Use Philips screwdriver.
7. If air bubbles are trapped, tap the sides of the flow cell with the outlet facing up to allow bubbles to exit upwards. DO NOT tap the face as it may damage the surface and decrease visibility in the footage.
8. Turn off pumps if no experiments are to follow immediately after cleaning. If experiments are to follow immediately, switch the dye and coagulant pump on and begin the experiment.

<div class="alert alert-block alert-danger">
This section is really great.

A point of clarification for what I said in the methods section: the procedure in the methods section should be the general form of this. For example you wouldn't go through every step, but you would explain the important steps, things to look for, goals (floc formation, video captures.) and then reference your manual!
</div>

## Experimental Checklist
* Check that the coagulant and dye are plugged into their proper pump tubings.
* Check that the flow cell is cleaned and free of air bubbles.
* Check that both the inlet and outlet valves are open.
* Check that the flow cell inlet and outlet are not covered by the silicone sheet.
* Check that the headloss adjustment is at the proper height.


## ProCoDA Method File
ProCoDA has not been used for this apparatus.

## Python Code

### Variables
$p$: pressure \
$\rho$: density of the fluid (water)\
$g$: gravity \
$h$: head loss \
$L$: length of tubing \
$\mu$: dynamic viscosity of the fluid (water) \
$Q$: flow rate\
$D$: Diameter of tube \

The equations for pressure:
$$\Delta p = \rho g \Delta h $$
$$\Delta p = \frac{128L}{\pi} \frac{\mu Q}{D^4}$$
**To calculate head loss**:
$$\Delta h = \frac{128L}{\rho g\pi} \frac{\mu Q}{D^4}$$

First, if we were to model one constriction with the average velocity through the pores of the filter column.

```python
from aide_design.play import *
import math as m
from scipy import constants
V_filter = 1.85*u.mm/u.s
A_filter = (0.5*u.mm)**2
Q_filter = V_filter*A_filter
Q_filter.to(u.ul/u.min)

L = 275*u.cm
g = constants.g*u.m/(u.s)**2
rho = 1*u.g/(u.cm)**3
mu = 8.90*(10**(-4))*u.Pa *u.s
D =  0.042*u.inch
deltah = (128*L*mu*Q_filter)/(rho*g*m.pi*D**4)
deltah.to(u.cm)

```

<div class="alert alert-block alert-danger">
Where does the V_filter and A_filter come from? Be explicit.
</div>

With the current set up, the team calculates 0.36 cm of head loss. This is too small to be able to adjust with the height of the waste tube, and therefore the team must find another solution. The first possible solution is to use a row of sand grains and then model the constriction through multiple pores. This allows us to increase the flow rate through the flow cell and thus have a higher, more manageable head ($\Delta H$).

```python
V_sand = 1.85*u.mm/u.s
A_sand = 0.5*u.mm * 10*u.mm
Q_sand = V_sand*A_sand
Q_sand.to(u.ul/u.min)
deltah_sand = (128*L*mu*Q_sand)/(rho*g*m.pi*D**4)
deltah_sand.to(u.cm)
```
With these changes, $\Delta H$ is 7.26 cm, which is more manageable, but still very small. Since the waste line in the lab is coiled, there is a chance that air in the line can increase the head loss in the line, and therefore can complicate the design. Therefore, if after running experiments, we find that the flow rate is too slow, we will increase the length of the microtubing used to increase $\Delta H$. The team would use a 100 ft long roll of microtubing.

```python
# If we use an entire roll of micro tubing
L2 = 100*u.feet
deltah2 = (128*L2*mu*Q_sand)/(rho*g*m.pi*D**4)
deltah2.to(u.cm)
```
The team calculated the $\Delta H$ to be 80 centimeters.

<div class="alert alert-block alert-danger">
What is Delta H in this case? A maximum if you used the whole roll of tubing? Is that even possible with the cieling height?

This section is significantly clearer than how it was described in the report methods section and should be a model for the rest of the report! shows great technical writing and strong comprehension of the material!
</div>

```python
# To convert the document from markdown to pdf
pandoc FilterConstrictions-Report1.md -o Filter-Constrictions_Research_Report1.pdf
```
