---
version: "0.1"
---
# Medical Robotics Atlas

> [!quote] What is the landscape of Medical Robotics, and where does each area fit within it? 

> i dont think i liked this one yet

## Purpose
- The Medical Robotics Atlas is the geographical map of the handbook.
Its purpose is to organize the entire field of Medical Robotics into *structured domains and subdomains*, allowing knowledge to be located within a broader context. Rather than functioning as a list of topics, the Atlas provides orientation, showing how different areas relate to each other and contribute to healthcare.
The Atlas also serves as a *navigation tool* for future specialization. As interests evolve, it helps identify where new concepts, projects, and research belong within the field.
## Description
- The Atlas is organized as a hierarchical structure.
Each domain represents a significant area of Medical Robotics, and each may contain multiple subfields. A domain is not intended to store detailed notes; instead, it acts as an index that points to concepts, projects, research questions, and relevant sections of the Question Journey.
The Atlas should remain stable over time. Changes should occur only when new technologies or research areas emerge or when the organization of the field becomes clearer.

## Structure

```
Medical Robotics

├── Domain
│    ├── Subdomain
│    │      ├── Technologies
│    │      ├── Applications
│    │      ├── Problems
│    │      ├── Concepts
│    │      ├── Projects
│    │      └── References
│    │
│    └── ...
│
└── ...
```

The Atlas answers one question repeatedly:
> **"Where does this belong?"**

## Rules
### Rule 1
Every topic must belong to at least one domain.
### Rule 2
Domains organize knowledge; they do not replace detailed notes.
### Rule 3
Organize by **purpose**, not by university disciplines.
For example, "Surgical Robotics" is a better domain than "Control Theory." Control Theory belongs elsewhere and supports many domains.
### Rule 4
A concept may appear in multiple domains through references rather than duplication.
### Rule 5
Each domain should begin with a short description explaining its purpose.
### Rule 6
Each domain should identify its major engineering challenges.
### Rule 7
Each domain should identify the healthcare problems it addresses.
### Rule 8
Domains should evolve slowly. Avoid reorganizing them unless there is a clear improvement in clarity or accuracy.
### Rule 9
Research papers, projects, and personal ideas should always be linked back to the appropriate domain.
### Rule 10
The Atlas should always reflect the current understanding of the Medical Robotics field, not temporary trends.

## Initial Domains
### 1. Surgical Robotics
**Purpose**
- Robotic systems that assist or perform surgical procedures with increased precision, dexterity, and control.
Examples:
- Robotic-assisted surgery
- Minimally invasive surgery
- Surgical navigation
- Robot-assisted endoscopy
### 2. Laboratory Robotics
**Purpose**
- Automation of biological, chemical, pharmaceutical, and medical laboratory tasks.
Examples:
- Sample handling
- Liquid handling
- Cell culture automation
- Hazardous experiment automation
- Autonomous laboratories
### 3. Rehabilitation Robotics
**Purpose**
- Robotic systems that support physical recovery, therapy, and motor rehabilitation.
Examples:
- Robotic exoskeletons
- Rehabilitation devices
- Therapy assistance
### 4. Prosthetics and Orthotics
**Purpose**
- Development of intelligent artificial limbs and assistive wearable devices.
Examples:
- Myoelectric prostheses
- Intelligent orthoses
- Adaptive prosthetic control
### 5. Assistive Robotics
**Purpose**
- Robots designed to improve independence and quality of life for patients and healthcare professionals.
Examples:
- Hospital service robots
- Elderly assistance
- Patient support
### 6. Medical Imaging and Navigation
**Purpose**
- Technologies that enable visualization, localization, and guidance during diagnosis or intervention.
Examples:
- Image-guided surgery
- Navigation systems
- Image registration
- 3D reconstruction
### 7. Microrobotics and Nanorobotics
**Purpose**
- Microscopic robotic systems capable of operating within biological environments.
Examples:
- Drug delivery
- Magnetic microrobots
- Capsule robots
- Swarm microrobotics
### 8. Foundational Technologies
This is a special domain.
- Unlike the others, it doesn't describe an application area. It groups technologies that support nearly every area of medical robotics.
Examples:
- Computer Vision
- Artificial Intelligence
- Embedded Systems
- Sensors
- Actuators
- Control Systems
- Machine Learning
- Human–Robot Interaction
- Haptics
- Soft Robotics
- Continuum Robotics
## Relationship with the Other Maps

### Question Journey
The Question Journey asks:
> "What should I learn next?"

The Atlas answers:
> "Where does this knowledge belong?"
### Competency Atlas
The Competency Atlas measures your ability within each domain and technology.
### Dependency Graph
The Dependency Graph explains the prerequisites needed to understand concepts found throughout the Atlas.

---

