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

