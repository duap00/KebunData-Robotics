# 🤖 KebunData-Robotics

An autonomous omni-wheel robot project designed for research, mobility, and STEAM education. This journey is documented for social media platforms like Meta, TikTok, and YouTube.

## 📌 Project Overview
- **Status:** In Progress (Research and Prototyping)
- **Objective:** Build a high-degree-of-freedom (DoF) mobile manipulator with holonomic movement.
- **Target Audience:** DIY enthusiasts, STEAM students, and robotics researchers.

## 🛠 Tech Stack & Tools
- **Languages:** Python, ROS (Robot Operating System)
- **Controller:** Raspberry Pi CM4 (Master)
- **Cloud/Data:** OCI, PostgreSQL, Firebase

## ⚙️ Hardware Specifications
### Mobility (Base)
- **Motors:** 3x 12V 430RPM 1kgfcm 32mm Planetary DC Geared Motors with Encoders
- **Wheels:** 3x Omni-wheels
- **Drivers:** 2x 10A Motor Drivers

### Articulation (Upper Body)
- **Servos:** 40x Robotis XL-320
- **Degrees of Freedom:** High-DoF capability for multiple limbs or expressive mechanisms.

### Power System
- **Battery:** 11.1V (3S) Hardcase LiPo (5000mAh - 8000mAh recommended)
- **Power Distribution:** - **12V Rail:** Direct connection for drive motors.
  - **7.4V Rail:** High-current Buck Converter for 40x XL-320 servos.
  - **5V Rail:** Dedicated regulator for Raspberry Pi CM4 to prevent noise-related crashes.
- **Safety:** Low-voltage alarm (3.0V per cell threshold).

## 📈 Progress & Milestones
- [x] Phase 1: Research and Prototyping
- [ ] Phase 2: Core Development
- [ ] Phase 3: Testing and Deployment

## 🔗 Resources
- **Repository:** [https://github.com/duap00/KebunData-Robotics](https://github.com/duap00/KebunData-Robotics)
- **Inspiration:** STEAM DIY Community

---
*Follow the journey on Meta, TikTok, and YouTube!*
"""

with open("README.md", "w") as f:
    f.write(content)
