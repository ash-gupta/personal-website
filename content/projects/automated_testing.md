---
title: "Automated Testing Software"
description: "A Python-based tool to streamline RF device testing, automating tasks and reducing manual effort."
dateString: November 2018
draft: false
tags: ["Python", "Project", "Automation"]
cover:
    image: "/projects/assets/automated_testing_cover.jpg"
---

During my third year of study, I interned at MimoMax Wireless, a Christchurch-based company specializing in the design and manufacturing of Multiple Input Multiple Output Radios.

My assignment was to design and develop an automated testing software, simplifying the laborious process of testing new radios.

## Project Requirements:

1. **User-Friendly GUI:** Intuitive interface for ease of use.
2. **Scalable Architecture:** Ability to accommodate new developments seamlessly.
3. **VISA Interface Compatibility:** Integration with VISA interface for enhanced flexibility.

The software, entirely crafted in Python, utilized PyQT for the GUI and VISA for testing equipment drivers. Given my initial unfamiliarity with PyQT and the VISA interface, there was a learning curve.

## Functionality Overview:

Upon initiating the software, it undergoes an initialization phase, dynamically discovering available drivers and configuring the GUI accordingly.

### Three User Modes:

1. **Equipment Control Panel:** Digital control to send commands via the VISA interface.
2. **Bench Testing:** Running compliance test scripts with user-entered parameters.
3. **Loop Script:** Creating and executing custom test scripts through a drag-and-drop interface.

### Visuals:

#### Control Panel
Configure the device under test and set parameters.
![Control Panel](/projects/assets/automated_testing_control_panel.jpg)

#### Equipment Control Panel
Dynamic loading based on available drivers, acting as a consolidated electronic control panel - to control the devices remotely.
![Equipment Control Panel](/projects/assets/automated_testing_equipment_control_panel.jpg)

#### Bench Testing
Enables engineers to run pre-compiled test cases in the background with minimal intervention. This is used by the team during the V&V stage to verify that the product meets regulatory standards.
![Bench Testing](/projects/assets/automated_testing_benchtest.jpg)

#### Loop Script
Allows engineers to create automated test scenarios without coding, using a drag-and-drop interface.
![Loop Script](/projects/assets/automated_testing_loop_script_panel.jpg)

## Impact:

The software drastically reduces human time by 98%, enabling more productive utilization rather than mundane testing.

Remarkably, this tool is still in use today (4 years later) by the MimoMax Team.
