# suitOS
#
# 3 Dec 17, update 12 Feb 2019

# An open source OS for your space suit.  Because, when something goes wrong on Mars, you are going to have to fix it yourself.

V 0.1

It is not possible to define requirements for software without first going down the rabbithole of hardware:

Space suit

HIGH LEVEL REQUIREMENTS
- a spacesuit - a self-contained life support and mobility unit for a single adult human to be used in the pressure, temperature and velocity extremes outside earth's atmosphere. Mobility is provided by user effort. 
- extremely long service use - a user must be able to wear a suit without taking it off for up to two years. 
- simple to operate - an inexperienced operator should be able to learn everything needed to operate the suit in a one-day training session.
- simple to service - a user should be able to maintain their own suit (troubleshoot, order and replace components) while it is in service.  There should only be a limited number of exceptions.
- lifecycle ecosystem - parts, supplies, advanced service are available anywhere the suits are operated. 
- redundancy. A single failure should not be catastrophic to the user. For example, it should be possible to puncture the suit and survive; there should be a way to survive a cracked helmet; a power failure should not endanger the oxygen supply.
- quote from Macleans, Aug 2015: ' lightweight, reliable, safe and as comfortable if possible'.

ASSEMBLY
- shell
    - layers
          - micrometeorite protection (1) - need some research into appropriate membranes
          - abrasion and puncture resistant layer (2)
          - insulating layer mylar (10)
          - insulating layers fibreglass (10)
          - compression layer (1)
          - joint assist elements (May be part of the compression layer or bladder) ie constant- volume joint elements.
          - air bladder (1)
          - cooling layer (1)
          - heating layer (are insulating layers enough with body heat?)
          - skin contact layer (1)
     - stitching and cementing
- helmet
          - glass bubble
          - suit- helmet seal. If a torso-hatch is the design, this seal can be permanant, with reduced weight, manufacturing tolerances, air leakages from mechanical openings (all detachable and bearing-assisted elements leak air), maintenance and failure risks when compared to a removable helmet.  The downside is that suffocation risk exists when working in non-operational environment, and a ventilation failure occurs and the astronaut is not able to get outside fresh air in quickly. There are also considerations of heat and moisture buildup. The design of this extended-use suit means that these systems will always be functioning when the suit is donned. This will be a different kind of suit.
          - will something be worn on the head inside the helmet (hair retaining, earpiece-retaining, light and radiation-blocking, head-insulating) hair net, cap, toque? Mustn't be able to slide down and impair vision, breathing.
           - solar shielding
                - retracting visor. Can we design an externally-mounted, collapsing cover to provide sun visor protection as well as insulation.  (Think of the retracting helmet in Guardians)
- power generation
     - solar - hard surfaces - moulded solar cells on the helmet, other surfaces. 
     - solar- soft surfaces - why can't we invent a solar-cell fabric, where the individual fibres are collecting, generating electricity and conducting current themselves?  It may also provide some radiation protection, but there might need to be some fail-safes to dump induction-induced currents from solar-flares or other electromagnetic activity...
     - body heat (a way to capture this energy that would otherwise be wasted and a way to provide cooling to the suit at the same time). Small scavenger units
     - motion
     - electromagnetic
     - piezoelectric (mustn't add addition effort because the suit already has a certain nominal resistance to motion). How about something in the soles of the shoe or in the swing of the arm?
      - If power generation units are implanted at each of the arm, leg and torso joints, they can also measure flex (translated to equivalent total rad of rotation) that can be used as the unit of wear measure for the suit as a whole).
- power storage
- entry/egress
     - hatch
          - opening
          - internal volume needed for a front-entry suit.
          - hatch cover - inside-opening for a positive seal under pressure.
               - pass-through tubes with integral check valves. This includes disconnected-shutoff valves in the suit. Hoses should also have these at the disconnect end. In emergency situations, this could allow one suited person to assist another with a damaged life support unit by connect a single unit alternately to the other's suit. 
               - mini hatch - for passing in water and food for long-duration spacewalks and medication, other supplies. 
                - mount for reversible display unit
               - mount for suit CPU unit and power supply
               - The hatch cover can be replaced as a single, separate unit. This means that repairs can be made at an external repair facility. 
              - the hatch should include a transparent section so that the user can look out while inside the 'expanded internal space'
          - seal mechanism, ease of use  See patent for scuba/spacesuit with Velcro and silicone ring-inside-ring. 
- seals (hatch, helmet, hoses)
- internal space. In the event of extended suit use, it should be possible to expand the internal space of the suit (accordion-style?) and withdraw the head from inside the helmet.  This would allow for feeding and sleep with the head fully inside the torso section.
     - it should be possible to seal the helmet off from the torso in an emergency.
     - it should be possible to pull arms and legs out of the suit extremities and curl into a sleeping position inside the interior space to sleep, and to conserve body heat. (Arms and legs should also individually be sealable from the torso of the suit from the inside in the event of an emergency). Imagine a 26-month period of subsistance survival: there will be long periods of inactivity in order to reduce oxygen, food and water and electrical energy demand.  (This suit is going to need a great built-in entertainment system or an intravenous drug dispensing unit)
     - allow passing objects (including food and water) through the chest 'airlock'.
     - touch screen on the internal side of the chest airlock for hands-on computer interactions.
     - repairs to the inside of the suit and to the computer control unit. 
     - it should be possible to recline the sitting suit against a wall-like surface in a stable position before entering the sleeping configuration. Sitting should minimize the contact with the ground which will conduct away heat. 
     - it will be difficult to close the internal space once opened: air pressure will expand the space and resist attempts to close it.  Possible solutions:
           -  Straps around the outside?
           -  Straps or cam-action clips (like ski boots) to cinch closed and to adjust the allowable opening.   
           -  Accordion folds that will naturally return to their folded shape when de pressurized.
           -  partial hard, clamshell design for the cover?  This might allow for more force to be applied when closing the internal space. 

MOBILITY
- crawl
     - knee protection
     - hand protection
     - neck extension suit mobility
- walk unassisted
     - fall recovery (see crawl capabilities, lol)
     - boot
     - leg flexibility
     - hip flexibility
- walk, power assisted
- weightless travel, powered
     - EMU attachment (compatibility?)
     - design for powered mobility unit
- swimming
     - buoyancy control
     - surfaces necessary for swimming

OPERATING SYSTEM - SuitOS
- audio - sound delivered to the astronaut
     - speaker
     - headset
     - bone conduction?
- display screen - helmet. There are issues associated with vision and focussing up close to the display that need to be understood
- display screen - internal, reversible (transparent screen), hatch-mounted.  Could this include a keyboard?
- voice control
     - voice input
      - speech-to-text
       - time-stamped recording and text storage
- software plug-in design
- hardware plug-in design
- wiring and connectors (extreme-temperature rated)
     - board
     - wiring harness
     - batteries
     - sensors
     - headset
     - wireless hardware and antenna
- functionality
     - control of radio
     - control of life support
     - navigation (with or without gps available)
     - scientific note-taking (human notes as well as electronic observations)
     - environmental and status reporting
     - media control
     - delivery of warnings
     - status reporting

LIFE SUPPORT
- air - backpack O2 storage and CO2 conversion to O2 equipment
- water
- food
- radiation protection
- waste removal
     - urine
          - collection
          - extract water
          - extract heat
          - residue storage and disposal
     - solid waste
           - collection
           - a specific diet can reduce the amount of solid waste produced?  This will be pretty important in extremely-long duration excursions. 
           - extract water
           - residue storage and disposal
- warning systems
- reaction systems - life-support emergency systems

CONSUMABLES AND PARTS
- replacement parts for the entire suit.  There will be no component that cannot be replaced by the end-user.  Theoretically, it should then be possible to build a complete suit from parts.  Issues:
  - if all the extremities are attached to the suit to maintain simple suit integrity, the 'part' becomes significant. If the helmet is cracked, the entire bladder assembly must be replaced unless the connection (cementing, stitching and other fastening) can be redone and quality-checked by the end-user themselves. 
  - Outstanding Issue - version control and interchangeability of parts over time.

The remainder of items in this section are additional and complementary components that can be provided by the suit manufacturer or other suppliers. 

