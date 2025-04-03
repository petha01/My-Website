# Pethaperumal Natarajan
## Fast Travel
  - [Education](#education)
  - [Past Experience](#past-experiences)
  - [Projects](#projects)
  - [Skills](#skills)
  - [Contact Info](#contact-info)
  - [Links](#links)

## Picture
<img src="./IMG_5059.JPG" alt="My picture" width="200"/>

## Education
- University of California San Diego
  - Major: MS Computer Engineering
  - Graduation Year: 2025
- University of California San Diego
  - Major: BS Computer Engineering
  - GPA: 3.752
  - Graduation Year: 2024
- Cambridge A-Levels
  - Taylor's College Lakeside Campus, Malaysia
  - Grade: 3A<sup>*</sup> 1A

## Past Experiences
- Motorola Solutions
  - Dec. 2024 – June 2025
  - Position: Embedded Software Engineer CO-OP
  - Built a tool that connects to a camera and is able to fully control the camera. Wrote scripts that allowed manufacturing, customer service, testers and developers to operate and debug almost every aspect of the camera easily without needing developer knowledge.
  - Configured Jenkins build jobs to automatically build and deploy the tool.
  - Integrated a feature into camera’s android OS that uses bluetooth to detect holster and automatically start recording for customer feature request.
- Ligron Bio
  - July 2024 - Sept 2024
  - Position: Aritificial Intelligence Engineer
  - Investigated different clustering models like KMeans and Hierarchical Clustering to find similarites between molecular glues which can then be used to find similarities with unknown molecules and discover molecular glues.
  - Built an autoencoder with which reduces redundancy in data leading to a more accurate model.
  - Used rdkit library to collect data like chain lengths and scaffold types about molecules in dataset.
- Motorola Solutions
  - June 2023 - Sept 2023
  - Position: Computer Engineering Intern
  - Modified memory management unit of radio to secure sensitive information on failure and created test cases to ensure the sensitive information is safe.
  -  Added features to output useful information like if developer options were activated and battery percentage to debugger upon failure. Fixed issues where the debugger outputs wrong failure time when DSP processor fails. This provides developer with more information when debugging.
  -  Analyzed RAM usage of radio upon booting up and looked for areas to decrease fragmentation. This intel was then
used to speed up radio boot up speed.
- Dassault Systemes
  - July 2022 - Sept 2022
  - Position: Test Engineer
  - About: Dassault Systemes is a French software corporation which develops software for 3D product design, simulation, manufacturing and other 3D related products. Letter of recommendation in website.
  - TypeScript Test Automation: I automated about 40 backlog tests for the web app using TypeScript which achieved the team’s backlog reduction goal by more that 40%.
  - Created Testing Library: I created and extended the testing library used to test the web app with reusable components so that future testings would be more efficient.
  - Collaboration: I collaborated with multiple other developers using GitLab and I learned to work a team with agile sprints.
  - [Recommendation Letter](./ds_recommendation.pdf)
- CSE Tutor
  - Sept. 2023 – June 2024
  - Tutored CSE 11(Introduction to Programming and Computational Problem-Solving) and CSE29 (Systems Programming and Software Tools). Resolved over 100 tickets.
- Luxembourg Expats
  - July 2021 - Sept 2021
  - Position: IT Research, Development
  - About: Luxembourg Expat is a startup company that is developing a social website that allows its users to meet new people, advertise their company/product/real estate, and request for help from the community.
  - React Javascript: I created an interactive webpage using React in NodeJS environment
  - Unit Testing: I used Jest to create unit tests on the website to make sure the website’s features work as required upon making new changes to the website.

## Projects
- Dual Core AI Accelerator Microprocessor
  - Verilog, Iverilog, Design Compiler, Innovus
  - Designed a weight 2D-systolic array accelerator with configurable dimensions.
  - Performed Hierarchical synthesis and placement and routing with Design Compiler and Innovus.
  - Created a testbench that loads SRAM correctly and runs verifies the output of accelerator.
  - Implemented clock gating to reduce power and multi-cycle path to remove timing violations in heavy logic paths.
- Pioneer HDnn Research
  - Designed RTL multiple baseline hyperdimensional neural network and the novel model presented.
  - Gathered hardware results for publication using Design Compiler and PCACTI.
- MyAdvantage Screen:
  - Python,  FastAPI, HTTP, HTML/JavaScript/CSS, Docker, RaspberryPi 
  - Created a screen that displays ads and uses geolocation to display personalized ads if the user is nearby.
  - Created backend using FastAPI that handled API requests from the frontend. Created mySQL database that stores users info, ads info and login session info. Used Google API to display interactive map, map image and directions.
  - Created and styled interactive website that displays ads and allows users to submit ads to screen.
- CPU Architecture Performance Predictor Research
  - Gem5, Chipyard, Verilator, SystemVerilog
  - Generate multiple RISC-V computer architectures using Chipyard and simulated their efficiency using verilator/gem5 to get training data.
  - Goal of research is to develop a model that can predict efficieny of an architecture to run specific programs.
- Advanced CPU Optimization Project
  - SystemVerilog, Verilator
  - Designed and implemented 4 optimizations to a baseline CPU to improve CPI. Implemented perceptron branch prediction, stream buffer, value prediction and cache set dueling.
  - chieved overall speed up of 1.3 for different types of programs.
  - [Link](https://github.com/achen200/optimized-mips-processor)
- NMAPORE Hardware Accelerator
  - SystemVerilog, Design Compiler, DesignWare
  - Created RTL for NMAPORE, a hardware accelerator for genome sequencing which uses kd-tree to to store genomic information. Used DesignWare Floating Point IPs to handle floating point operations.
  - Compiled design using Design Compiler to get delay, power and area estimations. Optimized delay by pipelining modules with long combinational logics.
- Microprocessor Design Project
  - SystemVerilog, Quartus Prime, ModelSim
  - Designed and created microprocessor ISA and RTL that is able to run 3 programs: encode, decode, find patterns.
  - Created a python script that compiles assembly code to machine code specified by the ISA.
  - Analyzed waveforms to debug RTL using ModelSim and measured delay, power and area using Quartus Prime.
  - [Link](https://github.com/petha01/CSE141L_Project)
- Autonomous Vehicle
  - Python, ROS2, OpenCV, DepthAI, PyTorch
  - Built a self driving car that is capable of using camera, LIDAR and GNSS to navigate through a track.
  - Trained car to navigate through track using a deep learning model from camera images using PyTorch.
  - Used template matching and DepthAI for image recognition that allowed the car to detect signs, humans, lanes follow lane and switch lanes.
  - [Link](https://github.com/UCSD-ECEMAE-148/spring-2023-final-project-team-2)
- Where To Eat:
  - Class project for CSE110 (Software Engineering). Created a web application that allows user to create a list of favorite restaurants and allows users to compare their list with other user to pick mutual favorites. Lead the front-end development of the project as the team designer. Set up the CI/CD pipeline for test automation. Created a priority queue class for sorting mechanisms. Created E2E tests for the web application using Jest and Puppeteer.
  - https://wheretwoeat.netlify.app/
  - https://github.com/cse110-fall22-group37/cse110-fall22-group37
- Connect 4 AI
  - C++
  - Made a Connect 4 AI that was capable of executing simple traps and beating new players for a class project in C. Student’s AI’s were played against each other to find the best one and my AI did the third best in class of 100 people.
- Signal Generator
  - Made a signal generator that was able to create different types of signals, shift the properties of signal and use envelopes to make distinct sounds. Collaborated with a group using GitHub to make the program. My part in this project shifting the frequency of the input signal in the frequency domain.
- CSV File Generator
  - Java
  - Made a CSV file generator that creates a CSV file with required type of data which can used for testing.
  - [Link](https://github.com/petha01/CSVFile)

## Skills
- **Programming Languages:** Python, Java, C++, C, MATLAB, ARM, Shell Scripting, HTML, CSS, Javascript, TypeScript, SystemVerilog/Verilog, Markdown, yml/yaml, TCL, Perl
- **Frameworks/Libraries:** JUnit, React, Jest, Puppeteer, Eclipse, Jupyter, Node.js, FastAPI, MQTT, Docker, SKlearn, PyTorch, OpenCV, DepthAI, Android Dev
- **Technologies:** Design Compiler, Questa/ModelSim, Iverilog, Cadence Virtuoso, Cadence Innovus, Cadence Xcelium, GTKWave, Quartus Prime, PSpice, Git, LaTeX, Microsoft Office, Adobe Illustrator/Photoshop
- **Courseworks:** Digital Design, Computer Architecture, CPU Optimizations, RTL Design/Synthesis/Simulation, VLSI, GPU Programming, Parallel Programming, Operating Systems, Operating Systems, Product Engineering, HTTP Protocols, Recommender Systems, Computer Vision, Autonomous Vehicles

## Contact Info
- Email: nk.petha@gmail.com
  
## Links
- [LinkedIn](https://www.linkedin.com/in/pethaperumal-natarajan/)
- [GitHub](https://github.com/petha01)

[Back to the top](#pethaperumal-natarajan)
