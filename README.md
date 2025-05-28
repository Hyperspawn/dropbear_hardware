# 🦿 Dropbear Hardware Repository

This repository contains the full mechanical design of **Dropbear**, a modular open-source humanoid robot developed by [Pointblank LLC](https://www.pointblankllc.com) & [Hyperspawn](https://github.com/Hyperspawn).

It includes CAD files for the complete robot as well as modular subassemblies for easier prototyping, simulation, and manufacturing.

---

## 🧱 Structure

### 🔧 `Assembly/`
- Full robot CAD as `.step` and `.f3z` (Fusion 360 archive with materials)

### 🦾 `subassemblies/`
Modular mechanical parts, structured by limb:
- `arms/`: Left & Right arms, Altair Inspire model, and finger prototypes
- `head/`: Full head unit (Also refer [Neck Assembly](https://github.com/robit-man/Dropbear-Neck-Assembly))
- `legs/`: Left & Right legs
- `pelvis/`: Central connector to legs and torso
- `torso/`: Main structural housing and spine

### 🖼 `Images/`
Rendered PNG views for quick reference, docs, or presentations

---

## 💡 Design Notes

- Designed using **Fusion 360** and exported to **STEP**, **STMOD**, and **USDZ** formats.
- All parts are either:
  - 3D-printable (refer to [Dropbear Printables](https://github.com/Hyperspawn/dropbear_printables))
  - CNC-machinable
  - Or can be sourced locally (refer to [Dropbear BOM](https://github.com/Hyperspawn/dropbear_bom))

---

## 📦 Use Cases

Dropbear is designed as a general-purpose humanoid platform — open, modular, and adaptable. While industry leaders like **Tesla Optimus**, **Figure 01**, and **Unitree H1** are building proprietary systems, Dropbear aims to democratize access to advanced robotic hardware.

### 🧠 Research & Development
- Robotics labs can prototype motion planning, control algorithms, or RL policies on an open humanoid.
- Serves as a physical benchmark alongside MuJoCo or Isaac Sim simulations.

### 👨‍🏫 Education & Academia
- Universities and teaching labs can use Dropbear as a full-stack robotics teaching platform — from mechanical design to high-level control.

### 🧪 AI Embodiment Testing
- Seamless integration with vision-language models (VLMs), LLMs, and RL agents makes it ideal for testing embodied AI policies.

### 🛠️ Makers & Indie Robotics
- Hackers, builders, and small teams can build humanoid systems without million-dollar labs or locked-down hardware stacks.

### 🤖 Simulation-to-Real Transfer
- Use with ROS2, Gazebo, and MuJoCo for sim2real experimentation.
- Easily export components for real-world deployment with custom firmware and electronics.


---

## 🧰 Dependencies

- **Fusion 360** (preferred for full assembly with materials)
- **Altair Inspire** (for structure validation + simulation)
- **FreeCAD** / **SolidWorks** (for STEP access)

---

## 📬 Contributing

Got a better frame layout, hand mechanism, or weight optimization? Fork and PR! Open source robotics gets better with shared iterations.

---

## 📄 License

[MIT](LICENSE)

---

Dropbear is part of the **Hyperspawn** platform — building free, advanced, embodied systems for the world.
