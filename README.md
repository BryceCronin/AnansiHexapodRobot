
# Anansi Hexapod Robot
The Anansi Hexapod Robot is a 3D-printable hexapod frame based on 24 Dynamixel MX-28 Robot Actuators. The design is radially symmetrical and offers mounting points for custom electronic components to be added.

### License
- Anansi Hexapod **Models** by Bryce Cronin (http://cronin.cloud) is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/ "Creative Commons Attribution 4.0 International License").

- Anansi Hexapod **Renders** © 2020 by Bryce Cronin (http://cronin.cloud) is licensed under a [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/ "Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License").

## Components
### Components to 3D-Print
Unless where otherwise noted, it is recommended to 3D-print these components with normal print settings. 
| Image | Component | Required | Quantity | Notes |
| --------- | --------- | -------- | -------- | ----- |
| ![](Renders/Individual%20Components/Body_Connector.png) | Body_Connector  | ✔️ Required | 6 | - |
| ![](Renders/Individual%20Components/Body_CoreSpacers.png) | Body_CoreSpacers | ❌ Optional  | 6 | Optional, but recommended to prevent overtightening of the *M6 60mm Bolts*. |
| ![](Renders/Individual%20Components/Body_BoardMount.png) | Body_BoardMount | ❌ Optional  | 4 | This component can be added to the *Body_Connector* component to provide mounting points for electronics, however it is recommended to design a custom component to suit your exact needs. |
| ![](Renders/Individual%20Components/Core_PartA.png) | Core_PartA  | ✔️ Required | 1 | May require high-precision 3D-print settings to allow for the *M6 Hex Nuts* to be inserted into this component. |
| ![](Renders/Individual%20Components/Core_PartB.png) |   | ✔️ Required | 1 | May require high-precision 3D-print settings to allow for this component to be inserted into Core_PartA.|
| ![](Renders/Individual%20Components/Leg_ConnectorA.png) | Leg_ConnectorA  | ✔️ Required | 24 | Print this piece so that it looks like a *'U'* shape when looking from above, this will make it flexible so that motors can be inserted and removed. Alternatively, you can edit the model to extend the oval shape to the very edge so that motors can be inserted and removed without a great amount of flexibility in the printed model.  |
| ![](Renders/Individual%20Components/Leg_ConnectorB.png) | Leg_ConnectorB  | ✔️ Required | 18 | 18 are required, but 24 are recommended if aesththetics are important to you. If you use 24, attach the extra components between the *Leg_ConnectorB* component and the *spacers* in each foot.|
| ![](Renders/Individual%20Components/Leg_BearingMount.png) | Leg_BearingMount  | ✔️ Required | 24 | - |
| ![](Renders/Individual%20Components/Leg_BearingSpacer.png) | Leg_BearingSpacer  | ✔️ Required | 24 | Print with high precision - it should fit snuggly into the recess on the Dynamixel motor. If it doesn't fit snuggly, consider designing a custom version of this component with your 3D-printers settings in mind.|
| ![](Renders/Individual%20Components/Leg_Horncap.png) | Leg_HornCap  | ❌ Optional | 24 | This component is purely for aesthetic reasons. It's optional, but will make your hexapod look nice and symetrical. |
| ![](Renders/Individual%20Components/Foot_PartA.png) | Foot_PartA  | ✔️ Required | 6 | - |
| ![](Renders/Individual%20Components/Foot_PartB.png) | Foot_PartB  | ✔️ Required | 6 | - |

### Other Components
You'll need to purchase or fabricate the below components yourself. I've included links to the exact products I used for illustrative purposes only, I recommend finding similar products that are available for purchase in your region. Consider 3D-printing the *Core_PartA* and *Body_Connector* components in order to test the sizing of screws and bolts before purchasing.
| Component | Required | Quantity | Notes |
| --------- | -------- | -------- | ----- |
| Dynamixel MX-28 Robot Actuators | ✔️ Required | 24 | These come in a few different models (T, AT, R, AR, etc). <br>*https://www.trossenrobotics.com/dynamixel-mx-28-robot-actuator.aspx*|
| 8mm x 22mm x 7mm Bearings | ✔️ Required | 24 | *https://www.ebay.com.au/itm/282588304295*|
| Rubber Feet | ❌ Optional | 6 | 20mm x 20mm so that they fit the bottom of *Foot_PartB*. <br>*https://www.jaycar.com.au/rubber-feet-large-stick-on-pk-20/p/HP0822* |
| M**3** **6**mm Screws| ✔️ Required | 168 | *https://www.jaycar.com.au/m3-x-6mm-steel-screws-pk-200/p/HP0401* |
| M**3** **10**mm Screws| ✔️ Required | 72 | *https://www.jaycar.com.au/m3-x-10mm-steel-screws-pk-200/p/HP0404* |
| M**3** **15**mm Screws| ✔️ Required | 24 | *https://www.jaycar.com.au/m3-x-15mm-steel-screws-pk-200/p/HP0407* |
| M**3** Hex Nuts | ✔️ Required | 72 |  *https://www.jaycar.com.au/m3-steel-nuts-pk-200/p/HP0426* |
| M**3** Washers | ❌ Optional | 192 | Highly recommended, but not required. These are used where the 3D-printed components are screwed into the Dyanamixel motors and the servo horns.<br>*https://www.jaycar.com.au/3mm-steel-flat-washers-pk-200/p/HP0431*|
| M**3** **10**mm Spacers | ✔️ Required | 48 | These are required for assembling the 6 feet. Alternatively, you could design and 3D-print a custom foot component that doesn't require spacers. Spacers were used so that the feet could be easily extended or shortened using different sized spacers. <br>*https://www.jaycar.com.au/m3-x-10mm-tapped-metal-spacers-pk100/p/HP0901*|
| M**6** **20**mm Bolts | ✔️ Required | 6| *https://www.bunnings.com.au/pinnacle-m6-x-20mm-yellow-zinc-hi-tensile-hex-bolt-and-nut-10-pack_p2320083*  |
| M**6** **60**mm Bolts | ✔️ Required | 6| *https://www.bunnings.com.au/pinnacle-m6-x-60mm-stainless-steel-hex-head-bolts-and-nuts-6-pack_p0087642* |
| M**6** Hex Nuts | ✔️ Required | 14 | I recommend using lock-nuts for 6 (out of the 14) of these to connect the 6 *Body_Connector* components together.<br>*https://www.bunnings.com.au/pinnacle-m6-x-60mm-stainless-steel-hex-head-bolts-and-nuts-6-pack_p0087642* |
| M**6** Washers | ❌ Optional | 18 | Recommended, but not required.<br>*https://www.bunnings.com.au/zenith-1-4-m6-zinc-plated-machine-washer-46-pack_p2420281* |
| Glue | ✔️ Required | 1 | A small amount of superglue is required for assembling the *core*.|

## Assembly Instructions
Refer to images of the completed hexapod for assistance in assembly process.
1. **3D-Print components:** 3D-print the required components. You can find advice for 3D-printing individual components in the 'notes' column in the 'Components to 3D-Print' table above.<br><br>
2. **Assemble the core:** Insert 8 *M6 Hex Nuts* into *Core_PartA*. Ensure the nuts are properly centred to the holes, then secure the nuts in place using glue. Then, glue *Core_PartB* into the cutout of *Core_PartA*.<br><br>
3. **Assemble the body:** Connect the interlocking wings of the 6 *Body_Connector* pieces so that they form a hexagon. Use 1 *M6 20mm bolt*, 2 *M6 washers*, and 1 *M6 hex nut* to connect each piece together.<br><br>
4. **Connect the body to the core:** Slide *M6 60mm bolt* through 1 *M6 washer*, then through a *Body_Connector* piece, then through a *Body_CoreSpacers* piece, then screw into the assembled core.<br><br>Repeat this for each side of the hexagon. Go slow, do not overtighten.<br><br>
5. **Prepare bearing assembly:** Insert a *Leg_BearingSpacing* into each Dynamixel motor (on the opposite side of the horn), they should fit snuggly. Then insert a *bearing* into each *Leg_ConnectorA* component, they should fit snuggly.<br><br>
6. **Attach motors:** Follow this step for each motor. Ensure the included servo horn is attached firmly to the motor, then slide it into a *Leg_ConnectorA* piece. <br><br>Next, slide an included servo horn screw through a *Leg_BearingMount* piece, then through *Leg_ConnectorA* (and the *bearing*), then through *Leg_BearingSpacer* (which is attached the the motor), then screw it into the motor.<br><br>On the other side of the motor, use the smaller included servo horn screws to screw through *Leg_ConnectorA* and into the servo horn in each of the 3 holes. If you want, you can then screw a *Leg_HornCap* on top to make it look pretty.<br><br>
7. **Leg assembly:** Now that each motor is attached to a *Leg_ConnectorA* piece, connect 6 of them to the 6 *Body_Connector* pieces using 4 *M3 15mm screws* and 4 *M3 washers* each. (This is also where you add the *Body_BoardMount* pieces if you've chosen to use them.)<br><br>Then, connect another *Leg_ConnectorA* piece (and its attached motor) at a 90 degree angle to the *Leg_ConnectorA* piece that is now attached to the body. Do this using 4 *M3 6mm screws* and 4 *M3 hex nuts*. This step might be difficult if you're using a bulky screwdriver.<br><br>Using 4 *M3 6mm screws* and 4 *M3 hex nuts*, connect 2 *Leg_ConnectorB* pieces together - repeat this 6 times. Then, attach each of these to the end of each limb using 4 *M3 10mm screws* and 4 *M3 washers*<br><br>Add another motor to the end of each limb using 4 *M3 10mm screws* and 4 *M3 washers*. Attach a *Leg_ConnectorB* piece to the *Leg_ConnectorA* piece at the end of the limb using 4 *M3 6mm screws* and 4 *M3 hex nuts*.<br><br>Attach the final motor to the end of the limb using 4 *M3 10mm screws* and 4 *M3 washers*. <br><br>
8. **Assemble the feet:** Use 8 *M3 6mm screws* and 4 *M3 10mm spacers* to attached *Foot_PartA* to *Foot_PartB*. Then, add the rubber foot to the bottom of *Foot_PartB*. Next, use 8 *M3 6mm screws* and 4 *M3 10mm spacers* to attach the foot to the end of the limb.<br><br>Repeat this step for each foot.<br><br>
9. You now have a completed hexapod. If you've had trouble following these instructions, please refer to fully assembled pictures. Errors may be present in these instructions, but it should hopefully be intuitive to figure out the solution.<br><br>Feel free to get in touch with me (Bryce Cronin) via LinkedIn if you have any questions.
