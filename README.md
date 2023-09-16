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


