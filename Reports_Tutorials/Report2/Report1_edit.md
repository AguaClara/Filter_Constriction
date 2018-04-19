multiple# Filter Constrictions, Spring 2018 Team
#### Thomas Bradford, Jacqueline Dokko, Jonathan Harris
#### April 20, 2018

<div class="alert alert-block alert-danger">
Please do not delete my comments. On the next submission I will use them to see if the issues were addressed and then I will delete them. If you disagree with a comment, just add your own underneath it. Also in the future, denote which report I should grade since there are two similarly named reports.
</div>

## Abstract

The Spring 2018 Filter Constrictions subteam developed and tested an apparatus to mimic floc behavior at constrictions between a filter’s sand grains. The Spring 2017 team had developed an apparatus including a flow cell that contained a wire to constrict flow. Spring 2018 members fabricated two alternative flow cells: one contained sand to form multiple constrictions; another contained a single channel cut from silicone. To better control the system’s flow, members added a needle valve and an adjustable metal arm to the apparatus. The subteam recorded and analyzed videos of floc accumulation in the new apparatus.

<div class="alert alert-block alert-danger">
Change "has worked" to "is working" in the first sentence to match with the sentence "the team aims to adjust" - Consistent verbs

What information are you trying to get out of your model? Are you only making modifications to the set-up this semester or are you running experiments too?

Model is used in terms of a experimental model and also a theoretical model, consider only calling the theoretical model a model and the experimental model an experimental apparatus.
</div>

## Introduction

