# Project Initialization:
---

### **1. Install Unity 3D and VR SDK**

   - **Unity 3D Installation:**
     1. Download the Unity Hub installer from the [official Unity website](https://unity.com/download).
     2. Open the Unity Hub application and sign in with your Unity ID or create a new account if you don’t have one.
     3. Navigate to the "Installs" tab in Unity Hub and click on the "Add" button.
     4. Select the version of Unity 3D you need for your project. For VR development, it's recommended to use the latest stable version to ensure compatibility with VR SDKs.
     5. Follow the installation prompts, including selecting additional modules such as "Android Build Support" or "iOS Build Support" if you plan to deploy to mobile VR platforms.

   - **VR SDK Installation:**
     1. **Oculus SDK:**
        - Visit the [Oculus Developer website](https://developer.oculus.com/downloads/package/unity-integration/) and download the Oculus Integration package for Unity.
        - Open your Unity project, go to "Assets" > "Import Package" > "Custom Package," and select the downloaded Oculus Integration package. Follow the import prompts to add the SDK to your project.
     2. **OpenXR SDK:**
        - In Unity, go to "Window" > "Package Manager."
        - In the Package Manager, search for "OpenXR" and install the OpenXR Plugin package. This SDK supports a wide range of VR devices and is useful for cross-platform development.
---

### **2. Create the Initial Unity Project File for VR**

   - Open Unity Hub and click on the "New Project" button.
   - Choose a suitable template for your project. For a VR project, you might select the "3D" template, as it provides a good starting point for immersive experiences.
   - Name your project appropriately, such as "VR College Explorer with AI Guide."
   - Set the project location where you want to save your files.
   - Click "Create" to initialize the project. Unity will set up the necessary project files and folders.
---

### **3. Organize Folders for Assets, Scripts, Scenes, and Prefabs**

   - Once your project is created, organize your project hierarchy for better management:
     1. **Assets Folder:**
        - Create subfolders within the "Assets" folder for better organization. Right-click in the Project window and select "Create" > "Folder."
        - Create folders named "Scenes," "Scripts," "Prefabs," "Models," "Materials," "Textures," and "Audio."
     2. **Scenes Folder:**
        - This folder will contain all your scene files (.unity). Create an initial scene, such as "MainScene," by going to "File" > "New Scene" and saving it in the "Scenes" folder.
     3. **Scripts Folder:**
        - This is where you'll store your C# scripts. Create subfolders if necessary to organize scripts based on their function (e.g., "PlayerScripts," "AIControllerScripts").
     4. **Prefabs Folder:**
        - This folder will hold all prefab files, which are reusable game objects or components. Prefabs can include characters, environmental elements, and interactive objects.
     5. **Models, Materials, Textures, and Audio Folders:**
        - Place your 3D models, materials, textures, and audio files in their respective folders to keep everything organized.
---

   - **Tools Used:**
     - **Unity Hub** - for managing Unity installations and projects.
     - **Unity 3D** - for developing the VR experience.
     - **Oculus SDK/OpenXR SDK** - for VR hardware support.
     - **Documentation Tool** - for recording the setup 
     process.
     - **Blender** - for creating the 3d model 

---