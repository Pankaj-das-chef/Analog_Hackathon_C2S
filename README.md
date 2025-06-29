# Analog_Hackathon_C2S
# Band Gap Current Reference Circuit (BGCR-1) using 90nm CMOS Technology

## Project Overview

This project focuses on the design and simulation of a robust Band Gap Current Reference (BGCR) circuit, tailored to meet the demanding requirements of **low-power wireless communication devices**. Utilizing **90nm CMOS technology**, the design aims to deliver a stable **100µA nominal output current** across a wide range of temperatures and supply voltages, crucial for reliable performance in applications like BLE and Zigbee modules.

## Specifications

Our design targets the following key performance metrics:

* **Output Current:** $100 \mu A \pm 5\%$ across the temperature range of $-40^\circ C$ to $125^\circ C$.
* **Technology:** 90nm CMOS process.
* **Power Supply:** 1.8V to 3.3V.
* **Power Consumption:** Less than $50 \mu W$ for the entire current reference circuit.
* **Temperature Coefficient:** Less than $50 \text{ ppm}/^\circ C$ for the output current.
* **Load Regulation:** Output current should remain stable within $\pm 2\%$ when the load voltage varies from 0 to 1V.

## Design Considerations

The core of this current reference relies on a **band gap voltage reference** to establish a highly stable and temperature-independent voltage, which is then converted into a current using a **current mirror**. Key considerations during the design process in 90nm CMOS technology included:

