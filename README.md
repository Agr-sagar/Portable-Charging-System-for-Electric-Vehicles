# Portable-Charging-System-for-Electric-Vehicles
## Abstract:
This project aims to design a portable charger dedicated to electric vehicles, providing convenient on-the-go charging solutions. The focus is on integrating advanced power electronics, high-capacity batteries, and compliant communication systems for optimal efficiency and safety. The project seeks to address the challenge of emergency charging scenarios for EVs.

## 1. Introduction:
The paradigm shift toward sustainable transportation has accelerated the prominence of electric vehicles (EVs) in recent years. This transition presents a pivotal challenge: ensuring uninterrupted access to charging infrastructure, especially in scenarios where an EV faces the risk of depletion before reaching a recharging station. To address this challenge, the focus of this project is to conceptualize and develop a portable charger expressly designed for EVs.

The fundamental motivation behind this endeavor stems from the necessity for a versatile and efficient solution to cater to the dynamic mobility needs of electric vehicles. This portable charger aims to bridge the gap in charging accessibility, offering a viable alternative to conventional fixed charging stations. By leveraging advancements in power electronics, battery technology, and charging protocols, the goal is to create a portable charging solution that aligns with industry standards, ensuring compatibility across various electric vehicle models.

This project's significance lies not only in its technological innovation but also in its potential to revolutionize the landscape of EV infrastructure. The ability to provide on-the-spot charging capability has the promise to alleviate concerns regarding range anxiety and bolster the convenience and feasibility of widespread EV adoption.

## 2. Portable Charger Design
#### 1. Charger Battery Pack:
The Li-ion battery pack serves as the primary power source for the portable charger. Its higher capacity allows for sufficient energy storage to facilitate the charging of electric vehicles. This component ensures portability and autonomy, enabling on-the-go charging without reliance on fixed power sources.
#### 2. Buck-Boost Converter:
The bidirectional buck-boost converter plays a pivotal role in efficiently transferring energy between the charger battery pack and the electric vehicle's battery. It regulates voltage levels, allowing seamless charging in both directions—either supplying power from the charger battery to the EV battery or recuperating energy from the EV back to the charger battery. Its bidirectional functionality optimizes the charging process for varying voltage scenarios.
#### 3. EV Battery Pack:
The EV battery pack represents the target battery for charging. It adheres to standard specifications suitable for real-world EV applications. The charger's design ensures compatibility with diverse EV models, accommodating different battery capacities and configurations prevalent in the market.
#### 4. Control Circuit:
The control circuit orchestrates the charging process by managing voltage, current, and control signals. It involves several key functions:
###### Voltage Measurement: 
Constant monitoring of the EV battery pack voltage to assess its state and determine the charging requirements.
###### Comparison with Nominal Voltage: 
Comparing the measured EV battery pack voltage with the nominal battery voltage to establish charging needs.
###### PI Controller: 
Utilizing a Proportional-Integral (PI) controller to generate a reference current based on the comparison of actual and nominal voltages. This reference current acts as the input for the current control circuit.
###### Current Control Circuit: 
Utilizing the reference current to regulate the duty cycle for the two Insulated Gate Bipolar Transistors (IGBTs) of the buck-boost converter. This ensures precise control of the charging current, optimizing the charging process while maintaining safety and efficiency.
#### 5. Safety Features:
Embedded safety features constitute a critical aspect of the charger's design. Overcurrent protection prevents damage by curbing excessive current flow. Overvoltage protection safeguards against voltage spikes, ensuring the charging process's safety. Moreover, the charger incorporates short-circuit protection, promptly detecting and mitigating short-circuit situations to prevent potential hazards, ensuring a secure charging environment.