- water, bottled or pouched, insulated (to allow for exposure to the elements for a short period of time and to slow the thawing process when brought inside the suit - to avoid freezing the occupant), 250ml. Opening designed to also refill cooling liquid, and attaches to suit drinking unit or to water recovery unit. Bottle is designed to operate outside the suit and will freeze or boil along with the contents at whatever the ambient temperature happens to be without failing.  Bottles pass through mini-hatch.  Packed in satchels of 24.  Will need a mechanism to equalize pressure to suit before opening. The same mechanism must permit out-gassing (without releasing all of the liquid to space) when the bottle is outside the suit in a vacuum.
- protein bars, 250g. Some efficient formulation allowing for balanced nutrition at 3 bars per day at minimum energy expenditure to minimize the amount of waste produced by the astronaut. 
- Batteries, rechargeable, AA? Storage for all power uses. Can storage be improved for the same form factor. A single battery type should be used for all applications.
- urine containers (urine concentrate or crystals, since virtually all water is reclaimed?). It might be good to have urine frozen into concentrated pucks also.  There are scientists studying the possibility of evolving plants that consume urine as a food source?
- Solid waste puck - containers (membrane)
- there should be a way to recover and retain salt lost along with sweat so it can be reused.  Otherwise this will collect in the suit after a period of time. 
- suit patches, which might be stored on the outside and the inside of the suit (if the interior space problem is solved)
- medical supplies - patches, syringes, etc.
- cables- any cables that are user-replaceable
- hoses for air and water systems
- multifunctional sensor units
- headsets or earpieces, if used. 
- head coverings
- suit underwear
- odour control - will it ever be possible to clean the suit (remove dead skin cells, odours and stains while the occupant is inside?
- External inflatable bubble (tent?) with self-contained airlock which can be attached to the suit torso portal to allow the operator to exit the suit for periods of time for showers, sleep, medical attention, etc.  the tent will need multiple suit attachment points (as many as the tent is rated for).  In an emergency, a person can crash into the tent in a spacesuit and seal it from the inside. 

ENVIRONMENTAL SENSING
- pressure, internal, external
- temperature, internal, external (also, on the suit exterior, the exposed vs non-exposed temperature)
- humidity?
- CO2, CO, O2, N2 air composition
- vital signs (continuous) - ♡ rate, breathing rate, core body temperature, blood pressure
- monitoring of eye activity (blinking, movement, pupil dilation).  This could be done with video also.  Imagine a small unit (3mmX10mmX75mm) curved to fit the inside and attached to the helmet, above the eyeline with inward cameras on each end, outward camera or cameras toward the centre, a small inward-facing LED display unit (single line text) a microphone and other environment sensors, with Bluetooth connectivity (unless Bluetooth is not useful in a high-radiation environment). 
- motion (accelerometer) in 3 axis (If the data from multiple sensors is to be used in any coordinated way, there will need to be some kind of calibration process, because it will not be possible to mount the units perfectly relative to each other in a soft suit. 

BUTTON SENSOR - can we make a standard, button-sized multi-sensor with Bluetooth connectivity so that a suit may have multiple input points inside and outside?  In an emergency, other suits or the ship itself (if a suit wearer is inside a spaceship) can pick up vital sign signals from a suit. It would require integral power supply so that it might mean that a solar -cell coating or some other means of generating and storing energy will be necessary. 

Sensor Button Specs:
- temp (-200 to +400 C)
- pressure (vacuum to 10psi)
- accelerometer (x,y, z)
- gyroscope (x,y,z)
- magnetometer (x,y,z) - this might still be useful in space and many commercial sensor units include three items together (accelerate, gyro', mag)
- humidity
- O2
- CO2 and CO
- N2
- low resolution camera (still or video)
- solar cells for power
- Bluetooth for communication (low power)
- led indicators (ex. short flash at long interval for power indicator), configurable 
- storage - it may not be possible or practical to transmit all he time
- microphone? To transmit outside sounds when sealed in the suit.
- speaker to transmit sounds outside when sealed in the suit. 
- physical connector when it is not practical to use Bluetooth. Could we use fibre-optic communication cables and laser-LED?  Imagine that the suit has small transparent ports built into the suit through which optical signals can be transmitted to a receiver device - there will be environments where radio signal interference will prevent the use of radio devices.
- the device will need to meet all the same environmental requirements that are specified for the suit.

COMMUNICATION
- very long range communications 1000km - 1+ AU backpack optional item with its own power supply and external antenna. It may not be practical to deploy this as a backpack item. 
- long range communication 10km - 1000km. Backpack optional item with its own power supply. 
- short range communication 10m - 10km. Built into the suit. 
     - voice
     - data
 - near field communication 0-10m built into the suit. 
     - sensors and CPU exchange data autonomously
     - consideration: radiation and electromagnetic interference from things such as solar flares may interrupt these kinds of communications. The suit should be able to function without this sensor data
- physical data connection where radio communication is not possible. Can we use fibre-optic technology to avoid wires passing through the suit? A clear portal built into the suit should be enough to exchange data with a unit that is attached to the outside surface of the suit?
- asynchronous messaging (for email, recordings, most data and OS updates)
- connection to the internet

User controls
- gesture recognition (eye, head movements, hand movements) 
- voice recognition - a natural system for giving commands and receiving feedback from the suit
-  touch-screen display will be useful only if a suit interior space can be engineered.
- physical controls. Minimize physical controls? But, there should be a mechanical control for emergency oxygen.

Task-Specific Functionality
- travel
- tool handling and storage
- lifting and transporting
- mining
- survival - lifeboat mode

INTEGRATION
- industrial design
- component placement and integration
- build management
- manufacturing
- production testing
- packaging and shipping
- style and branding

SUPPORT
 - land rover model - spare parts can be ordered anywhere humans go.
 - technical support - zendesk type service?  Self-contained FAQ self service manual installed with the OS is the minimum complete solution for locations out of communication.
 - OS updates.  Life-safety software requires greater certainty of updates.  User may wish to have more control about what and when an update is installed.  Full OS update will likely require a period of downtime for the suit.  OS updates may also be necessary to solve immediate life-safety issues - the suit must remain operatational during these types of OS updates.
 - maintenance
    - physical patching 
 - spare parts order and delivery
 - user equipment for self-service maintenance

TESTING
 - terrestrial experiment program
     - arctic exploration
     - altitude
     - underground
     - crowd-sourced tests
          - materials tests
          - procedures tests and learning tests
         - distributed manufacturing tests?

- space- based experiment program
     - compare computer chips in space
     - mobility tests

- Testing regime
 - facilities
 - apparatus
 - sensors
 - documentation

MARKETING

Public
  - general public
 - target markets
Clients
Education

What distinguishes this suit from every other?
     - it is an endurance suit - designed for extremely long duration survival. How long for a single-use?  26 months wait for a Hohmann launch window +18 months travel is the worst-case for a rescue mission to arrive at Mars.  A near- closed loop for life-support systems: define a new standard for suit life support service standard: 100/10/1 (amp-h/l oxygen/l water per day)
     -  self-sustaining means:
           - air supply management
               - very low leakage - no mechanical joints which leak under pressure. Molecular escape is minimized with materials selection?
               - air recycling (scrubbers, is there some economical way to split CO2 into C and O2?)
               - a water hydrolysis unit can produce oxygen (and hydrogen) from water. This would require a substantial source of electricity.
               - 
           - water management 
               - capture and purification of water from urine and ventilation moisture
               - water supply can be replenished while suit is operational
               - cooling water can be drunk in an emergency?
               - a perfectly closed-loop water system is it not likely possible, but there must be a spec for maximum replenish - 1 l per 10 days?
          - power 
               - generation from several available sources
               - suit consumption must be very low so that the suit can be always be on
               - life support systems must continue to function in the event of an operating system reboot or failure. 
               - software sub-systems can be reloaded and restarted without rebooting the whole system  (In the same way that a Tcl proc can be redefined on the fly)
                - main computer board should be hot-swappable (this implies that there is a redundant board or socket for a second board?
          - food
               - the operator can eat and replenish suit food supply while the suit is operational
          -  wastes 
               - energy and water are recovered from wastes. wastes are removeable from the suit. 
                - cooling has to be rethought - Waste body heat energy can't just be vented to space. It must be captured and (1) stored or (2) converted to electricity.   We don't have great heat storage technologies.   
           - cooling
               - closed loop 
               - it should be possible to operate the suit without cooling for 10minutes in order to swap out pump or cooling unit parts (or refill/replace fluids). 
          - mental health
                - communication with the outside world
                - there must be breaks from work routine for sleep and personal activities (entertainment,etc)
                - feedback 
     - reliability - systems need to be ultra-reliable. This means:
           - simple as possible with the fewest moving parts
          - redundancy in systems (a part can be changed out while the system is in operation)
          - user-serviceable everything

     - it is economical - $1M target price. This probably doesn't include life support or consumables. 

Corporate Knowledge retention- there seems to have been a loss of how things were done at NASA wrt space-suits. This may be a product of corporate secrecy (knowledge is held with the contractor) rather than loss of the actual knowledge?  Whatever development scheme is chosen, a full suit spec, parts list and construction/ repair manual must be available to any user so that diagnosis and repair can occur anywhere by a remote suit technician or user themselves if necessary. 

Training
  - user certification (use, maintenance)
   - online procedures available when the suit is in operation (how-to videos and procedure checklist, etc.). Logs are automatically recorded when checklists are used, and follow-up maintenance is scheduled. 
   - service technician training
   - manufacturing technician training (systems, materials, stitching, etc..)

Proposals for new elements: process
 - integration committee for proposal
 - assigned to a program, if needed
 - impacting programs identified (sign off checklist)
  - element assigned to a target test and production build
  - time and cost assessment (decision takeaway for rfp for example)
  - design signoff
 - test signoff
 - dispute resolution process for design and signoff decisions

Blue Sky department
  - researches and solicits ideas for future developments
  - outreach program, idea competitions, etc.
  - submits proposals to the integration committee to get new features on the development schedule
  - should this be the department that responds to rfp proposals?

Museum program - activities for kids, travelling exhibition
     - technical element: constant volume joint
     - technical element: micrrometeorite protection
     - technical element: finger dexterity
     - technical element: project management (follow a change request from idea to production)
     - technical element: quality control in manufacturing
     - angle measurement


Movie industry  - suit rentals

REFERENCE INFORMATION

Constellation space suit rfp:  http://web.archive.org/web/20090730021056/http://prod.nais.nasa.gov/cgi-bin/eps/synopsis.cgi?acqid=121486

http://web.archive.org/web/20090730021659/http://prod.nais.nasa.gov/cgi-bin/eps/sol.cgi?acqid=121486

http://www.astronaut-glove.us

http://history.nasa.gov/spacesuits.pdf

http://www.cs.mcgill.ca/~rwest/wikispeedia/wpcd/wp/s/Space_suit.htm

http://www.nasa.gov/offices/ipp/innovation_incubator/centennial_challenges/astronaut_glove/jsc_ag_visit_gallery_asset_index.html

http://science.howstuffworks.com/space-suit.htm

http://www.wired.com/2012/07/new-york-spacesuits/

Established Companies
http://www.davidclark.com/Aerospace/aerospac.shtml
http://www.orbitaloutfitters.com
http://www.ilcdover.com

Spacecraft insulation requirements. http://ntrs.nasa.gov/archive/nasa/casi.ntrs.nasa.gov/19990047691.pdf

http://copenhagensuborbitals.com/history/technology-history/spacesuit/
http://pacificspaceflight.com/ - Cameron Smith leads a non-commercial enterprise to develop a suit.  He had a partnership wfor th Copenhagen Suborbitals for a period of time which gave him the opportunity to learn about suit integration with capsules.
http://www.lpi.usra.edu/meetings/LEA/presentations/PSS_presentations/eppler_NAC_Pres_7046.pdf


Mom and pop spacesuit projects
https://www.youtube.com/channel/UCup7MB9ZJJMGYd2NVkK_kJQ
https://www.youtube.com/channel/UCPzFMJIsp2fOQ_ic5a_zXTA
https://www.youtube.com/watch?v=2gaFXZWhp4k

Patents

Nasa technical reports
http://hdl.handle.net/2060/20140009568
http://hdl.handle.net/2060/20140013121
http://hdl.handle.net/2060/20130011327
Kevlar strength testing (specific example under varying strain rates): http://sem-proceedings.com/08s/sem.org-SEM-XI-Int-Cong-s002p02-High-Strain-Rate-Testing-Kevlar-49.pdf

Constant volume joint: http://strangeblue.iwarp.com/spacesuits/design.html

CLASSIFIED ADVERTISEMENTS

Abbreviations
  - ODNO
  - LEO

For sale: Rhino 3100 suit, used, size large w. long-range comms package. Only 500k rad on the odometer, original bladder, never breached. Pressure and leakage test results available. Rated for 720 hour continuous operation, at 1atm.  Used for surface operations, Ceres, low radiation, 500curies lifetime suit exposure,  Lots of serviceable life left. FOB Diemos station. Will arrange for transfer to LEO for freight costs only.  100k obo, willing to trade for Baikonur re-entry ticket. 

For sale: Hamilton EMU in LEO, 100 spacewalk hrs only,  no propellant or charge. Minor damage to port-side upper attitude control nozzle assembly. Easily replaced. Other than this, it's a perfectly serviceable unit!  FOB ISS. Please view bid documents at jpl.nasa.gov

For sale: Rhino 1100 suit, parts only, bladder compromised.  POD, clean at your cost. $20K. FOB Diemos station. 

For sale : Constellation ascent suit, MkI, worn once, received the Garn treatment, clean at your cost.  FOB Cameron County Spaceport, Texas. $10K.

For sale: set of suits, unused, from abandoned mission, FOB JSC.  Please view tender documents at Jpl.nasa.gov

Need spacesuit maintenance or replacement parts or consumables?  We provide a complete range of suit maintenance and refurbishing services, certified by all the major manufacturers). We are conveniently located at Diemos Station. We also do certification tests.   Suit Integrity Services Corp (SISC). Text us at +034 443 555 7848.

For sale:  4 Rhino 3100 suits.  Tested to extreme survival rating (26 months), all worn to approximately 1 million rad. Current occupant still resident in three suits (Mars One Expedition 12) not planetside.  You rescue the party, and you can have all the suits.  Email for interception orbital parameters at +022 354 555 4433.

For sale: Why buy used when you can have new?  We carry all major suppliers (ILC, Orbital Outfitters, DKNYSpace, Rhino, SpaceX, Roots Exo. Reasonable freight rates to any SpaceX scheduled destination.   Visit SpacesuitClearanceCentre.com or visit us at L5 Station. Trade-ins welcome.

For sale: Rhino 1100 suit, 50K rad, free. Micrometeoroid-impact compromised suit, for parts only.  FOB LEO. ODNO

	For sale:  Compression suit, good condition. No helmet or accessories. Will require custom re-fitting.  FOB Mars One base.  10,000$M. 

For sale: left-hand glove, size small, aluminium Universal Type 2 joint.  FOB New York.

For sale: Orlov's Used Suits, provider of refurbished, quality-certified used space suits.  We have a large selection of suits and repair parts in stock. All suits come with certification and financing. We also deal in museum-quality and collector suits. We deliver to your site.  On-the-spot financing available.  We also accept trades. Come visit us at orloviandeals.com.

RHINO TESTEMONIALS

Successful missions - from space tourists and industrial application users. 
Survival stories - endurance android  suit longevity 
Survival stories - Other challenging situations
Mcguyver stories (improvised repairs)
Responsive design - new features added, tested and deployed quickly.  Includes software and hardware. 

STANDARDS
1.  Any legitimate buyer will have a suit tested before making an offer. Standard tests: nominal pressure, air loss, Inspections of hatch integrity, seam integrity, helmet glass clarity and safety, thermal regulation tests.  Suit sertification will be like standard automobile certification today. 
2.  Suit ratings
       - power consumption
       - air consumption
       - single-use period, hours. 
       - target environment (usually a matter of how much air the suit has).
       - interconnectivity
3.  Wear measurements
        - the sum of rotation measurements of shoulder, elbow, waist, knee movements expressed in rad or equivalent full rotations.  Note that every movement has an equivalent return movement: is it necessary to count everything twice? 
        - it might be a good idea to have a separate measurement for the gloves, since that will likely have the most repetitive motion action. 
          - the pressure bladder wear indicator may be the total pressurized time in hours.
4.  Sizing

PRODUCT LINE
Rhino 1100 - launch/re-entry suit. Hookups for open loop connection. 10hours of life support attached to open-loop spacecraft systems. 30 minutes of life support from canister.  This must provide protection against a submerged splashdown. 

Rhino 2100 - zero-g spacewalk suit.  100 hours life support.  No suit mass restriction. 

Rhino 3100 - planetary suit, long endurance habitat suit.  1000hrs life support.  Mass restrictions. 

Rhino 4100 - long term survival rescue suit. Survival rated for maximum Earth-Mars Hohmann transfer rescue time: 20,000 hrs with in-service replenishment of gas, food, fuel, water. 

---
Conflicting modification on September 22, 2015 at 6:45:25 PM:
---
HIGH LEVEL REQUIREMENTS
- a spacesuit - a self-contained life support and mobility unit for a single adult human to be used in the pressure, temperature and velocity extremes outside earth's atmosphere. Mobility is provided by user effort. 
- extremely long service use - a user must be able to wear a suit without taking it off for up to two years. 
- simple to operate - an inexperienced operator should be able to learn everything needed to operate the suit in a one-day training session.
- simple to service - a user should be able to maintain their own suit (troubleshoot, order and replace components) while it is in service.  There should only be a limited number of exceptions.
- lifecycle ecosystem - parts, supplies, advanced service are available anywhere the suits are operated. 
- redundancy. A single failure should not be catastrophic to the user. For example, it should be possible to puncture the suit and survive; there should be a way to survive a cracked helmet; a power failure should not endanger the oxygen supply. 
- 

- quote from Macleans, Aug 2015: ' lightweight, reliable, safe and as comfortable if possible'.

ASSEMBLY
- shell
    - layers
          - micrometeorite protection (1) - need some research into appropriate membranes
          - abrasion and puncture resistant layer (2)
          - insulating layer mylar (10)
          - insulating layers fibreglass (10)
          - compression layer (1)
          - joint assist elements (May be part of the compression layer or bladder) ie constant- volume joint elements.
          - air bladder (1)
          - cooling layer (1)
          - heating layer (are insulating layers enough with body heat?)
          - skin contact layer (1)
     - stitching
     - cementing where appropriate
     - helmet
          - glass bubble
           - retracting visor. Can we design an externally-mounted, collapsing cover to provide sun visor protection as well as insulation.  (Think of the retracting helmet in Guardians)
          - suit- helmet seal. If a torso-hatch is the design, this seal can be permanant, with reduced weight, manufacturing tolerances, air leakages from mechanical openings (all detachable and bearing-assisted elements leak air), maintenance and failure risks when compared to a removable helmet.  The downside is that suffocation risk exists when working in non-operational environment, and a ventilation failure occurs and the astronaut is not able to get outside fresh air in quickly. There are also considerations of heat and moisture buildup. The design of this extended-use suit means that these systems will always be functioning when the suit is donned. This will be a different kind of suit.
          - will something be worn on the head inside the helmet (hair retaining, earpiece-retaining, light and radiation-blocking, head-insulating) hair net, cap, toque? Mustn't be able to slide down and impair vision, breathing.
           - solar shielding
- power generation
     - solar - hard surfaces - moulded solar cells on the helmet, other surfaces. 
     - solar- soft surfaces - why can't we invent a solar-cell fabric, where the individual fibres are collecting, generating electricity and conducting current themselves?  It may also provide some radiation protection, but there might need to be some fail-safes to dump induction-induced currents from solar-flares or other electromagnetic activity...
     - body heat (a way to capture this energy that would otherwise be wasted and a way to provide cooling to the suit at the same time). Small scavenger units
     - motion
          - electromagnetic
          - piezoelectric (mustn't add addition effort because the suit already has a certain nominal resistance to motion). How about something in the soles of the shoe or in the swing of the arm?
           -       If power generation units are implanted at each of the arm, leg and torso joints, they can also measure flex (translated to equivalent total rad of rotation) that can be used as the unit of wear measure for the suit as a whole). 
- power storage
- entry/egress
     - hatch
          - opening
          - internal volume needed for a front-entry suit.
          - hatch cover - inside-opening for a positive seal under pressure.
               - pass-through tubes with integral check valves. This includes disconnected-shutoff valves. Hoses should also have these at the disconnect end. In emergency situations, this could allow one suited person to assist another with a damaged life support unit by connect a single unit alternately to the other's suit. 
               - mini hatch - for passing in water and food for long-duration spacewalks and medication, other supplies. 
                - mount for reversible display unit
               - mount for suit CPU unit and power supply
               - The hatch cover can be replaced as a single, separate unit. This means that repairs can be made at an external repair facility. 
              - the hatch should include a transparent section so that the user can look out while inside the 'expanded internal space'
          - seal mechanism, ease of use  See patent for scuba/spacesuit with Velcro and silicone ring-inside-ring. 
- seals (hatch, helmet, hoses)
- internal space. In the event of extended suit use, it should be possible to expand the internal space of the suit (accordion-style?) and withdraw the head from inside the helmet.  This would allow for feeding and sleep with the head fully inside the torso section.
     - it should be possible to seal the helmet off from the torso in an emergency.  
     - it should be possible to pull arms and legs out of the suit extremities and curl into a sleeping position inside the interior space to sleep, and to conserve body heat. (Arms and legs should also individually be sealable from the torso of the suit from the inside in the event of an emergency). Imagine a 26-month period of subsistance survival: there will be long periods of inactivity In order to reduce oxygen, food and water and electrical energy demand.  (This suit is going to need a great built-in entertainment system or an intravenous drug dispensing unit)
     - allow passing objects (including food and water) through the chest 'airlock'. 
     - touch screen on the internal side of the chest airlock for hands-on computer interactions.
     - repairs to the inside of the suit and to the computer control unit. 
     - it should be possible to recline the sitting suit against a wall-like surface Ina stable position before entering the sleeping configuration. Sitting should minimize the contact with the ground which will conduct away heat. 
     - it will be difficult to close the internal space once opened: air pressure will expand the space and resist attempts to close it.  Possible features:
           -    Straps around the outside?
           -  Straps or cam-action clips (like ski boots) to cinch closed and to adjust the allowable opening.   
           - Accordion folds that will naturally return to their folded shape when de pressurized.
           - partial hard, clamshell design for the cover?  This might allow for more force to be applied when closing the internal space. 
            - need to see scientific calculations to estimate the reasonable force needed. 

MOBILITY
- crawl
     - knee protection
     - hand protection
     - neck extension suit mobility
- walk unassisted
     - fall recovery (see crawl capabilities)
     - boot
     - leg flexibility
     - hip flexibility
     -
- walk, power assisted
- weightless travel, powered
     - EMU attachment (compatibility?)
     - design for powered mobility unit
     -
- swimming
     - buoyancy control

OPERATING SYSTEM - SuitOS
- audio - sound delivered to the astronaut
     - speaker
     - headset
     - bone transmission?
- display screen - helmet
- display screen - internal, reversible (transparent screen), hatch-mounted.  Could this include a keyboard?
- voice control input ("show xx")
- software plug-in design
- hardware plug-in design
- wiring and connectors (extreme-temperature rated)
     - board
     - wiring harness
     - batteries
     - sensors
     - headset
     - wireless hardware and antenna
     -
- functionality
     - control of radio
     - control of life support
     - navigation (with or without gps available)
     - scientific note-taking (human notes as well as electronic observations)_
     - environmental and status reporting
     - media control
     - delivery of warnings
     -

LIFE SUPPORT
- air - backpack storage
- water
- food
- radiation protection
- waste removal
     - urine
          - collection
          - extract water
          - extract heat
          - residue storage and disposal
     - solid waste
           - collection
           - a specific diet can reduce the amount of solid waste produced?  This will be pretty important in extremely-long duration excursions. 
           - extract water
           - residue storage and disposal
- warning systems
- reaction systems - life-support emergency systems

CONSUMABLES AND PARTS
- replacement parts for the entire suit.  There will be no component that cannot be replaced. It should be possible to build a complete suit from parts.  Issues:
  - if all the extremities are attached to maintain. Simpler integrity, the 'part' becomes significant. If the helmet is cracked, the entire bladder assembly must be replaced. 
  - version control and interchangeability of parts over time.  

Remainder of items in this section are additional and complementary components that can be provided by the suit manufacturer or other suppliers. 
- water, bottled or pouched, insulated (to allow for exposure to the elements for a short period of time and to slow the thawing process when brought inside the suit - to avoid freezing the occupant), 250ml. Opening designed to also refill cooling liquid, and attaches to suit drinking unit or to water recovery unit. Bottle is designed to operate outside the suit and will freeze or boil along with the contents at whatever the ambient temperature happens to be without failing.  Bottles pass through mini-hatch.  Packed in satchels of 24.  Will need a mechanism to equalize pressure to suit before opening. 
- protein bars, 250g. Some efficient formulation allowing for balanced nutrition at 3 bars per day at minimum energy expenditure to minimize the amount of waste produced by the astronaut. 
- Batteries, rechargeable, AA? Storage for all power uses. 
- urine containers (urine concentrate or crystals, since virtually all water is reclaimed?). It might be good to have urine frozen into concentrated pucks also. 
- Solid waste puck - containers (membrane)
- there should be a way to recover and retain salt lost along with sweat so it can be reused. 
- medical supplies - patches, syringes, etc.
- cables- any cables that are user-replaceable
- multifunctional sensor units
- headsets or earpieces, if used. 
- head coverings
- suit underwear
- odour control - will it ever be possible to clean the suit (remove dead skin cells, odours and stains while the occupant is inside?
- External inflatable bubble (tent?) with self-contained airlock which can be attached to the suit torso portal to allow the operator to exit the suit for periods of time for showers, sleep, medical attention, etc.  the tent will need multiple suit attachment points (as many as the tent is rated for).  In an emergency, a person can crash into the tent in a spacesuit and seal it from the inside. 

ENVIRONMENTAL AND OCCUPANT SENSING
- pressure, internal, external
- temperature, internal, external (also, on the suit exterior, the exposed vs non-exposed temperature)
- humidity?
- CO2, CO, O2, N2 air composition
- vital signs (continuous) - ♡ rate, breathing rate, core body temperature, blood pressure
- monitoring of eye activity (blinking, movement, pupil dilation).  This could be done with video also.  Imagine a small unit (3mmX10mmX75mm) curved to fit the inside and attached to the helmet, above the eyeline with inward cameras on each end, outward camera or cameras toward the centre, a small inward-facing LED display unit (single line text) a microphone and other environment sensors, with Bluetooth connectivity (unless Bluetooth is not useful in a high-radiation environment). 
- motion (accelerometer) in 3 axis (If the data from multiple sensors is to be used in any coordinated way, there will need to be some kind of calibration process, because it will not be possible to mount the units perfectly relative to each other in a soft suit. 
- can we make a button-sized multi-sensor with Bluetooth connectivity so that a suit may have multiple input points?  In an emergency, other suits or the ship itself (if a suit wearer is inside a spaceship) can pick up vital sign signals from a suit. It would require integral power supply so that it might mean that a solar -cell coating or some other means of generating and storing energy will be necessary. 

COMMUNICATION
- very long range communications 1000km - 1million km. backpack optional item with its own power supply and external antenna. 
- long range communication 10km - 1000km. Backpack optional item with its own power supply. 
- short range communication 10m - 10km. Built into the suit. 
     - voice
     - data
 - near field communication 0-10m built into the suit. 
     - sensors and CPU exchanging data
     - consideration: radiation and electromagnetic interference from things such as solar flares may interrupt these kinds of communications. The suit should be able to function without this sensor data
- asynchronous messaging (for email, recordings, most data and OS updates)
- connection to the internet

User controls
 - voice recognition - a natural system for giving commands and receiving feedback from the suit
 - physical controls. Minimize physical controls? But, there should be an emergency oxygen control. 
-  touch-screen display will be useful only if a suit interior space can be engineered. 

Task-Specific Functionality
- travel
- tool handling and storage
- lifting
- mining

INTEGRATION
- industrial design
- component placement and integration
- build management
- manufacturing
- production testing
- packaging and shipping

SUPPORT
 - land rover model - spare parts can be ordered anywhere humans go.
 - technical support - zendesk type service?
 - OS updates
 - maintenance
    - patching
    -
 - spare parts order and delivery
 - user equipment for self-service maintenance

TESTING
 - terrestrial experiment program
     - arctic exploration
     - altitude
     - underground
     - crowd-sourced tests
          - materials tests
          - procedures tests and learning tests
         - distributed manufacturing tests?

- space- based experiment program
     - compare computer chips in space
     - mobility tests

- Testing regime
 - facilities
 - apparatus
 - sensors
 - documentation

MARKETING

Public
  - general public
 - target markets
Clients
Education

- Web-site
- Twitter

What distinguishes this suit from every other?
     - it is an endurance suit - designed for extremely long duration survival. How long for a single-use?  26 months wait for a Hohmann launch window +18 months travel is the worst-case for a rescue mission to arrive at Mars.  A near- closed loop for life-support systems: define a new standard for suit life support replenishment 100/10/1 (amps/l oxygen/l water per day)
     -  self-sustaining means:
           - air supply management
               - very low leakage - no mechanical joints which leak under pressure
               - air recycling (scrubbers, is there some economical way to split CO2 into C and O2?)
               - a water hydrolysis unit can produce oxygen (and hydrogen) from water. This would require a substantial source of electricity.
               - 
           - water management 
               - capture and purification of water from urine and ventilation moisture
               - water supply can be replenished while suit is operational
               - cooling water can be drunk in an emergency?
               - a perfectly closed-loop water system is it not likely possible, but there must be a spec for maximum replenish - 1 l per 10 days?
          - power 
               - generation from several available sources
               - suit consumption must be very low so that the suit can be always be on
               - life support systems must continue to function in the event of an operating system reboot or failure. 
               - software sub-systems can be reloaded and restarted without rebooting the whole system  (In the same way that a Tcl proc can be redefined on the fly)
                - main computer board should be hot-swappable (this implies that there is a redundant board or socket for a second board?
          - food
               - the operator can eat and replenish suit food supply while the suit is operational
          -  wastes 
               - energy and water are recovered from wastes. wastes are removeable from the suit. 
                - cooling has to be rethought - Waste body heat energy can't just be vented to space. It must be captured and (1) stored or (2) converted to electricity.   We don't have great heat storage technologies.   
           - cooling
               - closed loop 
               - it should be possible to operate the suit without cooling for 10minutes in order to swap out pump or cooling unit parts (or refill/replace fluids). 
          - mental health
                - communication with outside world
                - feedback 
     - reliability - systems need to be ultra-reliable. This means:
           - simple as possible with the fewest moving parts
          - redundancy in systems (a part can be changed out while the system is in operation)
          - user-serviceable everything

     - it is economical - $1M target price. This probably doesn't include life support unit and consumables for a month. Total $250K for a turn-key excursion?
     - 

Corporate Knowledge retention- there seems to have been a loss of how things were done at NASA wrt space-suits. This may be a product of corporate secrecy (knowledge is held with the contractor) rather than loss of the actual knowledge?  Whatever development scheme is chosen, a full suit spec, parts list and construction/ repair manual must be available to any user so that diagnosis and repair can occur anywhere by a remote suit technician or user themselves if necessary. 

Training
  - user certification (use, maintenance)
   - online procedures available when the suit is in operation (how-to videos and procedure checklist, etc.). Logs are automatically recorded when checklists are used, and follow-up maintenance is scheduled. 
   - service technician training
   - manufacturing technician training (systems, materials, stitching, etc..)

Proposals for new elements: process
 - integration committee for proposal
 - assigned to a program, if needed
 - impacting programs identified (sign off checklist)
  - element assigned to a target test and production build
  - time and cost assessment (decision takeaway for rfp for example)
  - design signoff
 - test signoff
 - dispute resolution process for design and signoff decisions

Blue Sky department
  - researches and solicits ideas for future developments
  - outreach program, idea competitions, etc.
  - submits proposals to the integration committee to get new features on the development schedule
  - should this be the department that responds to rfp proposals?

Museum program - activities for kids, travelling exhibition
     - technical element: constant volume joint
     - technical element: micrrometeorite protection
     - technical element: finger dexterity
     - technical element: project management (follow a change request from idea to production)
     - technical element: quality control in manufacturing
     -

Movie industry  - suit rentals

REFERENCE INFORMATION

Constellation space suit rfp:  http://web.archive.org/web/20090730021056/http://prod.nais.nasa.gov/cgi-bin/eps/synopsis.cgi?acqid=121486

http://web.archive.org/web/20090730021659/http://prod.nais.nasa.gov/cgi-bin/eps/sol.cgi?acqid=121486

http://www.astronaut-glove.us

http://history.nasa.gov/spacesuits.pdf

http://www.cs.mcgill.ca/~rwest/wikispeedia/wpcd/wp/s/Space_suit.htm

http://www.nasa.gov/offices/ipp/innovation_incubator/centennial_challenges/astronaut_glove/jsc_ag_visit_gallery_asset_index.html

http://science.howstuffworks.com/space-suit.htm
https://www.quora.com/What-are-all-the-factors-considered-in-the-design-of-a-space-suit/answer/Robert-Frost-1

http://www.wired.com/2012/07/new-york-spacesuits/
http://www.popsci.com/technology/article/2012-07/victorias-secret-wings-designer-giving-private-spaceflight-makeover


Established Companies
http://www.davidclark.com/Aerospace/aerospac.shtml
http://www.orbitaloutfitters.com
http://www.ilcdover.com

Spacecraft insulation requirements. http://ntrs.nasa.gov/archive/nasa/casi.ntrs.nasa.gov/19990047691.pdf

http://copenhagensuborbitals.com/history/technology-history/spacesuit/
http://pacificspaceflight.com/
http://www.lpi.usra.edu/meetings/LEA/presentations/PSS_presentations/eppler_NAC_Pres_7046.pdf


Mom and pop spacesuit projects
https://www.youtube.com/channel/UCup7MB9ZJJMGYd2NVkK_kJQ
https://www.youtube.com/channel/UCPzFMJIsp2fOQ_ic5a_zXTA
https://www.youtube.com/watch?v=2gaFXZWhp4k

Patents

Nasa technical reports
http://hdl.handle.net/2060/20140009568
http://hdl.handle.net/2060/20140013121
http://hdl.handle.net/2060/20130011327

Constant volume joint: http://strangeblue.iwarp.com/spacesuits/design.html

CLASSIFIED ADVERTISEMENTS

For sale: Rhino 3100 suit, used, size large w. long-range comms package. Only 500k rad on the odometer, original bladder, never breached. Pressure and leakage test results available. Rated for 720 hour continuous operation, at 1atm.  Used for surface operations, Ceres, low radiation, 500curies lifetime suit exposure,  Lots of serviceable life left. FOB Diemos station. Will arrange for transfer to LEO for freight costs only.  100k obo, willing to trade for Baikonur re-entry ticket. 

For sale: Hamilton EMU in LEO, 100 spacewalk hrs only,  no propellant or charge. Minor damage to port attitude control nozzle. Easily replaced. Other than this, it's a perfectly serviceable unit!  FOB ISS. Please view bid documents at jpl.nasa.gov

For sale: Rhino 1100 suit, parts only, bladder compromised.  Previous occupant deceased.  $5000.  FOB Diemos station. 

For sale : Constellation ascent suit, MkI, worn once, received the Garn treatment.  FOB Cameron County Spaceport, Texas. $10K.

For sale: set of suits, unused, from abandoned mission, FOB JSC.  Please view tender documents at Jpl.nasa.gov

Need spacesuit maintenance or replacement parts or consumables?  We provide a complete range of suit maintenance and refurbishing services, certified by all the major manufacturers). We are conveniently located at Diemos Station. We also do certification tests.   Suit Integrity Services Corp (SISC). Text us at +034 443 843 7848.

For sale:  4 Rhino 3100 suits.  Tested to extreme survival rating (26 months), all worn to approximately 1 million rad. Current occupant still resident in three suits (Mars One Expedition 12) not planetside.  You rescue the party, and you can have all the suits.  Email for interception orbital parameters at +022 354 789 4433.

For sale: Why buy used when you can have new?  We carry all major suppliers (ILC, Orbital Outfitters, DKNYSpace, Rhino, SpaceX). Reasonable freight rates to any SpaceX scheduled destination.   Visit SpacesuitClearanceCentre.com or visit us at L5 Station. Trade-ins welcome. 

For sale: Rhino 1100 suit, 50K rad, free. Micrometeoroid-impact compromised suit, for parts only.  FOB LEO. ODNO

For sale:  Compression suit, good condition. No helmet or accessories. Will require custom re-fitting.  FOB Mars One base.  $10,000. 

For sale: left-hand glove, size small, aluminium Universal Type 2 joint.  FOB New York.

For sale: Orlov's Used Suits, provider of refurbished, quality-certified used space suits.  We have a large selection of suits and repair parts in stock. All suits come with certification and financing. We also deal in museum-quality and collector suits. We deliver to your site.  On-the-spot financing available.  We also accept trades. Come visit us at orloviandeals.com.

RHINO TESTEMONIALS

Successful missions - from space tourists and industrial application users. 
Survival stories - endurance And suit longevity 
Survival stories - Other challenging situations
Mcguyver stories (improvised repairs)
Responsive design - new features added, tested and deployed quickly.  Includes software and hardware. 

STANDARDS
1.  Any legitimate buyer will have a suit tested before making an offer. Standard tests: nominal pressure, air loss, Inspections of hatch integrity, seam integrity, helmet glass clarity and safety, thermal regulation tests.  Suit sertification will be like standard automobile certification today. 
2.  Suit ratings
       - power consumption
       - air consumption
       - single-use period, hours. 
       - target environment (usually a matter of how much as the suit has). This will be 
       - interconnectivity
3.  Wear measurements
        - the sum of rotation measurements of shoulder, elbow, waist, knee movements expressed in rad or equivalent full rotations.  Note that every movement has an equivalent return movement: is it necessary to count everything twice? 
        - it might be a good idea to have a separate measurement for the gloves, since that will likely have the most repetitive motion action. 
4.  Sizing

PRODUCT LINE
Rhino 1100 - launch/re-entry suit. Hookups for open loop connection. 10hours of life support attached to open-loop spacecraft systems. 30 minutes of life support from canister.  This must provide protection against a submerged splashdown. 

Rhino 2100 - zero-g spacewalk suit.  100 hours life support.  No weight restriction. 

Rhino 3100 - planetary suit, long endurance habitat suit.  1000hrs life support.  Mass restrictions. 

Rhino 4100 - long term survival rescue suit. Survival rated for maximum Earth-Mars Hohmann transfer rescue time: 20,000 hrs with in-service replenishment of gas, food, fuel, water. 

---
Conflicting modification on September 22, 2015 at 6:45:25 PM:
---
HIGH LEVEL REQUIREMENTS
- a spacesuit - a self-contained life support and mobility unit for a single adult human to be used in the pressure, temperature and velocity extremes outside earth's atmosphere. Mobility is provided by user effort. 
- extremely long service use - a user must be able to wear a suit without taking it off for up to two years. 
- simple to operate - an inexperienced operator should be able to learn everything needed to operate the suit in a one-day training session.
- simple to service - a user should be able to maintain their own suit (troubleshoot, order and replace components) while it is in service.  There should only be a limited number of exceptions.
- lifecycle ecosystem - parts, supplies, advanced service are available anywhere the suits are operated. 
- redundancy. A single failure should not be catastrophic to the user. For example, it should be possible to puncture the suit and survive; there should be a way to survive a cracked helmet; a power failure should not endanger the oxygen supply. 
- 

- quote from Macleans, Aug 2015: ' lightweight, reliable, safe and as comfortable if possible'.

ASSEMBLY
- shell
    - layers
          - micrometeorite protection (1) - need some research into appropriate membranes
          - abrasion and puncture resistant layer (2)
          - insulating layer mylar (10)
          - insulating layers fibreglass (10)
          - compression layer (1)
          - joint assist elements (May be part of the compression layer or bladder) ie constant- volume joint elements.
          - air bladder (1)
          - cooling layer (1)
          - heating layer (are insulating layers enough with body heat?)
          - skin contact layer (1)
     - stitching
     - cementing where appropriate
     - helmet
          - glass bubble
           - retracting visor. Can we design an externally-mounted, collapsing cover to provide sun visor protection as well as insulation.  (Think of the retracting helmet in Guardians)
          - suit- helmet seal. If a torso-hatch is the design, this seal can be permanant, with reduced weight, manufacturing tolerances, air leakages from mechanical openings (all detachable and bearing-assisted elements leak air), maintenance and failure risks when compared to a removable helmet.  The downside is that suffocation risk exists when working in non-operational environment, and a ventilation failure occurs and the astronaut is not able to get outside fresh air in quickly. There are also considerations of heat and moisture buildup. The design of this extended-use suit means that these systems will always be functioning when the suit is donned. This will be a different kind of suit.
          - will something be worn on the head inside the helmet (hair retaining, earpiece-retaining, light and radiation-blocking, head-insulating) hair net, cap, toque? Mustn't be able to slide down and impair vision, breathing.
           - solar shielding
- power generation
     - solar - hard surfaces - moulded solar cells on the helmet, other surfaces. 
     - solar- soft surfaces - why can't we invent a solar-cell fabric, where the individual fibres are collecting, generating electricity and conducting current themselves?  It may also provide some radiation protection, but there might need to be some fail-safes to dump induction-induced currents from solar-flares or other electromagnetic activity...
     - body heat (a way to capture this energy that would otherwise be wasted and a way to provide cooling to the suit at the same time). Small scavenger units
     - motion
          - electromagnetic
          - piezoelectric (mustn't add addition effort because the suit already has a certain nominal resistance to motion). How about something in the soles of the shoe or in the swing of the arm?
           -       If power generation units are implanted at each of the arm, leg and torso joints, they can also measure flex (translated to equivalent total rad of rotation) that can be used as the unit of wear measure for the suit as a whole). 
- power storage
- entry/egress
     - hatch
          - opening
          - internal volume needed for a front-entry suit.
          - hatch cover - inside-opening for a positive seal under pressure.
               - pass-through tubes with integral check valves. This includes disconnected-shutoff valves. Hoses should also have these at the disconnect end. In emergency situations, this could allow one suited person to assist another with a damaged life support unit by connect a single unit alternately to the other's suit. 
               - mini hatch - for passing in water and food for long-duration spacewalks and medication, other supplies. 
                - mount for reversible display unit
               - mount for suit CPU unit and power supply
               - The hatch cover can be replaced as a single, separate unit. This means that repairs can be made at an external repair facility. 
              - the hatch should include a transparent section so that the user can look out while inside the 'expanded internal space'
          - seal mechanism, ease of use  See patent for scuba/spacesuit with Velcro and silicone ring-inside-ring. 
- seals (hatch, helmet, hoses)
- internal space. In the event of extended suit use, it should be possible to expand the internal space of the suit (accordion-style?) and withdraw the head from inside the helmet.  This would allow for feeding and sleep with the head fully inside the torso section.
     - it should be possible to seal the helmet off from the torso in an emergency.  
     - it should be possible to pull arms and legs out of the suit extremities and curl into a sleeping position inside the interior space to sleep, and to conserve body heat. (Arms and legs should also individually be sealable from the torso of the suit from the inside in the event of an emergency). Imagine a 26-month period of subsistance survival: there will be long periods of inactivity In order to reduce oxygen, food and water and electrical energy demand.  (This suit is going to need a great built-in entertainment system or an intravenous drug dispensing unit)
     - allow passing objects (including food and water) through the chest 'airlock'. 
     - touch screen on the internal side of the chest airlock for hands-on computer interactions.
     - repairs to the inside of the suit and to the computer control unit. 
     - it should be possible to recline the sitting suit against a wall-like surface Ina stable position before entering the sleeping configuration. Sitting should minimize the contact with the ground which will conduct away heat. 
     - it will be difficult to close the internal space once opened: air pressure will expand the space and resist attempts to close it.  Possible features:
           -    Straps around the outside?
           -  Straps or cam-action clips (like ski boots) to cinch closed and to adjust the allowable opening.   
           - Accordion folds that will naturally return to their folded shape when de pressurized.
           - partial hard, clamshell design for the cover?  This might allow for more force to be applied when closing the internal space. 
            - need to see scientific calculations to estimate the reasonable force needed. 

MOBILITY
- crawl
     - knee protection
     - hand protection
     - neck extension suit mobility
- walk unassisted
     - fall recovery (see crawl capabilities)
     - boot
     - leg flexibility
     - hip flexibility
     -
- walk, power assisted
- weightless travel, powered
     - EMU attachment (compatibility?)
     - design for powered mobility unit
     -
- swimming
     - buoyancy control

OPERATING SYSTEM - SuitOS
- audio - sound delivered to the astronaut
     - speaker
     - headset
     - bone transmission?
- display screen - helmet
- display screen - internal, reversible (transparent screen), hatch-mounted.  Could this include a keyboard?
- voice control input ("show xx")
- software plug-in design
- hardware plug-in design
- wiring and connectors (extreme-temperature rated)
     - board
     - wiring harness
     - batteries
     - sensors
     - headset
     - wireless hardware and antenna
     -
- functionality
     - control of radio
     - control of life support
     - navigation (with or without gps available)
     - scientific note-taking (human notes as well as electronic observations)_
     - environmental and status reporting
     - media control
     - delivery of warnings
     -

LIFE SUPPORT
- air - backpack storage
- water
- food
- radiation protection
- waste removal
     - urine
          - collection
          - extract water
          - extract heat
          - residue storage and disposal
     - solid waste
           - collection
           - a specific diet can reduce the amount of solid waste produced?  This will be pretty important in extremely-long duration excursions. 
           - extract water
           - residue storage and disposal
- warning systems
- reaction systems - life-support emergency systems

CONSUMABLES AND PARTS
- replacement parts for the entire suit.  There will be no component that cannot be replaced. It should be possible to build a complete suit from parts.  Issues:
  - if all the extremities are attached to maintain. Simpler integrity, the 'part' becomes significant. If the helmet is cracked, the entire bladder assembly must be replaced. 
  - version control and interchangeability of parts over time.  

Remainder of items in this section are additional and complementary components that can be provided by the suit manufacturer or other suppliers. 
- water, bottled or pouched, insulated (to allow for exposure to the elements for a short period of time and to slow the thawing process when brought inside the suit - to avoid freezing the occupant), 250ml. Opening designed to also refill cooling liquid, and attaches to suit drinking unit or to water recovery unit. Bottle is designed to operate outside the suit and will freeze or boil along with the contents at whatever the ambient temperature happens to be without failing.  Bottles pass through mini-hatch.  Packed in satchels of 24.  Will need a mechanism to equalize pressure to suit before opening. 
- protein bars, 250g. Some efficient formulation allowing for balanced nutrition at 3 bars per day at minimum energy expenditure to minimize the amount of waste produced by the astronaut. 
- Batteries, rechargeable, AA? Storage for all power uses. 
- urine containers (urine concentrate or crystals, since virtually all water is reclaimed?). It might be good to have urine frozen into concentrated pucks also. 
- Solid waste puck - containers (membrane)
- there should be a way to recover and retain salt lost along with sweat so it can be reused. 
- medical supplies - patches, syringes, etc.
- cables- any cables that are user-replaceable
- multifunctional sensor units
- headsets or earpieces, if used. 
- head coverings
- suit underwear
- odour control - will it ever be possible to clean the suit (remove dead skin cells, odours and stains while the occupant is inside?
- External inflatable bubble (tent?) with self-contained airlock which can be attached to the suit torso portal to allow the operator to exit the suit for periods of time for showers, sleep, medical attention, etc.  the tent will need multiple suit attachment points (as many as the tent is rated for).  In an emergency, a person can crash into the tent in a spacesuit and seal it from the inside. 

ENVIRONMENTAL AND OCCUPANT SENSING
- pressure, internal, external
- temperature, internal, external (also, on the suit exterior, the exposed vs non-exposed temperature)
- humidity?
- CO2, CO, O2, N2 air composition
- vital signs (continuous) - ♡ rate, breathing rate, core body temperature, blood pressure
- monitoring of eye activity (blinking, movement, pupil dilation).  This could be done with video also.  Imagine a small unit (3mmX10mmX75mm) curved to fit the inside and attached to the helmet, above the eyeline with inward cameras on each end, outward camera or cameras toward the centre, a small inward-facing LED display unit (single line text) a microphone and other environment sensors, with Bluetooth connectivity (unless Bluetooth is not useful in a high-radiation environment). 
- motion (accelerometer) in 3 axis (If the data from multiple sensors is to be used in any coordinated way, there will need to be some kind of calibration process, because it will not be possible to mount the units perfectly relative to each other in a soft suit. 
- can we make a button-sized multi-sensor with Bluetooth connectivity so that a suit may have multiple input points?  In an emergency, other suits or the ship itself (if a suit wearer is inside a spaceship) can pick up vital sign signals from a suit. It would require integral power supply so that it might mean that a solar -cell coating or some other means of generating and storing energy will be necessary. 

COMMUNICATION
- very long range communications 1000km - 1million km. backpack optional item with its own power supply and external antenna. 
- long range communication 10km - 1000km. Backpack optional item with its own power supply. 
- short range communication 10m - 10km. Built into the suit. 
     - voice
     - data
 - near field communication 0-10m built into the suit. 
     - sensors and CPU exchanging data
     - consideration: radiation and electromagnetic interference from things such as solar flares may interrupt these kinds of communications. The suit should be able to function without this sensor data
- asynchronous messaging (for email, recordings, most data and OS updates)
- connection to the internet

User controls
 - voice recognition - a natural system for giving commands and receiving feedback from the suit
 - physical controls. Minimize physical controls? But, there should be an emergency oxygen control. 
-  touch-screen display will be useful only if a suit interior space can be engineered. 

Task-Specific Functionality
- travel
- tool handling and storage
- lifting
- mining

INTEGRATION
- industrial design
- component placement and integration
- build management
- manufacturing
- production testing
- packaging and shipping

SUPPORT
 - land rover model - spare parts can be ordered anywhere humans go.
 - technical support - zendesk type service?
 - OS updates
 - maintenance
    - patching
    -
 - spare parts order and delivery
 - user equipment for self-service maintenance

TESTING
 - terrestrial experiment program
     - arctic exploration
     - altitude
     - underground
     - crowd-sourced tests
          - materials tests
          - procedures tests and learning tests
         - distributed manufacturing tests?

- space- based experiment program
     - compare computer chips in space
     - mobility tests

- Testing regime
 - facilities
 - apparatus
 - sensors
 - documentation

MARKETING

Public
  - general public
 - target markets
Clients
Education

- Web-site
- Twitter

What distinguishes this suit from every other?
     - it is an endurance suit - designed for extremely long duration survival. How long for a single-use?  26 months wait for a Hohmann launch window +18 months travel is the worst-case for a rescue mission to arrive at Mars.  A near- closed loop for life-support systems: define a new standard for suit life support replenishment 100/10/1 (amps/l oxygen/l water per day)
     -  self-sustaining means:
           - air supply management
               - very low leakage - no mechanical joints which leak under pressure
               - air recycling (scrubbers, is there some economical way to split CO2 into C and O2?)
               - a water hydrolysis unit can produce oxygen (and hydrogen) from water. This would require a substantial source of electricity.
               - 
           - water management 
               - capture and purification of water from urine and ventilation moisture
               - water supply can be replenished while suit is operational
               - cooling water can be drunk in an emergency?
               - a perfectly closed-loop water system is it not likely possible, but there must be a spec for maximum replenish - 1 l per 10 days?
          - power 
               - generation from several available sources
               - suit consumption must be very low so that the suit can be always be on
               - life support systems must continue to function in the event of an operating system reboot or failure. 
               - software sub-systems can be reloaded and restarted without rebooting the whole system  (In the same way that a Tcl proc can be redefined on the fly)
                - main computer board should be hot-swappable (this implies that there is a redundant board or socket for a second board?
          - food
               - the operator can eat and replenish suit food supply while the suit is operational
          -  wastes 
               - energy and water are recovered from wastes. wastes are removeable from the suit. 
                - cooling has to be rethought - Waste body heat energy can't just be vented to space. It must be captured and (1) stored or (2) converted to electricity.   We don't have great heat storage technologies.   
           - cooling
               - closed loop 
               - it should be possible to operate the suit without cooling for 10minutes in order to swap out pump or cooling unit parts (or refill/replace fluids). 
          - mental health
                - communication with outside world
                - feedback 
     - reliability - systems need to be ultra-reliable. This means:
           - simple as possible with the fewest moving parts
          - redundancy in systems (a part can be changed out while the system is in operation)
          - user-serviceable everything

     - it is economical - $1M target price. This probably doesn't include life support unit and consumables for a month. Total $250K for a turn-key excursion?
     - 

Corporate Knowledge retention- there seems to have been a loss of how things were done at NASA wrt space-suits. This may be a product of corporate secrecy (knowledge is held with the contractor) rather than loss of the actual knowledge?  Whatever development scheme is chosen, a full suit spec, parts list and construction/ repair manual must be available to any user so that diagnosis and repair can occur anywhere by a remote suit technician or user themselves if necessary. 

Training
  - user certification (use, maintenance)
   - online procedures available when the suit is in operation (how-to videos and procedure checklist, etc.). Logs are automatically recorded when checklists are used, and follow-up maintenance is scheduled. 
   - service technician training
   - manufacturing technician training (systems, materials, stitching, etc..)

Proposals for new elements: process
 - integration committee for proposal
 - assigned to a program, if needed
 - impacting programs identified (sign off checklist)
  - element assigned to a target test and production build
  - time and cost assessment (decision takeaway for rfp for example)
  - design signoff
 - test signoff
 - dispute resolution process for design and signoff decisions

Blue Sky department
  - researches and solicits ideas for future developments
  - outreach program, idea competitions, etc.
  - submits proposals to the integration committee to get new features on the development schedule
  - should this be the department that responds to rfp proposals?

Museum program - activities for kids, travelling exhibition
     - technical element: constant volume joint
     - technical element: micrrometeorite protection
     - technical element: finger dexterity
     - technical element: project management (follow a change request from idea to production)
     - technical element: quality control in manufacturing
     -

Movie industry  - suit rentals

STRATEGY- HOW DO I BUILD THIS BUSINESS?

This company will have to employ a reverse Apollo program:  where we funded a massive space program, and technologies spun off into consumer product, this business will have to start with related consumer products and develop them until they result in a space-certified suit.

Level 0 - Consumer products, off-the-shelf materials.
- Goals - learn manufacturing techniques, 
- Products
	- coolers
	- soccer balls
	- 
- 

Level 1 - Manufacturing

Level 2


Wireless communication between components inside and outside the suit may not work.  Glass fibre?


REFERENCE INFORMATION

Constellation space suit rfp:  http://web.archive.org/web/20090730021056/http://prod.nais.nasa.gov/cgi-bin/eps/synopsis.cgi?acqid=121486

http://web.archive.org/web/20090730021659/http://prod.nais.nasa.gov/cgi-bin/eps/sol.cgi?acqid=121486

http://www.astronaut-glove.us

http://history.nasa.gov/spacesuits.pdf

http://www.cs.mcgill.ca/~rwest/wikispeedia/wpcd/wp/s/Space_suit.htm

http://www.nasa.gov/offices/ipp/innovation_incubator/centennial_challenges/astronaut_glove/jsc_ag_visit_gallery_asset_index.html

http://science.howstuffworks.com/space-suit.htm
https://www.quora.com/What-are-all-the-factors-considered-in-the-design-of-a-space-suit/answer/Robert-Frost-1

http://www.wired.com/2012/07/new-york-spacesuits/
http://www.popsci.com/technology/article/2012-07/victorias-secret-wings-designer-giving-private-spaceflight-makeover


Established Companies
http://www.davidclark.com/Aerospace/aerospac.shtml
http://www.orbitaloutfitters.com
http://www.ilcdover.com

Spacecraft insulation requirements. http://ntrs.nasa.gov/archive/nasa/casi.ntrs.nasa.gov/19990047691.pdf

http://copenhagensuborbitals.com/history/technology-history/spacesuit/
http://pacificspaceflight.com/
http://www.lpi.usra.edu/meetings/LEA/presentations/PSS_presentations/eppler_NAC_Pres_7046.pdf


Mom and pop spacesuit projects
https://www.youtube.com/channel/UCup7MB9ZJJMGYd2NVkK_kJQ
https://www.youtube.com/channel/UCPzFMJIsp2fOQ_ic5a_zXTA
https://www.youtube.com/watch?v=2gaFXZWhp4k

Patents

Nasa technical reports
http://hdl.handle.net/2060/20140009568
http://hdl.handle.net/2060/20140013121
http://hdl.handle.net/2060/20130011327

Constant volume joint: http://strangeblue.iwarp.com/spacesuits/design.html

CLASSIFIED ADVERTISEMENTS

For sale: Rhino 3100 suit, used, size large w. long-range comms package. Only 500k rad on the odometer, original bladder, never breached. Pressure and leakage test results available. Rated for 720 hour continuous operation, at 1atm.  Used for surface operations, Ceres, low radiation, 500curies lifetime suit exposure,  Lots of serviceable life left. FOB Diemos station. Will arrange for transfer to LEO for freight costs only.  100k obo, willing to trade for Baikonur re-entry ticket. 

For sale: Hamilton EMU in LEO, 100 spacewalk hrs only,  no propellant or charge. Minor damage to port attitude control nozzle. Easily replaced. Other than this, it's a perfectly serviceable unit!  FOB ISS. Please view bid documents at jpl.nasa.gov

For sale: Rhino 1100 suit, parts only, bladder compromised.  Previous occupant deceased.  $5000.  FOB Diemos station.   

For sale : Constellation ascent suit, MkI, worn once, received the Garn treatment.  FOB Cameron County Spaceport, Texas. $10K.

For sale: set of suits, unused, from abandoned mission, FOB JSC.  Please view tender documents at Jpl.nasa.gov

Need spacesuit maintenance or replacement parts or consumables?  We provide a complete range of suit maintenance and refurbishing services, certified by all the major manufacturers). We are conveniently located at Diemos Station. We also do certification tests.   Suit Integrity Services Corp (SISC). Text us at +034 443 843 7848.

For sale:  4 Rhino 3100 suits.  Tested to extreme survival rating (26 months), all worn to approximately 1 million rad. Current occupant still resident in three suits (Mars One Expedition 12) not planetside.  You rescue the party, and you can have all the suits.  Email for interception orbital parameters at +022 354 789 4433.

For sale: Why buy used when you can have new?  We carry all major suppliers (ILC, Orbital Outfitters, DKNYSpace, Rhino, SpaceX). Reasonable freight rates to any SpaceX scheduled destination.   Visit SpacesuitClearanceCentre.com or visit us at L5 Station. Trade-ins welcome. 

For sale: Rhino 1100 suit, 50K rad, free. Micrometeoroid-impact compromised suit, for parts only.  FOB LEO. ODNO

For sale:  Compression suit, good condition. No helmet or accessories. Will require custom re-fitting.  FOB Mars One base.  $10,000. 

For sale: left-hand glove, size small, aluminium Universal Type 2 joint.  FOB New York.

For sale: Orlov's Used Suits, provider of refurbished, quality-certified used space suits.  We have a large selection of suits and repair parts in stock. All suits come with certification and financing. We also deal in museum-quality and collector suits. We deliver to your site.  On-the-spot financing available.  We also accept trades. Come visit us at orloviandeals.com.

RHINO TESTEMONIALS

Successful missions - from space tourists and industrial application users. 
Survival stories - endurance And suit longevity 
Survival stories - Other challenging situations
Mcguyver stories (improvised repairs)
Responsive design - new features added, tested and deployed quickly.  Includes software and hardware. 

STANDARDS
1.  Any legitimate buyer will have a suit tested before making an offer. Standard tests: nominal pressure, air loss, Inspections of hatch integrity, seam integrity, helmet glass clarity and safety, thermal regulation tests.  Suit sertification will be like standard automobile certification today. 
2.  Suit ratings
       - power consumption
       - air consumption
       - single-use period, hours. 
       - target environment (usually a matter of how much as the suit has). This will be 
       - interconnectivity
3.  Wear measurements
        - the sum of rotation measurements of shoulder, elbow, waist, knee movements expressed in rad or equivalent full rotations.  Note that every movement has an equivalent return movement: is it necessary to count everything twice? 
        - it might be a good idea to have a separate measurement for the gloves, since that will likely have the most repetitive motion action. 
4.  Sizing

PRODUCT LINE
Rhino 1100 - launch/re-entry suit. Hookups for open loop connection. 10hours of life support attached to open-loop spacecraft systems. 30 minutes of life support from canister.  This must provide protection against a submerged splashdown. 

Rhino 2100 - zero-g spacewalk suit.  100 hours life support.  No weight restriction. 

Rhino 3100 - planetary suit, long endurance habitat suit.  1000hrs life support.  Mass restrictions. 

Rhino 4100 - long term survival rescue suit. Survival rated for maximum Earth-Mars Hohmann transfer rescue time: 20,000 hrs with in-service replenishment of gas, food, fuel, water. 



