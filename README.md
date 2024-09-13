# VR-Campus-Tour-with-AI-Assistance
### An Immersive Virtual Reality Experience for Exploring College Campuses with AI-Powered Guidance

<!-- ![VR College Explorer](your-image-link-here)  Add a relevant image or screenshot -->

---

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technology Stack](#technology-stack)
- [Installation & Setup](#installation--setup)
- [Usage Guide](#usage-guide)
- [AI Interaction](#ai-interaction)
- [Contributing](#contributing)
- [Future Enhancements](#future-enhancements)
- [Challenges Faced](#challenges-faced)
- [System Requirment](#system-requirment)
- [License](#license)
- [Contact](#contact)

---

## Project Overview

**Virtual Reality Campus tour with AI Assistance** is a virtual reality project designed to offer users an immersive experience where they can freely explore a highly detailed 3D environment of a college campus. The project integrates AI technology to create an intelligent guide that interacts with users, answers their questions, and provides information about different areas in the college.

This project showcases the intersection of **virtual reality**, **artificial intelligence**, and **3D modeling** in Unity. By combining these technologies, we aim to deliver an interactive experience for prospective students, visitors, or anyone curious about the college, enabling them to explore the campus from the comfort of their homes.

---

## Features

- **Fully Explorable 3D Environment:**  
  The college campus is modeled in detail, allowing users to walk through classrooms, corridors, libraries, and open spaces.  
  - **Dynamic Physics Interaction:** Doors can be opened, objects can be picked up, and environmental elements respond to player interaction.
  - **Navigation Markers:** Placeholders help users find their way around larger areas.

- **AI-Powered Guide:**  
  The AI character acts as a campus tour guide, capable of answering questions, explaining historical landmarks, and guiding users to different locations within the college.  
  - **Natural Language Processing (NLP):** Enables users to ask questions in natural language.
  - **Interactive Dialogues:** AI guide responds based on user queries, helping navigate and providing detailed descriptions.

- **VR Support:**  
  The project fully supports VR, enabling users to experience the campus as if they were physically there. The interface is designed for:
  - **Oculus Quest** and **SteamVR**, with controls optimized for both.

- **Voice Recognition:**  
  Built-in voice commands allow users to interact with the AI guide without needing to use controllers.
  
- **Optimized Performance:**  
  The project is designed to maintain a steady frame rate and smooth interaction, even in more detailed areas of the environment.

- **Educational Integration:**  
  The project includes educational content related to the college such as:
  - Academic departments, faculty offices, classrooms, labs, and more.

---

## Project Structure
<!--
Here's a breakdown of the key directories and files in the project:

```
/Assets
  /Scenes
    - Main.unity          # Main VR scene with the college environment
    - Menu.unity          # Main menu and startup screen
  /Scripts
    /AI
      - AIGuide.cs        # C# script for AI character behavior and interactions
    /Player
      - VRMovement.cs     # Player movement and controls for VR headset
    /UI
      - DialogueSystem.cs  # Script for displaying dialogues and user queries
  /Models
    - CollegeBuilding.fbx  # 3D model of the college campus
    - Classroom.obj        # 3D model of a classroom interior
  /Audio
    - BackgroundMusic.mp3  # Ambient sounds and music
    - AIGuideVoice.mp3     # Pre-recorded responses from the AI guide
``` 
-->
---

## Technology Stack

- **Unity3D** (2020 or later): Game engine for 3D modeling, physics, and environment interaction.
- **C#**: Main programming language for scripting game mechanics and Game and AI behavior.
- **Oculus SDK** and **SteamVR SDK**: For VR support.
- **OpenAI GPT-4**: For AI-powered voice interaction and natural language processing.
- **Blender**: Used to model and texture the 3D college environment.

---

## Installation & Setup

### Prerequisites
1. **Unity**: Install Unity Hub and the correct Unity version (2022.3.11f1).
2. **Oculus SDK or SteamVR SDK**: Download and install the required SDK for your VR headset.
3. **AI Service**: Set up an API key for OpenAI, or any other NLP/AI service you are integrating.

### Step-by-Step Guide
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Tauseefyusufzai/VR-Campus-Tour-with-AI-Assistance.git
   cd VR-College-Explorer
   ```

2. **Open in Unity**:
   - Open Unity Hub, and click **Open Project**.
   - Select the `VR-College-Explorer` folder.
   - Let Unity install any missing dependencies.

3. **Install VR SDKs**:
   - Import the **Oculus SDK** or **SteamVR SDK** from the Unity Asset Store or GitHub.
   - Set up the player settings for VR in **Project Settings > XR Plugin Management**.

4. **API Setup**:
   - In the `AIGuide.cs` script, replace placeholder API keys with your actual keys for AI interaction.

5. **Build and Run**:
   - Open **Build Settings** in Unity, select the appropriate platform (Windows or Android for Oculus Quest), and click **Build**.
   - Deploy the build to your VR device or run in the Unity editor.

---

## Usage Guide

### Navigating the Environment:
- Use the VR controllers to move, turn, and interact with objects in the environment.
- The teleportation system allows users to jump between large areas quickly.
  
### Interacting with the AI Guide:
- Approach the AI character (indicated with a glowing marker).
- Use voice commands like "Tell me about the library" or "Where is the cafeteria?"
- The guide will respond with audio and text-based answers.

### Debugging / Desktop Mode:
- If you don’t have access to a VR headset, you can run the project in desktop mode for development purposes. Use the mouse and keyboard to control movement.

---

## AI Interaction

The AI Guide uses a cloud-based natural language processing system to interpret and respond to user queries. Here's how the interaction works:

1. **Voice Input**: Users speak directly to the AI guide.
2. **Speech-to-Text**: The voice input is converted to text using the chosen AI service.
3. **Natural Language Understanding**: The AI interprets the user's query and matches it to predefined responses or fetches real-time information.
4. **Response**: The AI guide delivers the response through voice (pre-recorded or generated) and optional text display.

---

## Future Enhancements

- **Multiplayer Mode**: Allow multiple users to explore the campus together.
- **Advanced AI Features**: Implement dynamic AI behavior that adapts based on user interactions.
- **Expanded Campus**: Add more areas of the college and interactive events like virtual open days.
- **Performance Optimization**: Refine the game for lower-end devices and reduce resource consumption.
- **Multilingual Support**: Allow users to interact with the AI guide in multiple languages.
  
---

## Challenges Faced

Some challenges encountered during development:
- **Performance Tuning**: Balancing high-quality visuals with smooth VR performance.
- **AI Integration**: Ensuring the AI guide could respond meaningfully to various user queries without significant lag.
- **Voice Recognition**: Implementing voice commands that work seamlessly across different accents and noise levels.

---

## System Requirment

### **Minimum PC Requirements for Development:**

- **Operating System**: 
  - Windows 10 (64-bit) or later
  - macOS 10.14 or later (for development, but not recommended for VR playtesting)

- **Processor**: 
  - Intel Core i5-4590 / AMD Ryzen 5 1500X or better
  - A quad-core processor is recommended for handling VR workloads.

- **Graphics Card (GPU)**: 
  - NVIDIA GTX 1060 / AMD RX 580 or equivalent
  - At least 4 GB of VRAM. 
  - GTX 1060 is the baseline for smooth VR development with Unity and URP, but more powerful GPUs (like GTX 1660 Ti or RTX 2060) are highly recommended for complex scenes.

- **RAM**: 
  - 8 GB minimum (16 GB recommended)
  - VR development can be memory-intensive, especially with large assets and scenes.

- **Storage**: 
  - 20 GB of free space for Unity and the VR project.
  - SSD recommended for faster load times, both for Unity development and asset loading in VR.

- **VR Headset Compatibility**:
  - **Oculus Rift S** / **Oculus Quest 2** (with Link cable)
  - **HTC Vive** / **HTC Vive Pro**
  - **Valve Index**
  - **Windows Mixed Reality** headsets

- **Unity Version**: 
  - Unity 2021 or later (preferably Unity 2022 LTS) with **XR Plugin Management** and **XR Interaction Toolkit**.

### **Minimum PC Requirements for Running a VR Game (End User)**:

- **Processor**: 
  - Intel Core i5-4590 / AMD FX 8350 or better.

- **Graphics Card**: 
  - NVIDIA GTX 1060 / AMD RX 580 or better.

- **RAM**: 
  - 8 GB minimum.

- **Operating System**: 
  - Windows 10 (64-bit) or later.

- **VR Headset**:
  - Oculus Rift / Quest 2 (with Link)
  - HTC Vive
  - Valve Index

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

## Contact

For any questions, issues, or suggestions, feel free to reach out:
- **Name**: Tauseef Akhtar Yusufzai
- **Email**: your-email@example.com
- **GitHub**: [YourUsername](https://github.com/YourUsername)

---

