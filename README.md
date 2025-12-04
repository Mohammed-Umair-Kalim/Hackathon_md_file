Here's the content you requested in Markdown format:

```markdown
# Hackathon I: Physical AI & Humanoid Robotics Textbook

## Hackathon I: Create a Textbook for Teaching Physical AI & Humanoid Robotics Course

The future of work will be a partnership between people, intelligent agents (AI software), and robots. This shift won't necessarily eliminate jobs but will change what humans do, leading to a massive demand for new skills. We have already written a book on AI agents. Therefore, we want you to write a textbook to teach a course in Physical AI & Humanoid Robotics (The course details are documented below).

**Excel in the Hackathon and Launch Your Journey as an AI Startup Founder 🚀**

We’ve recently launched Panaversity (panaversity.org), an initiative focused on teaching cutting-edge AI courses. Alongside this, we’re working on publishing our first book, which you can explore at [ai-native.panaversity.org](http://ai-native.panaversity.org). Our next milestone is to build a portal where authors can create AI-native technical textbooks, and readers can easily access and learn from them using AI Agents. We also plan to publish O/A Level, Science, Engineering, and Medical AI-native books to support students and professionals across disciplines. If you perform well in this hackathon, you may be invited for an interview to join the Panaversity core team and potentially step into the role of a startup founder within this growing ecosystem. You will get a chance to work with Panaversity founders Zia, Rehan, Junaid, and Wania and become the very best. You may also get a chance to teach at Panaversity, PIAIC, and GIAIC.

## Requirements

You are required to complete a unified book project using **Claude Code** and **Spec-Kit Plus**. The core deliverables are:

1. **AI/Spec-Driven Book Creation**: Write a book using Docusaurus and deploy it to GitHub Pages. You will use Spec-Kit Plus ([GitHub Link](https://github.com/panaversity/spec-kit-plus/)) and Claude Code ([Claude Code](https://www.claude.com/product/claude-code)) to write the book.

2. **Integrated RAG Chatbot Development**: Build and embed a Retrieval-Augmented Generation (RAG) chatbot within the published book. This chatbot, utilizing the OpenAI Agents/ChatKit SDKs, FastAPI, Neon Serverless Postgres database, and Qdrant Cloud Free Tier, must be able to answer user questions about the book's content, including answering questions based only on text selected by the user.

3. **Points System**: Participants will receive points out of 100, for base functionality defined above.

4. **Extra Bonus Points**:  
   - Up to 50 extra points by creating and using reusable intelligence via Claude Code Subagents and Agent Skills in the book project.
   - Up to 50 extra bonus points if they also implement Signup and Signin using [Better Auth](https://www.better-auth.com/). At signup, you will ask questions from the user about their software and hardware background. Knowing the background of the user will allow you to personalize the content.
   - Up to 50 extra bonus points if the logged-in user can personalize the content in the chapters by pressing a button at the start of each chapter.
   - Up to 50 extra bonus points if the logged-in user can translate the content into Urdu in the chapters by pressing a button at the start of each chapter.

## Timeline

- **Submission Deadline**: Sunday, Nov 30, 2025 at 06:00 PM (form will close)
- **Live Presentations**: Sunday, Nov 30, 2025 starting at 6:00 PM on Zoom

**Top submissions will be invited via WhatsApp to present live on Zoom.**

Note: All submissions will be evaluated. Live presentation is by invitation only, but does not affect final scoring.

## Submit and Present Your Project

Once you have completed the project, you will submit your project here:

[Submit Your Project](https://forms.gle/CQsSEGM3GeCrL43c8)

Submit the following via the form:

- Public GitHub Repo Link
- Published Book Link for Github Pages or Vercel.
- Include a demo video link (must be under 90 seconds). Judges will only watch the first 90 seconds. You can use NotebookLM or record your demo.
- WhatsApp number (top submissions will be invited to present live)

Everyone is welcome to join the Zoom meeting to watch the presentations. Only invited participants will present their submissions. Meeting starts at 6:00 PM on Sunday, Nov 30:

### Join Zoom Meeting

- **Time**: Nov 30, 2025 06:00 PM
- [Join Zoom Meeting](https://us06web.zoom.us/j/84976847088?pwd=Z7t7NaeXwVmmR5fysCv7NiMbfbhIda.1)
- Meeting ID: 849 7684 7088
- Passcode: 305850

---

## The Course Details

### Physical AI & Humanoid Robotics

**Focus and Theme**: AI Systems in the Physical World. Embodied Intelligence.

**Goal**: Bridging the gap between the digital brain and the physical body. Students apply their AI knowledge to control Humanoid Robots in simulated and real-world environments.

### Quarter Overview

The future of AI extends beyond digital spaces into the physical world. This capstone quarter introduces **Physical AI**—AI systems that function in reality and comprehend physical laws. Students learn to design, simulate, and deploy humanoid robots capable of natural human interactions using ROS 2, Gazebo, and NVIDIA Isaac.

#### Module 1: The Robotic Nervous System (ROS 2)

- Focus: Middleware for robot control.
- ROS 2 Nodes, Topics, and Services.
- Bridging Python Agents to ROS controllers using rclpy.
- Understanding URDF (Unified Robot Description Format) for humanoids.

#### Module 2: The Digital Twin (Gazebo & Unity)

- Focus: Physics simulation and environment building.
- Simulating physics, gravity, and collisions in Gazebo.
- High-fidelity rendering and human-robot interaction in Unity.
- Simulating sensors: LiDAR, Depth Cameras, and IMUs.

#### Module 3: The AI-Robot Brain (NVIDIA Isaac™)

- Focus: Advanced perception and training.
- NVIDIA Isaac Sim: Photorealistic simulation and synthetic data generation.
- Isaac ROS: Hardware-accelerated VSLAM (Visual SLAM) and navigation.
- Nav2: Path planning for bipedal humanoid movement.

#### Module 4: Vision-Language-Action (VLA)

- Focus: The convergence of LLMs and Robotics.        
- Voice-to-Action: Using OpenAI Whisper for voice commands.
- Cognitive Planning: Using LLMs to translate natural language ("Clean the room") into a sequence of ROS 2 actions.
- **Capstone Project**: The Autonomous Humanoid. A final project where a simulated robot receives a voice command, plans a path, navigates obstacles, identifies an object using computer vision, and manipulates it.

### Why Physical AI Matters

Humanoid robots are poised to excel in our human-centered world because they share our physical form and can be trained with abundant data from interacting in human environments. This represents a significant transition from AI models confined to digital environments to embodied intelligence that operates in physical space.

---

## Learning Outcomes

- Understand Physical AI principles and embodied intelligence
- Master ROS 2 (Robot Operating System) for robotic control
- Simulate robots with Gazebo and Unity
- Develop with NVIDIA Isaac AI robot platform
- Design humanoid robots for natural interactions
- Integrate GPT models for conversational robotics

---

## Weekly Breakdown

### Weeks 1-2: Introduction to Physical AI

- Foundations of Physical AI and embodied intelligence
- From digital AI to robots that understand physical laws
- Overview of humanoid robotics landscape
- Sensor systems: LIDAR, cameras, IMUs, force/torque sensors

### Weeks 3-5: ROS 2 Fundamentals

- ROS 2 architecture and core concepts
- Nodes, topics, services, and actions
- Building ROS 2 packages with Python
- Launch files and parameter management

### Weeks 6-7: Robot Simulation with Gazebo

- Gazebo simulation environment setup
- URDF and SDF robot description formats
- Physics simulation and sensor simulation
- Introduction to Unity for robot visualization

### Weeks 8-10: NVIDIA Isaac Platform

- NVIDIA Isaac SDK and Isaac Sim
- AI-powered perception and manipulation
- Reinforcement learning for robot control
- Sim-to-real transfer techniques

### Weeks 11-12: Humanoid Robot Development

- Humanoid robot kinematics and dynamics
- Bipedal locomotion and balance control
- Manipulation and grasping with humanoid hands
- Natural human-robot interaction design

### Week 13: Conversational Robotics

- Integrating GPT models for conversational AI in robots
- Speech recognition and natural language understanding
- Multi-modal interaction: speech, gesture, vision

---

## Assessments

- ROS 2 package development project
- Gazebo simulation implementation
- Isaac-based perception pipeline
- Capstone: Simulated humanoid robot with conversational AI

---

## Hardware Requirements

This course is technically demanding. It sits at the intersection of three heavy computational loads: Physics Simulation (Isaac Sim/Gazebo), Visual Perception (SLAM/Computer Vision), and Generative AI (LLMs/VLA).

**The "Digital Twin" Workstation** (Required per Student)

- **GPU**: NVIDIA RTX 4070 Ti (12GB VRAM) or higher.
- **CPU**: Intel Core i7 (13th Gen+) or AMD Ryzen 9.
- **RAM**: 64 GB DDR5 (32 GB is the absolute minimum).
- **OS**: Ubuntu 22.04 LTS.

**The "Physical AI" Edge Kit**

- **The Brain**: NVIDIA Jetson Orin Nano (8GB) or Orin NX (16GB).
- **The Eyes**: Intel RealSense D435i or D455.
- **The Inner Ear**: USB IMU (BNO055).
- **Voice Interface**: ReSpeaker USB Microphone/Speaker array.

### Summary of Architecture

| Component        | Hardware                                      | Function                                      |
|------------------|-----------------------------------------------|-----------------------------------------------|
| **Sim Rig**      | PC with RTX 4080 + Ubuntu 22.04               | Runs Isaac Sim, Gazebo, Unity, and trains LLM/VLA models. |
| **Edge Brain**   | Jetson Orin Nano                              | Runs the "Inference" stack. Students deploy their code here. |
| **Sensors**      | RealSense Camera + Lidar                      | Connected to the Jetson to feed real-world data to the AI. |
| **Actuator**     | Unitree Go2 or G1 (Shared)                    | Receives motor commands from the Jetson.      |

If you do not have access to RTX-enabled workstations, we must restructure the course to rely entirely on cloud-based instances (like AWS RoboMaker or NVIDIA's cloud delivery for Omniverse), though this introduces significant latency and cost complexity.

### Option 2: High OpEx - The "Ether" Lab (Cloud-Native)

Best for: Rapid deployment or students with weak laptops.

1. **Cloud Workstations (AWS/Azure)**:
    - Instance Type: AWS g5.2xlarge (A10G GPU, 24GB VRAM) or g6e.xlarge.
    - Instance cost: ~$1.50/hour.
    - Total Cloud Bill: ~$205 per quarter.

2. **Local "Bridge" Hardware**:
    - Jetson Kit: $700 (One-time purchase).
    - Robot: Unitree Go2 Standard ~$3,000.

### The Economy Jetson Student Kit

| Component        | Model                             | Price (Approx.)  | Notes                             |
|------------------|-----------------------------------|------------------|-----------------------------------|
| **The Brain**    | NVIDIA Jetson Orin Nano (8GB)     | $249             | Capable of 40 TOPS.               |
| **The Eyes**     | Intel RealSense D435i             | $349             | Includes IMU (essential for SLAM).|
| **The Ears**     | ReSpeaker USB Mic Array v2.0      | $69              | Far-field microphone for voice commands. |
| **Wi-Fi**        | (Included in Dev Kit)             | $0               | The new "Super" kit includes the Wi-Fi module pre-installed. |
| **Power/Misc**   | SD Card (128GB) + Jumper Wires    | $30              | High-endurance microSD card required. |
| **TOTAL**        |                                   | ~$700 per kit    |                                   |

---

This Markdown file is structured with headings, bullet points, links, and tables, making it ideal for online documentation or course outline presentation. Let me know if you'd like to make any modifications!
```
