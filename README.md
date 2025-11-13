# Reflect-It - Docs

🧩 **Overview**

**Reflect It!** is a glass shader pack for Unity’s **Universal Render Pipeline (URP)** designed to create both realistic and stylized glass materials.  
It includes **12+ unique normal maps** and **three shader variants**, allowing flexible control over **refraction**, **reflection**, and **distortion**.

---

## 🚀 Quick Start

1. Import the asset into your **URP project**.  
2. Create a new **Material** and assign one of the included shaders:

   - `ReflectIt/Glass_Lit`  
   - `ReflectIt/Glass_Unlit`  
   - `ReflectIt/SimpleGlass_Lit`

3. Adjust **Transparency**, **Smoothness**, and **Refraction** values to fit your visual style.  
4. Assign a **Normal Map**, or enable **Triplanar Mode** for automatic projection on models without proper UVs.

---

## 🎨 Shader Variants

| Shader | Description | Recommended Use |
|--------|--------------|-----------------|
| **Glass_Lit** | Fully lit glass shader with realistic lighting, reflections, and refraction. | Architectural or realistic scenes. |
| **SimpleGlass_Lit** | Lightweight alternative for optimized or mobile projects. | Mobile or low-performance builds. |
| **Glass_Unlit** | Stylized/emissive version without lighting dependency. | Artistic or stylized games. |

---

## ⚙️ Main Properties

| Property | Description |
|-----------|--------------|
| `_Color` | Base color of the glass material. |
| `_Alpha` | Controls transparency level. |
| `_Smoothness` | Adjusts reflection sharpness. |
| `_IOR` | Index of Refraction (typical range: 0.0–0.33). |
| `_FrenselPower` / `_FrenselStrength` | Controls edge brightness and reflection intensity. |
| `_NormalTexture` / `_NormalStrength` | Defines surface detail and distortion strength. |
| `_UseTriplanarNormal` | Enables triplanar projection (no UVs required). |
| `_Blur` | Adds a frosted-glass blur effect to refraction. |

---

## 💡 Tips

- Combine multiple **normal maps** for complex surface effects.  
- Use **Triplanar mode** on modular or UV-less meshes.  
- Set up proper **lighting** and **reflection probes** for realistic refraction.  
- For **realistic glass:** use subtle refraction and high smoothness.  
- For **stylized glass:** use stronger colors and distortion values.

---

## 🔧 Compatibility

✅ **Universal Render Pipeline (URP)**  
❌ **Built-in Render Pipeline**  
❌ **High Definition Render Pipeline (HDRP)**

---

## 📄 License

Distributed under the **Unity Standard Asset Store EULA**.  
Allowed for both **personal** and **commercial** use.
