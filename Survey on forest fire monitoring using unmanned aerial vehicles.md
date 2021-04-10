### Introduction
- With human activity increasing around the globe and drastic climate change, it is estimated that the occurrence of wildfire will increase 3-5 times within the next century [7]
- Traditionally, forest fires have been detected using _human patrol, smoke detectors, thermal sensors, watch towers equipped with optoelectric cameras, satellite imagery and manned aircraft_ [9] [10]
- These methods are insufficient to provide a real-time update to the firefighters for strategic and tactical planning.
- While manned aircraft can confirm fire and provide real-time updates with full accuracy, it is extremely dangerous for the pilots [11]. 
  - In constrast, UAVs can access high-risk zones, provide an over-the-hill view, perform night time missions with no risk of human lives. 
  - Furthermore, UAVs can hover over a spot, have high spatial and spectral resolution and they can provide continuous fire information to the firefighters for ideal suppresion planning.
  - These advantages of UAVs can overcome the limitations of traditional fire detection methods and have significant contribution in early detection and suppression of wildfire
 
 #### General UAV based forest fire monitoring system
 - A single UAV or a fleet of cooperative UAVs fly over high-risk zones in a forest and capture images using their onboard optoelectronic sensors.
 - The captured visual or infrared images will be processed on board or through a ground station and identify the presence or absence of fire.
 - If a fire is confirmed then an alarm is sent to the nearby fire stations along with the location and size of the fire.

#### Use of UAVs in forets fire monitoring operations
- During the firefighting operations, the area under effect can get seriously covered by smoke, leading to impaired vision, polluted air and hazardous conditions [15]
  > During the forest fires, the area under effect can get seriously covered by smoke, leading to impaired vision, polluted air, and hazardous conditions. Sending firefighters in such environment is dangerous and risky. Instead, UAVs can be deployed quickly and they can be used to capture images from low altitudes and trace smoke plumes to locate the fire location, providing valuable information for firefighters to understand and assess the situation. 
- Past UAV aiding firefighter projects
  - Although the first use of unmanned aircraft for forest fire monitoring was reported in 1961, it did not generate much interest until 1996 when a fixed wing aircraft, Firebird 2001 carrying TV and FLIR camera, was used to aid firefighters in Montana, USA [11][19]
  - NASA Ames Research Center and United States Forest Service (USFS) [20] (2003): conducted the fire response experiment (FiRE) project using fixed-wing aircraft. The purpose of this experiment was to check the feasibility of incorporating UAVs into fire monitoring operations and they were able to achieve all the set goals using the UAV. 
  - University of South Florida [21] (2004): proposed a method of forest fire detection using UAVs and set up a small experiment that achieved 90% detection accuracy using their method
  - European commission COMET project [22, 23, 24] (2004, 2003, 2012): start researching on forest fire monitoring using unmanned system. Over the years, their work expanded and became an operational system with three UAVs (two fixed wing and one rotary wing) carrying visual, infrared and fire sensor. 
  - University of Michigan [26] (2011): used a 6 foot fixed-wing UAV equipped with an infrared camera and ran field tests under a heat-contrast environment to validate their proposed fire monitoring method. 
  - Prescribed burns in southeastern USA [27][28] (2016): fixed wing and rotary wing UAVs were used for data acquisition through visible and LWIR images 
  - Western Virginia [29] (2012): Zephyr UAS demonstrated the advantage of using UAv in firefighting scenario
  - Szendo fire department [30] (2006): UAVs are very useful for forest fire monitoring
  - Esposito et al. [31]: presented preliminary results of a fixed-wing mini UAV (equipped with camera, NIR and thermal infrared cameras).
  - Pastor et al. [15]: Sky-eye, an unmanned helicopter equipped with visual and thermal infrared cameras to provide fire and hotspot information to the ground station
  - Dutch FireFly project [32]: used helicopter to provide firefighters real-time aerial video for fire suppression assistance through two exercised fire scenarios
- Recent developments in UAV on fire monitoring:
  > Recent researches of UAVs in the fire monitoring problem concentrates on integrating the machine learning algorithms to enhance the fire detection accuracy 
  - Concordia university [13, 33, 34]: used a fire simulator and a quadrotor equipped with visual and infrared cameras to develop a fores fire monitoring system
  - Lee et al. [1]: burned tree branches to imitate forest fire scenario and captured videos of it using a UAV
  - Chen et al. [39]: proposed a forest fire monitoring method and tested their framework using a six-rotor UAV and fire simulator
  - Zhao et al. [38]: developed a forest monitoring fixed-wing UAV
  - Wardihani et al. [40]: conducted a prescribed fire experiment in Indonesia
- From reviewing the existing reports on UAV based forest fire monitoring system, we can divide the term "monitoring" into three separate tasks:
  - confirming the presence of fire
  - providing important information related to the existing fire
  - predicting future behavior for rapid containment and suppression
 
#### Forest fire detection using UAVs
- The first task of an ideal UAV assisted forest fire monitoring scheme involves patrolling potential high-risk zones
- high-risk zones: can be assessed through recent lightning, volcanic or human activities. 
- Data acquired by the patrolling UAVs needed 
