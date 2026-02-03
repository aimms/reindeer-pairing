# Reindeer Pairing Model 

[![Downloads](https://img.shields.io/github/downloads/aimms/reindeer-pairing/total?style=for-the-badge&logo=github&labelColor=000081&color=1847c9)](https://github.com/aimms/reindeer-pairing/releases)
![AIMMS Version](https://img.shields.io/badge/AIMMS-24.5-white?style=for-the-badge&labelColor=009B00&color=00D400)
![WebUI Version](https://img.shields.io/badge/WebUI-24.10.3.3-white?style=for-the-badge&labelColor=009B00&color=00D400)


This repository contains a functional AIMMS illustration of the **Stable Marriage Problem** (specifically the Stable Reindeer Pairing). It demonstrates how to pair "lefty" and "righty" reindeer in front of Santa's sleigh based on their individual preferences to ensure a stable and happy lineup.

## 🎯 Business Problem

The stable marriage problem is a classic optimization challenge in matching theory. In this festive scenario, Santa needs to find pairings where:
- **Stability:** No two reindeer would both prefer each other over their current assigned partners.
- **Preference Optimization:** Reindeer are matched based on ranked preference lists.
- **Variety:** Finding multiple stable solutions to allow Santa to vary the lineup year after year so the reindeer don't get bored.

## 📖 How to Use This Example

To get the most out of this model, we highly recommend reading our detailed step-by-step guide on the AIMMS How-to website:

👉 **[Read the Full Article: Reindeer Pairing Guide](https://how-to.aimms.com/Articles/434/434-reindeer-pairing.html)**

### Prerequisites
- **AIMMS:** You will need AIMMS installed to run the model. [Download the Free Academic Edition here](https://www.aimms.com/support/licensing/) if you are a student.
- **SQLite ODBC Driver:** This project uses a database for data persistence. Ensure you have the [SQLite ODBC Driver installed](https://how-to.aimms.com/Articles/118/118-Connect-SQLite.html).
- **WebUI:** This project features a complex custom page layout using CSS Grid and advanced UI styling.

### Technical Highlights
- **Constraint Programming (CP):** Uses the AIMMS CP Optimizer to handle logical "if-then" constraints and channel constraints.
- **Multiple Solutions:** Configured to return up to 1000 different stable pairings using `solution_storage_limit`.
- **DirectSQL:** Demonstrates how to use `DirectSQL` procedures to export the resulting pairings directly to a database.

## 🚀 Getting Started

1. **Download the Release:** Go to the [Releases](https://github.com/aimms/reindeer-pairing/releases) page and download the `.zip` file from the latest version.
2. **Open the Project:** Launch the `.aimms` file.
3. **Run the Model:** Use the WebUI workflow to solve the pairings and explore different stable configurations.

## 🤝 Support & Feedback

This example is maintained by the **AIMMS User Support Team**.
- Found an issue? [Open an issue](https://github.com/aimms/reindeer-pairing/issues).
- Questions? Reach out via the [AIMMS Community](https://community.aimms.com).

---
*Maintained by the AIMMS User Support Team. We optimize the way you build optimization.*
