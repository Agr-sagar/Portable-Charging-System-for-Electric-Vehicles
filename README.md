# Portable-Charging-System-for-Electric-Vehicles
## Abstract:
This project aims to design a portable charger dedicated to electric vehicles, providing convenient on-the-go charging solutions. The focus is on integrating advanced power electronics, high-capacity batteries, and compliant communication systems for optimal efficiency and safety. The project seeks to address the challenge of emergency charging scenarios for EVs.

## 1. Introduction:
The paradigm shift toward sustainable transportation has accelerated the prominence of electric vehicles (EVs) in recent years. This transition presents a pivotal challenge: ensuring uninterrupted access to charging infrastructure, especially in scenarios where an EV faces the risk of depletion before reaching a recharging station. To address this challenge, the focus of this project is to conceptualize and develop a portable charger expressly designed for EVs.

The fundamental motivation behind this endeavor stems from the necessity for a versatile and efficient solution to cater to the dynamic mobility needs of electric vehicles. This portable charger aims to bridge the gap in charging accessibility, offering a viable alternative to conventional fixed charging stations. By leveraging advancements in power electronics, battery technology, and charging protocols, the goal is to create a portable charging solution that aligns with industry standards, ensuring compatibility across various electric vehicle models.

This project's significance lies not only in its technological innovation but also in its potential to revolutionize the landscape of EV infrastructure. The ability to provide on-the-spot charging capability has the promise to alleviate concerns regarding range anxiety and bolster the convenience and feasibility of widespread EV adoption.

## 2. Portable Charger Design
#### 1. Charger Battery Pack:
Purpose: Serves as the primary power source for the portable charger.
Component: High-capacity Li-ion battery pack enabling on-the-go charging without reliance on fixed power sources.
Function: Stores energy required for charging electric vehicles, ensuring portability and autonomy.
#### 2. Bidirectional Buck-Boost Converter:
Purpose: Facilitates bidirectional energy transfer between the charger battery pack and the EV battery.
Function: Regulates voltage levels for efficient charging/discharging.
Modes:
Charge Mode: Draws power from the charger battery pack to charge the EV battery.
Discharge Mode: Allows energy transfer from the EV battery back to the charger battery pack when the EV is not actively charging, optimizing energy recovery.
#### 3. Electric Vehicle (EV) Battery Pack:
Purpose: Represents the target battery for charging, adhering to standard specifications for real-world EV applications.
Component: Diverse configurations to accommodate different EV models and battery capacities prevalent in the market.
Compatibility: Designed to ensure compatibility with varying EV battery configurations.
#### 4. Control Circuit:
Purpose: Manages and regulates the charging process by controlling voltage, current, and control signals.
Functions:
Voltage Measurement: Constantly monitors EV battery pack voltage to assess its state and charging requirements.
Comparison with Nominal Voltage: Compares measured EV battery voltage with nominal values to determine charging needs.
PI Controller: Utilizes a Proportional-Integral (PI) controller to generate reference current based on voltage comparisons.
Current Control Circuit: Regulates the duty cycle for the two Insulated Gate Bipolar Transistors (IGBTs) of the buck-boost converter based on the reference current. This ensures precise control of charging current, optimizing efficiency and safety.
#### 5. Safety Features:
Overcurrent Protection: Prevents excessive current flow, safeguarding components from damage.
Overvoltage Protection: Safeguards against high voltage spikes, ensuring safety during the charging process.
Short-Circuit Protection: Detects and mitigates short-circuit situations, preventing potential hazards
