+++
title = "Competency Matrix"
weight = 1
+++

This page shows how the coursebook's projects cover every competency in the curriculum for the compulsory subject "Informatik und Künstliche Intelligenz" (Computer Science and AI, grades 9–11). For each grade, it gives a short description of the projects and a matrix listing the curriculum wording, the semester assignment and the project that secures each competency.

**Note:** German is the source of truth for the exact curriculum wording. The English wording below is a working translation for orientation; where in doubt, defer to the German page.

## Framework

- **Time:** 1 lesson per week, taught as a double lesson (100 min) every second week, which gives **15 blocks per grade**. Holidays and cancellations are already subtracted.
- **Projects:** 3–4 projects per grade of 3–4 blocks each. Every project leads to a visible result.
- **Core and extensions:** All students work on the **core**, and the core alone secures the competencies. Each project has 2–3 **extensions** for faster or especially interested students; these are not relevant to the competencies.
- **Spiral curriculum:** Each grade builds directly on the previous one (grade 10 assumes grade 9, grade 11 assumes grade 10).
- **Semester assignment:** The semester given in the curriculum is a default. The focus lies in that semester, and preparing or revisiting the topic in the other semester is allowed.
- **Hardware:** Every hardware project can be completed entirely with a **simulator**.
- **Tools:** One text-based programming language across all three grades, plus Markdown (9), SQL with a file-based database (10), and HTML/CSS/JavaScript with a small web server framework (11).

**Legend:** ● competency is developed in the core of this project · ○ competency is revisited and deepened

## Grade 9

**Common thread:** The measurement data from P9.2 feeds the AI model in P9.3, and P9.4 reuses material from P9.1–P9.3.

### Projects

**P9.1 Reaction Game** (blocks 1–4)
: Students use a microcontroller or simulator to build a reaction game or mini gadget with a button, LED and buzzer. They first model its behavior as a state diagram and only then program it in a text-based programming language.

**P9.2 Classroom Climate Station** (blocks 5–8)
: A sensor measures temperature, noise or light in the classroom and sends the readings over the local network to a class computer. The class traces the path of the data and the actors involved, works out when measurements become personal data, and weighs the measurement interval against energy consumption.

**P9.3 Open the Window? – Decision Tree** (blocks 9–12)
: Students build a decision tree from their own measurement data, first by hand and then with an algorithm. They use training and test data to determine the error rate. Finally, they assess a real AI system for suitability as well as ethical and inclusive aspects.

**P9.4 Tech Fair** (blocks 13–15)
: Each group designs a project page or poster in Markdown with a separate layout, using openly licensed media correctly. Students match the tasks from their own projects to IT career fields.

### Matrix

| Area | Competency (curriculum wording, translated) | Sem. | P9.1 | P9.2 | P9.3 | P9.4 |
| --- | --- | --- | :---: | :---: | :---: | :---: |
| 01 | examine and name the path of data from collection to analysis, and by which actors it is used and collected for which purposes. | WS+SS | | ● | ○ | |
| 02 | implement algorithms in a text-based programming language for simple applications. | WS+SS | ● | | | |
| 03 | create, apply and evaluate simple AI models with the help of an algorithm, and assess AI systems for their suitability as well as ethical and inclusive aspects. | WS+SS | | | ● | |
| 05 | explain the basic idea of local networks and simple protocols, and independently connect a device to a local network. | WS+SS | | ● | | |
| 08 | create and adapt digital artifacts while separating form and content, and reuse them responsibly with regard to intellectual property. | WS+SS | | | | ● |
| 09 | abstract and model real objects or situations in a state-based and process-oriented way. | WS+SS | ● | | | |
| 10 | describe the spheres of privacy under the GDPR and justify their own behavior in the context of their everyday lives. | WS+SS | | ● | | |
| 11 | explain which technical factors (e.g. computing power, data transfer, storage) influence the energy and resource consumption of digital systems, and design systems sustainably. | WS+SS | | ● | | |
| 11 | describe the central career fields of computer science and information technology, assign typical tasks to them, and explain where computer science and AI play a role in (working) life and in society. | WS+SS | | | | ● |

## Grade 10

**Common thread:** The device from P10.1 supplies the data for P10.2. WS = blocks 1–7, SS = blocks 8–15.

### Projects

**P10.1 Smart Home in a Shoebox** (blocks 1–3, WS)
: Students configure a microcontroller or simulator with sensors and actuators and make it controllable over the network. They investigate the system's behavior by varying thresholds, feedback and reaction times.

**P10.2 The Device Learns** (blocks 4–7, WS)
: Sensor or gesture data is stored in suitable data structures (list/ring buffer, dictionary, table). Students work through a perceptron step by step, first on paper and then in code, and use it to control the device. A short, hands-on run through clustering (e.g. k-means on 2D points) shows how to handle unlabeled data.
: *Time-critical:* 2–3 blocks for the perceptron, clustering only briefly.

**P10.3 Our Own Platform** (blocks 8–11, SS)
: The requirements for a mini social network are given as user stories plus a use-case and class diagram, and students work through them. From these, the class derives a data model, writes SQL queries and joins tables. Alongside this, students look at how platforms and identity systems are built, at participation in society, and at EU rules on AI.

