# Filter Constrictions, Spring 2018 Team
#### Thomas Bradford, Jacqueline Dokko, Jonathan Harris
#### March 9, 2018

## Abstract

The Spring 2018 Filter Constrictions subteam has worked to improve the model of floc deposition at a flow constriction. Specifically, the model mimics clay-sand interactions at constrictions between a filter's sand particles. The current model is comprised of an acrylic flow cell using a wire as a flow constrictor. The Spring 2018 team aims to adjust this design by altering its internal components and its geometry; the team also plans to better control the system flow. After these changes to the model and schematic, the flow cell will more accurately represent floc behavior in AguaClara's stacked rapid sand filters.

## Introduction

The Filter Constrictions subteam aims to evaluate the theory that flocs passing through sand filters deposit preferentially at flow constrictions. According to this theory, due to a constriction’s convergent streamlines, particles passing near a pore’s edge progressively draw closer to this edge and deposit. As particles accumulate, shrinking the constriction, collision frequency increases. The velocity through the constriction then increases until the drag force on the deposited particles is sufficient to rotate them through the constriction.

To evaluate this theory, the Filter Constrictions subteam will develop a method to model and analyze floc accumulation at a sand filter’s constriction points. This research will be applied to better understand the filtration process in AguaClara’s water treatment plants.

The Fall 2017 subteam built a flow cell reactor comprised of two clear acrylic blocks that were separated by a specially shaped layer of silicone, creating a channel 0.5 mm deep. A 0.3 mm diameter wire restricted flow, resulting in a 0.2 mm vertical channel for particles to flow through. The camera recorded what occurred at this constriction. In order to record a higher quality video to analyze flow and deposition, the subteam used red dye instead of clay to create flocs.

The Spring 2018 subteam determined that the wire constriction was insufficient to accurately model constrictions in a sand filter. Since the camera recorded perpendicularly to the flow cell and the wire lay horizontally across said cell, the constriction was outside the camera’s plane of view. Also, the wire-constriction was two-dimensional; when flocs deposited, flocs were able to pass around them in a path dissimilar to that in a sand filter. The Spring 2018 subteam aims to alter the flow cell to contain more realistic constrictions, all visible to the camera. Since the filter’s sand grains are 0.6 mm in diameter, due to the geometry of large quantities of sand particles, each constriction should result from a channel, 0.5 mm in diameter and in depth, and a flow restriction of radius 0.3 mm. The subteam must determine the most effective and efficient way to implement these parameters.


## Literature Review and Previous Work

As the fluid passes through a pipe, minor head loss occurs when the flow encounters a sudden contraction. The change in flow area causes the streamlines to contract; the streamtube becomes smaller than the area it passed through right after the constriction. This causes the *vena contracta*: the place where the cross-sectional area of flow is at a minimum, as shown in Figure 1.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Hydraulic_vena_contracta_275px.png?raw=true"/>
</p>

**Figure 1**: Streamlines gradually converge before passing through a constriction. They converge until the *vena contracta*, after which they widen.


