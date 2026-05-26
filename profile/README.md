# AFRL-ARES: A Software For Autonomous Research

Welcome to the official GitHub home of the **Autonomous Research System (ARES)**, developed at the Air Force Research Laboratory (AFRL). Our mission is to accelerate the pace of scientific discovery by providing an open-source, modular, and accessible platform for closed-loop autonomous experimentation.

For in-depth documentation on ARES, Educational ARES (ATHENA), PyAres or the ARES Launcher, please visit https://afrl-ares.github.io/.

## Our Mission
The current pace of research is often limited by manual processes. ARES transforms traditional laboratories into **autonomous research robots** that design, execute, and analyze experiments using artificial intelligence. By closing the loop between planning and execution, ARES allows scientists to focus on high-level goals while the system handles the iterative discovery process.

## The ARES Ecosystem
Our software suite is built on modern engineering principles, designed to be flexible enough for complex research and simple enough for educational use.

### [ARES OS](https://github.com/AFRL-ARES/ARES)
The core orchestration engine. ARES OS 2.0 is a robust software suite written in **C#/.NET** with a modern **Blazor** frontend. It provides the structured interface required for modular laboratory control, handling everything from device registration to complex workflow execution.

### [ARES Launcher](https://github.com/AFRL-ARES/ARES-Launcher)
The management hub for the ARES environment. The Launcher is a desktop application designed to simplify the installation, setup, and execution of the ARES suite. It orchestrates the lifecycle of essential services. This includes the ARES Core, the web UI, and the database ensuring a seamless "one-click" experience for researchers.

### [PyAres](https://github.com/AFRL-ARES/PyAres)
The official Python library for ARES. We believe science should be accessible to those who know it best. PyAres is a high-level wrapper for the **gRPC/Protobuf API**, allowing scientists and researchers to write planners, analyzers, and device drivers in native Python without needing to manage the underlying C# architecture.

### [Educational-ARES](https://github.com/AFRL-ARES/Educational-ARES)
A specialized version of the ARES suite designed for classroom and low-cost environments. It supports autonomous 3D printing (specifically built for the Prusa MK4S) to teach the next generation of scientists the principles of autonomous research.

### [ARES-Datamodel](https://github.com/AFRL-ARES/ARES-datamodel)
The source of truth for our communication. This repository contains the Protobuf and gRPC definitions that ensure seamless, language-agnostic communication between the ARES core and its various plugins.

## Architecture & Design
ARES is built with a "Plugin-First" philosophy:
- **Modularity:** Easily swap out Planners (AI/ML models), Analyzers (Computer Vision/Data Processing), and Device Drivers.
- **Accessibility:** A web-based UI allows for remote monitoring and management of autonomous campaigns.
- **Scalability:** Leveraging gRPC for high-performance communication across different hardware and software environments.

## Contributing
Interested in contributing to the ARES ecosystem? Whether you're creating plugins for devices, new planners and analyzers, or looking to contribute to code in our core libraries, we want your help! Check out https://afrl-ares.github.io/docs/ares/contributing to learn more about how to contribute to our open source community.

## Contact
For potential collaborations, please reach out to Dr. Benji Maruyama at:
**Email:** benji.maruyama@afrl.af.mil

For Software Questions, please contact:
**Email:** ababeckis@dcscorp.com OR nkleiner@dcscorp.com

---
*ARES was developed by the Air Force Research Labs (AFRL) and is licensed under the MIT License. Please see individual repositories for specific license terms.*
