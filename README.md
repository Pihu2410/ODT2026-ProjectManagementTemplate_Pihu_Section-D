# Open Design and Technology  
## Final Project README

> **Project Weight:** 70%  
> **Team Size:** 2 students  
> **Project Duration:** 4 weeks  
> **Class Time Available:** 6 hours per class  
> **Total Time Available:** 48 effort-hours per team  
> **Project Type:** Playful, interactive, technology-based experience

---

# Before you begin

## Fork and rename this repository
After forking this repository, rename it using the format:

`ODT-2026-TeamName`

### Example
`ODT-2026-PixelWizards`

Do not keep the default repository name.

---

# How to use this README

This file is your team’s **working project document**.

You must keep updating it throughout the 4-week build period.  
By the final review, this README should clearly show:
- your idea,
- your planning,
- your design decisions,
- your technical process,
- your build progress,
- your testing,
- your failures and changes,
- your final outcome.

## Rules
- Fill every section.
- Do not delete headings.
- If something does not apply, write `Not applicable` and explain why.
- Add images, screenshots, sketches, links, and videos wherever useful.
- Update task status and weekly logs regularly.
- Use this file as evidence of process, not only as a final report.

---

# 1. Team Identity

## 1.1 Studio / Group Name
`Schizophrenic Hat Maker`

## 1.2 Team Members

| Name | Primary Role | Secondary Role | Strengths Brought to the Project |
|---|---|---|---|
| `Pihu Pant` | `Coding + App + Fabrication` | `Electronics + Mechanics` | `[Write here]` |

## 1.3 Project Title
`[The Sorting Hat]`

## 1.4 One-Line Pitch
`[An enchanted animatronic Sorting Hat that uses the art of Divination and embedded robotics to ceremonially place young wizards into their Hogwarts houses.]`

## 1.5 Expanded Project Idea
In 1–2 paragraphs, explain:
- what your project is,
- what kind of playful experience it creates,
- what makes it fun, curious, engaging, strange, satisfying, competitive, or delightful,
- what technologies are involved.

**Response:**  
`[Growing up, I loved Harry Potter! I've read all the books and rewatched all the movies about 10 times already. And the one character that fascinated me the most was none other than the iconic Sorting Hat. So, having been given the brief for the ODT project, I decided to make it. But, with a twist... I worked on creating a functioning animatronic version of the infamous Sorting Hat that can actually sort people into their Hogwarts houses. I had seen so many toys of the sorting hat when I was younger. I used to be so intrigued, so I thought that making one, which actually interacted with users and created a similar experience for them, would create such an amazing memory and a sense of childhood connection for them.
What makes it fun is the sheer theatricality of it — a hat that physically moves and dramatically "predicts" your destiny for you. It feels alive. A hat with opinions and a personality defies expectations and imagination alike. The combination of physical motion from the servos, the sound, and a reveal moment from the app is what makes this experience and idea intriguing and satisfying. This, layered with the nostalgia of getting a Harry Potter experience (or something similar), is what increases the enjoyment of it.
The SG90 servos move the hat's mouth and head. The LM2596 and/or the DC Power Supply converts the input power down to a clean 5V to keep them running smoothly. Whereas an ESP32 controls the timing and triggers the movement of the motors at some certain degrees. The app keeps announcing the houses and as people keep on feeding their data into the app.]`

---

# 2. Philosophy Fit

## 2.1 Experience, Not Social Problem
This module does **not** require your project to solve a large social problem.

You are allowed to build:
- toys,
- games,
- interactive objects,
- playful machines,
- kinetic artifacts,
- humorous devices,
- strange but delightful experiences,
- things that are entertaining to use or watch.

## 2.2 What kind of experience are you creating?
Answer the following:
- What is the experience?
- What do you want the player or participant to feel?
- Why would someone want to try it again?

**Response:**  
`[I want to create a fun and immersive experience which instills a sense of nostalgia in the participant when they use the app to get sorted and the actual app-paired sorting hat announces their house. I want every Potterhead to feel like they lived out a childhood dream when participating in this sorting activity. I think the idea of getting a Hogwarts house, one which one might not even expect, will make them want to try this activity again and again, to get the house they wish for, even if it doesn't work.]`

## 2.3 Design Persona
Complete the sentence below:

> We are designing this project as if we are a small creative studio making a **[toy / game / playable object / interactive experience]** for **[children / teens / adults / classmates / exhibition visitors / mixed audience]**.

**Response:**  
`[I am designing this project as if I am part of a small creative studio making an interactive ecperience for all age groups who love Harry Potter, or don't but are just interested in this whimsical experience.]`