The Filter Constrictions subteam aimed to evaluate the hypothesis that, as flocs flow through channels in stacked rapid sand (StaRS) filters, flocs deposit preferentially at the edges of flow constrictions. According to the StaRS Filter Theory subteam's Cylindrical Annulus Geometry (CAG) Theory, flocs passing near a constriction's edge progressively draw closer to this edge and deposit through sedimentation and interception [(Li et. al. 2018)](https://www.overleaf.com/read/cwqydwgftkmn). To evaluate the CAG theory and to better understand the filtration process in AguaClara's water treatment plants, the Filter Constrictions subteam developed a method to model and analyze floc accumulation at a sand filter’s constrictions.

The Spring 2017 subteam built a flow cell comprised of two clear acrylic blocks separated by a layer of silicone. Members cut a rectangular channel out of this silicone layer. A wire lay across the channel, decreasing the area for flocs to flow through and creating a constriction. While water containing flocs was pumped through the flow cell, a camera recorded what occurred at this single-wire constriction; to better distinguish flocs in the camera footage, the subteam generated flocs from red dye instead of clay.

<div class="alert alert-block alert-danger">
Consider putting the numbers/details in the methods or manual sections.

done
</div>

The Spring 2018 subteam determined that this design was insufficient to model a sand filter's constrictions. Since the camera recorded perpendicularly to the flow cell and the wire lay across said cell, the constriction was outside the camera’s plane of view. Also, the constriction was only two-dimensional; while some flocs deposited, other flocs passed around them in a path dissimilar to that in a sand filter. The Spring 2018 subteam aimed to alter the flow cell to contain more realistic constrictions, all visible to a camera.

To determine the most effective method to model floc accumulation, the subteam captured videos of flocs passing through two new constriction designs: a sand constriction, and a silicone constriction. These designs are explained in further detail in the Methods section.

<div class="alert alert-block alert-danger">
Again consider moving specific numbers into methods section.

The meaning of the last two sentences is unclear.

Give overview of how you will determine the most effective and efficient way to implement these parameters.

Good description of theory.
</div>

## Literature Review and Previous Work

When fluid passes through a channel and encounters a sudden constriction, minor head loss occurs. The change in flow area causes the fluid's streamlines to converge; as a result, after passing through the constriction, the streamtube's cross-sectional area becomes even smaller than that of the constriction itself. This creates the vena contracta: the location where the streamtube's cross-sectional area is at a minimum, as shown in Figure 1. After the vena contracta, the streamtube expands so its cross-sectional equals that of the channel [(Kanpur 2009)]().

<div class="alert alert-block alert-danger">
The sentence "the streamtube becomes smaller than the area it passed through right after the constriction" is unclear.
</div>

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Hydraulic_vena_contracta_275px.png?raw=true"/>
</p>

**Figure 1**: Streamlines gradually converge before passing through a constriction. They converge until the vena contracta, after which they widen.

While streamlines converge at the constriction, space decreases between the outermost streamline and the constriction's wall. This increases the chance that a floc collides with the constriction's wall and deposits. Floc accumulation at the constriction further decreases the cross-sectional area through the constriction, as shown in Figure 2. Due to flow continuity, as the flow's cross-sectional area decreases, the flow's velocity through the constriction increases; the rate of floc-collision accordingly increases. The flow's velocity increases until the fluid's drag on flocs is enough to prevent deposition and pulls the flocs through the constriction [(Weber-Shirk 2017)](https://courses.cit.cornell.edu/cee4540/pdf/Filtration.pdf). To evaluate the CAG theory, the Filter Constrictions subteam must determine where on the constrictions such floc deposition occurs.

<div class="alert alert-block alert-danger">
Do the flocs stick to the pipe walls or are they settling out? Saying that "a floc will come into contact with the wall and be captured" sounds like stickiness to me.

Some sentences don't make sense. Revise this paragraph

Why is vena contracta italicized?
</div>

<span style="color:green">
Jonathan - Captured and deposit are the words used in the StaRS Model paper and so we just wanted to be consistent with them and that is why we continued to use those words. However, I did add to the intro the two primary modes of deposition that they believe are taking place in the filter (sedimentation and interception)
</span>

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/ConstrictionsSandGrains.png?raw=true" width="35%"/>
</p>

**Figure 2**: Flow area decreases as flocs collide and accumulate at a constriction.

The Fall 2016 Milli-Sedimentation and Spring 2016 StaRS Filter Theory subteams provided evidence to support the CAG theory. The Milli-Sedimentation subteam found that when turbid water passed through nonaligned honeycomb structures, flocs deposited where flow was restricted between honeycombs [(Whiting et. al. 2016)](https://www.overleaf.com/8159891kkzwhhgszwtb#/28827379/). This demonstrated that flocs deposited preferentially at constrictions. The StaRS Filter Theory subteam conducted experiments on a clogged filter running at different flow rates to find the head loss through the filter; the subteam found that the head loss through the filter had a quadratic relationship with the flow rate. This suggested that minor losses were present in the clogged filter, and thus confirmed the presence of constrictions in the sand filter [(Chu et. al. 2016)](https://confluence.cornell.edu/display/AGUACLARA/StaRS+Filter+Theory?preview=/206635878/340897167/StaRSFilterTheoryReportFall2016.pdf).

The Fall 2017 Filter Constrictions subteam tested the CAG theory on a single-wire constriction flow cell. Camera recordings showed floc deposition at the constriction, though it was unclear as to where on the wire flocs deposited. Also, after a sufficiently large volume of flocs deposited on the constriction, the accumulated flocs fell through the constriction as a unit [(Dokko et. al. 2017)](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/). Members hypothesized this behavior to be equivalent to a StaRS filter's failure point [(Li et. al. 2017)](https://www.overleaf.com/6268224jmjfms#/21041070/).

<div class="alert alert-block alert-danger">
Is there a name for the filter constrictions theory detailed in the intro so that referring to it is easier?

Define StaRS acronym
</div>

## Methods

The Spring 2017 subteam developed an apparatus to model floc behavior at a sand filter's constrictions. Flocs, developed in a flocculator, were pumped through a flow cell with clear, acrylic walls; a camera recorded their behavior at a constriction in the flow cell. Such tests ran for durations up to an hour to observe short term and long term patterns, and ultimately to evaluate the CAG theory.

The original flow cell's constriction was comprised of a 0.5 mm space created by a water-tight silicon spacer between two acrylic walls, across which a 0.3 mm diameter wire lay and created a 0.2 mm constriction between the flow cell's walls. Though the flocs were historically made of coagulant (a.k.a. polyaluminum chloride, PACl) and clay, the 2017 Filter Constrictions subteam exchanged clay for red dye #40. This increased floc visibility, attributed to color contrast in the camera footage.

#### Experimental Apparatus
The Spring 2018 subteam altered Fall 2017's system, highlighted below in the Figure 3 schematic. The system was developed to recreate the portion of an AguaClara treatment plant in which layers of sand filter water in a StaRS filter. As shown in Figure 3, the system apparatus allowed water to flow from an inlet, carry an input of flocs0, enter the flow cell, and exit through a waste line.

Specifically, tap water entered the system from the inlet line, which was controlled by a peristaltic pump. The water then passed through the flow accumulator and needle valve, which inhibited pulsations caused by the peristaltic pump. An additional peristaltic pump input coagulant and dye into the water; the dye mimicked dirt particles found in water entering AguaClara plants. The mixture of water, dye, and coagulant entered the flocculator, the length of which had been calculated to generate flocs of the desired size through collision of dye and coagulant particles. The resulting mixture, now containing flocs, entered a branched tubing system that directed most flow away from the flow cell and into the waste line; this prevented overly high fluid velocities in the flow cell. After the remaining mixture passed through the flow cell, the flow cell's effluent traveled up tubing to the height of a vertically adjustable metal arm, to which the apex of the effluent tubing was attached. Effluent then drained into a waste container. Videos and images of the flow cell's constriction were taken with a FlyCap camera mounted next to the flow cell.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Sp18_Schematic_w_needlevalve.png?raw=true" width="70%"/>
</p>

**Figure 3**: This schematic represents the flow apparatus as designed by the Spring 2017 subteam and modified by the Spring 2018 subteam. Adapted and modified from [Dokko et. al. 2017](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/).


<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Apparatus.jpg?raw=true" width="50%"/>
</p>

**Figure 4**:  The flow apparatus in-laboratory, shown with labeled components. **Update with needle valve**

<div class="alert alert-block alert-danger">
Describe what else is in the scematic, walk us through the different parts and their importance? What tools do you use for data collections?

Figures are good references but they cannot stand by themselves.

RESOLVED
</div>

Figure 3 highlights the importance of the effluent, "head loss" tubing. Head loss ($\Delta H$) was the main driver for the pressure gradient across the flow cell, which in turn caused influent to flow through the flow cell. The difference in height ($\Delta H$) between the head loss tubing and the laboratory's waste line was proportional to this head loss, and therefore caused a particular pressure gradient across the flow cell, determining flocs' flow rate ($Q$). This height difference was manipulated with a vertically adjustable metal arm to create the necessary flow rates through different flow cell designs.

The ability to control this height difference was crucial in obtaining proper flow velocities to mimic those in StaRS filters. Previous semesters' Filter Constrictions subteams used various set heights within the laboratory, such as pipes near the ceiling. The Spring 2018 team designed and fabricated a vertically adjustable "head loss arm" using 80/20, an aluminum-rod framing system. The metal arm allowed for subteam members to control of the height of the head loss tubing's apex, as shown in Figure 5. The metal arm's most important component was a lever that allowed easy vertical movement of the 80/20 beam, as shown in Figure 6. This enabled control of the flow rate across the flow cell.

<div class="alert alert-block alert-danger">
Did not give background on what the experimental apparatus actually is. Without that, the head loss part does not make sense.

Also why is head loss important?

Describe 80/20

RESOLVED
</div>

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/HeadlossAdjuster.jpg?raw=true" width="25%" />
</p>

**Figure 5**: Vertically adjustable metal arm, fabricated with 80/20. The apex of the head loss tubing was attached to the top of the arm, as indicated by the red arrow.

<p align="center">
<img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/AdjustablePart.jpg?raw=true" width="25%"/>
</p>

**Figure 6**: Lever that required a 3/4 turn to tighten the metal arm in place.


#### Flow Cell Overview

The flow cell was developed as a means to observe the mechanisms under which StaRS filters operated. Scaled, two-dimensional replicates of constrictions in a StaRS filter were placed between the flow cell's walls using various materials, as mentioned in the Introduction. Clear material was needed for the flow cell's walls in order to observe and record the internal constriction. Silicone served as a water-tight border to separate two clear acrylic blocks and to contain the fluid passing through the flow cell, as shown in Figure 7.

To assemble the flow cell, the Spring 2018 subteam used the same two clear acrylic blocks as the Fall 2017 subteam. Two rows of screws along the bottom acrylic block, each row containing five tightened screws, guaranteed that the cell remained watertight.

 <p align="center">
 <img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/flowcellside.jpg?raw=true" width="40%" />

 </p>

 **Figure 7**: A silicone spacer was placed under pressure between two acrylic blocks, creating a watertight seal.

 The flow cell was set in a wooden mount, as shown in Figure 8. An LED rested behind the flow cell to provide backlighting for high-quality video recordings. The two tubes protruding from the back of the mount were the microtubes that served as inlet and outlet of the flow cell. The cell was always mounted such that the outlet would be on the bottom; this mimicked the gravitationally powered downward movement of flocs seen in StaRS filters. The inlet was connected to the aforementioned branched hard-tubing segment, and the outlet was connected to the head loss tubing, as shown in Figures 3 and 4.




<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/newmount.png?raw=true" width="25%"/>
</p>

**Figure 8**: A flow cell set in the previously fabricated mount.

<div class="alert alert-block alert-danger">
Good figures but not enough description of what they are.

I don't understand how water is flowing through the system.
</div>

#### Flow Cell Iterations

While the same acrylic material was used for each flow cell's walls, the constriction contained by each flow cell varied.

The first flow cell design, developed by the Spring 2017 team, contained a silicone spacer with a horizontal wire attached sat the middle, as shown in Figure 9. This model prevented the team from directly observing floc behavior at the wire-constriction.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/SIngleWireFlowCell.jpg?raw=true" width="60%"/>
</p>

**Figure 9**: The first flow cell iteration contained a single wire set horizontally across the cell [(Whiting et. al.)](https://www.overleaf.com/8159891kkzwhhgszwtb#/28827379/) **circle the wire**

The team designed a second iteration of the flow cell. A row of sand grains rested against the wire. This created multiple constrictions in the plane of view visible to the camera. The subteam considered gluing these sand grains inside the flow cell; however, the glue was opaque and prevented high-quality video recordings. The subteam modified this concept and decided to use sand grains slightly larger than the gap between the acrylic blocks, large enough to deform when pressed between the tightened blocks. As shown in Figure 10, this design was unsatisfactory for multiple reasons. The sand grains were misaligned, and large gaps arose between some grains. Experimental footage showed that flocs preferentially flowed between larger gaps, and the resulting flow patterns were dissimilar to those found in a sand filter.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/SandRowFlowCell2.jpg?raw=true" width = "50%"/>
</p>

**Figure 10**: The second flow cell iteration contained sand grains inserted at the constriction.

This model inspired the third iteration of the flow cell: the single-constriction design shown in Figure 11. The design consisted of a channel cut out of silicone with one constriction; this design was intended to prevent the inconsistencies found in the flow cell's second iteration. Specifically, each experiment would only test floc accumulation at one constriction, and the constriction's location and shape would be consistent between trials.

<p align="center">
  <img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/BumpConstriction%20Design.png?raw=true" width="40%"/>
</p>

**Figure 11**: The third flow cell iteration contained a single silicone channel with one constriction.

Issues arose when testing the flow cell's third iteration. The silicone channel shifted slightly after every cleaning session; the constriction's width varied in width between experiments, so the constriction's dimensions were inconsistent **(EDITING STOPPED HERE. CONTINUE ON FRIDAY (note from Tommy to Tommy))**. Tightening the screws squeezed together the acrylic plates, and the resulting pressure caused the silicone spacer to expand horizontally; occasionally, the subteam observed complete blockage of the channel because the channel walls had converged after the screws had been tightened. On another occasion, the entrance to the flow cell became clogged with flocs, as seen in Figure 12. A large floc can be seen obstructing the tapered entrance. Closer examination showed a smaller floc clogging the entrance further downstream, where the 0.5 mm channel began. Interestingly, "this"**what is this?** did not significantly affect the flow through the rest of the path **system? or flow cell?** and constriction. The team observed undisturbed flow of flocs through the constriction; this observation was deemed insignificant though it would be noted as a precaution for future experiments.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Videos/4_9_18/4_9_18_Entrance_Clogging_edited.jpg?raw=true" width=50%> </p>

**Figure 12** Image of the clogging observed at the entrance of the silicone flow cell. The green circle indicates the location of the clogging.

To compensate for the channel's inconsistent width, four wires were inserted into the silicone spacer. These wires extended out of the flow cell and could be pulled to adjust the channel's dimensions. Once the plates were tightly screwed together, the silicone spacer was immovable; the wires were only effective when the acrylic blocks were only somewhat tightened. Figure 13 highlights these changes; the green ovals indicate the insertion of wires in the silicone.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Single%20Constriction%20with%20wires.jpg?raw=true" width=50%> </p>

**Figure 13** Four wires were inserted into the silicone spacer in the third flow cell iteration. These allowed adjustment of the channel's width.

<div class="alert alert-block alert-danger">
This section has great content, but is it technically a construction complication? It seems more like a design process.

As an aside, this methods section is a little scattered and might benefit from reorganizing the sections.

RESOLVED
</div>

#### Needle Valve

Although the system's flow accumulator damped most pulsation from the peristaltic pumps, camera footage showed minute pulsations in floc movement. To further damp pulsation, a needle valve was inserted into the system in series with the flow accumulator and prior to the second peristaltic pump; the needle valve and flow accumulator were connected by hard tubing, as shown in Figure 14. A needle valve only allows fluid to flow at the pressure set by a knob at its base. As a result, the pressure of fluid exiting the needle valve remained constant and without pulsation.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/Needle%20Valve.jpg?raw=true" width = "50%"/>
</p>

**Figure 14**: The needle valve (Right) was inserted into the system between the flow accumulator (Left) and the second peristaltic pump. Blue arrows indicate the direction of flow relative to the valve.

#### Head Loss Design

**Jonathan - please rewrite/rearrange the Head Loss Design section** The following equation was used to calculate the apparatus' head loss and to determine the metal arm's appropriate height.

$$\Delta H = \frac{128L}{\rho g\pi} \frac{\mu Q}{D^4}$$

$Q$ in the third flow cell iteration was calculated to be 27.75 $\mu L / min$; the diameter $D$ of the microtubing was found to be 0.042 $in$. The length ($L$) of the microtubing was 275 $cm$, and the calculated flow rate through one constriction is 27.75 $\mu L / min$.

Using the **previous team's** flow cell measurements, the flow rate through a row of sand grains was calculated to be 555 $\mu L/min$; this is shown in Figure 15. **The length of microtubing contained in one roll is 100 $ft$**

Given these two lengths of microtubing and two flow values, the subteam calculated the head losses corresponding to each possible combination of tubing length and flow rate. Table 1 contains the results of these calculations.  

**Table 1**: The apparatus' calculated head loss at different flow rates and lengths of microtubing.

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

**Figure  15**: The dimensions of the flow cell as **designed by the Fall 2017** Filter Constrictions subteam [(Dokko et. al.)](https://www.overleaf.com/read/gjkjdyvyhnxs#/41170384/).

The **current flow cell** design, corresponding to values in Table 1's first row, has a head loss value less than 1$cm$. The subteam could not  manipulate the metal arm to produce this precise a value, so the subteam determined an alternative design. After the second flow cell iteration was tested (containing a row of sand grains laid across a  wire), and determining the iteration not to be ideal, the subteam decided to use a single-constriction design (iteration 3) matching Table 1's second row of values. It contained one flow constriction, a flow rate of 27.75 $\mu L/min$, and a microtubing length of 100 ft. The head loss of 4.026 $cm$ was the most feasible to implement.

**The subteam experimented with using a row of sand grains to act as constrictors; issues arose with keeping the sand in place. The sand also scratched the acrylic blocks. Determining that use of a row of sand grains was unideal, the team decided to use a design matching Table 1's second row of values.**

<div class="alert alert-block alert-danger">
Good analysis of these results.

Results & Analysis is really light right now, and I understand that this is only half way through the semester so there isn't much, but for the next report, add in more analysis of whatever results/design parameters you get.
</div>


### Procedure
In the apparatus, flocs were generated and passed through the flow cell to observe their behavior at constrictions.

To begin, the subteam activated the first peristaltic pump; this sent water through the system and pushed out any air bubbles. Once the system was equilibrated, dye and PACl were pumped into the system via the second peristaltic pump. As soon as the first floc approached the flow cell through the inlet tubing, the camera was activated to record floc behavior at the constriction. To be ready to record at any time, the camera was often configured and focused before this. If the constriction clogged with flocs, the video was ended and saved onto the subteam's computer for analysis, and the second peristaltic pump was halted.

To prepare for the next recording, the flow cell was cleaned of flocs and repositioned on its wooden mount. Cleaning was facilitated by the metal arm; once the arm was dropped to its lowest height, the great decrease in head loss let water flow at high rates through the flow cell. The arm was raised to its standard height after cleaning finished. To prevent bacterial growth in the system, the system was flushed with bleach every few weeks.

Further details of the procedure are outlined in the Manual section of this report.

<div class="alert alert-block alert-danger">
This Procedure Section does not actually have a procedure, which would be a set of steps on how to run the experiment. This is a description of your apparatus and should be moved there. In the Procedure Section, provide the How-to on how to run your experiment and how you collected data.

RESOLVED
</div>


## Results and Analysis
After developing the two alternative flow cell designs (sand constriction, Iteration 2; single constriction, Iteration 3), the team recorded videos of the floc accumulation in each. The experimental recordings and analyses of them are detailed in this section.

### Sand Constrictions

In the second flow cell iteration, the subteam inserted sand grains into the flow cell to form multiple constrictions. As flocs flowed between the sand grains, the team captured videos to determine where on the sand grains the flocs deposited.

First, the subteam had multiple rows of sand in the flow cell, but it became difficult to track the  floc particles due to the sand grains' three-dimensional nature; it was difficult to determine whether flocs deposited above, below, or beside the sand grains. The subteam simplified the constriction by placing the multiple rows with a single row of sand grains. However, particle deposition location remained ambiguous. Also, when an insufficient number of sand grains were placed in the flow cell, wide spaces opened between the sand grains for fluid to flow through; the team was unable to see actual deposition of the flocs on the sand grains. These phenomena are described further in the following sections.

#### Version 1: Multiple Rows of Sand
The first set of experiments conducted had multiple rows of sand grains in the flow cell. In [the video recorded on 3-22-18](https://drive.google.com/file/d/1hOHrj7Ubxsh54PmYMRggNziXhx6_08Uu/view?usp=sharing), flocs were seen flowing between the sand grains. While some flocs deposited, others were never captured and quickly exited the flow cell. This led to the belief that there was a large active zone in which most flocs deposit. The active zone represented the depth of the filter at which most flocs were deposited or removed by a filter. The StaRS Filter Theory team has worked on the calculations for the possible depth of this active zone, but it currently unknown. In figure 16,

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Videos/3-22-18%20Screenshot%201.png?raw=true" width ="70%" /> </p>

**Figure 16**: Image from video taken on 3/22/18 near the start of the experiment.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Videos/3-22-18%20Screenshot%202.png?raw=true" width ="70%" /> </p>

**Figure 17**: Image from the video taken 3/22/18 near the end of the experiment.

After multiple experiments, the team decided to attempt to capture videos of flocs as they flow through just a single row of sand grains.

#### Version 2: Single Row of Sand
[3-23-18 video](https://drive.google.com/file/d/125flfmdWQUzdLbNkAbIODlrEk_kotEMs/view?usp=sharing)

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Videos/3-23-18/3-23-18%20Single%20Row.PNG?raw=true" width ="70%" /></p>

**Figure 18**: Image of the single row of sand grains in the flow cell. This image was taken prior to floc release into the flow cell, so no clogging can be observed.

<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Videos/3-23-18/3-23-18_SettlesFlocs.png?raw=true" width ="70%" /></p>

**Figure 19**: Image of the single row of sand grains in the flow cell after more flocs deposited.

### Single Constriction

The third flow cell design, containing a single silicone-constriction, is shown in Figure 20. In this linked [3-28-18 video](https://drive.google.com/file/d/1eUqzdHFOanrB5mDO5vKKBjmP23TB9VkM/view?usp=sharing), a floc passes through the constriction at 0:03. This floc moves quickly and does not deposit. This was inferred to be caused by the **short head loss tubing (was the pressure difference too high?)**.

Also, when this flow cell was constructed, both the inlet and outlet tubing leaked from their fittings in the acrylic sheet. Because of this defect, the team interchanged the silicone sheet into the old flow cell. As a result, the flow cell in the 3-28-18 video had the short head loss tubing (275cm) rather than the new (100') tubing. The lack of head loss in the outlet tubing of the flow cell caused the large pressure difference which drove the high velocity flow through the single constriction. High velocities caused large shear forces and did not allow the flocs to behave as they would in a StaRS filter, so they freely flowed through the constriction rather than depositing.
<p align="center"><img src="https://github.com/AguaClara/filter-constrictions/blob/master/Images/SingleConstrictionFlowCell.jpg?raw=true" width ="50%" /></p>

**Figure 20**: Image of the third flow cell design, containing a single silicone-constriction, mounted with the LED in position. Flow moves from top to bottom (inlet to outlet).

Once the head loss tubing was readjusted to the proper 100' tubing, [the 4-10-18 video](https://drive.google.com/file/d/12uSo2vY5D1GoX5RjIcvQRDqIQclu3EPT/view?usp=sharing) was recorded. Floc flow and deposition can be observed 0:05 through 0:10. The flow velocity is much slower than that in the 3-28-18 video, due to the installment of the proper outlet tubing. This allowed for a proper pressure gradient to create the corresponding flow velocity. However, a majority of the flocs did not deposit but flowed freely through the constriction. This could be due to uneven channel width throughout the flow cell, such that some parts of the constriction were wider than others, allowing flocs to pass freely even though other areas were already clogged.





## Conclusions
The multiple new models developed by the team brought up a few interesting details for the team to consider. The inconsistency in the spacing with the sand model prevented the team from moving forward with either of the sand model designs. The implementation of a single constriction model required the installment of a long head loss microtube to further discourage flow through the flow cell. The initial videos recorded showed how the previous flow cell velocity was much greater than the estimated actual velocity through a pore of 2 mL/min. The accuracy of the flow velocity as well as the dimensions of the flow cell itself was shown to be vital to the results of the constriction observation. Thus, the replacement of the old microtubing with the new 100 ft microtubing was a necessary solution to this issue. The new flow velocity observed in the most recent videos are accurate to the 2 ml/min necessary for an accurate model.

The consistency in the spacing with the silicone single constriction flow cell was the main advantage over the sand models. However, the first few experiments with the silicone proved to be less consistent than expected as the silicone would slip and move between different experiments. On the contrary, these inconsistencies were minute compared to those observed in the sand models thus the single constriction model with the needle valve was still deemed to be the best model thus far. The needle valve allowed for a reduction in the minute pulsations observed in the flow cell. The flow accumulator was implemented in the earlier iterations of the system which seemed to decrease the major pulsation. However, considering the microscale environment of the constriction, diminishing all pulsation in the flow cell is of great importance, thus the needle valve will remain as an integral part of the system. The most accurate model would help the team understand the physics of the occurrences at the constrictions between each sand grain within the sand filter such that these can be optimized for maximum performance within the plant

<div class="alert alert-block alert-danger">
What videos are you referrig to? You don't talk about collecting any data, only designing changes to your system. You also do not discuss velocity differences.

Additionally, this is the first time you reference "sand grains in a row"

These conclusions don't match up to what you spoke about in your methods/results/analysis portions.

It is also one long paragraph
</div>

## Future Work

In order to optimize the flow cell velocity to that of fluid flowing through one constriction in a StaRS filter, the consistency in the spacing of the silicone must be optimized. The most recent implementation of the wires on the sides of the silicone sheet have yet to be tested. However, they seem to provide the team with much more flexibility in adjustment of the channel size so far. This new method will need to be observed in future experiments and adjusted as needed.

Though the flow cell velocity has come much closer to that seen in a StaRS filter due to the 100 ft microtubing, the velocity inside the flow cell has yet to be confirmed. The accuracy of the flow cell velocity to the calculated one can be tested using ImageJ particle tracking to measure floc velocity in the flow cell. It is likely that this confirmation with be conducted after the team experiments with ways to obtain a consistent single constriction channel width using the silicone sheet with wires.

 With the single constriction, the occurrences at the constriction have become more difficult to observe due to the dramatically reduced size of the flow cell compared to the previous layers or rows of sand. The maximum zoom on the current camera is able to record the general flow at the constriction; however, the camera does not record videos of enough pixelation and quality to be able to observe the very minute details of floc behavior at the constriction. A potential solution is the see if any additional lenses could be added to the camera for further zoom. Alternatively, it may be possible to obtain a computer with the badnwidth which would be able to handle the recording of higher quality videos. Currently, the team uses 40% quality for image quality whne recording due to the computer or program's inability to handle files that are any largeer than 40% quality.

<div class="alert alert-block alert-danger">
These are gret coherent next steps, but again I don't understand where they are coming from because they weren't mentioned in your results/analysis.I am not sure what the minute pulsation is or the flow accumulator.

In general, you should not be introducing new concepts in the future work or conclusion areas.
</div>


## Bibliography
Chu, T

Dokko, J., Fernandez-Bermejo, B., Sausele, D., Wu, C. (2017). Filter Constrictions, Fall 2017.  

Kanpur,

Li, J., Weber-Shirk, M., (2018). A Model for Stacked Rapid Sand Filters.

Logan, B. E., Hermanowicz, S. W., & Parker, A. S. (1987). A Fundamental Model for Trickling Filter Process Design. Journal (Water Pollution Control Federation), 59(12), 1029–1042.

Weber-Shirk, M.

Whiting, J., Shah, J., and Wang, T. (2016). Milli-sedimentation, Fall 2016.

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
* Needle valve borrowed from the teaching lab

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
    - Check that neither the outlet nor inlet holes are covered by the silicone piece. The silicone piece can slide around during this step.
    - Some screws may not slide in easily due to misalignment. To bypass this, loosely attach all ten screws, then tighten all for better alignment. Use Philips screwdriver.
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

First, if we were to model one constriction with the average velocity through the pores of the filter column.

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

<div class="alert alert-block alert-danger">
Where does the V_filter and A_filter come from? Be explicit.
</div>

With the current set up, the team calculates 0.36 cm of head loss ($\Delta H$). This is too small to be able to adjust with the height of the waste tube, and therefore the team must find another solution. The first possible solution is to use a row of sand grains and then model the constriction through multiple pores. This allows us to increase the flow rate through the flow cell and thus have a higher, more manageable head, which is difference between the height of the top of the head loss tubing and the height of the waste line in the lab.

```python
V_sand = 1.85*u.mm/u.s # average velocity through a filter
A_sand = 0.5*u.mm * 10*u.mm # area of flow cell
# Find the flow rate (Q)
Q_sand = V_sand*A_sand
Q_sand.to(u.ul/u.min)
# Find the head loss
deltah_sand = (128*L*mu*Q_sand)/(rho*g*m.pi*D**4)
deltah_sand.to(u.cm)
```
With these changes, $\Delta H$ is 7.26 cm, which is more manageable, but still very small. Since the waste line in the lab is coiled, there is a chance that air in the line can increase the head loss in the line, and therefore can complicate the design. Therefore, if after running experiments, we find that the flow rate is too slow, we will increase the length of the microtubing used to increase $\Delta H$. The team would use a 100 ft long roll of microtubing.

```python
# If we use an entire roll of micro tubing, the change in the head loss
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
