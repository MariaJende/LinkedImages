
# 1st Term Project - Project Plan

 ***Maria Jende, 14.01.2026***  

</br>

## Personal Motivation

With my first-term project, I aim to build my understanding and skillset in creative coding and programming in general, with a particular focus on the technical foundations of particle simulation for web-based applications. I also want to challenge myself by diving into an unfamiliar topic to me. For that reason, I’m glad to have the opportunity through this project to gain hands-on experience in creating web-based applications that are visually engaging and interactive for users.  
</br>

### References

Particle simulation:  
<https://nullprogram.com/webgl-particles/>  
<https://particle-love.com/>  
<https://particlesimulation.w3spaces.com/>

Three.js "pathway experiences":  
<https://www.aquarium.ru/en>  
<https://a-way-to-go.com/>  
<https://logartis.info/>  
</br>

## Project Description

For my first-term project, I aim to strengthen my creative coding skills and deepen my understanding of particle simulation. To achieve this, I plan to develop an interactive web application using three.js.

The experience will guide the user along a rollercoaster-like pathway that can be controlled interactively: the user will be able to move forward, pause, or travel backward along the path. Throughout this journey, different particle simulations will appear, evolve, and eventually dissolve. The overarching goal of the website is to create an interactive and visually playful experience.

I will begin by focusing on the core technical functionality rather than visual refinement. This includes implementing the scrollable pathway and establishing a stable system for particle evolution. Once the project reaches a technically stable state, I will expand upon it by introducing more complex particle behaviors and refining their motion to create more engaging dynamics as well as working on visual aesthetics.

Eventually, I would like the particles to form simple shapes that could support a small narrative/topic, which is yet to be defined. Additionally, to further enhance user engagement, I aim to incorporate particle interactions that respond to mouse hovering. These features, however, are considered optional extensions and are not part of the project’s minimum viable outcome.

Visually I want it to be bright and colourful without coming off too strong, so looking more at natural as well as muted and pastel colors.

Regarding audio, this will be the area of least focus due to time constraints. I plan to use subtle ambient sound, either royalty-free material or compositions created by myself using Ableton and Vital, to complement the visual experience without becoming a central element.

### Moods

| <img src="https://i.pinimg.com/1200x/95/5a/04/955a048904f3785207e680d34b62ceac.jpg" alt="Mood 1" width="200"> | <img src="https://i.pinimg.com/736x/bc/2f/78/bc2f7803b24f1fdd86bfcecdc212bcb2.jpg" width="200"> | <img src="https://i.pinimg.com/736x/8b/a5/b9/8ba5b93fe89dc0b9cc5614ddc9a2a1ab.jpg" width="200"> | <img src="https://i.pinimg.com/1200x/f6/5e/98/f65e98845f0b0be84ec3af3bcc0fd34f.jpg" width="200"> | <img src="https://i.pinimg.com/736x/17/fb/52/17fb52cdb83e896cb3b8163204d153a8.jpg" width="200"> |
| ----- | ----- |  ----- |  ----- |  ----- |
| https://pin.it/7AtMGJR8J | https://pin.it/4G6dCbUkW | http://phototrails.info/visualizations/radial-visualization/ | https://pin.it/AkEora7lZ | https://sk.pinterest.com/pin/11399805458537751/ |


## Categorization

**Creative/artistic development | Software development | Research/Experimentation | Algorithms |  Audio-visual design**

The intended result is focusing on creating a visually interesting and interactive user experience and therefore falls within the domain of **creative and artistic development**.

At the same time, the project aligns with **software development**, since it involves building a technically stable interactive website using three.js, including user control and particle behavior simulation.

Additionally, the project can be understood as **personal research and experimentation**, as it is driven by an exploratory learning process focused on strengthening creative coding skills and investigating particle simulation techniques through iterative development.

**Algorithms** are also present, particularly in the design and evolution of the beforementioned particle systems, although algorithm creation is not the primary focus.

While the project only eventually include audiovisual components, such as motion reactive audio and subtle ambient sound, **audio-visual design** remains a secondary concern.

Narrative development and hardware or pipeline development do not currently play a central role in the project.  
</br>

## Technical Setup / Tech Stack

This technical workflow is subject to change or can include mistakes since I’m still unfamiliar with the specific workflow necessary to achieve this.

The core technical component is three.js, which is used to render the 3D environment, manage the camera, and display the particle systems. JavaScript serves as the main programming language, connecting user input to visual behavior. I will use VS Code as code editor.

The project is developed as a web-based application. The website is hosted as static files on a server, but is executed locally in the user’s browser using JavaScript and WebGL.
All components (rendering, interaction, particle simulation, audio etc.) are integrated within a single browser-based system, allowing them to influence one another in real time.  
User interaction is handled through standard web input methods such as scrolling, mouse movement, and hovering, which control navigation along the path (and might influence particle and audio behavior).

```mermaid
flowchart LR
    A[Project is developed using personal equipmentand VS Code for JavaScript, Eventually Ableton and Vital for sound generation] --> B[Upload files to the hosting server like Netlify or GitHub Pages, which stores Index html, javascript files, assets etc.]
    B --> C[User opens website] --> D[Files downloaded from hosting server to user's browser] --> E[Website 3d scene runs locally on user's device] 
    style fill:342535,stroke:transparent,color:#ffffff
```
</br>

## Unique selling point

