# VTOL UAV Project

## Overview
This project focuses on developing an unmanned Vertical Take-Off and Landing (VTOL) aircraft that combines the advantages of fixed-wing airplanes and rotary-wing aircraft. The goal is to create an efficient and affordable design that demonstrates the potential of VTOL UAVs in real-world applications.

### Motivation
Traditional airplanes offer high efficiency and long flight times but require large runways for operation. Rotary-wing aircraft, like drones, can take off and land anywhere but sacrifice efficiency and flight time. VTOL aircraft aim to bridge this gap, offering runway-free operation with extended efficiency and range. This project simplifies the VTOL concept to make it accessible and cost-effective for research and practical use.

## Objectives
- **Expand research** into unmanned VTOL aircraft.
- Design a vehicle that uses the same aerodynamic surfaces for hover and cruise flight.
- Build a functional prototype to demonstrate efficiency, mobility, and cost-effectiveness.

## Applications
- Cargo delivery in urban and remote areas.
- Medical supply delivery to inaccessible locations.
- Green alternatives for transportation.
- Data gathering and mapping in areas without runway infrastructure.

## Features
- **Tail-Sitter Design**: Inspired by the "Convair XFY Pogo," the aircraft can hover, transition, and cruise efficiently.
- **Symmetrical Airfoil**: Ensures consistent handling during hover and cruise phases.
- **Counter-Rotating Propellers**: Enhance stability, prevent stalls, and provide yaw control.
- **Iterative Development**: Combines modeling, prototyping, and flight testing for design refinement.

## Materials
### Hardware
- Balsa wood, plywood, carbon fiber rods
- Aluminum landing gear, foam wheels, foam sheets, Monokote

### Electronics
| Component                          | Price   | Source                                                      |
|------------------------------------|---------|------------------------------------------------------------|
| Teensy 3.1 ARM Processor          | $19.80  | [PJRC Store](https://www.pjrc.com/store/teensy3.html)       |
| Eagle A3 Super 3 Gyro             | $40.99  | [Motion RC](https://www.motionrc.com/products/eagle-a3-super-3-standard-edition-airplane-gyro) |
| Power Distribution Board          | $8.55   | [Source](https://rb.gy/u0de9b)                             |
| Brushless Motors (2x)             | $25.33  | [Source](https://rb.gy/0chueu)                             |
| Electronic Speed Controllers (2x) | $43.82  | [Source](https://rb.gy/x6bpjf)                             |
| Lithium Polymer Battery           | $120.00 | Hobby Store                                                |

### Software
- Inkscape, Adobe Illustrator
- Fusion 360 for 3D modeling
- Arduino IDE for microcontroller programming

## Methods
1. **Brainstorming and Planning**
   - Develop a design inspired by existing VTOL aircraft.
2. **Computer-Aided Design (CAD)**
   - Create 3D and 2D models for prototyping.
3. **Small-Scale Prototyping**
   - Build and test scale models to validate design assumptions.
4. **Iteration Cycle**
   - Refine the design and programming based on feedback and test results.
5. **Full-Scale Construction**
   - Assemble the final model and conduct flight tests.

## Results
- Successful execution of vertical take-off, hover, cruise, and landing.
- Stable and efficient performance observed during tests.
- Demonstrated endurance surpassing typical rotary-wing UAVs.

## Challenges and Solutions
- **Flight Controller Configuration**: Combined fixed-wing and microcontroller systems for stabilization.
- **Structural Support**: Reinforced wings with carbon fiber.
- **Emergency Landing Gear**: Added conventional landing gear for testing and contingencies.

## Conclusion
This project highlights the potential of VTOL UAVs to revolutionize aviation by combining mobility and efficiency. The research proves that a simplified VTOL design can perform reliably while keeping costs low. Future work can build on this foundation to enhance design and scalability.

## Repository Structure
```
VTOL-UAV-Project
├── CAD-Models
├── Code
├── Documentation
├── Prototypes
└── Test-Logs
```

## License
This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgments
Special thanks to the Model Aeronautics Association of Canada and the Mississauga Model Flying Club for their support.