After the *vena contracta*, the stream tube expands to the fit the pipe [(Kanpur 2009)](). In sand filters, particles are more likely to be captured at these flow restrictions. As the streamlines converge at the restriction, the streamlines become denser. Space between the outermost streamline and the constriction wall decreases, increasing the chance that a floc will come in contact with the wall and be captured. Flocs build up at the constriction at an increasing rate of collisions between particles increase. This further decreases the flow area, as shown in Figure 2. As the flow area becomes smaller, the velocity of the water passing through the constriction reaches a point where it is great enough that the drag of particles colliding with the constriction is enough to prevent attachment and to push the particle through the smaller area [(Weber-Shirk 2017)](https://courses.cit.cornell.edu/cee4540/pdf/Flow%20Control%20and%20Measurement.pdf).

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/ConstrictionsSandGrains.png?raw=true" width="35%"/>
</p>

**Figure 2**: Flow area decreases as flocs collide and accumulate at the constriction.

The Fall 2016 Milli-Sedimentation Team found that when turbid water passed through nonaligned honeycomb structures, flocs deposited where flow was constricted between honeycombs. Both the Milli-Sedimentation team and the StaRS Filter team provided evidence to support the filter constrictions theory detailed in the introduction
[(Whiting et. al. 2016)](https://www.overleaf.com/8159891kkzwhhgszwtb#/28827379/). The theory was then tested using the precursor to the current flow cell model which used a singular wire constriction between two acrylic slabs, recorded with a camera. The recording showed flocs depositing at the constriction, though it was unclear at which portion of the constriction. These experiments also demonstrated that, after a large volume of flocs deposited on the constriction, there was a point at which the large floc deposition fell through as a unit [(Dokko et. al. 2017)](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/). This was hypothesized to be equivalent to the failure point seen in the StaRS filter [(Li et. al. 2017)](https://www.overleaf.com/6268224jmjfms#/21041070/).

## Methods

#### Experimental Apparatus

The apparatus' head loss ($\Delta H$) is manipulated to create the necessary flow rate ($Q$) through the flow cell. Previous semesters' Filter Constrictions subteams used various set heights within the laboratory, such as pipes near the ceiling. The Spring 2018 team designed and fabricated a vertically adjustable head loss arm using 80/20. This device allows more accurate control of the height of the T-connector at the top of the head loss tubing, as shown in Figure 3. The arm's most important component is a lever that allows easy vertical movement of the 80/20 beam, as shown in Figure 4. This enables more accurate control of the apparatus' head loss.

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/HeadlossAdjuster.jpg?raw=true" width="25%" />
</p>

**Figure 3**: Vertically adjustable head loss arm. The head loss tubing was attached to the top of the arm, as indicated by the red arrow.

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/AdjustablePart.jpg?raw=true" width="25%"/>
</p>

**Figure 4**: Lever that required a 3/4 turn to tighten the arm in place.

#### Schematic

The team created a new schematic, shown in Figure 5, to highlight the importance of the head loss tubing to the apparatus. The difference in the height ($\Delta H$) of the head loss tubing and the red waste line in lab dictate the flow rate through the flow cell due to the pressure differences both sides of the flow cell.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Copy%20of%20Schematic.jpg?raw=true" width="70%"/>
</p>

**Figure 5**: The schematic represents the flow apparatus as designed by the Fall 2017 subteam. The changes made highlight the importance of the head loss tubing at the ceiling and its relationship to the laboratory waste line. Adapted and modified from [Dokko et. al. 2017](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/).

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Apparatus.jpg?raw=true" width="50%"/>
</p>

**Figure 6**:  The flow apparatus, shown with labeled parts.

#### Flow Cell

To assemble the flow cell, the Spring 2018 subteam used the same two clear acrylic blocks as the Fall 2017 subteam. The silicon layer between the acrylic blocks was cut to constrict flow, as shown in Figure 7. Two rows along the bottom acrylic block, with five tightened screws each, guarantee that the cell is watertight, as depicted in Figures 8 and 9. The flow cell is mounted in the wooden mount as shown in Figure 9. An LED rests in the mount, behind the flow cell, to provide backlighting for high-quality video recordings.

<p align="center">
  <img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/BumpConstriction%20Design.png?raw=true" width="40%"/>
</p>

**Figure 7**: The new design of the flow cell models a single constriction column, so that the team can take videos showing where flocs settle on the constriction.

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/flowcellside.jpg?raw=true" width="40%" />

</p>

**Figure 8**: This silicone spacer is placed under pressure between two acrylic blocks, creating a watertight seal.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/newmount.png?raw=true" width="25%"/>
</p>

**Figure 9**: The flow cell contained in the previously created mount.

#### Complications in construction

As the team discussed methods to design a new constriction, the first idea was to add a row of sand in the current flow cell. The team considered gluing the sand inside the flow cell; however, the glue was opaque and prevented high-quality video recordings.  The team then decided to use sand grains slightly larger than the gap between the acrylic blocks, large enough to deform when pressed between the tightening blocks. As shown in Figure 10, this design was unsatisfactory for multiple reasons. The sand grains were misaligned, and large gaps arose between some grains. Water preferentially flowed between larger gaps, and the resulting flow patterns were dissimilar to those found in a sand filter.


<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/SandRowFlowCell2.jpg?raw=true" width = "50%"/>
</p>

**Figure 10**: The row of sand grains inserted at the constriction.

### Procedure
To observe the floc-sand interactions at a constriction, a flow cell was developed to model the microscale occurrence. The flow cell had clear acrylic walls to allow for video recordings of the constriction. Analysis of the footage allows evaluation of the hypothesis.

The system was set up in such a way that flocs would be developed in the flocculator preceding the flow cell; the floc behavior would then be recorded by a close-up camera set at the constriction of the flow cell. These experiments were run for durations up to an hour to observe the short term and long term events at the constriction.

In the past, the constriction was modeled through a 0.5 mm space created by a water-tight silicon spacer between the acrylic pieces where a 0.3 mm diameter wire created a 0.2 mm constriction between the acrylic walls of the cell. Though the flocs have historically been made of coagulant (PACl) and clay, the Filter Constrictions subteam recently chose to switch out the clay for red dye #40. This increased floc visibility, attributed to color contrast in the video footage.

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


<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Flowcellsketch.jpg?raw=true" width ="50%" />
</p>

**Figure  11**: The dimensions of the flow cell as designed by the Fall 2017 Filter Constrictions subteam [(Dokko et. al.)](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/).

The current design, corresponding to values in Table 1's first row, has a head loss value less than 1$cm$. The team cannot satisfactorily manipulate the 80/20 arm to produce this precise value, so the team must find an alternative design.

The subteam experimented with using a row of sand particles to act as constrictors; issues arose with keeping the sand in place. The sand also scratched the acrylic blocks. Determining that use of a row of sand particles was unideal, the team decided to use a design matching Table 1's second row of values. It will contain one flow constriction, a flow rate of 27.75 $\mu L/min$, and a microtubing length of 100 ft. The head loss of 4.026 $cm$ is the most feasible to implement.

## Conclusions
The multiple new models developed by the team brought up a few interesting details for the team to consider. The implementation of a single constriction model required the installment of a long headloss microtube to further discourage flow through the flow cell. The videos recorded showed how the previous flow cell velocity was much greater than the estimated actual velocity through a pore of 2mL/min. The accuracy of the flow velocity as well as the dimensions of the flow cell itself was shown to be vital to the results of the constriction observation. Also, it became apparent that the calculated velocity from the headloss tubing was potentially different from the velocity that was actually created in the flow cell by the apparatus. The team planned to address this discrepancy by measuring the actual flow in the flow cell and manipulating the headloss tubing until the proper velocity was accomplished. In order to avoid this same issue in the future, the team inputted an adjustable headloss tubing apparatus such that the height of the tubing could easily be adjusted. Once the team figures out the relation between the absolute height of the tubing and the flow cell velocity, the height can easily be adjusted in case the flow cell requires a higher velocity (i.e. modeling more than one constriction) than that used for the one constriction model. This would be applicable to the model which uses sand grains in a row since that would model approximately ten constrictions at once. The most accurate model would help the team understand the physics of the occurrences at the constrictions between each sand particle within the sand filter such that these can be optimized for maximum performance within the plant.

## Future Work

In order to optimize the flow cell velocity to that of fluid flowing through one constriction in a StaRS filter, the length of the headloss tubing must be increased. This will greatly increase headloss and allow for a decreased flow cell velocity through the model of the single constriction. The team believes that this can be accomplished by coiling a long microtube around a cylindrical base to decrease the need for an unrealistic height increase. The team must also calculate the proper length of this microtube in order to ensure that the flow velocity is accurate to that of the actual StaRS filter. The accuracy of the flow cell velocity to the calculated one can be tested using ImageJ particle tracking to measure the actual velocity in the flow cell. Alternatively, the outflow from the flow cell can be collected with respect to time to measure the velocity as well. After these are optimized, the team can determine which constriction works best as an accurate model of the flow in a sand filter.

Further, the team is looking to insert a needle valve as part of the apparatus. This would allow for a reduction in the minute pulsation observed in the flow cell. The flow accumulator was implemented in the earlier iterations of the system which seemed to decrease the major pulsation. However, considering the microscale environment of the constriction, diminishing all pulsation in the flow cell is of great importance. This step would have to come after the team figures out the details of the new constriction design.




## Bibliography
Logan, B. E., Hermanowicz, S. W., & Parker, A. S. (1987). A Fundamental Model for Trickling Filter Process Design. Journal (Water Pollution Control Federation), 59(12), 1029–1042.

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



```python
# To convert the document from markdown to pdf
pandoc FilterConstrictionsReport.md -o Filter-Constrictions_Research_Report.pdf
```
