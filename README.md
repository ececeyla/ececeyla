# Ece Ceyla Demir

**Electrical and Electronics Engineering · Middle East Technical University (METU)**

**Research interests:** Analog & Mixed-Signal IC Design · RFICs · SiGe Semiconductor Devices · Circuit-to-Layout Verification

I am an undergraduate electrical and electronics engineering student interested in how integrated circuits work from transistor-level behavior to physical implementation. My experience connects **SiGe HBT and RF circuit characterization**, **electromagnetic simulation**, and **embedded hardware that has been manufactured and deployed**.

In 2026, I worked on open-source RFIC design and verification at **Karlsruhe Institute of Technology (KIT / IHE)** and underwater acoustic telemetry systems at **Universitat Politècnica de Catalunya (UPC / SARTI)**. I have also contributed to the electronics of **METU Formula Racing's Devrim 26**.

## Selected research and engineering work

### [IHP SG13G2 RFIC Characterization · KIT](https://github.com/ececeyla/ihp-sg13g2-rfic-characterization)

**SiGe HBT · S-parameters · Noise and stability · EM simulation**

- Conducted DC, AC, RF S-parameter, Smith chart, noise and stability analyses of the IHP `npn13G2` HBT.
- Worked with KLayout and openEMS on custom passive layouts, two-port transmission lines and a three-port T-junction.
- Studied transistor-level layout verification with DRC/LVS.
- **Tools:** Xschem, Ngspice, IHP SG13G2 OpenPDK, KLayout, AppCSXCAD, openEMS, Python.
- Repository includes a historical technical report and clearly labeled reconstructed tooling; reconstructed files are not represented as original internship sources.

### [Underwater Acoustic Telemetry · UPC / SARTI](https://github.com/ececeyla/underwater-acoustic-telemetry)

**ESP32-S3 · Acoustic modems · GNSS · LTE-M/NB-IoT**

- Contributed to an experimental surface/submerged telemetry network involving acoustic pings and distance measurement, GNSS position reporting and remote monitoring.
- Worked with embedded firmware, modem state and sleep/wake behavior, and web-based node status monitoring.
- Repository includes a synthetic offline demo and backend test suite. Real-world localization accuracy is not claimed.

### [Devrim 26 Sensor-Interface PCB · METU Formula Racing](https://github.com/ececeyla/metu_formula)

**Embedded hardware · Sensor conditioning · CAN · USB–UART · Power electronics**

Contributed to the team's ESP32-based sensor-interface board for **Devrim 26**, featuring analog sensor interfaces, SN65HVD230 CAN, FT230XS USB–UART, and 12 V / 5 V / 3.3 V supplies.

The board was **manufactured, tested and used in the car**; the contributor reports that it met the applicable Formula Racing requirements. The project is collaborative, and this description does not imply single-author ownership of every sheet.

![Devrim 26 sensor-interface architecture, derived from the seven-sheet EasyEDA schematic](assets/formula-sensor-architecture.svg)

<sub>The image is a functional architecture diagram, not a fabricated-board photo or PCB routing view.</sub>

## Current focus

I am particularly interested in **analog/mixed-signal receivers, RF/mmWave ICs, SiGe and semiconductor device research**. My current university capstone work involves a **laser-rangefinder receiver-IC architecture**, including front-end amplification and time-programmed gain control. This project is in development; no tapeout or measured chip results are claimed.

## Tools and methods

`Ngspice` · `Xschem` · `IHP SG13G2 OpenPDK` · `KLayout` · `openEMS` · `Python` · `C/C++` · `ESP32` · `PlatformIO` · `CAN` · `EasyEDA` · `Git`

---

*The project repositories may be private pending research and team publication review. Historical, synthetic, simulated, and physically tested results are labeled separately.*