For me, the main value of this project lies in my personal learning process and in creating an engaging outcome for the user. While the concept itself is not entirely new or innovative, the project aims to result in an experience that is visually pleasing and interactive, with the potential to create a small moment of curiosity or enjoyment.  
</br>

## Expected Results

Since I am a novice in creative coding, it is difficult for me to assess what can be regarded as a realistic outcome within the given scope.

### Baseline solution

At the very least, I would like to reach a point where I have a short website (approximately 5 seconds when constantly scrolling) featuring a simple particle animation and basic interaction. The user will be able to scroll forward, while stopping the scroll will result in the experience pausing. At this stage, the visual appearance is secondary. The most important goal is to achieve a stable website with the key functionalities in place. These include scrolling along a pathway and at least one basic particle simulation. The audio will consist of royalty-free ambient sound.
Best possible solution
If everything works out as planned, the best possible solution would include all elements of the baseline solution, with increased effort placed especially on design, particle behaviour, interactivity, and audio. The design would be further refined, including particle shapes, backgrounds, pathway design, and colour scheme. The particles would be animated in more interesting and diverse ways and might optionally form specific shapes or patterns. The pathway interactivity would be extended to allow the user to move backwards, and possibly to influence particle behaviour through mouse hovering. Last but not least, I would love to add a self-made ambient sound.  
</br>

### Vision and Future Work

I would love to use this project as the groundwork for a more complex website, which aims to tell a narrative or offer additional functionality.  
For example, it could become the landing page or an add-on for my personal portfolio website.  
Another idea, which I personally would really enjoy, is to support the theme of memories and their fading, visualised through particles. For example, users could upload images that they like and want to preserve and remember in the future. There could also be the possibility to add text. The idea is to create an interactive photo album along the pathway, where the user’s personal images appear and dissolve through a particle simulation. Of course, questions of data handling and privacy need to be carefully considered to ensure a safe experience when users upload private photos. This photo album could then be preserved for the user to rediscover at some point in the future, for example via email, download, or another form of retrieval.

Regarding the scaling of the project, if I have time left, I would first try to increase the level of interactivity for the user. This could include influencing particles, audio reacting to user actions and particle behaviour, as well as enhancing the visual interest, for example through particles forming shapes.

In a future iteration, I would love to place a stronger focus on audio, making it more fitting to the particle dynamics and the overall mood of the experience. I can also imagine making particle behaviour reactive to audio. For example, particles could trigger subtle sounds when the user hovers over them, or when they dissolve or change. Audio feedback could also be tied to the user’s movement along the path, such as stopping, moving forward, or travelling backward.  
</br>

| <img src="https://i.pinimg.com/736x/70/11/51/701151a12c9330454e7415a4d58691f5.jpg" width="200"> | <img src="https://i.pinimg.com/1200x/0f/be/a6/0fbea61ac0e95e89b35f33d29a74a60b.jpg" width="200"> | <img src="https://i.pinimg.com/1200x/cb/b9/28/cbb92868404b881d23da0fa1c2e0cfde.jpg" width="200"> | <img src="https://i.pinimg.com/1200x/ff/a1/c0/ffa1c0075be82c32a521a0f811db9ae2.jpg" width="200"> | <img src="https://i.pinimg.com/1200x/bc/7c/0f/bc7c0fd89f6e6655d8347631c8e76e29.jpg" width="200"> |
| ------------------------ | ------------------------ | ------------------------ | ------------------------ | ------------------------ |
| https://pin.it/eJ8uK6LIC | https://pin.it/60IBoUh70 | https://pin.it/AitsD0M07 | https://pin.it/IyvScV4PD | https://pin.it/262PGJGTU |

</br>

## Challenges

Almost every aspect of this project is new to me, which also makes up its greatest challenge. I have very limited experience with web-based and creative coding, and my understanding of particle simulation is still fairly basic. This is precisely why I chose this project: I want to actively engage with creative coding and learn through hands-on experimentation, even though I expect to encounter difficulties and moments of being stuck along the way.

Through this process, I aim to strengthen my ability to set priorities and to work effectively within a given timeframe. The project will also challenge me to continuously adjust my expectations, to let go when necessary, and to avoid becoming hindered by perfectionism.

At present, my biggest challenge is developing a realistic time schedule. Due to my limited technical background, it is difficult for me to accurately estimate how long specific tasks will take. Developing a more honest and achievable approach to time planning is therefore an important learning objective of this project. At the same time, I want to become more comfortable recognising when it is useful or necessary to ask for help and to actively seek guidance when I encounter obstacles.  
</br>

## Time Schedule

| Month    | Cal. Week | Intended Progress |
| -----    | --------- | ----------------- |
| January  | 2         | Theoretical research; simple p5.js particle tests; concept refinement |
|          | 3         | Starting with three.js and web implementation |
|          | 4         | Three.js particle tests |
| Jan/Feb  | 5-6       | Test website with super basic particle simulation / redefinition of final product |
| February | 7-8       | Implementation of rollercoaster function (interactivity) |
|          | 9         | Varying particle behaviour along the pathway |
| March    | 10        | Design adjustments; Audio |
|          | 11        | Final adjustements; Documentation |

</br>

### Milestones

| Date       | Milestone |
| ---------- | --------- |
| 09/02/2026 | Basic and stable Test website &rarr; Redefining goal after previous findings |
| 02/03/2026 | Final website with functionalities and simulation; Starting design adjustments |
| 15/03/2026 | Project delivery date |