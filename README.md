## The Limerick Parklet
This elective sought to improve an existing parklet bench design to make it easier and faster to assemble. The parametric bench exists as a set of 155 18mm Marine Plywood CNC cut panels, each of a different size and shape, connected by threaded bars, secured by nuts and separated using CNC cut Marine Plywood spacers of 18mm and 12mm thickness to produce a 30mm space between each panel.  
As the design was before starting this project, the bench could only be assembled by approximately 3 people at a time and in one direction only. Due to the parametric nature of the bench, the threaded bars were each of a different length and needed to be cut. So an aim of the elective was to speed up the construction process and standardise the materials required as much as possible. 
  
![The complete bench](https://github.com/SAULdigitalfabrication/benchparklet/blob/master/16931111_1493991527280438_752524957_o.jpg)

### Cutting the Panels
  * **Elements Required** (_to create the entire bench_)
   1. Access to a CNC Router with a bed size of at least 1220x2440mm
   2. 26x 18mm 1220x2440mm Marine Plywood sheets
   3. 1x 12mm 1220x2440mm Marine Plywood sheet  
   
* Each plywood sheet must be loaded onto the CNC router bed and secured in place using at least one screw on each corner
  * ensure that these are no more than 20mm into the sheet as otherwise his will interfere with the drawing
* Open the file of the first sheet to be cut onto the relevant CNC cutting software (in our case we used VCarve PRO)
* Assign the correct material qualities, e.g. the 1220x2440mm sheet size and 18mm thickness
* The holes will be drilled first: On the drawing, select all holes to be drilled and assign them a drilling toolpath, with a depth of about 19mm (this ensures that the CNC will cut through the whole material) and select that the drill follows the inside path of the line
* Next the labelling numbers will be engraved, or pocketed, into the panels. Select all the numbers and assign them a pocketing toolpath with a depth of 9mm
* Lastly the Panels themselves will be cutout. Select the panel outlines and assign them a cutting profile. Again, assign the depth to be 19mm to ensure that the are entirely cut out and select that the drill follows the outside path of the line. When cutting out elements, rather than drilling or engraving, tabs must be added to make sure that the panels do not move as they are being cut out. Add about 4 tabs to each panel.
* Once all toolpaths have been assigned, save the file and open it in the relevant software that your CNC machine can read (In our case, ShopBot3).
* Correct the x,y and z co-ordinates of the CNC and then begin cutting the file.
  * Ensure that safety procedures are followed, e.g. Dust extraction is turned on and that safety goggles and ear protection is worn.


### Grouping of 10 
In order to make the construction easier and less time consuming, it was decided that the bench would be split into sections of 10 panels as this was considered a manageable size and weight for one person. By subdividing the bench into different sections, it allows each section to be preassembled off site so that on-site, simply attaching each section to each other is the only assembly required. It also allows many different versions of the bench to be created as only 8 or 12 sections need be constructed, rather than all 15. If the bench is to be dismantled, it can be broken into the groupings of ten once more and stored in these groupings.

### Cutting the Threaded Bar
  * **Elements Required**
   1. Access to an Angle Grinder
   2. 28x 1m long, 12mm diameter threaded bar  
     * These will be cut to produce 45x 485mm lengths and 42x 110mm lengths
   
In order for each set of ten panels to be able to be attached to each other, the threaded bars must be cut to 485mm lengths, this is just enough to attach the 10 panels and be able to secure a nut at each end. If it was any longer, it would disrupt the spacing between sets. Ensure safety precautions are employed with the use of the angle grinder, e.g. wear protective clothing and eye protection etc.. After the bars are cut, they must be filed down to ensure that the nut will fit correctly and that the elements will not be too sharp.  
23 bars will be cut to produce 45x 485mm lengths with approximately half a bar to spare. (2 lengths per 1m bar)
5 bars will be cut to produce 40x 110mm lengths. (8 lengths per 1m bar) the remaining 2 110mm lengths can be cut from the half bar spare from the 485mm cuts.

### Assembling a set of 10
  * **Elements Required**
   1. A Set of 10 Sequential Panels
   2. 27x 18mm Spacers
   3. 27x 12mm Spacers
   4. 3x 485mm long, 12mm diameter threaded bars
   5. 6x 12mm diameter nuts  

Once all the correct parts have been gathered follow this process for each set  
* Attach a nut to one end of three threaded bars
* Slot each of these bars through the holes on  the first panel, e.g. Panel 1, Panel 11, Panel 21, etc.,
  * Ensure that the number on the panel is facing outwards, e.g, not facing in the direction where the next panel will be placed.
* Place an 18mm and a 12mm spacer on each bar
* Slot the following panel onto the bars, e.g. Panel 2, Panel 12, Panel 22 etc.,
* Place an 18mm and a 12mm spacer on each bar once more
* Repeat this process until all ten panels have been attached together
* To close the set: Attach the remaining 3 nuts to the ends of the threaded bars

### Attaching each set of 10 to another
  * **Elements required**
   1. 2x An assembled set of 10 Panels
   2. 3x 110mm long, 12mm diameter threaded bars
   3. 3x 18mm Spacers
   4. 3x 12mm Spacers
   5. 6x 12mm diameter nuts
   
* Slot an 110mm length threaded bar through one of the linking holes (marked L) on the last panel of the first set, e.g. Panel 10, Panel 20, Panel 30 etc.,
* Attach a 12mm diameter nut to the end of the bar that is now between two panels, e.g. the end between panel 9 and 10, panel 19 and 20, panel 29 and 30 etc.,
* Repeat this process for all three linking holes
* Attach an 18mm and a 12mm spacer to the end of each of the 110mm bars sticking out of the end of the set of 10 panels
* Once this is down, position the second set of 10 panels so that each of the linking holes line up and so that the connection 100mm bars can be slotted through the first panel of the adjoining set.
  * Two people may be required to move both sets into place to ensure that they line up correctly
* Once the two sets are aligned and the bars now thread both panels, e.g. panels 10 and 11, panels 20 and 21, panels 30 and 31 etc., attach the remaining 3 nuts to the open end of each 110mm bar
* Repeat this process for your desired number of sets to complete the construction of the bench

### Total Schedule of Material and Projected Cost
**26x 18mm Marine Plywood Sheets =>** 26x €62.24 = _€1,618.24_ (IrishWire Products Pricing)  
**1x 12mm Marine Plywood Sheet =>** 1x €48.71 = _€48.71_ (IrishWire Products Pricing)  
**28x 1m long, 12mm diameter threaded bar =>** 28x  =  
**174x 12mm diameter nuts =>** 174x =  


### Hacking the Bench

The main aim of this elective was to take the existing bench design and adapt it to be assembled more easily. To save material we decided to try hack the old panels to fit the new system of grouped panels. The existing holes in the panels are not always common to 10 sequential panels so the location of new holes must be found and drilled.  
To do this each set of ten panels had to be overlaid on top of each other on AutoCAD using the old holes as base points as there is no point common to all panels. Some of the existing holes were retained but in some sets, new holes were needed.   
In order to determine an accurate location to drill new holes, templates were created to be used as drilling guides. These were lasercut out of 3mm MDF. Two bars were placed into two of the existing holes on the panels and then the templates were slotted on top. Any new holes required would then have their position identified using the templates and could be drilled using a hand drill. This procedure was repeated for each panel that required new holes to be drilled.  
Unfortunately some of the new holes were not drilled accurately and when each set was being assembled, the holes did not line up.  
When it went correctly, it took approximately 20 minutes to drill the new holes and assemble one group of ten panels.  
For those sets whose templates did not work as hoped, it is expected that it would take about 30 minutes to one hour to fix and redraw the templates, they will then need to be lasercut.
 * The first few templates were cut out of MDF, while, to reduce the cost send on materials, others were then cut out of grey card, which I think proved less effective as they moved around more when trying to drill the new holes, and the holes in the grey card which marked the position of the existing holes, were widened by the friction against the threaded bars, and I believe that inaccuracies arose here.

### The Platform
Another aim of this elective was to design a foundation system that would allow the bench to sit on different terrains and be adaptable to small slopes. Many different solutions were proposed and tested, some proved to be too costly while others, which attempted to integrate more into the structure of the bench, actually made the whole bench much too high off of the ground and too unstable. A 1:1 scale prototype for a basic platform with drainage channels and holes was designed and CNC cut out of 12mm plywood, which was actually much more stable than we anticipated. After speaking with our tutor it was recommended that we explore the technology of CNC routing more in the design but unfortunately a new prototype was not realised due to time constraints since we decided to prioritise the construction of the bench over the platform, and then ran into problems there. The ideal solution for the platform would have been one that adopted the same language as the bench design and consist of shallow strips of plywood laid on the ground with the grain on edge, if they are spaced close enough together it would still be comfortable to walk on and also the gaps between strips would deal with surface water pooling. It woud also deal with addressing the level change between the road and the kerb very well as the profile of the strips could have rounded edges (to reduce the tripping hazard) and the height of the strips can be easily adjusted to match the kerb height.

### Conclusion
The research and proposals of the elective worked in theory, but the failure to finish the assembly of the bench proved that it was more difficult to carry out than expected. We believe that the system will still work, as exemplified by the correctly assembled pieces, but perhaps not enough care was taken in the creation of the templates and in the execution of drilling the new holes. If the files had been more organised and the holes correctly labelled, this may have helped a considerable amount