---

# 3. Inspiration

## 3.1 References
List what inspired the project.

| Source Type | Title / Link | What Inspired You |
|---|---|---|
| `[Video]` | `[[Link or title]](https://www.instructables.com/Full-Animatronic-Sorting-Hat-With-Custom-Software/)` | `[I borrowed or learned from the animatronic part of this existing project.]` |
| `[Video / Object]` | `[(https://www.instagram.com/reel/DXGUjeEEm3r/?igsh=MTNmbHJxYWE4ejZzOQ%3D%3D&wa_logging_event=video_play_open)]` | `[I kind of got inspired to lay the cloth layered on top of the basic structure of the animatronic.]` |

## 3.2 Original Twist
What makes your project original?

**Response:**  
`[Most sorting hat experiences are purely digital or purely physical. This one connects both — a phone app collects your name and date of birth, calculates your numerology life path number and destiny number, and that result determines your house, mixing a little bit of the art of Divination. The hat then speaks along with the app's content as the app sorts the person to their respective house. Another original feature that I decided to incorporate is that invisible connection between a number derived from your actual birth details and a physical object that reacts to it, making the experience feel genuinely personal and rather intriguing.]`

---

# 4. Project Intent

## 4.1 Core Interaction Loop
Describe the main loop of interaction.

Examples:
- press → launch → score → reset
- connect → control → observe → repeat
- turn → trigger → react → repeat
- move object → sensor detects → sound/light response → player reacts

**Response:**  
`User → App → ESP32 → Servo movement + audio response`

## 4.2 Intended Player / Audience

| Question | Response |
|---|---|
| Who is this for? | `[All potterheads who wish to experience the magic they've only witnessed on book pages and movie screens. Non-potterheads are also welcome.]` |
| Age range | `[For all]` |
| Solo or multiplayer | `[Solo]` |
| Expected duration of one round | `[1-2 minutes]` |
| What should the player feel? | `[The player should feel joy, amused and amazed to see the animatronic setup]` |
| Is explanation required before use? | `[It is required to be mentioned before hand that the Sorting Hat will sort on the basis of their name and date of birth.]` |

## 4.3 Player Journey
Describe exactly how a player will use the project.

1. **Approach:** `[The player gets intrigued by the moving anim]`
2. **Start:** `[How do they begin?]`
3. **First Action:** `[What do they do first?]`
4. **Main Interaction:** `[What keeps happening during use?]`
5. **System Response:** `[How does the project respond?]`
6. **Win / Lose / End Condition:** `[How does one round end?]`
7. **Reset:** `[How does the next round begin?]`

## 4.4 Rules of Play
If your project is a game, list the rules clearly.

- `[My artefact is not a game, its rather an experience. The only specification there is is that the app requires one's name and date of birth to sort him/her to a Hogwarts House.]`

---

# 5. Definition of Success

## 5.1 Definition of “Playable”
Your project will be considered complete only if these conditions are met.

- [ ] `[The servo mothers show movement about the facial expressions of the hat.]`
- [ ] `[The app is able to calculate the life path number and the destiny number from the name and date of birth of the person.]`
- [ ] `[The voice of the sorting hat is mostly accurate.]`
- [ ] `[All these features intrigue people into coming to experience the exhibit.]`

## 5.2 Minimum Viable Version
What is the smallest version of this project that still delivers the core experience?

**Response:**  
`[The smallest version of theproject, in my opinion, can be a cone with a slit as the mouth and one servo motor to communicate the same experience, with a simple app having a button which keeps saying iconic sorting hat sayings.]`

## 5.3 Stretch Features
What features are nice to have but not essential?

- `[LED lights (which I was planning earlier).]`
- `[Taking the a picture or face scanning in the app.]`
- `[The small downloadable card/certificate at the end of the sorting.]`

---

# 6. System Overview

## 6.1 Project Type
Check all that apply.

- [✅] Electronics-based
- [✅] Mechanical
- [ ] Sensor-based
- [✅] App-connected
- [✅] Motorized
- [✅] Sound-based
- [ ] Light-based
- [✅] Screen/UI-based
- [ ] Fabricated structure
- [ ] Game logic based
- [ ] Installation / tabletop experience
- [✅] Other: `[Experience based artefacty]`

## 6.2 High-Level System Description
Explain how the system works in simple terms.

