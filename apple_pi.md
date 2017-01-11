
# A.P.P.L.E.: P.I.

Automated Personal Production, Low Effort: Planetary Interaction


## Goals

This guide will help you design a PI chain for:

 * A single character
 * In null-sec or wormholes
 * That earns 15-30 million isk / day
 * With only 10 minutes of effort / day


## Overview

 1. Find a friendly system that can generate one of the simple P4s.
 2. Create four extraction planets that export P1s.
 3. Create one factory planet that takes P1s and creates the P4.
 4. Every day, export from extractors, export P4s from factory, import P1s to factory.
 5. Once every two weeks or so, order the final P1 ingredient from a trade hub and import it to the factory.


## Skill Requirements

**Minimum:**

 * Remote Sensing I
 * Command Center Upgrades IV
 * Planetology IV
 * Advanced Planetology I
 * Interplanetary Consolidation IV

**To improve isk / hour:**

 * Command Center Upgrades V
 * Advanced Planetology IV

**To skip importing the final P1 from a trade hub:**

 * Interplanetary Consolidation V


## First Time Setup

### Select P4 and Planets

  1. Download the [PI Material Diagrams v1.4](http://www.hst-soft.de/korai/EVE_PI_Diagrams_v1_4.pdf).
  2. Look up a friendly system on [Dotlan](http://evemaps.dotlan.net), then click Celestials. For the purposes of this guide I will use [U-HVIX](http://evemaps.dotlan.net/system/U-HVIX/celestials).
  3. Look at the PI material diagram for one of the simple P4s:
      * Nano-Factory
      * Organic Mortar Applicators
      * Sterile Conduits

  To create the P4, you need 8 "paired" Raw Materials and 1 stand-alone Raw Material. Each of our 4 extraction planets will extract 2 of the paired Raw Materials.
     
  4. Ignoring the Raw Material used directly in the High-Tech Production Plant, select 4 extraction planets, which will extract 2 Raw Materials apiece.
     
     For example, in U-HVIX, I decide to build Organic Mortar Applicators. I need to extract the following:
      * Noble Metals
      * Base Metals
      * Heavy Metals
      * Non-CS Crystals
      * Aqueous Liquids
      * Ionic Solutions
      * Noble Gas
      * Reactive Gas
     
  By comparing U-HVIX's planet list with the material diagram, a few decisions are made for me. Reactive Gas is only available from Gas planets, so U-HIVX V will extract that. I do not have a Plasma planet, so Noble Metals will have to come from U-HIVX II or III. Non-CS Crystals only come from Lava planets, so U-HVIX I will extract that.
     
     With a little deduction, I end up with the following extraction planet decisions:
     
     <table>
      <tr>
        <th>Planet</th>
        <th>Raw Materials</th>
      </tr>
      <tr>
        <td>U-HVIX I (Lava)
        </td>
        <td>
          Non-CS Crystals<br/>
          Heavy Metals
        </td>
      </tr>
      <tr>
        <td>U-HVIX III (Barren)
        </td>
        <td>
          Base Metals<br/>
          Noble Metals
        </td>
      </tr>
      <tr>
        <td>U-HVIX V (Gas)
        </td>
        <td>
          Reactive Gas<br/>
          Noble Gas
        </td>
      </tr>
      <tr>
        <td>U-HVIX VI (Storm)
        </td>
        <td>
          Aqueous Liquids<br/>
          Ionic Solutions
        </td>
      </tr>
     </table>
     
     If you cannot find a combination of extraction planets to extract all 8 paired Raw Materials, try a different simple P4 or a different system.
     

  5. Select a Temperate or Barren planet to be your factory planet.
  6. Buy a Command Center for each planet type.


### Build Extraction Planets

For each extraction planet, build 2 clusters of extractors, basic industrial facilities, and a launchpad.

  1. Undock with the command centers in your cargohold, and if you are not tethered, warp to a citadel so you're tethered.
  2. View the planet in planet mode.
  3. Click Build, expand Command Centers, then click <Planet Type> Command Center.
  4. Place it anywhere on the planet, then click Submit.
  5. Click the Command Center.
  6. In the Command Center window, click the circular Upgrade button, click the maximum upgrade level, then click Submit.
  
  **Build the facilities.**
  
  7. Click Scan, then select the first item this planet will extract.
  8. Drag the slider until there are only a few pockets of white displayed on the surface.
  9. Click Build, expand Extractor Control Units, then click <Planet Type> Extractor Control Unit.
  10. Place the extractor control unit so that its outline covers as many white spots as possible.
  11. Click Submit.
  12. Expand Spaceports, click <Planet Type> Launchpad, then place it directly next to the extractor control unit.
  13. Expand Processors, then click <Planet Type> Basic Industry Facility.
  14. If you have Command Center Upgrades IV, place 3 Basic Industry Facilities next to the Launchpad. If you have Command Center Upgrades V, place 4 Basic Industry Facilities next to the Launchpad.
  15. Expand Planetary Links, then click Create Link and connect the Extractor Control Unit and the Basic Industry Facilities to the Launchpad.
  16. Click Submit.
  
  You should now have a cluster that looks like this:
    
  <img src="http://i.imgur.com/xjZ4wB5.png" alt="5 facilities clustered around a Launchpad" />
    
  **Route the materials.**
  
  17. Click a Basic Industry Facility, click Schematics, find the Basic Commodity produced by this Raw Material, then click Install.
  18. Repeat for each Basic Industry Facility, then click Submit.
  19. Click the Extractor, click Products, then click the extracted Raw Material.
  20. Click Create Route, then select the Launchpad and click Create Route.
  21. Click the Launchpad, click Routes, then click the Raw Material with the type "Incoming".
  22. Click Create Route, then select a Basic Industry Facility and click Create Route.
  23. Repeat Steps 21 and 22 until the Raw Material is routed to all the Basic Industry Facilities.
  24. Click a Basic Industry Facility, click Products, then click the produced Basic Commodity.
  25. Click Create Route, then select the Launchpad and click Create Route.
  26. Click Submit.
  27. Repeat steps 7 through 26 for the other Raw Material this planet will extract.
  
  If you have Interplanetary Consolidation V, set up the final Raw Material extraction facility the same way, but both sets of facilities should produce the final Basic Commodity instead of 2 separate Basic Commodities.

### Select and Build a Factory Planet

  1. Undock with the command center in your cargohold, and if you are not tethered, warp to a citadel so you're tethered.
  2. View the planet in planet mode.
  3. Click Build, expand Command Centers, then pick <Planet Type> Command Center.
  4. Place it anywhere on the planet, then click Submit.
  5. Click on the Command Center.
  6. In the Command Center window, click the circular Upgrade button, click the maximum upgrade level, then click Submit.
     
  The goal of this planet is to build a three-tiered factory system. Here's my layout:
     
  <img src="http://i.imgur.com/Rbiff3G.png" alt="16 p2 factories, 4 p3 factories, 1 p4 factory, with 3 launchpads and 1 storage facility." />
  
  7. Click Build, expand Processors, then click <Planet Type> Advanced Industry Facility.
  8. Place sixteen Advanced Industry Facilities, in four groups of four, below the Command Center. These are the P2 creation facilities.
  9. Expand Spaceports, then click <Planet Type> Launchpad.
  10. Place two Launchpads on the same line as the Command Center, nestled between 8 of the P2 creation facilities.
  11. Click Build, expand Processors, then click <Planet Type> Advanced Industry Facility.
  12. Place four Advanced Industry Facilities, in two groups of two, above the Command Center. These are the P3 creation facilities.
  13. Click Storage Facilities, then click <Planet Type> Storage Facility.
  14. Place one Storage Facility above the P3 creation facilities.
  15. Click Build, expand Processors, then click <Planet Type> High Tech Production Plant.
  16. Place one High Tech Production Plant above the Storage Facility.
  13. Expand Spaceports, then click <Planet Type> Launchpad.
  14. Place one Launchpad above the High Tech Production Plant.
  15. Click Submit.
  
  **Build the links.**
  
  16. Expand Planetary Links, then click Create Link.
  17. Connect all sixteen P2 Advanced Industry Facilities to their nearest launchpad. A launchpad should only service 8 P2 Advanced Industry Facilities.
  18. Connect all four P3 Advanced Industry Facilities to their nearest launchpad. A launchpad should only service 2 P3 Advanced Industry Facilities.
  19. Connect all four P3 Advanced Industry Facilities to the Storage Facility.
  20. Connect the P4 High Tech Production Plant to the Storage Facility.
  21. Connect the P4 High Tech Production Plant to the top launchpad.
  22. Click Submit to save the links.
  
  **Set up schematics.**
  
  23. Click a P2 Advanced Industry Facility, click Schematics, select a Refined Commodity, then click Install.
  24. Set the same Refined Commodity schematic for each set of four P2 Advanced Industry Facilities. It is best to put the P2s that will be combined into a P3 on the same side. For example, I set Mechanical Parts and Consumer Electronics on the left side of my U-HVIX factory and I set Coolant and Oxides on the right side of my U-HVIX factory.
  25. Click a P3 Advanced Industry Facility, click Schematics, select a Specialized Commodity, then click Install.
  26. Set the same Specialized Commodity schematic for each set of two P3 Advanced Industry Facilities. For example, I set Robotics on the left side of my U-HVIX factory and Condensates on the right side of my U-HVIX factory.
  27. Click the P4 High Tech Production Plant, click Schematics, select a Advanced Commodity, then click Install.
  28. Click Submit.
  
  **Set up the Routes.**
  
  29. Click a P2 Advanced Industry Facility, click Products, then click the produced Refined Commodity.
  30. Click Create Route, then select the Launchpad connected to the industry facility, then click Create Route.
  31. Repeat for each P2 Advanced Industry Facility. All P2s should output into the connected Launchpad.
  32. Click the Launchpad into which you just output the P2 routes. Click Routes, then click one of the two Refined Commodities with the type "Incoming".
  33. Click Create Route, then select one of the two P3 Advanced Industry Facilities, and click Create Route.
  34. Repeat steps 32 and 33 until all Refined Commodities are routed from the Launchpads into the P3 Advanced Industry Facilities.
  29. Click a P3 Advanced Industry Facility, click Products, then click the produced Refined Commodity.
  30. Click Create Route, then select the Storage Facility connected to the Industry Facility, then click Create Route.
  31. Repeat for each P3 Advanced Industry Facility. All P3s should output into the connected Storage Facility.
  32. Click the Storage Facility into which you just output the P3 routes. Click Routes, then click one of the two Specialized Commodities with the type "Incoming".
  33. Click Create Route, then select the High Tech Production Plant, and click Create Route.
  34. Repeat steps 32 and 33 for the other Specialized Commodity.
  35. Click the High Tech Production Plant, click Products, then click the produced Advanced Commodity.
  36. Click Create Route, then select the Storage Facility connected to the Industry Facility, then click Create Route.
  37. Click Submit.

### Start the First Extraction Cycles

For each extraction planet:

  1. View the extractor planet in planet mode.
  2. Click the Extractor, then click Survey for Deposits. 
  3. In the surveying window, set the Extraction area size to 23 hours.
  4. Add and move extractor head units until the Program Output is greater than 18,000 units (if you have three basic facilities) or greater than 24,000 units per hour (four basic facilities).
  5. Click Install Program.
  6. Repeat steps 1 through 5 for the other Extractor on the planet, then click Submit.
  7. Dock up and grab yourself a cold beverage.

### Export and Import the First Extraction Cycles

  1. Wait at least one hour after the first extraction cycle has started. The extraction planet Launchpads will have some Basic Commodities (P1s) in them.
  2. View the extractor planet in planet view mode.
  3. Click the Launchpad, click Launch, then drag the Basic Commodity (P1) to the left pane.
  4. Click the "<Planet Type> Launchpad <ID>" list, then click the other launchpad.
  5. Drag the other Basic Commodity (P1) to the left pane.
  6. Click Transfer.
  7. Repeat steps 1 through 6 for each extraction planet.
  8. Change into an Epithal or hauling ship, then undock.
  9. Warp to each extraction planet's customs office, then drag the contents of the customs office into your cargohold.
  10. Warp to the factory planet customs office.
  11. Drag the contents of your cargohold into the customs office.
  12. Warp back to a citadel to re-tether.
  13. View the factory planet in planet view mode.
  14. Double-click the left Launchpad.
  15. Drag only the Basic Commodities (P1s) required for the left side's Advanced Industrial Facilities, then click Transfer. For example, my U-HVIX left-side factories require Reactive Metals, Precious Metals, Toxic Metals, and Chiral Structures.
  16. Double-click the right Launchpad.
  17. Drag only the Basic Commodities (P1s) required for the right side's Advanced Industrial Facilities, then click Transfer. For example, my U-HVIX right-side factories require Water, Electrolytes, Oxidizing Compound, and Oxygen.

### Import the Final Basic Commodity

The final Basic Commodity needs to be imported to the top launchpad. If you have Interplanetary Consolidation V, this will come from a fifth extractor planet. Otherwise, it will need to be imported from a trade up.

  1. Fill your cargohold with the final Basic Commodity (P1). In this example, I ship Bacteria down from Jita, fill my cargohold, and undock.
  2. Warp to the factory planet customs office.
  3. Drag the contents of your cargohold into the customs office.
  4. View the factory planet in planet view mode.
  5. Double-click the top Launchpad.
  6. Drag as much of the final Basic Commodity into the Launchpad, then click Transfer.
  7. Return the contents of the customs office to your cargohold.
  8. Warp back to a citadel to re-tether.
  9. Click the top Launchpad, click Storage, then click the Basic Commodity.
  10. Click Create Route, then select the High Tech Production Planet, then click Create Route.
  11. Click Submit.

You now have a completely working PI chain!

## Daily Routine

The hard work is over; let's loot and restart your profit machine!

  1. Grab your trusty hauler.
  2. Undock and tether at a citadel in the system.
  3. For each extraction planet, launch all Basic Commodities (P1s) to the customs office.
  4. For each extraction planet, restart all extractors. Set the extraction cycle however you want, but make sure you either have greater than 18,000 units per hour, or greater than 24,000 units per hour (depending on 3 or 4 Basic Industrial Facilities).
  5. View the factory planet in planet view mode.
  6. Click the Storage Facility, click Storage, click Expedited Transfer, then click any launchpad with free storage.
  7. Drag the Advanced Commodity to the "To Be Transferred" pane, then click Execute Transfer.
  8. Launch the Advanced Commodity to the customs office.
  10. Warp to each of the extraction planet customs offices, and loot them.
  11. Warp to the factory planet customs office, and loot the Advanced Commodity.
  12. Drag the Basic Commodities to the customs office.
  13. Warp to a citadel to re-tether.
  14. Import the Basic Commodities to their respective Launchpads.

