# Hello DES INV 202 Student!
Welcome to your new GitHub repository! 

# Index
[Week 1](README.md#week-1-example-report-1)

[Week 2](README.md#week-2)

[Week 3](README.md#week-3)

[Week 4](README.md#week-4)

[Week 5](README.md#week-5)

[Week 6](README.md#week-6)

[Week 7](README.md#week-7)

[Week 8](README.md#week-8)

[Week 9](README.md#week-9)

[Week 10](README.md#week-10)

[Week 11](README.md#week-11)

[Week 12](README.md#week-12)

[Week 13](README.md#week-13)

[Week 14](README.md#week-14)


</br>
---

# Week 14 #
### Dec 5th, 2024 ###

Reflection:
This week, I completed Momlog (Moment Log), our final project. My contributions encompassed nearly every aspect of the development process, including:

Writing the Arduino code for the wearable necklace.
Implementing BLE (Bluetooth Low Energy) logic to enable communication between the device and the web app.
Developing both the frontend and backend for the web app.
This project proved to be particularly challenging due to network restrictions at Berkeley. I had to change my approach six times before finally getting the system to work seamlessly using BLE. Additionally, I integrated Zerowidth into the project as an intermediary for handling OpenAI queries instead of directly hitting the OpenAI API, which improved reliability and efficiency.

Despite not being a programmer, I took on and successfully executed this technical challenge, and I’m genuinely proud of the outcome. This project stands as a testament to my persistence, adaptability, and ability to learn new skills under pressure.

<br>

Speculation:
Momlog is now functional, but there is potential to further refine and scale the system. For instance, expanding its compatibility with other devices and exploring additional AI-based analysis features could enhance its utility. This project also gave me deeper insights into programming and hardware integration, which I can leverage in future interdisciplinary projects.
</br>
</br></br>
Final working frontend with bakcend of MomLog</br></br>
<img width="400" alt="Final working frontend with bakcend of MomLog" src="assets/141.jpeg">
</br></br></br>
Working Zerowidth flow for image analysis</br></br>
<img width="400" alt="Working Zerowidth flow for image analysis" src="assets/142.png">
</br></br>
Working BLE transmition</br></br>
<img width="400" alt="Working BLE transmition" src="assets/143.png">
</br>
</br>
</br>

# Week 13 #
### Nov 21st, 2024 ###

Reflection:
This week, I began work on my final project, Momlog (Moment Log). The project involves creating a wearable necklace equipped with a camera that captures photos when the user is happy. The captured data will then be analyzed and displayed on a connected web application. The project has two key components: the physical prototype of the necklace and the web app for data visualization.

My role in the project is focused on developing the backend for the device. I have already created the backend and frontend code for the web app to test the OpenAI connection, which is functioning as intended. Currently, I’m waiting for my teammates to complete their respective parts so I can integrate all the codes into a cohesive system.
<br>

Speculation:
Looking ahead, the integration phase will be critical for ensuring the functionality and smooth interaction between the physical device and the web app. Once complete, Momlog has the potential to not only capture and analyze happy moments but also provide insights into the emotional patterns of users. This could lead to interesting applications in mental health and wellness tracking, particularly as wearables become more prominent in personal health management. I aim to further refine the backend to ensure scalability and efficiency once the prototype is fully assembled.

</br>
</br></br>
Photo of working web app</br></br>
<img width="400" alt="Photo of working web app" src="assets/131.jpeg">
</br></br></br>
System prompt for openai GPT 4o in bakcend using python</br></br>
<img width="400" alt="System prompt for openai GPT 4o in bakcend using python" src="assets/132.png">
</br></br>
Process Diagram</br></br>
<img width="400" alt="Process Diagram" src="assets/133.png">
</br></br></br>
System Diagram</br></br>
<img width="400" alt="System Diagram" src="assets/134.png">
</br>
</br>
</br>


# Week 12 #
### Nov 14th, 2024 ###

Reflection:
This week, without a TDF submission deadline, I focused my time on two ongoing elective projects. The first project involves using an iPhone’s native camera to create a stereoscopic passthrough feed, enabling the display of AR objects in real-world environments. This project has been challenging due to hardware constraints imposed by Apple, which has required us to experiment with multiple approaches to overcome these limitations. Currently, I’m exploring the use of Aruco markers and a multicam setup to achieve our goals. It’s a complex task, but I’m hopeful that we’ll be able to implement a solution that meets our project requirements.

My second project centers on mathematically quantifying visual hierarchy and contrast to create a framework that automates the process of establishing visual hierarchy in UI design. I believe this work could lead to a framework that streamlines the development of basic UI elements, making the design process more efficient. Prof. Dubberly has been providing valuable insights on this project, and I’m considering turning it into a research paper. I’ve been working late nights at Jacobs Hall, often from 9 p.m. until midnight, when the space is quiet and free from distractions, allowing me to focus deeply on my work.

<br>

Speculation:
Looking forward, I believe that if we manage to implement the multicam setup with Aruco markers, it could open up new possibilities for AR applications on iPhones, even with the hardware limitations. This could pave the way for more immersive AR experiences without requiring specialized hardware. In terms of the UI hierarchy project, creating a framework for automating visual hierarchy could significantly impact design tools, making them more accessible to non-designers and optimizing workflows for professionals. This could lead to a future where fundamental UI principles are embedded into design software, allowing for automated yet visually coherent layouts that adhere to established design standards.

</br>
</br></br>
Photo of XR Iphone projec</br></br>
<img width="400" alt="Photo of XR Iphone project" src="assets/121.png">
</br></br></br>
Formula for Calculating Composite Contrast Score for fonts (Work in progress)</br></br>
<img width="400" alt="Formula for Calculating Composite Contrast Score for fonts (Work in progress)" src="assets/122.png">
</br>
</br>
</br>

# Week 11 #
### Nov 7th, 2024 ###

Reflection:
This week, I focused on further developing my work on ZeroWidth by creating my own AI agent. This AI agent can “drink” beers and become progressively more intoxicated with each beer, affecting its responses. The concept could potentially evolve into a full application, serving as a “Drinking Buddy” or even a “Drunk Therapist.” Writing the system prompt to accurately simulate intoxication levels was a significant challenge—I spent over an hour refining it. I also used ChatGPT to rewrite the system prompt, and after some iterations, it finally worked. This has been an incredibly fun project; I can’t help but laugh whenever I read the AI’s responses at different levels of “drunkenness.”

<br>

Speculation:
Looking ahead, my next step will be to streamline the process by reducing the number of GPT agents from three to one to save both time and cost. I’m also considering creating a knowledge base to give the AI a more friendly, conversational tone—something that makes it feel more like a familiar friend. Another goal is to incorporate a voice component using OpenAI’s TTS model, which could add a unique element to the experience. Training the AI to speak with slurred speech and respond with “drunk” intonations based on the text would be an exciting challenge. If successful, this could lead to applications beyond entertainment, such as enhancing virtual companion or AI-driven role-play scenarios. I’m eager to see how these ideas develop in the coming weeks.
</br>
</br></br>
System prompt to make the AI agent progressively more drunk</br></br>
<img width="400" alt="System prompt to make the AI agent progressively more drunk" src="assets/113.png">
</br></br></br>
AI Agent response after having 15 beers</br></br>
<img width="400" alt="AI Agent response after having 15 beers" src="assets/112.png">
</br></br></br>
Diagramatic analysis of my AI agent</br></br>
<img width="400" alt="Diagramatic analysis of my AI agent" src="assets/111.png">
</br>
</br>
</br>

# Week 10 #
### October 31st, 2024 ###

Reflection:
It is Thursday, and this week has been a bit more relaxed since we just completed our project. I've been thinking about potentially using my Bluetooth keyboard project as my final TDF project. Jeff mentioned that there are some minimum requirements for the final project that haven't been announced yet, so I'm waiting to hear what those entail before finalizing my plan for the keyboard project. I'm genuinely excited to work on AI as well, as I've recently been introduced to RAG (Retrieval-Augmented Generation), which I find fascinating. Yesterday, I experimented with a few flows on ZeroWidth to explore its potential applications in this context.

<br>

Speculation:
As I look forward, I think there's significant potential for AI to transform how customizable hardware projects like the Bluetooth keyboard could function. If I integrate RAG, the keyboard could adapt to users' specific workflows, offering predictive typing features, task suggestions, or even voice-assisted commands. This could make it much more than a standard keyboard and turn it into a dynamic productivity tool. With the rapid advancement of AI-driven personalized technology, we could see tools like these evolving into essential, adaptable devices that adjust based on real-time user input. Projects like these represent a potential shift toward hardware that intelligently "learns" and adapts to user needs, creating a more streamlined and efficient experience.
</br>
</br></br>
Exploration of ZeroWidth</br></br>
<img width="400" alt="Exploration of ZeroWidth" src="assets/101.png">
</br>
</br>
</br>

# Week 9 #
### October 24th, 2024 ###

Reflection:
It’s Thursday, and last night, I didn’t leave until 1 a.m. because I was busy working on the TDF Project 2 video. Here is the video link for the project: https://youtu.be/lZJBR3rfQgQ I’m genuinely happy with the outcome, especially since we had to include additional circuitry to achieve the Remembrall functionality, even though it wasn’t essential for its primary purpose. I’m especially proud of my team for deciding to refine and polish this project further to create a portfolio-worthy piece. Separately, I’ve been working on my personal project, which involves designing a micro board. I made some updates, including a new 3D model where I opted not to use an OLED display. This decision was primarily to conserve space and improve battery performance. Instead, I decided to go with a vertical rotary encoder, which will act as an undo/redo knob, alongside two touch buttons—one to open Figma and the other to open the browser. Tomorrow, I plan to order the remaining electronic components, and once they arrive, I’ll begin working on the PCB.

<br>

Speculation:
Reflecting on my micro board design, I believe its modularity and customizability could be incredibly appealing for a range of users. Imagine the potential if this device could be expanded further with AI or automation features; it could become an essential tool for professionals in fields from design to gaming. As the market for compact, specialized devices grows, customizable macro boards like mine could attract attention, especially if they simplify workflows or allow for user-specific programming options. This could represent a future shift in how people approach productivity tools, favoring personalized, small-scale devices that can be tailored to individual needs. With further refinement and integration, such a device could serve as a template for a new category of versatile, modular productivity hardware.
</br>
</br></br>
Personal Project: 3D Rendering of MacroBoard</br></br>
<img width="400" alt="Personal Project: 3D Rendering of Macro Keyboard" src="assets/91.png">
</br></br></br>
I am creating the final circuit using hot glue and protoboards</br></br>
<img width="400" alt="I am creating the final circuit using hot glue and protoboards" src="assets/92.png">
</br></br></br>
Button input for Project 2</br></br>
<img width="400" alt="Button input for Project 2" src="assets/93.png">
</br></br></br>
Project 2 Hero Image</br></br>
<img width="400" alt="Project 2 Hero Image" src="assets/94.png">
</br>
</br>
</br>

# Week 8 #
### October 17th, 2024 ###

Reflection:
It is Thursday, and I’m currently balancing two projects. For the TDF project, my team is creating a Remembrall—a device inspired by the Harry Potter series that acts as an ambient display, changing colors based on Google Calendar events. We’ve made substantial progress, but we’re stuck on the Google Cloud integration, which has been a challenging hurdle. Today, I plan to assemble the final stacked circuit using prototyping boards, soldering all the components to create a compact, vertically-stacked design. This setup will minimize the horizontal footprint, making the circuit compact enough to fit inside the spherical Remembrall enclosure. Separately, I’m working on a personal project: a customizable micropad with nine keys, a roller, and an OLED display. I created a 3D prototype to test the dimensions and realized that I need larger keycaps. I’ve already written a proof-of-concept code that allows me to close windows on macOS with a simple keystroke (Cmd+Q). My goal for next week is to create a working 3x3 keyboard prototype.

<br>

Speculation:
If we successfully integrate Google Cloud with the Remembrall, it could pave the way for future ambient devices that seamlessly interact with user schedules, alerts, and other personal data. Imagine a range of ambient displays that subtly remind users of upcoming tasks without disrupting their flow, providing a physical, intuitive connection to their digital lives. The micropad project, on the other hand, has the potential to inspire more DIY, customizable hardware projects tailored for specific workflows. In an era where people crave efficiency and simplicity, user-friendly, programmable tools like this could gain significant traction. With ongoing advancements in connectivity and cloud integration, such devices could one day function as modular productivity hubs, offering users an unprecedented level of personalization in their daily routines.
</br>
</br></br>
Experiement: Working circuit with inputs and outputs for Project 2</br></br>
<img width="400" alt="Experiement: Working circuit with inputs and outputs for Project 2" src="assets/81.jpeg">
</br></br></br>
Personal Project: Step 1 of Macro Keyboard (Created a one key bluetooth keyboard)</br></br>
<img width="400" alt="Personal Project: Step 1 of Macro Keyboard (Created a one key bluetooth keyboard)" src="assets/83.jpeg">
</br></br></br>
Sketches of design and mechanish of outer shell of Remembrall for Project 2</br></br>
<img width="400" alt="Sketches of design and mechanish of outer shell of Remembrall for Project 2" src="assets/84.jpeg">

</br>
</br>
</br>

# Week 7 #
### October 10th, 2024 ###

Reflection:
It is Thursday, and after rewatching the Harry Potter movies last week, I got the idea of making a Remembrall for my Studio Foundations class. The assignment was to create an ambient display, and I proposed building a glowing orb that connects to Google Calendar, changing colors based on whether there’s an upcoming event or not. My teammates, Sharon and Vivian, and I met on Tuesday to write up the project proposal. I created the system and process diagrams while they worked on the text. I’m thrilled to bring this concept to life! In addition to the Remembrall, I’ve also started working on a personal project, a macro keyboard with programmable keys. I want the keyboard to have an ergonomic design, but balancing functionality with an appealing aesthetic is challenging.

<br>
Speculation:
The Remembrall project, if executed well, could serve as a prototype for a range of ambient devices that provide timely notifications without the intrusiveness of traditional screens. In a future where technology is integrated seamlessly into everyday life, ambient devices like these could be key players, enhancing productivity and organization without overwhelming users. On the other hand, my ergonomic macro keyboard project represents a growing trend in personalizing hardware for maximum comfort and efficiency. If successful, it could inspire others to create similar ergonomic tools, leading to a shift in how we approach productivity accessories. With the increasing awareness of ergonomic design in tech, more products might emerge that focus on balancing usability and visual appeal, especially in work-from-home environments.
</br>
</br></br>
Working session with team for Project 2 Proposal Report</br></br>
<img width="400" alt="Working session with team for Project 2 Proposal Report" src="assets/proposal_working.png">

</br>
</br>
</br>

# Week 6 #
### October 3rd, 2024 ###

Reflection:
It’s Thursday, and I had a lot of fun working on the flashing LED project. I added four LEDs that alternated in sequence and included a start/stop function via a button press, which made the project feel festive, almost like Christmas lights. Afterward, I completed two more assignments: one involving a publish/subscribe model and the other an FSR/LED color project. However, I ran into an issue after initially compiling the FSR/LED code—the system refused to compile further, and I haven’t yet figured out why. I’ll document any solutions I find in next week’s report.

<br>

Speculation:
This week’s LED project underscores the potential for simple, interactive lighting solutions to enhance user experiences in both personal and commercial spaces. As technology progresses, we could see more integration of interactive lighting in areas like home decor and retail, creating engaging environments that react to user inputs. The publish/subscribe model could lead to new IoT applications, allowing devices within smart homes to communicate and trigger responses based on shared data. For example, future applications might include systems that respond to environmental changes, enabling a more interconnected, automated home that adapts to its occupants' needs seamlessly.
</br>
</br>
</br>
Experiement: Blinking LED lights</br></br>
<img width="400" alt="Experiement: Blinking LED lights" src="assets/RGB_3.png">
</br>
</br></br>
Experument: Potentiometer</br></br>
<img width="400" alt="Experument: Potentiometer" src="assets/lights_1.png">
</br>
</br></br>
Experiment: Christmas Lights (Extension of Blinking LED Lights)</br></br>
<img width="400" alt="Experiment: Christmas Lights (Extension of Blinking LED Lights)" src="assets/battery_2.png">

</br>
</br>
</br>

# Week 5 #
### September 26th, 2024 ###

Reflection:
It’s Thursday, and I’ve created a flowchart that maps out my journey to a destination by either public transport, walking, or using Uber. The system pulls data from Uber (for pricing), BART/AC Transit (for ETAs), and Google (for total journey time and cost). Google then compiles this information and presents it on Google Maps, allowing me to select my preferred mode of transport based on my preferences for cost and travel time.

<br>

Speculation:
This exercise in data integration for transportation planning offers a glimpse into the potential of smart city infrastructure, where real-time data can help residents optimize their travel routes. As smart city technologies evolve, we may see a trend toward integrated, adaptive transportation solutions that factor in live data from various sources. This could mean that users no longer need to consult multiple apps but can instead access all transit options from a single, intuitive platform. Such innovations could transform urban living, making commuting more efficient, sustainable, and user-centered.
</br></br></br>
Example of ecosystem: Uber</br></br>
<img width="400" alt="Example of ecosystem: Uber" src="assets/transportation_ecosystem.png">

</br>
</br>
</br>

# Week 4 #
### September 19th, 2024 ###
Reflection:
It’s Monday, and I’ve just finished creating a video demonstrating a Grasshopper project. Here’s the video link: https://youtu.be/3rTEaj7E28s. Initially, I tried a brute-force approach that cost me about two hours, but switching to a more nuanced method eventually worked. I also refined my plant holder design after noticing it was drooping from the plant’s weight due to a lack of structural supports. I adjusted the design to include stronger supports, making it more durable and stable.

<br>

Speculation:
Grasshopper's flexibility and scalability highlight its potential for applications in fields that require parametric design, such as architecture and product design. This tool could help create adaptive structures that respond to changing conditions or design requirements, opening the door for innovative approaches in sustainable design. As more industries look to optimize materials and energy use, Grasshopper-like tools could become vital, enabling designers to test and iterate their creations for both functional and aesthetic considerations. This could lead to a future where sustainability is built into the design process from the outset.

</br>
Personal Project: Plant holder with section for keeping keys and wallet</br></br>
<img width="400" alt="Personal Project: Plant holder with section for keeping keys and wallet" src="assets/plant_holder_2.png">
</br>
</br>
</br>

# Week 3 #
### September 12th, 2024 ###
Reflection:
Throughout this week, I explored Grasshopper via YouTube tutorials and successfully created a phone stand design. Initially, my model lacked stability, but with feedback from Chris Myers, I adjusted the design. I’ve also been working on an ergonomic macro keyboard with programmable keys, experimenting with different designs that balance functionality and aesthetics. Separately, I created a diagram for the Grasshopper mobile stand file, tested a rough prototype for stability, and experimented with balance-based designs inspired by a laptop stand I saw on Amazon.

<br>

Speculation:
Grasshopper’s workflow-based approach could revolutionize the way designers think about structure and design, enabling them to create functional, adaptable designs through parametric adjustments. In the future, this method could become commonplace, allowing designers to create customized, user-friendly solutions. For my ergonomic keyboard, achieving both functionality and aesthetics could serve as a model for future products that prioritize user comfort without compromising design appeal. As ergonomic technology becomes more accessible, we might see increased demand for customizable products that meet individual needs for both productivity and physical well-being.
</br>

I tried grasshopper over the weekend. I was had used Fusion in college but never knew that design could be encoded in such a workflow. I found it fascinating. I love automation and love making block diagrams. This method of using logical flows to breakdown components of designs essentially means that the design will always work (functionally) if the parameters are entered correctly. I am more interested in AR/VR and UI/UX design, but have to admit that I did find the use of workflows in physical design quite fascinating. Don't know if I would want to master grasshopper, but I would deffinetely want to explore more. I have added a few screenshots below where I tried using a cone for the inner shape of the stand. I also tried changing the outer shape from cylinder to sphere but that didn't work and I dont know why yet.

</br>
Tried using cylinder as outer shape for sphere, did not work.</br></br>
<img width="400" alt="Tried using cylinder as outer shape for sphere" src="assets/something_went_wrong.png">
</br>
</br>
Used cone as inner shape for the stand.</br></br>
<img width="400" alt="used cone as inner shape" src="assets/cone_inner_shape.png">
</br>
</br>
It is Monday night and as I was browsing amazon I saw the most amazing laptop stand I have ever seen. I am thinking of making a phone stand like this that works on the principles of balance and center of mass rather than a solid block with a line carved out to keep the phone.

</br></br></br>
Inspiration for phone stand</br></br>
<img width="400" alt="Inspiration for phone stand" src="assets/balance_stand_inspo.png">
</br>
</br>
I worked on creating the diagram for the grasshopper file for the mobile phone. </br></br></br>
Diagramtic analysis of Grasshopper file shard by TJ</br></br>
<img width="400" alt="Diagramtic analysis of Grasshopper file shard by TJ" src="assets/block_diagram_mobile_stand.png">
</br>
</br>
It's Tuesday, I am sitting in the MDes studio waiting for my plant stand 3d print while I am trying to sketch ideas for the phone stand. I made a rough prototype using figma and laser cut 0.25" wood to make it. It somehow works Lol. If I poke the phone (try to use the touch screen) it wobbles and might fall. It also doesnt work in landscape mode.
</br></br>
Diagram for intial protype based on centroid point</br></br>
<img width="400" alt="Diagram for intial protype based on centroid point" src="assets/Phone_stand_proto_1_sketch.png">
</br>
</br></br>
Prototype for phone stand made using laser cut wooden sheet</br></br>
<img width="400" alt="Prototype for phone stand made using laser cut wooden sheet" src="assets/phone_stand_proto_1.jpeg">
</br>
</br></br>
Initial prototype tested using phone
</br></br>
<img width="400" alt="Initial prototype tested using phone" src="assets/Phone_stand_proto_working.jpeg">
</br></br>

I also made a 3d model for the mobile stand so that i dont have to attach the two legs separately. The design allows e to attach my phone while the stand is horizontal and then prop it up. I didn't realise I could do this until Chris Myers pointed it out.</br>
</br></br>
Stand in horizontal position to place phone</br></br>
<img width="400" alt="Stand in horizontal position to place phone" src="assets/phone_stand_proto_2_sitting.jpeg"></br></br></br>
Stand in vertical position to hold the phone</br></br>
<img width="400" alt="Stand in vertical position to hold the phone" src="assets/phone_stand_proto_2_standing.jpeg">
</br>

---

# Week 2 #
### September 5th, 2024 ###
</br>
Reflection:
This week, I learned to laser cut and spent nearly an hour perfecting my design through multiple attempts. Initially, I faced issues with the design being unrecognized as a cuttable path, even with correct stroke settings. After troubleshooting, I successfully cut a Cal keychain. Given the expense of official Cal merchandise, this was a satisfying achievement. I also helped a friend with her first laser-cutting project, which was a rewarding experience.

<br>

Speculation:
Laser cutting's accessibility and flexibility make it ideal for personalizing small items like accessories, potentially transforming how people approach custom merchandise. In a world where consumers increasingly value personalization, tools like laser cutters could drive the popularity of DIY production for unique, self-designed items. This shift could encourage a broader movement toward consumer-designed products, with more people creating and customizing goods from home, further democratizing design and production.
</br></br></br>
Acrylic material used for laser cutting with failures and final cut</br></br>
<img width="400" alt="Acrylic material used for laser cutting with failures and final cut" src="assets/week_2_img.jpeg">

</br>
</br>