Include:
- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
`The Sorting Hat is an animatronic system. The ESP32 microcontroller runs a MicroPython script that processes a pre-defined sequence of servo angles in a timed loop. It outputs movement across five servo motors controlling the mouth, eyes, and tip of the hat, producing expressive, lifelike animation for two minutes before resetting. There is also an app that sorts you into houses based on your Name and Birth date input. The system calculates your life path number and your destiny number, based on which we get assigned character traits. These traits get configured according to the 4 hogwart's houses.`

## 6.3 Input / Output Map

| System Part | Type | What It Does |
|---|---|---|
| `[Name and Age Input in app]` | Input | `[Used to calculate the life path number and the destiny number]` |
| `[ESP32 / Controller]` | Processing | `[Acts like the brain of the circuit, which basically commands other components to function a certain way - for me, it was connected to process input and output from the app and the servo motors, respectively.]` |
| `[Servo]` | Output | `[The up and down motion of the mouth, eyes and tip of the hat s it rotates from 0 deg to 180 deg.]` |
| `[Mechanical Assembly]` | Physical Action | `[The back and forth motion of the mouth, eyes and hat tip using the servo motors, while the app speaks and takes the name and age input of the participant to start the corting process.]` |

---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch
Add an early sketch of the full idea.

**Insert image below:**  
`[<img width="847" height="1447" alt="WhatsApp Image 2026-04-22 at 01 29 25 (1)" src="https://github.com/user-attachments/assets/29bf7615-cffb-4c63-bc06-34e9d446ccb4" />
]`

Example:
```md

```

## 7.2 Labeled Build Sketch
Add a sketch with labels showing:
- structure,
- electronics placement,
- user touch points,
- moving parts,
- output elements.

**Insert image below:**  
`[<img width="1599" height="899" alt="WhatsApp Image 2026-04-14 at 10 51 16" src="https://github.com/user-attachments/assets/36721383-73fc-4237-9e20-32f68c59176d" />]`

## 7.3 Approximate Dimensions

| Dimension | Value |
|---|---|
| Length | `[25-35cm]` |
| Width | `[12-15 cm]` |
| Height | `[20-30 cm]` |
| Estimated weight | `[~900 gms]` |

---

# 8. Mechanical Planning

## 8.1 Mechanical Features
Check all that apply.

- [ ] Gears
- [ ] Pulleys
- [ ] Belt drives
- [✅] Linkages
- [ ] Hinges
- [ ] Shafts
- [ ] Springs
- [ ] Bearings
- [ ] Wheels
- [ ] Sliders
- [ ] Levers
- [ ] Not applicable

## 8.2 Mechanical Description
Describe the mechanism and what it is meant to do.

**Response:**  
`[The mechanism in the sorting hat is a system of 5 servo motors, which upon running the code, rotate simulaneously at different angles and differenet intervals of time to mimick the movement of the infamouse talking hat from Harry Potter.]`

## 8.3 Motion Planning
If something moves, explain:
- what moves,
- what causes the movement,
- how far it moves,
- how fast it moves,
- what could go wrong.

**Response:**  
`[Five servo motors move within the hat — two controlling the mouth, two for the eyes, and one for the tip.Five servo motors move within the hat — two controlling the mouth, two for the eyes, and one for the tip. Each servo is driven by PWM signals from the ESP32, which vary the pulse width to rotate the horn to a target angle. Movement is constrained between roughly 45° and 135°, keeping all servos well within their safe mechanical range. Each frame executes in 250 milliseconds, giving the motion a deliberate, expressive pace rather than snapping instantly. Things that could go wrong include a servo binding against the fabric interior, duty cycle values drifting slightly on different hardware causing unintended strain, or the hat's physical structure resisting movement if mounting points shift — all of which could cause a servo to stall, overheat, or strip its gears over time.]`

## 8.4 Simulation / CAD / Animation Before Making
If your project includes mechanical motion, document the digital planning before fabrication.

| Tool Used | File / Link | What Was Tested |
|---|---|---|
| `[Phyiscal - Wooden scewers and ice cream sticks]` | `[N/A]` | `[To test the links/joints to be added to the servo motors]` |
| `[N/A]` | `[N/a]` | `[What did you validate?]` |

## 8.5 Changes After Digital Testing
What changed after the CAD, animation, or simulation stage?

**Response:**  
`[Not a lot changed after the testing, it just validated my approach and made it less difficult for me to execute it on the real model.]`

---

# 9. Electronics Planning

## 9.1 Electronics Used

| Component | Quantity | Purpose |
|---|---:|---|
| `[ESP32]` | `1` | `[Main controller]` |
| `[Power Supply]` | `[1]` | `[12V to 5 V supply]` |
| `[Servo Motors]` | `[5]` | `[To make the Animatronic move. ]` |

