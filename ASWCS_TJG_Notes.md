### System Boundary

- Sea-based collection system
  - Defined interface
- Recycling center
  - Defined interface (mostly)
- Autonomous movement boundary
  - Outside of ports and shipping lanes
  - Exclusive of "anomalous" events
- Bunker location
  - Assumed well-defined interface
  - Human interaction
  
### Create

- [x] Package Diagram containing packages
- [x] Use Case Diagrams
- [x] Stakeholders Diagram
- [x] Requirements

### Requirements (Draft)

- The ASWCS shall operate with a maximum downtime of seven days in any four month period.
- The ASWCS shall communicate any anomalous situations to the ground station. (via...?)
- The budget for production, maintenance, and operation of at least one ASWCS transport vessel for a period of three years shall not exceed 56 million dollars. 
- All elements of the ASWCS shall be in service prior to August 1, 2021. (Yeah, that's gonna happen.)
- The ASWCS transport vessel shall have a minimum range of 3500 nautical miles.
- The ASWCS transport vessel shall be piloted while in port, as well as between the harbor and any shipping lane.
- The ASWCS transport vessel shall maintain a minimum distance of 0.25 nautical miles from all other vessels while operating in autonomous mode.
- Control and communication channels to and from the ASWCS transport vessel shall be encrypted.
- The ASWCS transport vessel shall broadcast its position to a ground station at intervals not to exceed (TBR).
- The ASWCS transport vessel shall broadcast changes in status to a ground station, such as underway to docking, docking to docked, transferring waste, etc.
- The ASWCS transport vessel shall broadcast changes in cargo weight and volume.
- The ASWCS transport vessel shall autonomously dock with sea-based waste collection systems using a documented hardware interface.
- The ASWCS transport vessel shall autonomously onload plastic waste from a conveyor belt located at a height of 20 feet above the waterline.
- The ASWCS transport vessel shall supply 50 A of 220 VAC power to the sea-based collection system conveyor belt.
- The ASWCS transport vessel shall autonomously plug in the connector required to supply 220 VAC power to the sea-based collection system conveyor belt.
- The ASWCS transport vessel shall receive plastic waste from the sea-based collection system conveyor belt at a maximum rate of 20 cubic feet per minute.
- The ASWCS transport vessel shall have a minimum waste cargo capacity of 6460 cubic feet.
- The ASWCS transport vessel shall be capable of traveling a maximum distance of 2400 nautical miles in 10 days (TBR map distance vs "sea route" distance).
- The ASWCS transport vessel shall be capable of docking with the sea-based collection system with ocean swells up to a maximum of six feet.
- The ASWCS transport vessel shall be capable of offloading the waste cargo to a height of 30 feet above waterline.


### Desirements

- The ASWCS shall have living quarters and associated amentities (lavatory, kitchen, etc) for up to five research personnel.


### Leo's User Story List

1. Transport System will be low cost and use sustainable design implementation with minimal environmental impact
1. Transport System will expedite recycling processing
1. Transport System will have minimal logistical needs and maintenance costs
1. Transport System will use 100% renewable energy source for operation
1. Stakeholders for: Environmentalists, Conservation Organizations, Budget Stakeholders (non-profit organizations), Coastal Communities
1. Stakeholders against: Ocean Life Preservation Organizations, Coastal Community Members Against Recycling Processing Centers
1. Transport System will be autonomously operated except for times that require manual operation and maintenance needs
1. Transport System will start from a docking station and travel autonomously to the collection center. The system will collect the waste and transport it back to the recycling center.
1. Transport System will be a modular design such that specific subsystems will be reusable. Other subsystems will use materials that are as sustainable and recyclable as practical.


## Team Presentation Thoughts

### Purpose

The reason for a team project is to demonstrate what we've learned, *not* to design an autonomous waste transportation system. To that end, a few representative diagrams are sufficient, without going into great design detail. Broad strokes...

### Outline

- Diagrams:
  - Overall Context Diagram
  - A few "normal op" context diagrams to feed into an FFBD, e.g.:
    - Transiting from harbor dock to open ocean (perhaps skip return case)
    - Transiting from open ocean to collection site (perhaps skip return case)
    - Taking on waste from collection site
    - Offloading waste to recycling facility
  - Functional Flow Block Diagram - Normal Op
  - IDEF0 - Normal Op
  - Package Diagram 
  - Use Case Diagram - one or two should be sufficient
  - Activity Diagrams
    - One with major blocks from FFBD
    - Two or three more to break down some of the major blocks, e.g. details on docking or controlling vessel autonomously
  - Requirements Diagram/Table 
    - This one is pretty easy using the Excel I/O
    - I added all the compiled requirements into my diagram and they're also in an Excel file
    - I have *not* connected any together in the diagram, or added anything to columns other than name and text
  - Block Definition Diagrams
    - May only need one overall diagram
  - State Machine Diagram(s)
    - Should be able to get away with one showing various vessel states
  - We'll learn about these next week:
    - Sequence Diagram(s)
    - Internal Block Diagram(s)
    - Parametric Diagram(s)
    
