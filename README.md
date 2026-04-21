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

- `[Rule 1]`
- `[Rule 2]`
- `[Rule 3]`
- `[Rule 4]`

---

# 5. Definition of Success

## 5.1 Definition of “Playable”
Your project will be considered complete only if these conditions are met.

- [ ] `[Condition 1]`
- [ ] `[Condition 2]`
- [ ] `[Condition 3]`
- [ ] `[Condition 4]`
- [ ] `[Condition 5]`

## 5.2 Minimum Viable Version
What is the smallest version of this project that still delivers the core experience?

**Response:**  
`[Write here]`

## 5.3 Stretch Features
What features are nice to have but not essential?

- `[Stretch feature 1]`
- `[Stretch feature 2]`
- `[Stretch feature 3]`

---

# 6. System Overview

## 6.1 Project Type
Check all that apply.

- [ ] Electronics-based
- [ ] Mechanical
- [ ] Sensor-based
- [ ] App-connected
- [ ] Motorized
- [ ] Sound-based
- [ ] Light-based
- [ ] Screen/UI-based
- [ ] Fabricated structure
- [ ] Game logic based
- [ ] Installation / tabletop experience
- [ ] Other: `[Write here]`

## 6.2 High-Level System Description
Explain how the system works in simple terms.

Include:
- input,
- processing,
- output,
- physical structure,
- app interaction if any.

**Response:**  
`[Write here]`

## 6.3 Input / Output Map

| System Part | Type | What It Does |
|---|---|---|
| `[Button / Sensor / Switch / App Input]` | Input | `[Describe]` |
| `[ESP32 / Controller]` | Processing | `[Describe]` |
| `[LED / Motor / Servo / Buzzer / Display]` | Output | `[Describe]` |
| `[Mechanical Assembly]` | Physical Action | `[Describe]` |

---

# 7. Sketches and Visual Planning

## 7.1 Concept Sketch
Add an early sketch of the full idea.

**Insert image below:**  
`[Upload image and link here]`

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
`[Upload image and link here]`

## 7.3 Approximate Dimensions

| Dimension | Value |
|---|---|
| Length | `[Write here]` |
| Width | `[Write here]` |
| Height | `[Write here]` |
| Estimated weight | `[Write here]` |

---

# 8. Mechanical Planning

## 8.1 Mechanical Features
Check all that apply.

- [ ] Gears
- [ ] Pulleys
- [ ] Belt drives
- [ ] Linkages
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
`[Write here]`

## 8.3 Motion Planning
If something moves, explain:
- what moves,
- what causes the movement,
- how far it moves,
- how fast it moves,
- what could go wrong.

**Response:**  
`[Write here]`

## 8.4 Simulation / CAD / Animation Before Making
If your project includes mechanical motion, document the digital planning before fabrication.

| Tool Used | File / Link | What Was Tested |
|---|---|---|
| `[Fusion 360 / Tinkercad / other]` | `[Link or screenshot]` | `[What did you validate?]` |
| `[Tool]` | `[Link or screenshot]` | `[What did you validate?]` |

## 8.5 Changes After Digital Testing
What changed after the CAD, animation, or simulation stage?

**Response:**  
`[Write here]`

---

# 9. Electronics Planning

## 9.1 Electronics Used

| Component | Quantity | Purpose |
|---|---:|---|
| `[ESP32]` | `1` | `[Main controller]` |
| `[Component]` | `[Qty]` | `[Purpose]` |
| `[Component]` | `[Qty]` | `[Purpose]` |

## 9.2 Wiring Plan
Describe the main electrical connections.

**Response:**  
`[Write here]`

## 9.3 Circuit Diagram
Insert a hand-drawn or software-made circuit diagram.

**Insert image below:**  
`[Upload image and link here]`

## 9.4 Power Plan

| Question | Response |
|---|---|
| Power source | `[USB / battery / adapter / other]` |
| Voltage required | `[Write here]` |
| Current concerns | `[Write here]` |
| Safety concerns | `[Write here]` |

---

# 10. Software Planning

## 10.1 Software Tools

| Tool / Platform | Purpose |
|---|---|
| `[MicroPython / Arduino / MIT App Inventor / CAD tool / other]` | `[Purpose]` |
| `[Tool]` | `[Purpose]` |

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
| `[Bluetooth connection]` | `[Method]` | `[What counts as success?]` |
| `[Mechanism movement]` | `[Method]` | `[What counts as success?]` |
| `[Sensor behavior]` | `[Method]` | `[What counts as success?]` |
| `[App communication]` | `[Method]` | `[What counts as success?]` |

## 16.2 Playtesting Plan

| Question | How You Will Check |
|---|---|
| Do players understand what to do? | `[Method]` |
| Is the interaction satisfying? | `[Method]` |
| Do players want another turn? | `[Method]` |
| Is the challenge balanced? | `[Method]` |
| Is the response clear and immediate? | `[Method]` |

## 16.3 Testing and Debugging Log

| Date | Problem Found | Type | What You Tried | Result | Next Action |
|---|---|---|---|---|---|
| `[April 9th, 2026]` | `[While making the layered portion of the sorting hat, I tried to hold it up, but my measurements were worng and I had messed up yhe radius of the different conical portions which were to be stacked up.]` | `[Technical / Mechanical / UI / Gameplay]` | `[What you did]` | `[Worked / Partly / Failed]` | `[Next step]` |
| `[Date]` | `[Describe issue]` | `[Type]` | `[What you did]` | `[Result]` | `[Next step]` |

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



```

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