**P10.4 Secret Messages & Explainer Video** (blocks 12–15, SS)
: Students encrypt messages by hand with a simple symmetric cipher (e.g. XOR or Vigenère) and work through small numeric examples of asymmetric key exchange (e.g. Diffie-Hellman) or encryption/signatures (e.g. RSA). They compare authentication methods (password, second factor, e-government ID), weighing security against usability. The result is an accessible multimedia explainer for a target group of their choice.

### Matrix

| Area | Competency (curriculum wording, translated) | Sem. | P10.1 | P10.2 | P10.3 | P10.4 |
| --- | --- | --- | :---: | :---: | :---: | :---: |
| 01 | carry out simple data modeling and queries and combine data from data stores. | SS | | | ● | |
| 02 | implement algorithms using suitable data structures. | WS | | ● | | |
| 03 | carry out basic machine learning methods step by step using suitable algorithms and explain how they work. | WS | | ● | | |
| 04 | configure computer systems with peripherals, sensors or actuators and basic network functionality, and use them for everyday tasks. | WS | ● | | | |
| 06 | build simple interactive systems and investigate and explain their behavior by varying inputs and feedback. | WS | ● | | | |
| 07 | understand requirements for software or technical systems expressed in natural language and simple graphical notations. | SS | | | ● | |
| 08 | create multimedia artifacts with different forms of access for different user groups (including with regard to inclusion) and justify the principles used. | SS | | | | ● |
| 10 | apply and explain different symmetric and asymmetric encryption and authentication methods, and weigh their advantages and disadvantages regarding security, usability and privacy in different social and legal contexts. | SS | | | | ● |
| 11 | explain how digital infrastructures (e.g. identity systems, platforms, e-government services, social media) are technically built and enable or limit participation in society, and assess the opportunities and risks of digital infrastructures. | SS | | | ● | |

## Grade 11

**Common thread:** The assistant is designed in P11.2 and built in P11.3. WS = blocks 1–8, SS = blocks 9–15.

### Projects

**P11.1 A Look Inside AI** (blocks 1–4, WS)
: Students first work through forward propagation in a mini network by hand or in a spreadsheet, then implement it in code. They test generative AI systematically and document errors and biases. An overview of "which method for which problem?" draws on the methods from grades 9 and 10. To finish, the class reflects on the effects of AI on the world of work.

**P11.2 An Assistant for Everyone** (blocks 5–8, WS)
: The class sketches an information system for the school that takes the interests of different groups into account from ethical and inclusive perspectives. Students compare forms of interaction and build paper prototypes in quick rounds. In a focused observation task (≈ 1 block), they compare two provided demo apps — a single data lookup (e.g. a page that reloads data on each click) and a video call with a persistent connection — by briefly interrupting the network connection and observing what happens in each case. From this they derive which technical requirements (retries, timeouts, reconnection) are needed for reliable use.

**P11.3 The Assistant Goes Online** (blocks 9–12, SS)
: Students build part of the P11.2 design as a small web app. They start from a given, faulty initial version and correct and improve its code. Along the way, they separate client and server parts and adapt the existing layout. While debugging stuck code, they run into the question of whether a program will ever finish or just needs more time; this motivates the halting problem as an example of a non-computable problem.

**P11.4 Data Detectives** (blocks 13–15, SS)
: Students learn the principles of OSINT and derive new information from their own (or a fictional) data footprint. In a guessing game played in pairs, they search for a name in a sorted list (e.g. a class list or phone book): one partner answers only "earlier" or "later" in the alphabet. They play once guessing in sequence (linear) and once always guessing the midpoint of the remaining range (binary), and compare how many questions each needs. Using provided code for linear search and a recursive and an iterative version of binary search, they then test the same idea on a larger dataset and measure the running time.

### Matrix

| Area | Competency (curriculum wording, translated) | Sem. | P11.1 | P11.2 | P11.3 | P11.4 |
| --- | --- | --- | :---: | :---: | :---: | :---: |
| 02 | improve/correct given program code where needed. | SS | | | ● | |
| 02 | compare algorithms using simple runtime estimates (recursive and non-recursive) and name an example of a non-computable problem. | SS | | | ● | ● |
| 03 | explain the basic functioning of neural networks and generative AI, analyze their results (including errors and bias), and reflect on the effects of AI on the world of work. | WS | ● | | | |
| 03 | compare AI application areas and justify which method is suitable for a given problem type. | WS | ● | | | |
| 05 | explain different models of network communication (e.g. stateless/connection-oriented), analyze network-based services, and assess which technical requirements are needed for reliable use. | WS | | ● | | |
| 06 | describe and compare forms of interaction with computer systems and classify their use for diverse user groups with justification. | WS | | ● | | |
| 08 | design simple web-based applications, distinguish client-side and server-side parts, and adapt existing web artifacts in a targeted way. | SS | | | ● | |
| 10 | explain the principles of open source intelligence (OSINT) and derive new information from their own data footprint. | SS | | | | ● |
| 11 | sketch computer systems that take different given interests and human needs into account, including from ethical and inclusive perspectives. | WS | | ● | | |

## Overview

| Grade | Projects | Blocks | Competencies covered |
| --- | --- | --- | --- |
| 9 | P9.1–P9.4 | 15 | 9 / 9 |
| 10 | P10.1–P10.4 | 15 | 9 / 9 |
| 11 | P11.1–P11.4 | 15 | 9 / 9 |
| **Total** | **12** | **45** | **27 / 27** |
