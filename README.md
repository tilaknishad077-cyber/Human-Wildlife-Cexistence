Smart Early Warning Network for Human–Wildlife Coexistence

A technology-based approach to safer villages and wildlife protection

Developed for the WILDHACK Wildlife Coexistence Ideathon 2026, organised at BIT Ballarpur in collaboration with Tadoba Andhari Tiger Reserve.

---

1. Why We Chose This Problem

Living near a forest is part of everyday life for many communities around Tadoba. However, when a tiger or leopard enters nearby farmland or a village, people may not get enough time to react safely.

Farmers working in their fields, villagers walking at night, and families living close to forest boundaries can all face risks. Often, information about animal sightings spreads through phone calls or word of mouth, which may not reach everyone on time.

We started thinking about one simple question:

What if people could receive a warning before they unknowingly came close to a wild animal?

That question inspired us to develop the Smart Early Warning Network. Our aim is to help villagers stay informed, support forest officers with timely information, and reduce situations that could put both people and wildlife at risk.

Our proposed target is to deliver alerts within 30 seconds of a confirmed detection during the pilot. This is a goal we want to test in real conditions, not a result we have already achieved.

2. Our Proposed Solution

We have divided the project into two phases so that we can begin with a practical prototype and gradually expand the system.

Phase 1: A Simple Village Safety App

The first phase focuses on making wildlife-related information easier to share and access.

- Three language options: Marathi, Hindi and English, so more people can use the application comfortably.
- One-tap SOS: Allows a person to request help and share their location with forest officers, subject to available connectivity and location permissions.
- Wildlife sighting reports: Villagers can submit a photo, location and other relevant details about an animal sighting.
- Sighting map: Helps display reported sightings and identify areas where additional attention may be needed.
- Safety information: Provides simple guidance on what people should do when a wild animal is spotted nearby.

The main idea is to keep the application straightforward, especially for people who may not be familiar with complicated technology.

Phase 2: Smart Hardware for Village Safety

The second phase introduces physical devices that can help detect possible wildlife activity and warn nearby communities.

1. Solar-powered acoustic sensor nodes

These nodes would be installed near selected farm boundaries or other suitable locations. They would monitor sounds and vibrations that may indicate unusual activity. LoRa radio could then transmit small alert messages to nearby devices.

Sound alone cannot reliably identify a tiger or leopard, so these sensors would need careful testing and multiple checks to reduce false alarms.

2. Smart camera traps

Cameras placed at selected wildlife corridors would capture images when movement is detected. An AI model running on the device could analyse the images and attempt to distinguish between wildlife, livestock and other animals.

Only the detection result and relevant alert information would need to be transmitted, rather than sending video over the LoRa network.

Where approved by wildlife authorities, additional warning devices could be considered. Any lights or sounds would need to be designed carefully to avoid disturbing wildlife or creating unsafe situations.

3. Solar-powered village siren beacons

Warning units installed at suitable public locations could use amber lights for caution and red lights for danger. They could also play recorded voice announcements in Marathi.

This would help people who do not own smartphones or have reliable mobile internet access.

The warning levels and messages would be coordinated with the Forest Department to prevent confusion and unnecessary panic.

3. How the System Would Work

Our proposed alert process is designed to be simple:

1. A sensor or camera detects unusual activity.
2. The device checks the available signals or image classification before generating an alert.
3. A short alert message is transmitted through LoRa radio to a nearby gateway.
4. The gateway forwards the information to the monitoring dashboard and, where connectivity is available, the mobile application.
5. Forest officers can review the alert and take appropriate action.
6. The relevant village warning beacon activates when the alert meets the agreed safety criteria.

The goal is to provide useful information early enough for people to make safer decisions.

4. Why We Are Considering LoRa

One challenge in forest-edge villages is that mobile network coverage may be weak or unreliable.

LoRa is a low-power wireless communication technology that can transmit small amounts of data over long distances under suitable conditions. It can be useful for sending sensor readings and warning messages without relying on a mobile data connection between every device.

However, LoRa has limited data capacity and does not transmit video like a normal internet connection. Our proposed system would therefore process camera images locally and send only the necessary alert information.

The actual communication range would depend on terrain, vegetation, antenna placement and interference. We would need field testing to determine suitable locations and whether a LoRa gateway or mesh arrangement would work best.

5. Our Development Roadmap

Timeline| Planned work
Months 1–3| Develop and test the mobile application, SOS feature and basic reporting system in a small pilot area.
Months 4–6| Test acoustic sensors along selected farm boundaries and evaluate false alarms.
Months 7–12| Trial camera-based detection and village siren beacons, subject to permissions, funding and successful earlier tests.

We plan to start small, learn from the people who would actually use the system, and improve it before considering wider deployment.

6. Where Our Project Stands Today

At this stage, our project is an ideathon concept supported by a prototype demonstration. We are exploring how the application, sensors, communication network and warning devices could work together as one system.

Our actual prototype currently demonstrates: [Describe exactly what your working demo does, including the hardware, sensor readings, buzzer, dashboard or alert functionality.]

The complete wildlife detection network is still under development. Solar-powered acoustic nodes, thermal cameras, AI-based animal classification and an interconnected village siren network are proposed future features, not completed or field-validated components.

We believe it is important to be honest about what we have built so far and what still needs testing. Our next step is to validate the individual components before attempting a full village-level deployment.

7. Challenges We Need to Address

We understand that a system like this must work reliably in real environments, not just during a demonstration.

- Cost: Thermal cameras, solar power systems, gateways and maintenance may be expensive.
- False alarms: Wind, livestock, vehicles and other sounds or movements could trigger incorrect warnings.
- Reliability: Devices must withstand rain, dust, heat, power fluctuations and outdoor conditions.
- Maintenance: A clear plan is needed for who will inspect, repair and maintain equipment in each village.
- Connectivity: The system must account for locations where neither mobile networks nor long-range radio links work consistently.
- Privacy: Personal locations, photographs and wildlife sighting reports must be handled responsibly.
- Wildlife safety: Detection and warning devices must not unnecessarily disturb animals or interfere with their natural movement.

We would work with villagers and forest officers to address these challenges before deploying the system on a larger scale.

8. Who Could Benefit From This Project?

Local communities: Earlier warnings could help villagers make informed decisions and reduce the risk of unexpected encounters.

Farmers: Timely information could help farmers avoid entering a reported high-risk area until it is considered safe.

Forest Department: Organised sighting reports and detection alerts could provide additional information for monitoring and response.

Wildlife: By helping people respond more safely and reducing the chances of panic or retaliation, the system could contribute to better human–wildlife coexistence.

The project is not intended to replace forest officers or guarantee that every encounter can be prevented. It is designed to support existing safety and conservation efforts.

9. References and Further Reading

We used the following publications and initiatives to explore the problem and understand existing approaches to wildlife monitoring:

1. The India Forum — “Tiger-Human Conflict around Tadoba-Andhari Reserve of Maharashtra.”
2. Dhanwatey et al. (2013) — “Large carnivore attacks on humans in central India: A case study from the Tadoba-Andhari Tiger Reserve.”
3. BioScience (2023) — “Mitigating human-wildlife conflict and monitoring endangered tigers using a real-time camera-based alert system.”
4. RESOLVE — TrailGuard AI initiative for wildlife monitoring and conservation.

These references provide background on human–wildlife conflict and existing monitoring approaches. The final project documentation should include verified links or publication details for each source.

---

Our vision is simple: help communities live more safely alongside wildlife through practical technology, timely information and cooperation with the people protecting Tadoba.

Empowering communities. Protecting wildlife. Building coexistence.