## 9.2 Wiring Plan
Describe the main electrical connections.

**Response:**  
`[Each servo has three wires, power, ground, and signal. All five servo power wires connect to a shared 5V supply, and all ground wires share a common ground with the ESP32. The signal wire of each servo connects to its own dedicated GPIO pin (13, 14, 25, 26, and 27), allowing the ESP32 to control each servo independently by sending PWM pulses down that wire.]`

## 9.3 Circuit Diagram
Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`

## 9.4 Power Plan

| Question | Response |
|---|---|
| Power source | `[ESP32 - USB + 5V Power supply - Adaptor]` |
| Voltage required | `The servo motors require 5V to move independently]` |
| Current concerns | `[Because of the use of a 12 V adaptor and a power suplly/even a buck convertor, using 5 servos simultaneously could lead to insuficient current supply.]` |
| Safety concerns | `[If powered on for too long, the power supply module can get fried/broken. If we keep testing servos again and again, the servos can max out and not work properly on the day of the exhibition.]` |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform | Purpose |
|---|---|
| `[MicroPython]` | `[To make the animatronic function and perform the tasks I want it to perform.]` |
| `[Google AI Studio]` | `[To make the app I want to connect to the sorting hat where the sorting hat acts as the sound output.]` |

## 10.2 Software Logic
Describe what the code must do.

Include:
- startup behavior,
- input handling,
- sensor reading,
- decision logic,
- output behavior,
- communication logic,
- reset behavior.

**Response:**  
`[Write here]`

## 10.3 Code Flowchart
Insert a flowchart showing your code logic.

Suggested sequence:
- start,
- initialize,
- wait for input,
- read input,
- decision,
- trigger output,
- repeat or reset,
- error handling.

**Insert image below:**  
`[Upload image and link here]`

## 10.4 Pseudocode

```text
[Write your pseudocode here]
```

---

# 11. MIT App Inventor Plan

## 11.1 Is an app part of this project?
- [ ] Yes
- [ ] No

If yes, complete this section.

## 11.2 Why is the app needed?
Explain what the app adds to the experience.

Examples:
- remote control,
- score tracking,
- mode selection,
- personalization,
- triggering effects,
- displaying data.

**Response:**  
`[Write here]`

## 11.3 App Features

| Feature | Purpose |
|---|---|
| `[Bluetooth connect button]` | `[Purpose]` |
| `[Score display]` | `[Purpose]` |
| `[Control button / slider / label]` | `[Purpose]` |

## 11.4 UI Mockup
Insert a sketch or screenshot of the app interface.

**Insert image below:**  
`[Upload image and link here]`

## 11.5 App Screen Flow

1. `[Step 1]`
2. `[Step 2]`
3. `[Step 3]`
4. `[Step 4]`

---

# 12. Bill of Materials

## 12.1 Full BOM

| Item | Quantity | In Kit? | Need to Buy? | Estimated Cost | Material / Spec | Why This Choice? |
|---|---:|---|---|---:|---|---|
| `[ESP32]` | `1` | `Yes` | `No` | `0` | `[Spec]` | `[Reason]` |
| `[Item]` | `[Qty]` | `[Yes/No]` | `[Yes/No]` | `[Cost]` | `[Spec]` | `[Reason]` |
| `[Item]` | `[Qty]` | `[Yes/No]` | `[Yes/No]` | `[Cost]` | `[Spec]` | `[Reason]` |

## 12.2 Material Justification
Explain why you selected your main materials and components.

Examples:
- Why acrylic instead of cardboard?
- Why MDF instead of 3D print?
- Why servo instead of DC motor?
- Why bearing instead of a plain shaft hole?

**Response:**  
`[Write here]`

## 12.3 Items to Purchase Separately

| Item | Why Needed | Purchase Link | Latest Safe Date to Procure | Status |
|---|---|---|---|---|
| `[Item]` | `[Reason]` | `[Link]` | `[Date]` | `[Pending / Ordered / Received]` |
| `[Item]` | `[Reason]` | `[Link]` | `[Date]` | `[Pending / Ordered / Received]` |

## 12.4 Budget Summary

| Budget Item | Estimated Cost |
|---|---:|
| Electronics | `[Cost]` |
| Mechanical parts | `[Cost]` |
| Fabrication materials | `[Cost]` |
| Purchased extras | `[Cost]` |
| Contingency | `[Cost]` |
| **Total** | `[Cost]` |

## 12.5 Budget Reflection
If your cost is too high, what can be simplified, removed, substituted, or shared?

**Response:**  
`[Write here]`

---

# 13. Planning the Work

## 13.1 Team Working Agreement
Write how your team will work together.

Include:
- how tasks are divided,
- how decisions are made,
- how progress will be checked,
- what happens if a task is delayed,
- how documentation will be maintained.

**Response:**  
`[Write here]`

## 13.2 Task Breakdown

| Task ID | Task | Owner | Estimated Hours | Deadline | Dependency | Status |
|---|---|---|---:|---|---|---|
| T1 | `[Finalize concept]` | `[Name]` | `2` | `[Date]` | `None` | `To Do` |
| T2 | `[Complete BOM]` | `[Name]` | `1` | `[Date]` | `T1` | `To Do` |
| T3 | `[Test electronics]` | `[Name]` | `2` | `[Date]` | `T1` | `To Do` |
| T4 | `[Build structure]` | `[Name]` | `4` | `[Date]` | `T1` | `To Do` |
| T5 | `[Write control code]` | `[Name]` | `4` | `[Date]` | `T3` | `To Do` |
| T6 | `[Integrate system]` | `[Name]` | `4` | `[Date]` | `T4, T5` | `To Do` |
| T7 | `[Playtest]` | `[Name]` | `2` | `[Date]` | `T6` | `To Do` |
| T8 | `[Refine and document]` | `[Name]` | `3` | `[Date]` | `T7` | `To Do` |

## 13.3 Responsibility Split

| Area | Main Owner | Support Owner |
|---|---|---|
| Concept and gameplay | `[Name]` | `[Name]` |
| Electronics | `[Name]` | `[Name]` |
| Coding | `[Name]` | `[Name]` |
| App | `[Name]` | `[Name]` |
| Mechanical build | `[Name]` | `[Name]` |
| Testing | `[Name]` | `[Name]` |
| Documentation | `[Name]` | `[Name]` |

---

# 14. Weekly Milestones

## 14.1 Four-Week Plan

### Week 1 — Plan and De-risk
Expected outcomes:
- [ ] Idea finalized
- [ ] Core interaction decided
- [ ] Sketches made
- [ ] BOM completed
- [ ] Purchase needs identified
- [ ] Key uncertainty identified
- [ ] Basic feasibility tested

### Week 2 — Build Subsystems
Expected outcomes:
- [ ] Electronics tests completed
- [ ] CAD / structure planning completed
- [ ] App UI started if needed
- [ ] Mechanical concept tested
- [ ] Main subsystems partially working

### Week 3 — Integrate
Expected outcomes:
- [ ] Physical body built
- [ ] Electronics integrated
- [ ] Code connected to hardware
- [ ] App connected if required
- [ ] First playable version exists

### Week 4 — Refine and Finish
Expected outcomes:
- [ ] Technical bugs reduced
- [ ] Playtesting completed
- [ ] Improvements made
- [ ] Documentation completed
- [ ] Final build ready

## 14.2 Weekly Update Log

| Week | Planned Goal | What Actually Happened | What Changed | Next Steps |
|---|---|---|---|---|
| Week 1 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |
| Week 2 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |
| Week 3 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |
| Week 4 | `[Write here]` | `[Write here]` | `[Write here]` | `[Write here]` |

---

# 15. Risks and Unknowns

## 15.1 Risk Register

| Risk | Type | Likelihood | Impact | Mitigation Plan | Owner |
|---|---|---|---|---|---|
| `[Example: Bluetooth disconnects]` | `Technical` | `Medium` | `High` | `[Fallback interaction / simplify connection flow]` | `[Name]` |
| `[Example: Structure breaks during play]` | `Mechanical` | `Medium` | `High` | `[Reinforce joints / change material]` | `[Name]` |
| `[Risk]` | `[Technical / Material / Time / Gameplay]` | `[Low/Medium/High]` | `[Low/Medium/High]` | `[Plan]` | `[Name]` |
| `[Risk]` | `[Type]` | `[Low/Medium/High]` | `[Low/Medium/High]` | `[Plan]` | `[Name]` |

## 15.2 Biggest Unknown Right Now
What is the single biggest uncertainty in your project at this stage?

**Response:**  
`[Write here]`

---

# 16. Testing and Playtesting

## 16.1 Technical Testing Plan

| What Needs Testing | How You Will Test It | Success Condition |
|---|---|---|
| `[Bluetooth connection]` | `[N/A]` | `[N/A]` |
| `[Mechanism movement]` | `[I'll test it by testing one of the servo joints. Then 3 together and then all 5 together.]` | `[If all 5 servos move together, I would count that as a success because the angle at which they rotate is something I can adjust.]` |
| `[Sensor behavior]` | `[N/A]` | `[N/A]` |
| `[App communication]` | `[In my case, I would connect the app to the ESP32 via WiFi, and to verify, we'll first check by establishing a connection and running a code for the WiFi connection. Then we can establish a connection using the static IP address of the ESP32.]` | `[If a simple function can be carried out through the app and to the ESP32, then I would consider a success.]` |

## 16.2 Playtesting Plan

| Question | How You Will Check |
|---|---|
| Do players understand what to do? | `[N/A]` |
| Is the interaction satisfying? | `[I would observe the level of intrigue in the their actions, their facial expressions and their body language around the experience and alos while they are experiencing it.]` |
| Do players want another turn? | `[If they disagree with the verdict of the sorting hat, I would assume they would want to try it again.]` |
| Is the challenge balanced? | `[N/A]` |
| Is the response clear and immediate? | `[If they immediately start reacting to the different aspects of the experience, I would say that the response becomes clear.]` |

## 16.3 Testing and Debugging Log

| Date | Problem Found | Type | What You Tried | Result | Next Action |
|---|---|---|---|---|---|
| `[April 9th, 2026]` | `[While making the layered portion of the sorting hat, I tried to hold it up, but my measurements were worng and I had messed up yhe radius of the different conical portions which were to be stacked up.]` | `[Mechanical]` | `[I stacked and slotted it in a way which helped it the structure balance more, yet still look just as crooked and whimsical.]` | `[Worked]` | `[After that, I stuck the cardboard circular servo bases inside the conicalstructures.]` |
| `[April 18th, 2026 - April 19th, 2026]` | `[As I was making the app, I kept coming across an error where the placement of the components were very off and I couldn't find my way around it.]` | `[UI]` | `[Entirely changed the way I was making the app. Instead of using the classic MIT App Inventor, I decided to use Google AI Studio.]` | `[The app came out better than ever]` | `[I tried to connect the app to the ESP32, but it didn't work.]` |

## 16.4 Playtesting Notes

| Tester | What They Did | What Confused Them | What They Enjoyed | What You Will Change |
|---|---|---|---|---|
| `[Senior]` | `[They all asked if they had to wear it on their head to be sorted]` | `[How was the hat going to moving.]` | `[THey were excited to be sorted and really intrigued by the fact that the hat was moving via code.]` | `[I will try to make it wearable since it is not currently wearable.]` |
| `[Peer]` | `[They saw the skeleton of the hat and asked if I was making the sorting hat]` | `[How did it work?]` | `[It moves like the actual hat and you can get sorted into a house]` | `[I think I'll change some of the servo placements and might even increase the proportions of the hat itself to add more room for movement for the servos.]` |

---

# 17. Build Documentation

## 17.1 Fabrication Process
Describe how the project was physically made.

Include:
- cutting,
- 3D printing,
- assembly,
- fastening,
- wiring,
- finishing,
- revisions.

**Response:**  
`[I experimented with making the base using corrugated cardboard, which did not prove to be useful. I then made the base with thick chart paper, and this became my base model. Here, I made the servo bases with cardboard, where I stuck the servo motors. Then for the servo joints, for the free movement within the sorting hat, I used the plastic sketch pen and marker barrels, which I then fixed to the servo with screws. This is when my base model was ready.
Then, I covered the hat with white musline cloth, which I then painted with brown and black paint to give more of the sorting hat look.]`

## 17.2 Build Photos
Add photos throughout the project.

Suggested images:
- early sketch,
- prototype,
- electronics testing,
- mechanism test,
- app screenshot,
- final build.

Example:
```md

-

```<img width="847" height="1447" alt="WhatsApp Image 2026-04-22 at 01 29 25 (1)" src="https://github.com/user-attachments/assets/3e39ab16-bab8-4a8b-bd6c-d8b59b0b0760" />
<img width="1600" height="1082" alt="WhatsApp Image 2026-04-22 at 01 29 25" src="https://github.com/user-attachments/assets/13ce9e1e-e7d5-4d95-a97c-66cf6fc20d52" />
<img width="899" height="1599" alt="WhatsApp Image 2026-04-22 at 01 43 03" src="https://github.com/user-attachments/assets/9d2b0a03-b4d7-4fd2-b4a2-e9793e7e8368" />
<img width="899" height="1599" alt="WhatsApp Image 2026-04-22 at 01 43 03 (2)" src="https://github.com/user-attachments/assets/5002d6c7-0f3a-4fd8-b351-133e3ab7c4f3" />
<img width="900" height="1600" alt="WhatsApp Image 2026-04-22 at 01 43 03 (1)" src="https://github.com/user-attachments/assets/b4aca397-cebf-4665-84d0-69d93e40bc33" />
<img width="900" height="1600" alt="WhatsApp Image 2026-04-22 at 01 43 02" src="https://github.com/user-attachments/assets/0a7c6488-ed5f-4c2d-b3f7-eda5b257ab3f" />
<img width="899" height="1599" alt="WhatsApp Image 2026-04-22 at 01 43 02 (3)" src="https://github.com/user-attachments/assets/3090d629-b3c1-4620-9912-9ae3aec841fa" />
<img width="899" height="1599" alt="WhatsApp Image 2026-04-22 at 01 43 02 (2)" src="https://github.com/user-attachments/assets/ff535ecc-cbf9-4526-a955-48f289694626" />
<img width="899" height="1599" alt="WhatsApp Image 2026-04-22 at 01 43 02 (1)" src="https://github.com/user-attachments/assets/c954a4bb-6270-47af-83d1-f1e9824ca267" />
<img width="900" height="1600" alt="WhatsApp Image 2026-04-22 at 01 43 01" src="https://github.com/user-attachments/assets/910eb253-fdc5-431e-97c9-3501bdfcebe1" />
<img width="1600" height="900" alt="WhatsApp Image 2026-04-22 at 01 43 01 (2)" src="https://github.com/user-attachments/assets/ff09c79f-1d58-4c83-9f69-9acb003c5f65" />
<img width="900" height="1600" alt="WhatsApp Image 2026-04-22 at 01 43 01 (1)" src="https://github.com/user-attachments/assets/d78298a3-6dec-40ab-b068-c032c2c2f991" />
<img width="900" height="1600" alt="WhatsApp Image 2026-04-22 at 01 43 00" src="https://github.com/user-attachments/assets/068cf913-7fd4-4a9b-b096-b33a2f5b7413" />
<img width="899" height="1599" alt="WhatsApp Image 2026-04-22 at 01 42 59" src="https://github.com/user-attachments/assets/885054c6-04dc-4ed5-89d3-c24f94f54b6a" />
<img width="1600" height="900" alt="WhatsApp Image 2026-04-22 at 01 42 59 (2)" src="https://github.com/user-attachments/assets/0aaf84d2-cd6e-4fcd-8ca2-0f60847f9610" />
<img width="900" height="1600" alt="WhatsApp Image 2026-04-22 at 01 42 59 (1)" src="https://github.com/user-attachments/assets/0fff8060-26dc-461c-a325-308f7d0dd1b6" />


## 17.3 Version History

| Version | Date | What Changed | Why |
|---|---|---|---|
| `Sorting hat combined with the app` | `[April 9th, 2026]` | `[Decided to add leds after a while which would flash the different colours of the houses while being sorted]` | `[I thought it would look cool as someone gets sorted as the hat's eyes reflect the colour of their houses.]` |
| `LED version` | `[April 15th, 2026]` | `[Ditched the LEDs in the eyes idea.]` | `[I actually forgot about them, and I had made most of the circuit connections by then. But the issue I understood was that there would be 8 LEDs in the eye cavity where the servo motors are also present - the LEDs might interfere with their movement]` |
| `Might not even make it` | `[April 19th 2026` | `[I might not be able to make my project anymore.]` | `[The Power module caught fire, the ESP32 got corrupted, and my servo motors stopped working.]` |
| `We can do this` | `[April 20th 2026 - April 21st, 2026` | `[I gave it a few more goes, while aslo asking for moy friend's power supply, and buying myself a buck converter and an ESP32.]` | `[I realised that I couldn't let go of the project I had been working so hard for in the last few weeks, so I decided to retrace my steps and start over. And in exactly 24 hours with 50+ hours of now sleep, I had finally made my sorting had and the app.]` |

---

# 18. Final Outcome

## 18.1 Final Description
Describe the final version of your project.

**Response:**  
`[Right now, my project is an animatronic Sorting Hat from Harry Potter, which, when code runs, moves its 5 servo motors to mimic the hat's talking mechanism. Then, its partner app is where it scans the face and says some very iconic sorting hat dialogues in that deep, gravelly voice we all know so well. After the picture gets scanned, we put in our name, and our date of birth and the app calculates the life path number and the destiny number, which gives certain characteristics to people, and these characteristics correspond to the sorting of the houses. After the sorting is done, there is a certificate of sorts, which we can read for download for ourselves.]`

## 18.2 What Works Well
- `[The way the hat is structured and coloured works nicely.]`
- `[The movement of the servo motors create a good mimicking action of the sorting hat's talking.]`
- `[The buck convertor works well with heavy structures like these.]`

## 18.3 What Still Needs Improvement
- `[The 5 servo system moving the hat needs to be planned and placed better.]`
- `[The connection between the app and the hat can be established more efficiently ]`
- `[The assembly and colour of the hat itself can be improved.]`

## 18.4 What Changed From the Original Plan
How did the project change from the initial idea?

**Response:**  
`[Initially, the app and the hat would have been part of one single system, but due to constant challenges with my ESP32 not being able to connect with the app, and the issues with my power supply module, I separated the system into layers and validated them independently, which changed the course of my project but also kept its essence intact.
]`

---

# 19. Reflection

## 19.1 Team Reflection
What did your team do well?  
What slowed you down?  
How well did you manage time, tasks, and responsibilities?

**Response:**  
`[My teammate and I mutually decided that we wanted to work on different projects, so working alone meant I was responsible for every decision, which was both freeing and overwhelming at times. There was no one to split tasks with when things went wrong, so debugging, fabrication, and coding all fell on me simultaneously. Internalised crashouts became a normal occurrence when working on the project. Time management suffered as a result, underestimating how long physical assembly would take, consistently eating into the time I'd planned for testing, debugging, and refinement.]`

## 19.2 Technical Reflection
What did you learn about:
- electronics,
- coding,
- mechanisms,
- fabrication,
- integration?

**Response:**  
`[This project taught me that servo electronics are far more sensitive than expected, with small wiring inconsistencies causing unpredictable behaviour, and ultimately, sudden crashes. Writing clean, structured MicroPython made debugging much easier. And mechanically mounting servos inside a fabric hat required more precision than anticipated. Fabrication involved constant compromises, and integrating all five components revealed that nothing works in isolation — every layer affects the next, and then ultimately the final submission.]`

## 19.3 Design Reflection
What did you learn about:
- designing for play,
- delight,
- clarity,
- physical interaction,
- player understanding,
- iteration?

**Response:**  
`[Working on the Sorting Hat taught me that physical interaction has real consequences (good and bad) that code alone can't predict, servo calibration and my ESP32 catching fire being the clearest examples. But the moment servos showed combined movements, it brought so much joy and relief to see how something that seemed impossible a second ago became something I overcame with a few syntax changes. This relief brings clarity, and it then leads to iteration, which is where most real design decisions happen. Here, designing for play ultimately means making something feel alive, not just functional.]`

## 19.4 If You Had One More Week
What would you improve next?

**Response:**  
`[If I had been given one more week to work on the project, I would've tried to make the hat entirely wearable, along with that, I think, I would want to explore making the base wia 3D printing, which would have made the structure easier to handle and sturdier.]`

---

# 20. Final Submission Checklist

Before submission, confirm that:
- [ ] Team details are complete
- [ ] Project description is complete
- [ ] Inspiration sources are included
- [ ] Player journey is written
- [ ] Sketches are added
- [ ] BOM is complete
- [ ] Purchase list is complete
- [ ] Budget summary is complete
- [ ] Mechanical planning is documented if applicable
- [ ] App planning is documented if applicable
- [ ] Code flowchart is added
- [ ] Task breakdown is complete
- [ ] Weekly logs are updated
- [ ] Risk register is complete
- [ ] Testing log is updated
- [ ] Playtesting notes are included
- [ ] Build photos are included
- [ ] Final reflection is written

---

# 21. Suggested Repository Structure

```text
project-repo/
├── README.md
├── images/
│   ├── concept-sketch.jpg
│   ├── labeled-sketch.jpg
│   ├── circuit-diagram.jpg
│   ├── ui-mockup.jpg
│   ├── prototype-1.jpg
│   └── final-build.jpg
├── code/
│   ├── main.py
│   ├── test_code.py
│   └── notes.md
├── cad/
│   ├── models/
│   └── screenshots/
└── docs/
    ├── references.md
    └── extra-notes.md
```

---

# 22. Instructor Review

## 22.1 Proposal Approval
- [ ] Approved to proceed
- [ ] Approved with changes
- [ ] Rework required before proceeding

**Instructor comments:**  
`[Instructor fills this section]`

## 22.2 Midpoint Review
`[Instructor fills this section]`

## 22.3 Final Review Notes
`[Instructor fills this section]`
