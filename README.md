# BioListener

BioListener is an open-source project designed to revolutionize biosensing with portable, affordable, multi-channel biosensing boards.

Powered by the ESP32 microcontroller, BioListener boards enable real-time data transfer via Wi-Fi, Bluetooth, and BLE, as well as on-board signal processing. These passive electrode-based boards are versatile tools for education, research, and innovation. At an estimated cost of **just $30 per 8-channel board**, BioListener offers an unparalleled alternative to costly devices like OpenBCI Cyton, which are often limited to one per group due to budget constraints. With BioListener, everyone can have access to their own device, fostering hands-on learning and experimentation. This democratization of biosensing technology supports applications in neurorehabilitation, VR, gaming, assistive technologies, and beyond.

The project has already completed the initial prototyping phase, delivering two functional PCB designs (each utilizing a different ADC chip to ensure resilience against global chip shortages). Pre-evaluation results show significant promise.

---

## Project Overview

### Key Features
- **Affordable & Accessible**: $30 per 8 channel board, democratizing biosensing technology.
- **Resilient Design**: Two distinct board designs utilizing AD7771 and ADS131M08 ADC chips.
- **High Connectivity**: Powered by ESP32 for Wi-Fi, Bluetooth, and BLE communication.
- **Customizability**: Modular add-ons for extended functionality.
- **Portable**: Compact size with 3D-printed enclosures.

### Supported Applications
BioListener is optimized for capturing biosignals in diverse scenarios, such as:
- **EEG**: Electroencephalography for brainwaves live monitoring.
- **EMG**: Electromyography for muscle activity monitoring.
- **ECG**: Electrocardiography for single- and multi-lead cardiac signal monitoring.
- **EOG**: Electrooculography for eye movement detection and analysis.

---

## Repositories Overview

| Repository Name                                                                                    | Description                                                                                                        | Links                                                                          |
|----------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------|
| **[BioListener Evaluation](https://github.com/serhii-matsyshyn/biolistener_evaluation)**           | Scripts, data, and experimental setups for evaluating BioListener hardware performance and real-world use.         | [View Repository](https://github.com/serhii-matsyshyn/biolistener_evaluation)  |
| **[BioListener Firmware](https://github.com/serhii-matsyshyn/biolistener_firmware)**               | Firmware for the ESP32-based BioListener device.                                                                   | [View Repository](https://github.com/serhii-matsyshyn/biolistener_firmware)    |
| **[BioListener Hardware](https://github.com/serhii-matsyshyn/biolistener_hardware)**               | Contains PCB source files, schematics, BOMs, and fabrication files for BioListener boards.                         | [View Repository](https://github.com/serhii-matsyshyn/biolistener_hardware)    |
| **[BioListener 3D Models](https://github.com/serhii-matsyshyn/biolistener_3d_models)**             | Includes Fusion360 sources and STL files for 3D-printed models for BioListener boards, such as 3D case model, etc. | [View Repository](https://github.com/serhii-matsyshyn/biolistener_3d_models)   |
| **[BioListener fork of BrainFlow](https://github.com/serhii-matsyshyn/biolistener_brainflow)**     | Fork of BrainFlow with BioListener support.                                                                        | [View Repository](https://github.com/serhii-matsyshyn/biolistener_brainflow)   |
| **[BioListener fork of OpenBCI GUI](https://github.com/serhii-matsyshyn/biolistener_openbci_gui)** | Fork of OpenBCI GUI with BioListener support.                                                                      | [View Repository](https://github.com/serhii-matsyshyn/biolistener_openbci_gui) |
---

## Current Progress
- **Prototyping**: Two functional board designs with promising pre-evaluation results.
- **Integration**: Work underway to integrate with BrainFlow and other popular frameworks.
- **Firmware Development**: Initial firmware development for Wi-Fi real-time data transfer to BrainFlow server.

---

## TODOs

- **Firmware Development**
  - [ ] Enhance features for offline mode and unstable network handling.
  - [ ] Implement auto device discovery using mDNS and DNS-SD for easy setup.
  - [ ] Optimize firmware for IoT applications and daisy-chaining (up to 16 channels).
  - [ ] Develop plug-and-play apps for educational and research use.

- **Testing & Validation**
  - [ ] Add Jupiter notebook for evaluation
  - [ ] Create connection schematic for evaluation steps
  - [ ] Describe evaluation process, add evaluation setup images
  - [ ] Finish documenting standardized testing procedures to ensure reliability in real-world applications.
  - [ ] Add evaluation results to README
  - [ ] Compare prototypes with high-cost solutions.

- **Hardware Development**
  - [ ] Finalize PCB designs for mass production.
  - [ ] Produce additional prototypes.
  - [ ] Refine 3D-printed enclosures for better portability and durability.
  - [ ] Develop modular add-ons like bio-feedback-based electrical stimulation boards.
  - [ ] Explore additional ADC chips for broader compatibility.

- **Documentation**
  - [ ] Create step-by-step guides for hardware assembly and firmware setup.
  - [ ] Develop tutorials and case studies for various use cases.
  - [ ] Provide troubleshooting documentation for common issues.


---
## Licensing
BioListener is fully open-source, with repositories licensed as follows:
- **Code**: [GNU General Public License v3.0 (GPL-3.0)](https://www.gnu.org/licenses/gpl-3.0.html).
- **Hardware Designs**: [CERN Open Hardware Licence, Version 2 - Strongly Reciprocal](https://cern-ohl.web.cern.ch/).
- **Experimental Data**: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
- **Documentation**: [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

---

For questions, contributions, or discussions, feel free to create an issue or pull request in the respective repositories.
