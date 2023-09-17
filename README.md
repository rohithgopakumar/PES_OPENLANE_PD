# Advanced Physical Design using OpenLANE/Sky130

This README provides an overview of the Advanced Physical Design using OpenLANE and the Sky130 process technology. OpenLANE is an open-source digital RTL-to-GDSII flow that automates the entire ASIC design process, and Sky130 is a popular PDK (Process Design Kit) provided by Google and Skywater Technology Foundry.

#  OpenLane FLow 

![image](https://github.com/rohithgopakumar/PES_OPENLANE_PD/assets/131611312/eec9181d-0530-49cb-b531-9f6dc3d62085)

## Table of Contents
- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Advanced Topics](#advanced-topics)
- [Contributing](#contributing)
- [License](#license)

## Introduction

OpenLANE is a powerful tool for automating the physical design process, making it accessible to both beginners and experts. This guide focuses on advanced techniques and best practices for designing digital integrated circuits using OpenLANE and the Sky130 PDK.

## Prerequisites

Before you can use OpenLANE for advanced physical design, you should have the following prerequisites in place:

1. **Linux Environment**: OpenLANE works best on a Linux-based operating system. Ubuntu 20.04 LTS is recommended.

2. **OpenLANE Installation**: Ensure you have OpenLANE installed and configured. You can follow the [official OpenLANE installation guide](https://github.com/efabless/openlane) for this.

3. **Sky130 PDK**: Download and install the Sky130 PDK. You can find detailed instructions on the [Sky130 PDK GitHub repository](https://github.com/google/skywater-pdk).

4. **RTL Design**: Have your RTL (Register Transfer Level) design ready in Verilog.

5. **Design Constraints**: Prepare your design constraints in the form of SDC (Synopsys Design Constraints) files.

6. **EDA Tools**: Make sure you have the required EDA (Electronic Design Automation) tools like Yosys, Magic, and other tools needed for the design flow.

## Getting Started

Once you have the prerequisites in place, follow these steps to get started with advanced physical design using OpenLANE and Sky130:

1. **Design Preparation**: Ensure that your RTL design and design constraints are ready.

2. **Directory Setup**: Create a working directory for your project and navigate to it.

3. **OpenLANE Configuration**: Set up your OpenLANE configuration files for your project. You can use the provided `config.tcl` as a starting point.

4. **Design Setup**: Copy your RTL files and design constraints into the appropriate directories within your OpenLANE project directory.

5. **Running OpenLANE**: Execute the OpenLANE flow using the following command:
   ```bash
   ./flow.tcl -design <design_name>
---

## Advanced Topics
Advanced Topics
For in-depth understanding and advanced topics related to OpenLANE and Sky130, consider exploring the following areas:

- Clock Domain Crossing (CDC): Handling asynchronous clock domains.
- Low Power Design: Techniques for reducing power consumption.
- Custom Layouts: Creating custom cell libraries or IP blocks.
- Advanced Timing Constraints: Fine-tuning timing constraints.
- EDA Tool Customization: Configuring and using alternative EDA tools.
- Design Optimization: Strategies for optimizing area, power, and performance.

This README serves as a starting point for advanced physical design using OpenLANE and the Sky130 process technology. It's important to consult the official documentation and additional resources for more detailed information and troubleshooting.

For more information and detailed usage instructions, please refer to the [official OpenLANE documentation](https://github.com/efabless/openlane).

Feel free to contribute to this project by submitting issues or pull requests. Your contributions are greatly appreciated.

## License

This project is licensed under the terms of the MIT License. See the [LICENSE.md](LICENSE.md) file for details.




# COURSE CONTENT

</details>
<details>
<summary>DAY 1:  Inception of open-source EDA,Openlane and sky130 PDK </summary>
<br>






# Inception of Open-Source EDA: OpenLane and Sky130 PDK

## Introduction

Welcome to the Inception of Open-Source EDA project, where we explore the integration of OpenLane with the Skywater 130nm Process Design Kit (PDK). This open-source initiative aims to facilitate digital chip design and manufacturing, making EDA tools more accessible and collaborative.

## Table of Contents
1. [Prerequisites](#1-prerequisites)
2. [Installation](#2-installation)
3. [Getting Started](#3-getting-started)
4. [ Additional Resources](#4- Additional Resources)
5. [Troubleshooting](#5-Troubleshooting)
6. [License](#6-license)
7. [ Flop Ratio](#7- Flop Ratio)

## 1. Prerequisites

Before you begin, ensure you have met the following requirements:

- **Linux Environment**: OpenLane and Skywater PDK are primarily designed for Linux. We recommend using Ubuntu 18.04 LTS or later.

- **Git**: You'll need Git for version control and project setup.

- **Python**: Ensure you have Python 3.6 or higher installed on your system.

- **Docker**: Docker is used for containerization, simplifying the installation of various tools.

- **Synopsys Tools (Optional)**: Some stages of the flow may require specific EDA tools, such as Design Compiler. Note that these tools might require licenses.

## 2. Installation

Follow these steps to set up the project:

1. Clone the OpenLane repository:

   ```shell
   git clone https://github.com/The-OpenROAD-Project/OpenLane.git


## 3. Getting Started

Now that you have everything set up, you can start using OpenLane and exploring the Sky130 PDK:

### Run OpenLane

To run OpenLane, enter the OpenLane container:

```shell
make mount
```


![openlane_open_check](https://github.com/rohithgopakumar/pes_asic_class/assets/131611312/6928cc6f-4190-4a54-a369-796ed5fe84e6)



![openlane_open1](https://github.com/rohithgopakumar/pes_asic_class/assets/131611312/11765d62-c629-4354-82a5-63c43d449b4c)



![openlane_prep](https://github.com/rohithgopakumar/pes_asic_class/assets/131611312/19fab514-98f6-4243-b354-aff0e0894391)



## 4. Additional Resources

- **OpenLane Documentation**: Explore the comprehensive [OpenLane documentation](https://github.com/The-OpenROAD-Project/OpenLane) to learn more about the tool's capabilities and usage.

- **Skywater 130nm PDK Documentation**: Refer to the official [Skywater PDK documentation](https://github.com/google/skywater-pdk) for detailed information on the PDK components, usage, and design rules.

- **Community and Support**: Join the OpenLane and Sky130 PDK communities on platforms like GitHub and Reddit to ask questions, share experiences, and collaborate with others in the field of digital chip design.

## 5. Troubleshooting

If you encounter issues during the installation or usage of OpenLane or the Sky130 PDK, please refer to the troubleshooting section in the respective documentation. You can also seek assistance from the community through forums and discussion groups.
.

## 6. License

This project is distributed under the MIT License. For more details, please refer to the [LICENSE](LICENSE.md) file.


Thank you for joining us on this journey to make chip design more accessible and collaborative. We look forward to seeing the amazing designs you create using OpenLane and the Sky130 PDK!


## 7. Flop Ratio

The flop ratio is an important consideration in chip design, representing the balance between flip-flops (FFs) and logic elements. Achieving the right flop ratio is crucial for optimizing power consumption, performance, and area utilization in your designs.

When working on your chip design projects using OpenLane and the Sky130 PDK, keep the following tips in mind:

- **Ratio Guidelines**: Consult industry-standard guidelines or design specifications for the optimal flop ratio for your specific application.

- **OpenLane Tools**: OpenLane provides tools and options for analyzing and optimizing your flop ratio during the design process. Refer to the OpenLane documentation for details on how to use these features effectively.

- **Performance vs. Power**: Adjusting the flop ratio can impact both the performance and power consumption of your chip. Be mindful of your project's requirements and goals when making these adjustments.

- **Simulation**: Before finalizing your design, perform simulations to evaluate the impact of the flop ratio on functionality and timing. OpenLane offers simulation capabilities to assist in this process.

Balancing the flop ratio is a critical aspect of chip design, and OpenLane offers the flexibility and tools necessary to fine-tune this ratio to meet your project's objectives.



![flop_ratio](https://github.com/rohithgopakumar/pes_asic_class/assets/131611312/99475158-736a-423b-9666-b7609779129b)








</details>
<details>
<summary>DAY 2 : Good floorplan vs bad floorplan and introduction to librabry cells </summary>
<br>



# Chip Floor Planning Considerations

## Introduction

Chip floor planning is a crucial phase in the integrated circuit (IC) design process. It involves arranging various functional blocks and components on the chip's surface to optimize performance, minimize power consumption, and ensure manufacturability. This README provides an overview of key considerations and best practices for effective chip floor planning.

## Table of Contents

1. [Overview](#overview)
2. [Key Considerations](#key-considerations)
3. [Best Practices](#best-practices)
4. [Documentation](#documentation)
5. [Conclusion](#conclusion)

## Overview

### What is Chip Floor Planning?

Chip floor planning is the process of defining the physical layout of an integrated circuit on a silicon wafer or other semiconductor substrate. It involves determining the placement of logic gates, memory cells, I/O pads, and other components to achieve the desired chip functionality while meeting various design constraints.

### Importance of Chip Floor Planning

Effective floor planning has a profound impact on the final chip's performance, power consumption, and manufacturability. It influences factors such as signal delays, power delivery efficiency, and the ease of testing and debugging. A well-executed floor plan can significantly reduce design iterations and development time.


![dim_1_floorplan](https://github.com/rohithgopakumar/PES_OPENLANE_PD/assets/131611312/495f92fb-381d-41a6-9622-ecd55f312a26)



![dim2_floorplan](https://github.com/rohithgopakumar/PES_OPENLANE_PD/assets/131611312/f7f9d2a6-aa0f-41ba-b736-446c1e41c452)


![floorplan_layout](https://github.com/rohithgopakumar/PES_OPENLANE_PD/assets/131611312/38dad18f-d702-4443-9f9b-7205496184de)


![metal_layer_layout](https://github.com/rohithgopakumar/PES_OPENLANE_PD/assets/131611312/44263811-a0e9-4e4f-970b-847341c1d970)



![standard_cells_layout_buff](https://github.com/rohithgopakumar/PES_OPENLANE_PD/assets/131611312/40a66c89-9aef-4185-a7be-d7ec54cbf0b9)


## Key Considerations

### 1. Functional Block Placement

Deciding where to place different functional blocks is crucial. Blocks that frequently exchange data should be positioned close to each other to minimize signal delays, while those with less interaction can be placed farther apart.

### 2. Power Distribution

Efficient power distribution networks are vital to ensure that all components receive a stable power supply. Careful consideration of power grid topology, voltage domains, and decoupling capacitors is necessary.

### 3. Signal Routing

Planning the routing of signals between blocks and components is critical for minimizing signal congestion, reducing wirelength, and maintaining signal integrity.

### 4. Clock Distribution

Designing a robust clock distribution network is essential for synchronizing operations across the chip. This involves determining clock sources, clock domains, and minimizing clock skew.

### 5. Thermal Management

Heat dissipation is a significant concern in chip design. Proper floor planning should include provisions for thermal management, such as placing power-hungry blocks away from critical areas and incorporating heat sinks.

### 6. Manufacturing Constraints

Compliance with manufacturing constraints, such as minimum feature size and design rule checks (DRC), is crucial to ensure that the chip can be fabricated successfully.

### 7. EDA Tools

Utilize Electronic Design Automation (EDA) tools for floor planning tasks. These tools assist in placement, routing, and verification processes, streamlining the design workflow.

## Best Practices

### 1. Hierarchical Floor Planning

Organize the chip's layout hierarchically, breaking it into manageable blocks and sub-blocks. This enhances design modularity and simplifies design changes.

### 2. Regularity and Symmetry

Maintaining regular and symmetric chip layouts can facilitate manufacturability and simplify design rules.

### 3. Minimizing Wirelength

Efforts to reduce wirelength can help lower power consumption and improve signal integrity. Use optimal placement strategies to achieve this.

### 4. Noise and Crosstalk Mitigation

Consider noise and crosstalk at the floor planning stage and incorporate measures to minimize their impact, such as separating noisy and sensitive blocks.

### 5. Design for Testability (DFT)

Include testability features like scan chains, boundary scan, and built-in self-test (BIST) in the floor plan to enable efficient chip testing.

### 6. Design Rule Checking (DRC)

Regularly perform design rule checks to ensure compliance with manufacturing constraints and fix any violations promptly.

## Documentation

Maintain comprehensive documentation throughout the floor planning process. This documentation should include:

### 1. Floor Plan Diagrams

Detailed floor plan diagrams illustrating the placement of blocks, components, power grid, and signal routing.


![image](https://github.com/rohithgopakumar/PES_OPENLANE_PD/assets/131611312/c7647c53-c669-468a-bffb-2087bea2baca)


### 2. Design Constraints

A clear list of design constraints, including power requirements, signal timing, clock specifications, and manufacturing rules.

### 3. Design Guidelines

Guidelines and best practices specific to your chip design project to ensure consistency and clarity for the design team.

# Cell Design and Characterization Flow

## Overview

This readme file provides an overview of the Cell Design and Characterization Flow, outlining the process and steps involved in designing and characterizing electronic cells for integrated circuits. This flow is essential for ensuring the functionality and performance of electronic components in semiconductor devices.

## Table of Contents

1. **Introduction**
2. **Prerequisites**
3. **Design Phase**
   - 3.1 Cell Specification
   - 3.2 Schematic Design
   - 3.3 Layout Design
4. **Characterization Phase**
   - 4.1 Simulation Setup
   - 4.2 Performance Metrics
   - 4.3 Monte Carlo Analysis
5. **Documentation**
6. **Conclusion**
7. **References**

## 1. Introduction

The Cell Design and Characterization Flow is a crucial part of the semiconductor design process. It involves designing and characterizing individual electronic cells that make up integrated circuits. This process ensures that the cells meet performance requirements, such as speed, power consumption, and reliability, while adhering to manufacturing constraints.

## 2. Prerequisites

Before starting the Cell Design and Characterization Flow, ensure you have the following prerequisites:

- A clear understanding of the target application and its requirements.
- Proficiency in electronic circuit design tools (e.g., Cadence Virtuoso, Synopsys Design Compiler).
- Access to semiconductor foundry design kits and technology libraries.
- Simulation tools for electronic circuit analysis (e.g., SPICE simulators).

## 3. Design Phase

The design phase involves creating the electronic cell that will be used in the integrated circuit. This phase consists of the following steps:

### 3.1 Cell Specification

Define the specifications of the electronic cell, including its functionality, input/output requirements, and performance goals. This step serves as the foundation for the entire design process.

### 3.2 Schematic Design

Create the circuit schematic for the electronic cell using electronic design automation (EDA) tools. Ensure that the schematic accurately represents the desired functionality and adheres to design rules and constraints.

### 3.3 Layout Design

Translate the schematic into a physical layout that can be manufactured. Pay close attention to layout constraints, parasitics, and manufacturability. Perform design rule checks (DRC) and layout vs. schematic (LVS) verification to ensure correctness.

## 4. Characterization Phase

The characterization phase involves assessing the performance of the electronic cell through simulations and analyses. This phase includes the following steps:

### 4.1 Simulation Setup

Set up simulations to analyze the electronic cell's behavior under various conditions, such as different voltage levels, temperatures, and process variations. Use SPICE simulations to evaluate electrical characteristics.

### 4.2 Performance Metrics

Measure and analyze performance metrics, including speed (delay), power consumption, and noise margins. Ensure that the cell meets or exceeds the specified requirements.

### 4.3 Monte Carlo Analysis

Perform Monte Carlo analysis to assess the impact of process variations on the cell's performance. This helps ensure that the cell remains robust under manufacturing variability.

## 5. Documentation

Thoroughly document the design and characterization process. Create design specification documents, schematic diagrams, layout files, simulation setup details, and characterization reports. Clear documentation is crucial for collaboration and future reference.

## 6. Conclusion

The Cell Design and Characterization Flow is a critical aspect of semiconductor design, ensuring that electronic cells meet performance and reliability criteria. By following this flow and continuously refining the cell design, you can contribute to the successful development of integrated circuits.


</details>
<details>
<summary>DAY 3:  Design library cell using Magic Layout and ngspice characterization </summary>
<br>



# Design Library

Welcome to the Design Library! This repository contains a collection of design templates and components created using Magic Layout and characterized using ngspice. This README will provide you with an overview of the contents, instructions for usage, and information on how to contribute to this library.

## Table of Contents

1. [Introduction](#introduction)
2. [Contents](#contents)
3. [Getting Started](#getting-started)
4. [Usage](#usage)
5. [Characterization](#characterization)


## 1. Introduction

The Design Library is a resource for engineers and designers working on integrated circuit (IC) design. It contains pre-designed templates and components that can be used as a starting point for various IC projects. These designs have been created and characterized using Magic Layout and ngspice, providing a solid foundation for your custom IC designs.

## 2. Contents

The Design Library is organized into the following directories:

- `templates/`: This directory contains pre-designed templates for common IC components such as amplifiers, oscillators, and filters.

- `components/`: Here, you'll find individual IC components like transistors, capacitors, and resistors that can be used to assemble your custom designs.

- `characterization/`: Contains characterization data and simulation files for the components and templates in the library.

- `documentation/`: Documentation and user guides for using the library and performing simulations.

## 3. Getting Started

To get started with the Design Library, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using Git:

git clone https://github.com/yourusername/design-library.git

2. **Install Magic Layout**: Install Magic Layout on your machine if you haven't already. You can find installation instructions in the [Magic Layout documentation](https://magic-layout-docs.example.com).

3. **Install ngspice**: Install ngspice, the circuit simulator, according to the instructions provided on the [ngspice website](https://ngspice.sourceforge.io/download.html).

## 4. Usage

The Design Library provides templates and components that you can use as a starting point for your IC designs. Here's how to use them:

1. **Open Magic Layout**: Launch Magic Layout using the terminal:

2. **Load a Template or Component**: Use Magic's `load` command to load a template or component from the `templates/` or `components/` directory:

3. **Customize and Edit**: Modify the loaded design to meet your project requirements.

4. **Characterization**: Before finalizing your design, refer to the characterization data in the `characterization/` directory for each component to ensure accurate simulation results.

5. **Simulate**: Use ngspice to simulate your design and verify its functionality. Example simulation commands and setups can be found in the documentation.

6. **Document Your Design**: Document your design in the `documentation/` directory, including schematics, layout diagrams, and simulation results.

## 5. Characterization

The `characterization/` directory contains important data and simulation files for each component and template in the library. These files include transistor models, parameter sweeps, and characterization data. Always refer to this data when using components to ensure accurate simulations and designs.
  
