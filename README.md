<h1 align="center">Wacky Wheels</h1>
<h3 align="center">High-Octane, Physics-Based Racing Game | Built with Unity & C#</h3>

<p align="center">
  A high-octane, physics-based racing game built in Unity. Featuring chaotic tracks, unpredictable hazards, and a customizable vehicle roster, <strong>Wacky Wheels</strong> is designed to test reflex-based gameplay, state tracking, and precision vehicle physics orchestration.
</p>

<p align="center">
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge" alt="License" />
  </a>
</p>

---

### Core Features

* **Rigid Physics-Driven Mechanics:** Leverages Unity's 3D physics engine (`Rigidbody` manipulation, custom surface friction matrices, and precise angular velocity dampening) to simulate car mechanics, high-impact collisions, and tactile drift controls.
* **Modular Vehicle Architecture:** Implements abstract object structures in C# to easily configure disparate wheel-torque profiles, weight distribution parameters, and engine power limits across the car roster.
* **Dynamic Track Obstacles:** Integrates modular event-driven triggers and kinematic obstacles that test player handling in real time.
* **Polished UI/UX (Unity UGUI):** Engineered with canvas optimizations, managing real-time responsive speedometers, contextual state changes, and unified menus.

---

### Development Stack

**Game Engine & Logic**
<p align="left">
  <img src="https://img.shields.io/badge/Unity_Engine-000000?style=for-the-badge&logo=unity&logoColor=white" alt="Unity" />
  <img src="https://img.shields.io/badge/C%23_Scripting-239120?style=for-the-badge&logo=c-sharp&logoColor=white" alt="C#" />
</p>

---

### Gameplay & Systems Showcase

<p align="center">
  <img src="Images/1.PNG" width="48%" />
  <img src="Images/2.PNG" width="48%" />
</p>
<p align="center">
  <img src="Images/4.PNG" width="48%" />
  <img src="Images/6.PNG" width="48%" />
</p>

---

### How to Run & Build

**1. Clone the repository:**
```bash
git clone https://github.com/filipposobrijanu/Wacky-Wheels-Game.git
cd Wacky-Wheels-Game
```

**2. Open Project in Unity Editor:**
* Launch **Unity Hub**.
* Click **Add** -> **Add project from disk** and select the cloned root repository folder.
* Ensure your editor version matches or is compatible with the project configuration (recommended: Unity 2022.3 LTS or higher).

**3. Build or Play:**
* Open the default main menu scene found in `Assets/Scenes/`.
* Press the **Play** button in the editor toolbar to test instantly, or navigate to **File -> Build Settings** to generate a standalone runtime artifact (`.exe` or `.app`).
