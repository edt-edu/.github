# Engineering Digital Twin Education Community

Welcome to the **Engineering Digital Twin Education** organization. Our mission is to bridge the gap between theory and practice by providing a collaborative space to share, 
learn, and build Digital Twins for research and educational purposes.


## Our Vision
Digital Twins are complex systems-of-systems. Whether for **cutting-edge research** in Model-Based DevOps (MBDO) 
or for **hands-on engineering education**, we believe that sharing open-source setups is the best way to accelerate innovation and learning.

## Initial Use Case: The FischerTechnik Factory
The community started with outcomes from the **ANR MBDO project**. Our flagship setup features:
* **Physical Platform:** FischerTechnik Industrial Factory.
* **Control Hardware:** KUNBUS Revolution Pi (RevPi) controllers.
* **Software Stack:** Open-source SCADA, utility scripts, and synchronization models.

This setup serves as a blueprint that we aim to extend with Digital Twin services (incl. Simulation, deviation detection, monitoring, replanning, predictive maintenance, ....).

## Research & Education
We (will) provide a dual-purpose ecosystem:
* **For Researchers:** A foundation for experimenting with Digital Twin.
* **For Educators:** Ready-to-use lab setups and pedagogical resources to teach the next generation of digital twin engineers.

## Community & Troubleshooting
Building Digital Twins involves "real-world" challenges. We use this space to exchange on:
* **Hardware hurdles:** Wiring or hardware issues, configuration.
* **Software integration:** Bridging the gap between physical twin and digital twins.
* **Solutions:** Documentation of hacks, fixes, and optimizations.

---

## How to Contribute?
We are an open community! You can contribute by:
1. **Sharing your Use Case:** Do you have a different factory or controller? Let's integrate it!
2. **Improving Tools:** Refactoring scripts or adding new GitHub Actions for CI/CD.
3. **Joining Discussions:** Use the **Discussions** tab to ask questions or share your hardware "war stories."

## Acknowledgments
Initial core contributions stem from the [ANR MBDO project](https://mbdo.github.io). We thank all partners for their commitment to opening this research to the wider community.

---
## Repositories

The EDT-Edu ecosystem is organized across several complementary repositories.

### Public repositories

- [`cps-fischertechnik`](https://github.com/edt-edu/cps-fischertechnik) — Software and resources for the Fischertechnik cyber-physical production system, including controllers, Factory SCADA, SysML-based tooling, and related hardware assets.

- [`dt-platform`](https://github.com/edt-edu/dt-platform) — Reusable software components and experimental implementations for building Digital Twin platforms, including gateways, visualization tools, and Digital Twin services.

- [`dt-setups`](https://github.com/edt-edu/dt-setups) — Configuration, deployment, and demonstration assets for reproducible Digital Twin experimental setups, combining platform components, physical systems, and supporting infrastructure.

- [`DT-Use-Cases`](https://github.com/edt-edu/DT-Use-Cases) — Digital Twin implementations associated with the paper *Digital Twins for Manufacturing Systems: A Case Study Based On a Fischertechnik Factory* and related to our main use cases from the MBDO project.

- [`.github`](https://github.com/edt-edu/.github) — Organization-wide GitHub configuration and the source of this organization profile.

### Internal and restricted repositories

Some resources are not publicly available because they are used for internal project coordination or contain material subject to access restrictions:

- [`project-management`](https://github.com/edt-edu/project-management) *(private)* — Internal project-management resources and coordination material shared by EDT-Edu contributors.

- [`documentation-archive`](https://github.com/edt-edu/documentation-archive) *(private)* — Archive of technical and reference documentation used by the project, including documentation that cannot be redistributed publicly.

- [`fischertechnik-3d-models-restricted`](https://github.com/edt-edu/fischertechnik-3d-models-restricted) *(restricted access)* — 3D models and related Fischertechnik assets whose redistribution is restricted. Access is limited to authorized project members.

## Developer communication

Technical contributors can use the **edt-edu-dev@irisa.fr** mailing list for cross-repository development discussions and coordination.

The list is intended in particular for:

- discussing architecture, refactoring, and changes affecting several repositories;
- coordinating the integration and supervision of students contributing to EDT-Edu;
- announcing important issues or pull requests that require discussion or collective decisions;
- sharing technical information relevant to EDT-Edu developers.

Repository-specific work should remain in GitHub issues and discussions whenever possible. The mailing list complements these tools for topics that need broader coordination across the EDT-Edu development community.


---
[Website (edt.edu)](https://edt.edu) 
