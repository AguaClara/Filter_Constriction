# Filter Constrictions, Spring 2018 Team
#### Thomas Bradford, Jacqueline Dokko, Jonathan Harris
#### May 18, 2018

## Abstract

The Spring 2018 Filter Constrictions subteam developed and tested an apparatus to mimic floc behavior at constrictions between a filter's sand grains. The Spring 2017 team had developed an apparatus including a flow cell that contained a wire to constrict flow. Spring 2018 members fabricated two alternative kinds of flow cells: one contained sand to form multiple constrictions, and another contained a single channel cut from silicone. To better control the system’s flow, members added a needle valve and an adjustable metal arm to the apparatus. The subteam recorded and analyzed videos of floc accumulation in the new apparatus to discern any patterns. Understanding floc behavior at constrictions would facilitate more thorough understanding of AguaClara's sand filters. With more thorough understanding comes the ability to design more efficient filters.


## Introduction

The Filter Constrictions subteam aimed to evaluate the hypothesis that flocs deposit preferentially at the edges of flow constrictions as they flow through stacked rapid sand (StaRS) filters. According to the StaRS Filter Theory subteam's Cylindrical Annulus Geometry (CAG) Theory, flocs passing near a constriction's edge progressively draw closer to this edge and deposit through sedimentation and interception [(Li et al. 2018)](https://www.overleaf.com/read/cwqydwgftkmn). To evaluate the CAG theory and to better understand the filtration process in AguaClara's water treatment plants, the Filter Constrictions subteam developed a method to model and analyze floc accumulation at a sand filter’s constrictions. Through developing and analyzing a useful model of floc accumulation, the Filter Constrictions subteam will be able to understand the mechanisms of floc deposition better, and therefore understand how to optimize filter efficiency.


The Spring 2017 subteam had built a flow cell comprised of two clear acrylic blocks separated by a layer of silicone (aka. the "silicone spacer"). Members cut out a portion of the silicone, resulting in a rectangular channel. A wire lay across the channel, decreasing the area for flocs to flow through and creating a constriction. Water containing flocs was pumped through the flow cell, entering via an inlet tube, flowing through the cell, passing through the constriction, and exiting via an outlet tube. A camera recorded what occurred at this single-wire constriction.  To better distinguish flocs in the camera footage, the subteam generated flocs from red dye instead of clay. This flow-cell design is illustrated in Figures 1 and 2.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/final_flow_cell_diagram.jpg?raw=true" width="70%"/>
</p>

**Figure 1**: The above image is a labeled diagram (not to scale) of a bird's eye view of the flow cell design, comprised of a constriction within a water-tight silicone spacer, pressed between two acrylic blocks. As clarified in Figure 2, a second acrylic block lies in the plane of the page between the reader and the silicone spacer. The inlet and outlet tubes extend out of the page as well. In the case of the Spring 2017 flow cell, the constriction was a metal wire.


<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/fixed_horizontal_cross_section.jpg?raw=true" width="70%"/>
</p>

**Figure 2**: The above image is a labeled diagram (not to scale) of the horizontal cross-section of the flow cell design, as viewed perpendicularly to the channel (water flows across the plane of the page).

The Spring 2018 subteam determined that this design was insufficient to model a sand filter's constrictions. Since the camera recorded perpendicularly to the flow cell and the wire lay across said cell, the constriction was outside the camera’s plane of view. Also, the constriction was only two-dimensional. While some flocs deposited, other flocs passed around them in a path dissimilar to that in a sand filter. The Spring 2018 subteam aimed to alter the flow cell to contain more realistic constrictions, all visible to a camera.

To determine the most effective method to model floc accumulation, the subteam captured videos of flocs passing through two new constriction designs: a sand constriction, and a silicone constriction. These designs are explained in further detail in the Methods section.



## Literature Review and Previous Work

When fluid passes through a channel and encounters a sudden constriction, minor head loss occurs. The change in flow area causes the fluid's streamlines to converge. As a result, after passing through the constriction, the streamtube's cross-sectional area becomes even smaller than that of the constriction itself. This creates the vena contracta: the location where the streamtube's cross-sectional area is at a minimum, as shown in Figure 3. After the vena contracta, the streamtube expands, so its cross-sectional area equals that of the channel [(Kanpur 2009)]().

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Hydraulic_vena_contracta_275px.png?raw=true"/>
</p>

**Figure 3**: Streamlines gradually converge before passing through a constriction. They converge until the vena contracta, after which they widen.

While streamlines converge at the constriction, space decreases between the outermost streamline and the constriction's wall. This increases the chance that a floc collides with the constriction's wall and deposits. Floc accumulation at the constriction further decreases the cross-sectional area through the constriction, as shown in Figure 4. Due to flow continuity, as the flow's cross-sectional area decreases, the flow's velocity through the constriction increases. The rate of floc-collision accordingly increases. The flow's velocity increases until the fluid's drag on flocs are enough to prevent deposition and pulls the flocs through the constriction [(Weber-Shirk 2017)](https://courses.cit.cornell.edu/cee4540/pdf/Filtration.pdf). To evaluate the CAG theory, the Filter Constrictions subteam must determine where on a constriction such floc deposition occurs.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/ConstrictionsSandGrains.png?raw=true" width="35%"/>
</p>

**Figure 4**: Flow area decreases as flocs collide and accumulate at a constriction.

The Fall 2016 Milli-Sedimentation and Spring 2016 StaRS Filter Theory subteams provided evidence to support the CAG theory. The Milli-Sedimentation subteam found that when turbid water passed through nonaligned honeycomb structures, flocs deposited where flow was constricted between honeycombs [(Whiting et al. 2016)](https://www.overleaf.com/8159891kkzwhhgszwtb#/28827379/). This demonstrated that flocs deposited preferentially at constrictions. The StaRS Filter Theory subteam conducted experiments on a clogged filter running at different flow rates to find the head loss through the filter. The subteam found that the head loss had a quadratic relationship with the flow rate. This suggested that minor losses were present in the clogged filter, and thus confirmed the presence of constrictions in the sand filter [(Chu et al. 2016)](https://confluence.cornell.edu/display/AGUACLARA/StaRS+Filter+Theory?preview=/206635878/340897167/StaRSFilterTheoryReportFall2016.pdf).

The Fall 2017 Filter Constrictions subteam tested the CAG theory on a single-wire constriction flow cell. Camera footage showed floc deposition at the constriction. Although flocs deposited along the wire, it was unclear where on the wire's circumference they deposited. Figure 5 illustrates this. Also, after a sufficiently large volume of flocs deposited on the constriction, the accumulated flocs fell through the constriction as a unit [(Dokko et al. 2017)](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/). Members hypothesized this behavior to be equivalent to a StaRS filter's failure point [(Li et al. 2017)](https://www.overleaf.com/6268224jmjfms#/21041070/).

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Cross-Section_wire_final.jpg?raw=true" width="60%"/>
</p>

**Figure 5**: The above image is a labeled diagram (not to scale) of the partial horizontal cross-section of the flow cell as developed by the Spring 2017 subteam. Red arrows indicate the different locations that flocs may have deposited on the wire. Other flow cell components, such as the silicone spacer and tubes, are not depicted.


To further evaluate the CAG theory, the Spring 2018 team aimed to construct and test new constriction designs.

## Methods

The Spring 2017 subteam developed an apparatus to model floc behavior at a sand filter's constrictions. Flocs, developed in a flocculator, were pumped through a flow cell with clear, acrylic walls. A camera recorded their behavior at a constriction in the flow cell. Such tests ran for durations up to an hour to observe short-term and long-term patterns, and ultimately to evaluate the CAG theory.

The original flow cell's constriction was comprised of a 0.5 mm space created by a water-tight silicon spacer between two acrylic walls, across which a 0.3 mm diameter wire lay and created a 0.2 mm constriction between the flow cell's walls. Though the flocs were historically made of coagulant (a.k.a. polyaluminum chloride, PACl) and clay, the 2017 Filter Constrictions subteam exchanged clay for red dye #40. This increased floc visibility, attributed to color contrast in the camera footage. This flow cell design is illustrated in Figures 1, 2, and 10.


#### Experimental Apparatus
The Spring 2018 subteam altered Fall 2017's system, highlighted below in the Figure 6 schematic. The system was developed to recreate the portion of an AguaClara treatment plant in which layers of sand filter water in a StaRS filter. As shown in Figure 6, the system apparatus allowed water to flow from an inlet, carry input of flocs, enter the flow cell, and exit through a waste line.

Specifically, tap water entered the system from the inlet line, which was controlled by a peristaltic pump. The water then passed through a flow accumulator and needle valve, which inhibited pulsations caused by the peristaltic pump. An additional peristaltic pump input coagulant and dye into the water. The dye mimicked dirt particles found in water entering AguaClara plants. The mixture of water, dye, and coagulant flowed into the flocculator, the length of which had been calculated to generate flocs of the desired size through the collision of dye and coagulant particles. The resulting mixture, now containing flocs, entered a branched tubing system that directed most flow away from the flow cell and into the waste line. This prevented overly high fluid velocities in the flow cell. After the remaining mixture passed through the flow cell, the flow cell's effluent traveled up the tubing to the height of a vertically adjustable metal arm, to which the apex of the effluent tubing was attached. Effluent then drained into a waste container. Videos and images of the flow cell's constriction were taken with a FlyCap camera mounted next to the flow cell.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Sp18_Schematic_w_needlevalve.png?raw=true" width="90%"/>
</p>

**Figure 6**: This schematic represents the flow apparatus as designed by the Spring 2017 subteam and modified by the Spring 2018 subteam. Adapted and modified from [Dokko et al. 2017](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/).


<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Apparatus.jpg?raw=true" width="50%"/>
</p>

**Figure 7**:  The above image is a photograph of the Filter Constriction subteam's flow apparatus in the laboratory, with digitally added labels.

Figure 6 highlights the importance of the effluent, "head loss" tubing. Head loss ($\Delta H$) was the primary driver for the pressure gradient across the flow cell, which in turn caused influent to flow through the flow cell. The difference in height ($\Delta H$) between the head loss tubing and the laboratory's waste line was proportional to this head loss and therefore caused a pressure gradient across the flow cell, determining flocs' flow rate ($Q$). This height difference was manipulated with a vertically adjustable metal arm to create the necessary flow rates through different flow cell designs.

The ability to control this height difference was crucial in obtaining proper flow velocities that mimicked those in StaRS filters. Previous semesters' Filter Constrictions subteams used various set heights within the laboratory, such as pipes near the ceiling. The Spring 2018 team designed and fabricated a vertically adjustable "head loss arm" using 80/20, an aluminum-rod framing system. The metal arm allowed for subteam members to control the height of the head loss tubing's apex, as shown in Figure 8. The metal arm's most important component was a lever that allowed easy vertical movement of the 80/20 beam, as shown in Figure 9. This enabled control of the flow rate across the flow cell.

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/HeadlossAdjuster.jpg?raw=true" width="25%" />
</p>

**Figure 8**: The above image is a photograph of the vertically adjustable metal arm, fabricated with 80/20. The apex of the head loss tubing was attached to the top of the arm, as indicated by the red arrow.

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/AdjustablePart.jpg?raw=true" width="25%"/>
</p>

**Figure 9**: A red circle indicates the Lever that required a 3/4 turn to fasten the metal arm in place.

#### Flow Cell Overview

The flow cell was developed to mimic the mechanisms under which StaRS filters operate. Scaled, two-dimensional replicates of constrictions in a StaRS filter were placed between the flow cell's walls using various materials, as mentioned in the Introduction. Clear acrylic was needed for the flow cell's walls to observe and record the internal constriction. Silicone served as a water-tight border to separate two clear acrylic blocks and to contain the fluid passing through the flow cell, as shown in Figure 10.

To assemble the flow cell, the Spring 2018 subteam used the same two clear acrylic blocks as the Fall 2017 subteam. Two rows of screws along the bottom acrylic block, each row containing five tightened screws, guaranteed that the cell remained watertight.

 <p align="center">
 <img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/flowcellside.jpg?raw=true" width="40%" />

 </p>

 **Figure 10**: This depiction of a horizontal view of the flow cell shows how a silicone spacer (depicted as orange in Figures 1 and 2) was placed under pressure between two acrylic blocks, creating a watertight seal. Red arrows indicate the location of screws through both acrylic blocks.


 The flow cell was set in a wooden mount, as shown in Figure 11. An LED rested behind the flow cell to provide backlighting for high-quality video recordings. The two microtubes protruding from the back of the mount served as inlet and outlet of the flow cell. The flow cell was always mounted such that the outlet was beneath the inlet. This mimicked the gravitationally powered, downward movement of flocs seen in StaRS filters. The inlet was connected to the aforementioned branched hard-tubing segment, and the outlet was connected to the head loss tubing.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/newmount.png?raw=true" width="25%"/>
</p>

**Figure 11**: The above image is a photograph of a flow cell set in the previously fabricated mount.

#### Flow Cell Iterations

While the same acrylic material was used for each flow cell’s walls, the design of the constriction contained in the flow cell varied for each iteration.

The first flow cell design, developed by the Spring 2017 team, contained a silicone spacer with a horizontal wire attached at the middle, as shown in Figure 12. This model prevented the subteam from directly observing floc behavior at the wire-constriction.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/SingleWireFlowCellCircled.jpg?raw=true" width="60%"/>
</p>

**Figure 12**: The first flow cell iteration contained a single wire set horizontally across the flow cell [(Whiting et al.)](https://www.overleaf.com/8159891kkzwhhgszwtb#/28827379/). The wire is circled in green in the image.

The subteam designed a second iteration of the flow cell. A row of sand grains rested against the wire as mentioned above. This created multiple constrictions in the plane of view visible to the camera. The subteam considered gluing these sand grains inside the flow cell. However, the glue was opaque and prevented high-quality video recordings. The subteam modified this concept and decided to use sand grains slightly larger than the gap between the acrylic blocks, large enough to partially deform and remain immobile when pressed between the tightened blocks. Figure 13 shows a photograph of this design.

This design was unsatisfactory for multiple reasons. The sand grains were misaligned, and significant gaps arose between some grains. Footage showed that flocs preferentially flowed between more massive gaps, and the resulting flow patterns were dissimilar to those found in a sand filter. Another issue was the inability to keep the sand stationary while closing the flow cell. Any small volume of water that interacted with the sand would quickly move the grains due to their light weight and small size. The sand also scratched the acrylic blocks, partially hindering the camera's ability to record floc behavior at the constriction.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/SandRowFlowCell2.jpg?raw=true" width = "50%"/>
</p>

**Figure 13**: The second flow cell iteration contained sand grains inserted at the constriction. A red circle indicates the sand grains.

The sand model inspired the third iteration of the flow cell: the single-constriction design illustrated in Figure 14. The design consisted of a channel cut out of silicone with one constriction. This design was intended to prevent the inconsistencies found in the flow cell's second iteration. Specifically, each experiment would only test floc accumulation at one constriction, and the constriction's location and shape would be consistent between trials.

<p align="center">
  <img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/BumpConstriction%20Design.png?raw=true" width="40%"/>
</p>

**Figure 14**: The third flow cell iteration contained a single silicone channel with one constriction.

Issues arose when testing this design. After each experiment, when the flow cell was cleaned, the silicone channel shifted slightly. Also, tightening the screws squeezed together the acrylic plates, and the resulting pressure caused the silicone spacer to expand horizontally. As a result, the constriction's dimensions were inconsistent between experiments. Occasionally, the subteam observed complete blockage of the channel because the channel's silicone walls had converged after the screws had been tightened. On another occasion, the entrance to the flow cell became clogged with flocs, as seen in Figure 15. A large floc obstructed the channel's tapered entrance. Closer examination showed a smaller floc clogging the entrance further downstream, where the 0.5 mm channel began. Interestingly, the observed blockage did not significantly affect the flow through the rest of the channel length. The subteam observed the uninterrupted flow of flocs through the constriction. This observation was deemed insignificant, though it was noted as a precaution for future experiments.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Videos/4_9_18/4_9_18_Entrance_Clogging_edited.jpg?raw=true" width=50%> </p>

**Figure 15**: The above image is a photograph of the clogging at the entrance of the silicone channel. The green circle indicates the location of the clogging.

To compensate for the channel's inconsistent width, four wires were inserted into the silicone spacer. These wires extend out of the flow cell and could be pulled to adjust the channel's width. Once the acrylic blocks were tightly screwed together, the silicone spacer was immovable. The wires were only effective when the acrylic blocks were only somewhat tightened. Figure 16 highlights this modification.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Single%20Constriction%20with%20wires.jpg?raw=true" width=50%> </p>

**Figure 16**: Four wires were inserted into the silicone spacer, allowing adjustment of the channel's width. Green ovals indicate the insertion of wires into the silicone.

#### Needle Valve

Due to the microscopic scale at which the flow cell's constriction was observed, it was critical to minimize water's pulsation in the system. Pulsation would have caused flocs to oscillate in the flow cell, disturbing their natural flow and inhibiting deposition. Although the system's flow accumulator damped most pulsation caused by the peristaltic pumps, camera footage showed residual pulsation in floc movement. To further damp pulsation, a needle valve was inserted into the system in series with the flow accumulator and before the second peristaltic pump. The needle valve and flow accumulator were connected by hard tubing, as shown in Figure 17.

A needle valve forces fluid to flow at a particular pressure, set by a knob at its base. As a result, the pressure of fluid exiting the needle valve remained constant and without pulsation.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Needle%20Valve.jpg?raw=true" width = "50%"/>
</p>

**Figure 17**: The needle valve (Right, foreground) was inserted into the system between the flow accumulator (Left, foreground) and the second peristaltic pump. Blue arrows indicate the direction of flow relative to the valve.


#### Head Loss Design

As mentioned earlier, the head loss tubing was crucial for control water's velocity in the flow cell. Calculations were conducted to determine the precise length and height necessary for the head loss tubing to achieve the optimal velocity (equal to water's velocity in a StaRS filter). The following equation was used to calculate the apparatus' head loss and to determine the metal arm's appropriate height.

$$\Delta H = \frac{128L}{\rho g\pi} \frac{\mu Q}{D^4}$$

The diameter $D$ of the microtubing was found to be 0.042 $in$, and the length ($L$) of the microtubing was 275 $cm$. Using the previous team's flow cell dimensional measurements, the flow rate ($Q$) through a row of sand grains, based on the sand grain pore sizes, was calculated to be 555 $\mu L/min$. Figure 18 shows the flow cell's exact dimensions.

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Flowcellsketch.jpg?raw=true" width ="50%" />
</p>

**Figure 18**: The dimensions of the flow cell as designed by the Fall 2017 Filter Constrictions subteam [(Dokko et al.)](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/).

The $Q$ value in the third flow cell iteration (single constriction model) was calculated to be 27.75 $\mu L / min$. The microtubing diameter was the same as that of the sand model, but the length of the microtubing used was the entire length of a roll of microtubing, which is 100 $ft$ or 3048 $cm$.

This $Q$ value differed significantly from the velocity necessary for the flow cell iterations with larger flow cell volumes. Since these do not require a substantial pressure difference, flow cell iterations with high flow rates had a shorter head loss and smaller pressure difference than the flow cells with smaller volumes. The larger flow cell volume meant that more water needed to flow into the flow cell to emulate the flow through more constrictions than just a single constriction.

Given these two lengths of microtubing and two flow values, the subteam calculated the head losses corresponding to each possible combination of tubing length and flow rate. Table 1 contains the results of these calculations.

**Table 1**: The apparatus' calculated head loss differed based on flow rates and lengths of microtubing.

| Length of tube ($L$)    | Flow Rate ($Q$)   | Head loss ($\Delta H$)  |
|:-----------------------:|:-----------------:|:-----------------------:|
|        275 $cm$         | 27.75 $\mu L/min$ |         0.363 $cm$      |
|       3048 $cm$         | 27.75 $\mu L/min$ |         4.026 $cm$      |
|        275 $cm$         | 555 $\mu L/min$   |         7.262 $cm$      |
|       3048 $cm$         | 555 $\mu L/min$   |        80.492 $cm$      |

The wire-based flow cell design (aka. Iteration 1) at the start of the semester, corresponding to values in Table 1's first row, had a head loss value less than 1$cm$. The subteam could not manipulate the metal arm to produce this precise a value, so the subteam developed the second flow cell iteration, containing sand grains resting against a wire. After testing this iteration and determining it not to be ideal, the subteam developed a third flow cell iteration. It contained a single silicone constriction, matching Table 1's second row of values. It had a flow rate of 27.75 $\mu L/min$ and had a microtubing length of 100 ft. The head loss of 4.026 $cm$ was the most feasible to implement.

### Procedure

To begin an experiment, the subteam activated the first peristaltic pump. This sent water through the system and pushed out air bubbles. Once the system was equilibrated, dye and PACl were pumped into the system via the second peristaltic pump. The camera was configured and focused on the flow cell's constriction. As soon as the first floc approached the flow cell through the inlet tubing, the camera was activated to record floc behavior at the constriction. If the constriction clogged with flocs, the video was ended and saved onto the subteam's computer for analysis, and the second peristaltic pump was halted.

To prepare for the next recording, the flow cell was cleaned of flocs and repositioned on its wooden mount. When the arm was dropped to its lowest height, the increase in head loss let water flow at high rates through the flow cell. After cleaning finished, the arm was raised to its standard height. To prevent bacterial growth in the system, the system was flushed with bleach every few weeks.

Further details of the procedure are outlined in the Manual section of this report.

## Results and Analysis
After developing the two alternative flow cell designs (sand constriction, Iteration 2; single constriction, Iteration 3), the subteam recorded videos of floc accumulation in each. Once the needle valve was implemented, no significant pulsations were observed in the flow cells, even at low velocities. The experimental recordings and analyses of them are detailed in this section.

### Iteration 2: Sand Constrictions

In the second flow cell iteration, the subteam inserted sand grains into the flow cell to form multiple constrictions. As flocs flowed between the sand grains, the subteam captured videos to determine where on the sand grains the flocs deposited.

First, the subteam placed multiple rows of sand in the flow cell, but it became difficult to track the floc particles due to the sand grains' three-dimensional nature. It was uncertain whether flocs deposited above, below or beside the sand grains. The subteam simplified the constriction by replacing the multiple rows with a single row of sand grains. However, the exact locations of particle deposition remained ambiguous. Also, when an insufficient number of sand grains were placed in the flow cell, wide spaces opened between the sand grains for fluid to flow through.

Despite these issues, another version of the flow cell's second iteration was developed, containing several more rows of sand than the first version. Instead of the camera recording floc activity at the top of a sand-bed, the camera recorded floc activity in the midst of a sand-bed. A comparison of Figures 19 and 23 clarifies this distinction. Despite the sources mentioned above of error, such as the uncertain location of floc-deposition, general flow patterns were still discernible.

These ideas are discussed in the following sections.

#### Version 1: Multiple Rows of Sand (Top of Sand Bed)
The first set of experiments conducted had multiple rows of sand grains in the flow cell. In [this video recorded on 3-22-18](https://drive.google.com/file/d/14c_HhhH84Yhtt9AUTCWwiGHFTU7hYYra/view?usp=sharing), flocs were seen flowing between the sand grains. While some flocs deposited, others quickly exited the flow cell. This led the subteam to believe that a large active zone existed in which most flocs deposited. Most flocs were filtered out by the first few layers of sand with decreasing filtration capabilities deeper into the stacked filter. The term "active zone" refers to the depth of the filter at which most flocs have deposited in or been removed by a filter. The StaRS Filter Theory subteam has worked on the calculations for the possible depth of this active zone, but it remains inconclusive.

The flow cell was shaken side to side to represent random packing of the sand grains, which changed places before settling in the flow cell. Figure 19 shows a clean bed of sand grains before flocs deposited. As flocs entered the flow cell and deposited, the subteam realized that many large flocs entered the flow cell and quickly clogged the pores. In Figure 20, the subteam observed a few large flocs settling in the middle of the sand bed. The subteam decreased the concentrations of influent PACl and Red #40 dye to allow smaller flocs to form in the flocculator and thus smaller flocs to enter into the flow cell.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Videos/3_20_18/3-20-18_Image1.png?raw=true" width ="60%" /> </p>

**Figure 19**: The above is an image from camera footage taken on 3-20-18 near the start of the experiment, while the sand bed was clean.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Videos/3_20_18/3-20-18_Image3.png?raw=true" width ="60%" /> </p>

**Figure 20**: The above is an image from camera footage taken on 3-20-18. Large flocs deposited and clogged the sand bed's pores.  


Figure 19 showed the clean sand bed before floc deposition. As the subteam ran the experiment, flocs clogged and grew in the microtubing that led to the flow cell. In [following videos such as this one](https://drive.google.com/file/d/1hOHrj7Ubxsh54PmYMRggNziXhx6_08Uu/view?usp=sharing), the subteam continued to observe large flocs entering the flow cell.

The subteam switched from 0.05 mg/L concentrations of PACl and Red #40 dye to concentrations of 0.025 mg/L. The subteam did not capture any videos of the multiple rows of sand with these new concentrations due to software malfunctions. However, the decreased floc sizes are shown in the single row of sand experiments.


#### Version 2: Single Row of Sand
After multiple trials of floc deposition in Version 1, the subteam decided to capture videos of flocs flowing through just a single row of sand grains. Members believed particle deposition would potentially be more straightforward to observe. However, in the Version 2 flow cell, significant gaps between sand grains easily formed, and flocs easily passed through the row of sand grains. In [this video recorded on 3-23-18](https://drive.google.com/file/d/1QrMVALonsbg38C-L-hiBwzUfG4mSw_TF/view?usp=sharing), a gap existed on the right-hand side of the flow cell, and many flocs freely traveled through that region. Despite the gap, the subteam observed flocs depositing in other regions. As Figures 21 and 22 show, the subteam observed floc deposition in the midsection and left-hand side of the flow cell. However, since sand grains are 3-dimensional, it was difficult to tell where on the sand grain these flocs deposited.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Videos/3-23-18/3-23-18%20Single%20Row.PNG?raw=true" width ="60%" /></p>

**Figure 21**: Image of the single row of sand grains in the flow cell. This image was taken before floc release into the flow cell so that no clogging can be observed.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Videos/3-23-18/3-23-18_SettlesFlocs.png?raw=true" width ="60%" /></p>

**Figure 22**: Image of the single row of sand grains in the flow cell after more flocs deposited.


#### Version 3: Several Rows of Sand (Middle of Sand Bed)

The subteam also tested an Iteration 2 flow cell that contained several extra rows of sand grains, such that the camera recorded floc behavior in the midst of the sand bed. Upon reviewing Figures 19 and 21, one sees that Versions 1 and 2 camera footage mainly recorded floc behavior while entering a sand bed. Figure 23 shows that Version 3 camera footage recorded floc behavior having already entered a sand bed.

The subteam's concern is floc deposition throughout a sand filter. Thus, Version 3 complemented Versions 1 and 2. Although Version 3 suffered from the same aforementioned errors, it did provide some supporting evidence for previously held theories.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/20180504_unclogged_sand.jpg?raw=true" width ="60%" /> </p>

**Figure 23**: The above image is a photograph taken on 5-4-18 of the sand constrictions in the Iteration 2, Version 3 flow cell.

In [this video recorded on 5-4-18](https://drive.google.com/file/d/1DuMp1rfhoZNUDqlUVvI3CcMa3_RofPJ3/view?usp=sharing), similar to floc behavior in Version 1 footage, many flocs passed quickly through the sand grains. While the top of the sand-bed was invisible to the camera in this set-up, it was inferred that the top of the sand bed likely captured the majority of flocs. This supported the idea of a strong initial active zone, as stated in the Version 1 analysis. Only a few flocs remained to deposit within the rest of the sand bed, and many continued to pass through due to their small size. However, three new phenomena were observed in this video.

At 0:09 in the sand-bed's center, and at 0:06 in the sand-bed's left-hand portion, subteam members saw a floc pull other flocs through a constriction. This illustrated the phenomenon described in the Literature Review and Previous Work section: flocs deposit at constrictions until they reach some threshold, and future collisions force all flocs through the constriction.

At 0:04 in the sand-bed's left-hand portion, a floc caught at the apex of the curve of a sand-grain. At first, this appeared to suggest that flocs do deposit at the apex of constrictions. However, this instance likely occurred because the floc was relatively large, and the apex of the sand grain's curve formed a constriction smaller than the floc itself. This was not necessarily due to any aforementioned theories concerning streamlines and deposition mechanisms.

At 0:09 in the sand-bed's left-hand portion, the subteam saw a floc deposit atop a group of other flocs. This most likely occurred because of floc accumulation effectively shrinking the constriction, as explained in the Literature Review and Previous Work section, and as illustrated in Figures 3 and 4.

While the Version 3 camera footage did not show any conclusive evidence supporting the CAG theory, it did demonstrate previously held ideas.

The Iteration 2 flow cells were the closest replicates of the actual StaRS filter. However, it was unable to provide the subteam with accurate visualization of the precise location of floc deposition within a constriction. The subteam decided to use a single constriction design to test and observe where particle deposition happens.

### Iteration 3: Single Constriction

Figure 24 shows the third flow cell iteration, containing a single silicone-constriction. In [this video recorded on 3-29-18](https://drive.google.com/file/d/1eUqzdHFOanrB5mDO5vKKBjmP23TB9VkM/view?usp=sharing), a floc passed through the constriction at 0:03. This floc moved quickly and did not deposit. This was inferred to be caused by the short head loss tubing since the pressure gradient was too high, and therefore the velocity was too high.

When this flow cell was constructed, both the inlet and outlet tubing leaked from their fittings in the acrylic block. Because of this defect, the subteam replaced the acrylic blocks with those from the Iteration 1 flow cell. As a result, the flow cell in the 3-28-18 video had the short head loss tubing (275cm) rather than the new (100') tubing. The lack of head loss in the flow cell's outlet tubing caused a large pressure difference, which drove the high-velocity flow through the single constriction. This high velocity caused large shear forces and did not allow the flocs to behave as they would in a StaRS filter, so they freely flowed through the constriction rather than depositing.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/SingleConstrictionFlowCell.jpg?raw=true" width ="50%" /></p>

**Figure 24**: The above image is a photograph of the Iteration 3 flow cell, containing a single silicone-constriction, mounted with an LED behind it. Flow moves from top to bottom, from the inlet to the outlet tubing.  

##### Lack Of Floc Deposition

Once the head loss tubing was replaced with the proper 100' tubing, [the 4-10-18 video](https://drive.google.com/file/d/1CYJIeKLKguId76H67681LhZNNdwgqFQ3/view?usp=sharing) was recorded where floc flow and deposition was observed. The flow velocity was much slower than that in the 3-28-18 video, due to the installment of the proper outlet tubing. This allowed for a proper pressure gradient to create the corresponding flow velocity. Once the pore appeared to be clogged by the first few flocs, flocs still flowed past the constriction. This supported the StaRS filter theory depicted in Figure 25: a pore can capture a certain volume of flocs, which further shrinks the constriction until the resulting increasing shear and velocity become too great for any more flocs to be able to deposit. This was also supported by [this video recorded on 4-24-18](https://drive.google.com/file/d/1PEqdgf9bHZXCGsj_gXbMeIdrcFr8vTHD/view?usp=sharing), which showed that high velocities prevent floc deposition in constrictions.
<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Pore%20Clogging%20Theory.jpg?raw=true" width ="80%" /></p>

**Figure 25:** The above image is a visual representation of the pore-clogging hypothesis of floc deposition at a constriction. Flocs deposit on the walls of a constriction, gradually narrowing the pore through which flocs can flow. The pore can only take on a particular volume of flocs until no further flocs can deposit.

As the subteam ran more experiments, flocs continued not to deposit onto the silicone constriction. There are two theories as to why this was the case. The first theory is that the flocs have the same partial charge as silicone. The flocs and silicone repel each other, thus significantly decreasing the chances of deposition during filtration. The other theory is that due to possible slanted cuts of the constriction during fabrication, flocs were able to slip underneath the constriction and not deposit.

Flocs were observed passing under the silicone constriction in [this video recorded on 4-26-18](https://drive.google.com/file/d/1CpyezAN9FH9EDzT5S8Y6oLGJVwDMLIb5/view?usp=sharing). The subteam believed that as the silicone was cut, a slanted line was formed instead of a vertical line. The flocs were then unable to deposit on the constriction and instead passed underneath the silicone. Figure 26 shows how flocs can pass under an imperfect constriction.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Uneven_Cut.png?raw=true" width ="60%" /></p>

**Figure 26:** The above image is a depiction of the horizontal cross-section of the flow cell, as viewed along the channel (water flows out of the plane of the page). The camera records from above the acrylic wall, and the slant hinders the camera from capturing floc deposition underneath.

## Conclusions
The multiple new models developed by the subteam brought up a few interesting details for consideration. The inconsistency in the spacing with the Iteration 2 sand model prevented the subteam from moving forward with any of the three sand model designs. The implementation of the Iteration 3 single constriction model required the installment of a long head loss microtube to discourage flow through the flow cell further. The initial videos recorded showed how the previous flow cell velocity was much greater than the estimated actual velocity through a pore of 2 mL/min. The accuracy of the flow velocity as well as the dimensions of the flow cell itself was shown to be vital to the observed results of the experiments. Thus, the replacement of the old microtubing with the new 100 ft microtubing was a necessary solution to this issue. The new flow velocities observed in the most recent videos are accurate to the 2 ml/min necessary for an accurate model.

The consistency in the spacing with the silicone single constriction flow cell was the main advantage over the sand models. However, the first few experiments with the silicone proved to be less consistent than expected, as the silicone would slip and move between experiments. These inconsistencies were minute compared to those observed in the sand models. The Iteration 3 single constriction model was still deemed to be the best model thus far. The needle valve allowed for a reduction in the minute pulsations observed in the flow cell. The flow accumulator was implemented in the earlier iterations of the system which seemed to decrease the significant pulsation. However, considering the microscale environment of the constriction, diminishing all pulsation in the flow cell is of great importance. Thus the needle valve will remain as an integral part of the system. The most accurate model would help the subteam understand the physics of the occurrences at the constrictions between each sand grain within the sand filter, such that these can be optimized for maximum performance within the AguaClara plant.

The experiments conducted with the different models have qualitatively supported the CAG theory. The Iteration 3 single constriction model showed that flocs ceased to deposit at a constriction at a certain point, after which more flocs pass through the constriction regardless of apparent clogging. This supported the hypothesis that the flocs deposit at the constriction until the flocs create a pore so small that the velocity reaches its maximum. This maximum velocity, corresponding to minimum constriction radius, was hypothesized to be a result of the maximum shear that the flocs could tolerate.

## Future Work

With the Iteration 3 single constriction, the occurrences at the constriction have become more difficult to observe due to the dramatically reduced size of the flow cell, as compared to Iterations 1 and 2. The maximum zoom on the current camera can record the general flow at the constriction. However, the camera does not record videos of enough pixelation and quality to be able to observe the minute details of floc behavior at the constriction. A potential solution is to see if any additional lenses could be added to the camera for further zoom. Alternatively, it may be possible to obtain a computer with the bandwidth which would be able to handle the recording of higher quality videos. Currently, the subteam uses 40% quality for image quality when recording, due to the computer or program's inability to handle files that are any larger than 40% quality.

To turn these qualitative observations into concrete data, the subteam should plan on using image analysis software such as ImageJ to analyze the change in floc deposition over time. Colored pixel concentrations before and after the constriction can be recorded as a function of time to observe the changes in floc concentration after water has passed through the constriction. These quantitative comparisons could help further support the pore-clogging theory.

Though the subteam has come a long way from the Iteration 1 single wire model to the Iteration 3 single constriction model with silicone, there seems to be a need to be able to have a top view of the constriction. This would allow for the observation of the pore clogging in the plane of the pore. A proposed idea for this form of observation is the fabrication of a 3-dimensional model similar to the one modeled in Figure 27. The videos would be recorded from the right top or a diagonal view. This may allow for the subteam to view the flocs depositing at the periphery of the pore and slowly narrowing the constriction.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Cube%20Design.jpg?raw=true" width ="80%" /></p>

**Figure 27:** The above image is an illustration of a potential 3-dimensional model of the sand filter that has been proposed for a top view of the constrictions.

## Bibliography
Chu, T, Li, L., Harris, J. (2016). StaRS Filter Theory, Spring 2016.

Dokko, J., Fernandez-Bermejo, B., Sausele, D., Wu, C. (2017). Filter Constrictions, Fall 2017.

Kanpur, I. (2017), Losses Due to Sudden Contraction.

Li, J., Weber-Shirk, M., (2018). A Model for Stacked Rapid Sand Filters.

Logan, B. E., Hermanowicz, S. W., & Parker, A. S. (1987). A Fundamental Model for Trickling Filter Process Design. Journal (Water Pollution Control Federation), 59(12), 1029–1042.

Weber-Shirk, M.

Whiting, J., Shah, J., and Wang, T. (2016). Milli-sedimentation, Fall 2016.

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
* A Gilmont Instruments needle valve borrowed from the teaching lab

## Experimental Methods
### Set-up
1. Turn the valves of the inlet (Blue) and outlet (Red) hoses to the open positions (vertical handle).
    - If the dye and/or coagulant bottles are not connected to the system, replace the water bottles with the correct chemicals. See tube labeling to ensure proper correspondence of microtubing to the chemical.
2. Turn on the pumps and make sure that both the water pump and coagulant/dye pumps are running in the clockwise direction.
3. Ensure both pumps are on "INT" mode.
4. Set the water pump to 38.9 rpm and the dye/coagulant pump to 20 rpm **Jonathan, please fix these numbers**.
5. Set up the camera and connect it to the computer. If it does not show up, click Force IP.

 Setting up the camera
 1.  Unscrew the caps from both ends of the camera and the camera holding device connected to the computer.
 2.  Screw the camera onto the holding device
 3.  Attention: It is essential that no fingerprints are left on any of the lenses of the camera to ensure no disruption in the footage


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
7. Click the button on the file type, and it should automatically select the appropriate values for the file type.
8. Click "Start Recording" at the bottom of the window.
    - Check that the number of "Corrupted Images" remains low and the number of "Saved Images" increases accordingly.
    - Do not record for too long as the video may not save properly if it is too large.

### Cleaning Procedure
1. Obtain a bucket and fill it with clean, cold water. Place it on a stand to put it at the height of the flow cell mount.
    - Cold water is necessary to minimize dissolved oxygen levels. This will prevent air bubble formation in the flow cell later.
2. Turn the valves of the inlet (Blue) and outlet (Red) hoses to the open positions (vertical handle).
3. Turn on just the water pump to flush out the system of chemicals.
4. Submerge the flow cell in the bucket of cold water and open the flow cell by unscrewing all ten screws.
5. Clean the flow cell using glass cleaner and paper towels.
6. While maintaining the flow cell underwater, reassemble the flow cell with proper silicon and wire orientation. Screw all 10 screws tightly.
    - Check that the silicone piece covers neither the outlet nor inlet holes. The silicone piece can slide around during this step.
    - Some screws may not slide in easily due to misalignment. To bypass this, loosely attach all ten screws, then tighten all for better alignment. Use Philips screwdriver.
7. If air bubbles are trapped, tap the sides of the flow cell with the outlet facing up to allow bubbles to exit upwards. DO NOT tap the face as it may damage the surface and decrease visibility in the footage.
8. Turn off pumps if no experiments are to follow immediately after cleaning. If experiments are to follow immediately, switch the dye and coagulant pump on and begin the experiment.

## Experimental Checklist
* Check that the coagulant and dye are plugged into their proper pump tubings.
* Check that the flow cell is cleaned and free of air bubbles.
* Check that both the inlet and outlet valves are open.
* Check that the silicone sheet does not cover the flow cell inlet and outlet.
* Check that the head loss adjustment is at the proper height.


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

First, if we were to model one constriction with the average velocity through the pores of the filter column. The velocity of a filter is 1.85 $\frac{mm}{s}$, the area of the filter of the flow cell was found using the width of the flow channel shown in Figure 14.

```python
from aide_design.play import *
import math as m
from scipy import constants
V_filter = 1.85*u.mm/u.s # average velocity through a filter
A_filter = (0.5*u.mm)**2 # average area of flow columns in a filter
Q_filter = V_filter*A_filter
Q_filter.to(u.ul/u.min)

L = 275*u.cm # length of micro tubing
g = constants.g*u.m/(u.s)**2
rho = 1*u.g/(u.cm)**3
mu = 8.90*(10**(-4))*u.Pa *u.s
D =  0.042*u.inch # diameter of microtubing, found on McMaster
deltah = (128*L*mu*Q_filter)/(rho*g*m.pi*D**4)
deltah.to(u.cm)

```

With the current set up, the subteam calculates 0.36 cm of head loss ($\Delta H$). This is too small to be able to adjust with the height of the waste tube, and therefore the subteam must find another solution. The first possible solution is to use a row of sand grains and then model the constriction through multiple pores. This allows us to increase the flow rate through the flow cell and thus have a higher, more manageable head, which is the difference between the height of the top of the head loss tubing and the height of the waste line in the lab. The width of the flow channel was 10mm, and the depth of the flow channel was 0.5mm.

```python
V_sand = 1.85*u.mm/u.s # average velocity through a filter
depth = 0.5*u.mm
width = 10*u.mm
A_sand = depth * width # area of flow cell
# Find the flow rate (Q)
Q_sand = V_sand*A_sand
Q_sand.to(u.ul/u.min)
# Find the head loss
deltah_sand = (128*L*mu*Q_sand)/(rho*g*m.pi*D**4)
deltah_sand.to(u.cm)
```
With these changes, $\Delta H$ is 7.26 cm, which is more manageable, but still very small. Since the waste line in the lab is coiled, there is a chance that air in the line can increase the head loss in the line, and therefore can complicate the design. Therefore, if after running experiments, we find that the flow rate is too slow, we will increase the length of the microtubing used to increase $\Delta H$. The subteam would use a 100 ft long roll of microtubing.

```python
# If we use an entire roll of micro tubing, the change in the head loss
L2 = 100*u.feet
deltah2 = (128*L2*mu*Q_sand)/(rho*g*m.pi*D**4)
deltah2.to(u.cm)
```
The subteam calculated the $\Delta H$ to be 80 centimeters. Therefore, the height of the subteam's head loss tubing would only have to be 80cm lower than the height of the waste line in the lab.

```python
# To convert the document from markdown to pdf
pandoc FilterConstrictions-Report1.md -o Filter-Constrictions_Research_Report1.pdf
```
