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

<img width="326" height="479" alt="Screenshot 2026-10-16 213540" src="https://github.com/user-attachments/assets/6b05d304-20e8-4053-9bab-1bf3a9cfe594" />



**search tree**

<img width="752" height="484" alt="Screenshot 2026-10-16 205708" src="https://github.com/user-attachments/assets/7253e3f3-31d6-4803-933f-74a0b8da8625" />



**Question 3**

**1. Route Evaluations (Path Cost Calculations)**

 **Route 1 (Northern Corridor via Nakuru and Eldoret):**
  
  Nairobi → Naivasha: 91 km,
  Naivasha → Nakuru: 75 km,
  Nakuru → Eldoret: 160 km,
  Eldoret → Kisumu: 125 km.
  
  Total Distance: 91+75+160+125 = 451 km

**Route 2 (Northern Corridor via Nakuru and Kericho):**

  Nairobi → Naivasha: 91 km,
  Naivasha → Nakuru: 75 km,
  Nakuru → Kericho: 107 km,
  Kericho → Kisumu: 80 km.
  
  Total Distance: 91+75+107+80=353 km

**Route 3 (Central Highlands via Thika, Nyeri, Nakuru and Kericho):**

  Nairobi → Thika: 47 km,
  Thika → Nyeri: 113 km,
  Nyeri → Nakuru: 167 km,
  Nakuru → Kericho: 107 km,
  Kericho → Kisumu: 80 km.
  
  Total Distance: 47+113+167+107+80= 514 km

**Route 4 (Central Highlands via Thika, Nyeri, Nakuru and Eldoret)**

   Nairobi → Thika: 47 km,
   Thika → Nyeri: 113 km,
   Nyeri → Nakuru: 167 km,
   Nakuru → Eldoret: 160 km,
   Eldoret → Kisumu: 125 km.

   Total Distance: 47+113+167+160+125= 612 km


**2. Optimal Path Determination**

  **Comparing the total path costs of all valid sequences from Nairobi to Kisumu:**
  
  Route 1: 451 km,
  Route 2: 353 km (Optimal Path),
  Route 3: 514 km,
  Route 4: 612 km.

The optimal path for the trailer is **Nairobi → Naivasha → Nakuru → Kericho → Kisumu**, with a minimum total path cost of 353 kilometers.


**Cool Team Photo**
<img width="948" height="421" alt="Screenshot 2026-10-16 201057" src="https://github.com/user-attachments/assets/e61df615-0685-41ee-b005-29f1d8d9b03d" />




