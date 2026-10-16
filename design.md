**QUESTION 1: PEAS FRAMEWORK AND 5 AGENT ENVIRONMENTS**
PEAS stands for Performance measure, Environment, Actuators and Sensors. It describes what an intelligent agent should achieve, where it operates, how it acts and how it gathers information.

  a.)Performance measure: Deliver cargo safely to its destination, minimize total travel distance and fuel consumption, obey     traffic rules, avoid accidents, minimize delays and protect the cargo.
  
  b.)Environment: Kenya's highway network, including roads, towns, cities, junctions, other vehicles, pedestrians, weather       conditions, road signs, traffic lights and obstacles.
  
  c.)Actuators:	Steering system, accelerator, brakes, gear controls, indicators, headlights, horn and communication systems.
  
  d.)Sensors:	GPS, cameras, radar, LiDAR, speedometer, proximity sensors, fuel-level sensors, engine sensors and digital maps

**AGENT ENVIRONMENTS**
  
  
   Observability dimension:                   (Partially observable):      The trailer cannot directly observe every aspect of the road.                                                                  Other vehicles may obstruct its view, and some hazards may be                                                                  outside sensor range.

  Determinism or Stochastic:         (Stochastic):               The results of actions are not always predictable because of                                                                  traffic, weather, road conditions and the behavior of other                                                                   road users.

  Episodic or sequential:            (Sequential):               Each driving decision affects later decisions, including the                                                                   route taken, fuel consumption, arrival time and safety.

  Static or dynamic:                 (Dynamic):                  The environment changes while the trailer is operating.                                                                       Vehicles move, traffic conditions change and obstacles can                                                                     appear.

  Single-agent or multi-agent:        (multi-agent):              The self-driving trailer operates alongside other vehicles,                                                                   drivers, pedestrians and potentially other autonomous                                                                         vehicles. Their actions influence the trailer's decisions                                                                      and its ability to reach its destination safely

**Question 2**

**Directed Graph**

<img width="338" height="430" alt="Screenshot 2026-10-16 205059" src="https://github.com/user-attachments/assets/a4e81f2f-ff41-4014-b4eb-a1274f81d841" />


**search tree**

<img width="752" height="484" alt="Screenshot 2026-10-16 205708" src="https://github.com/user-attachments/assets/7253e3f3-31d6-4803-933f-74a0b8da8625" />



**Question 3**

**1. Route Evaluations (Path Cost Calculations)**

 **Route 1 (Northern Corridor via Nakuru and Eldoret):**
  
  Nairobi → Naivasha: 76 km,
  Naivasha → Nakuru: 74 km,
  Nakuru → Eldoret: 157 km,
  Eldoret → Kisumu: 115 km.
  
  Total Distance: 76 + 74 + 157 + 115 = 422 km

**Route 2 (Northern Corridor via Nakuru and Kericho):**

  Nairobi → Naivasha: 76 km,
  Naivasha → Nakuru: 74 km,
  Nakuru → Kericho: 85 km,
  Kericho → Kisumu: 80 km.
  
  Total Distance: 76+74+85+80=315 km

**Route 3 (Central Highlands via Thika, Nyeri, and Nakuru):**

  Nairobi → Thika: 45 km,
  Thika → Nyeri: 110 km,
  Nyeri → Nakuru: 115 km,
  Nakuru → Kericho: 85 km,
  Kericho → Kisumu: 80 km.
  
  Total Distance: 45+110+115+85+80=435 km

**2. Optimal Path Determination**

  **Comparing the total path costs of all valid sequences from Nairobi to Kisumu:**
  
  Route 1: 422 km,
  Route 2: 315 km (Optimal Path),
  Route 3: 435 km.

The optimal path for the trailer is **Nairobi → Naivasha → Nakuru → Kericho → Kisumu**, with a minimum total path cost of 315 kilometers.




