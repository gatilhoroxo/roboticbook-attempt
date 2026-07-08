---
version: "0.1"
---
# Knowledge Note Standard
> [!quote] How should knowledge be recorded so it can be understood, connected, and reused in the future?
## Purpose
- The Knowledge Note Standard defines a common structure for recording concepts throughout the handbook.
Its purpose is to ensure that every note answers the same essential questions, making knowledge easier to understand, review, and connect. A consistent format reduces cognitive effort and allows attention to remain focused on learning rather than formatting.
The standard is intentionally simple in Version 0.1. It should encourage frequent use and evolve only when additional structure provides clear value.
## Description
A knowledge note represents **one concept**.
It should *capture the essence of that concept* without becoming a textbook chapter. The note is not intended to replace books, lectures, or papers; instead, it acts as your personal understanding of the topic.
Each note should be concise, connected to the rest of the handbook, and easy to update as your understanding improves.
## Structure

```
Question
↓
Intuition
↓
Definition
↓
Engineering Perspective
↓
Medical Robotics Perspective
↓
Connections
↓
Reflection
```

Simple enough that every note follows the same structure.
## Rules
### Rule 1
One note represents one concept.
### Rule 2
Begin with the question the concept answers.
### Rule 3
Write the intuition before the formal definition.
If you can't explain the intuition, you probably don't understand the concept well enough yet.
### Rule 4
Definitions should be precise but concise.
If they become too long, summarize the core idea and reference a textbook or paper.
### Rule 5
Always explain why the concept matters from an engineering perspective.
Ask:
> _"Why would an engineer care about this?"_
### Rule 6
Whenever possible, explain how the concept appears in medical robotics.
Even if the connection is small, making it explicit strengthens your mental model.
### Rule 7
Every note should connect to at least one other concept.
Knowledge grows as a network.
### Rule 8
Reflections should capture **your understanding**, not copy someone else's explanation.
### Rule 9
Keep notes short enough to review quickly.
The goal is understanding, not documentation.
### Rule 10
A note is never finished.
Update it whenever your understanding improves.
## Template
I think this template is exactly the right size for Version 0.1.
### Question
> What question does this concept answer?
### Intuition
> How would I explain this idea to someone seeing it for the first time?
### Definition
> What is the formal definition?
### Engineering Perspective
> Why is this concept important in engineering?
### Medical Robotics Perspective
> Where does this concept appear in medical robotics?
### Connections
**Requires**
...
**Supports**
...
**Unlocks**
...
### Reflection
- What surprised me?
- What is still confusing?
- What should I explore next?

## Relationship with the Other Maps
### Question Journey
The note answers one of the journey's questions.
### Medical Robotics Atlas
The note belongs to one or more Atlas domains.
### Competency Atlas
The note contributes evidence toward one or more competencies.
### Dependency Graph
The note explicitly records its prerequisites and what it enables.

---

<<<<<<< HEAD:handbook-v0.1/4_knowledge-note-standard.md

---
---

## Example
Let's imagine a note for **Sensors**.
### Question
How can a robot obtain information about its environment?
### Intuition
A sensor is like the robot's way of perceiving the world. Just as humans use eyes, ears, and touch, robots use devices that convert physical phenomena into information.
### Definition
A sensor is a device that measures a physical property and converts it into data that can be processed by a control system.
### Engineering Perspective
Sensors enable feedback, control, localization, monitoring, and decision-making.
Without sensors, most robots cannot adapt to changes in their environment.
### Medical Robotics Perspective
Examples include:
- surgical cameras,
- force sensors,
- ultrasound probes,
- encoders,
- IMUs,
- biosensors.
### Connections
Requires
- Signal basics
- Measurement concepts
Supports
- Control Systems
- Computer Vision
Unlocks
- Sensor Fusion
- Robot Perception
- Autonomous Systems
### Reflection
"I used to think cameras were the most important sensor. Now I understand that robots can perceive the environment through many different sensing modalities depending on the task."


---
=======
>>>>>>> 2f77e9d (feat: atualizações no handbook, readme e uma parte da estrutura):recursos/handbook-v0.1/4_knowledge-note-standard.md
