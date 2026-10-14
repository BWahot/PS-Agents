**QUESTION 1: PEAS FRAMEWORK AND 5 AGENT ENVIRONMENTS**
PEAS stands for Performance measure, Environment, Actuators and Sensors. It describes what an intelligent agent should achieve, where it operates, how it acts and how it gathers information.

  a.)Performance measure: Deliver cargo safely to its destination, minimize total travel distance and fuel consumption, obey     traffic rules, avoid accidents, minimize delays and protect the cargo.
  
  b.)Environment: Kenya's highway network, including roads, towns, cities, junctions, other vehicles, pedestrians, weather       conditions, road signs, traffic lights and obstacles.
  
  c.)Actuators:	Steering system, accelerator, brakes, gear controls, indicators, headlights, horn and communication systems.
  
  d.)Sensors:	GPS, cameras, radar, LiDAR, speedometer, proximity sensors, fuel-level sensors, engine sensors and digital maps

**AGENT ENVIRONMENTS**
  |EniIronment Dimension|          |Classification|          |explanation|
  
   Observability                   Partially observable      The trailer cannot directly observe every aspect of the road.                                                                  Other vehicles may obstruct its view, and some hazards may be                                                                  outside sensor range.

  Determinism or Stochastic         Stochastic               The results of actions are not always predictable because of                                                                  traffic, weather, road conditions and the behavior of other                                                                   road users.

  Episodic or sequential            Sequential               Each driving decision affects later decisions, including the                                                                   route taken, fuel consumption, arrival time and safety.

  Static or dynamic                 Dynamic                  The environment changes while the trailer is operating.                                                                       Vehicles move, traffic conditions change and obstacles can                                                                     appear.

  Single-agent or multi-agent        multi-agent              The self-driving trailer operates alongside other vehicles,                                                                   drivers, pedestrians and potentially other autonomous                                                                         vehicles. Their actions influence the trailer's decisions                                                                      and its ability to reach its destination safely
