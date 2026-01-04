# Truss-2D-Analysis
# 🏗️ ANSYS Static Structural Analysis of a 14-Member 2D Truss

## 📋 Project Overview
This repository contains a **static structural analysis** of a 14-member 2D truss structure performed in **ANSYS Mechanical**. The simulation analyzes the truss's deformation and stress distribution under multiple downward forces, with results validated against engineering principles.

---

## 🎯 Key Results

### 📏 **Maximum Total Deformation:** 4.1589 mm
![Total Deformation](Truss%20Total%20Deformation.jpg)

### ⚠️ **Maximum Stress Conditions:**
- **Direct Stress Range:** -331.37 MPa to 140.59 MPa
- **Maximum Combined Stress:** 140.59 MPa
- **Minimum Combined Stress:** -338.12 MPa

### 📊 **Reaction Forces at Supports:**
- **Total Reaction Force:** 5,361.9 N at each support
- **X-direction Reactions:** ±3,832.5 N (opposite directions)
- **Y-direction Reactions:** 3,750 N each (upward)

---

## 🏗️ **Model Specifications**

### 📐 **Geometry**
- **Type:** 2D Truss Structure (14 members)
- **Dimensions:** 3.0 m (length) × 0.9 m (height)
- **Total Length of Members:** 13.193 m
- **Number of Nodes:** 183
- **Number of Elements:** 96 (Beam elements)

### 🔩 **Cross-Sectional Properties**
- **Type:** Rectangular (Rect1)
- **Dimensions:** 4 mm × 4 mm
- **Area:** 1.6 × 10⁻⁵ m²
- **Moment of Inertia (Iyy, Izz):** 2.1333 × 10⁻¹¹ m⁴

### ⚙️ **Material Properties** (Structural Steel)
| Property | Value | Unit |
|----------|-------|------|
| Density | 7850 | kg/m³ |
| Young's Modulus | 200 | GPa |
| Poisson's Ratio | 0.3 | - |
| Yield Strength | 250 | MPa |
| Ultimate Tensile Strength | 460 | MPa |
| Thermal Expansion Coefficient | 1.2 × 10⁻⁵ | 1/°C |

---

## 🔧 **Boundary Conditions & Loading**

### 🏗️ **Supports**
- **Fixed Support 1:** Leftmost node (full constraint)
- **Fixed Support 2:** Rightmost node (full constraint)

### ⬇️ **Applied Loads** (5 points along top chord)
- **Force Type:** Concentrated Nodal Forces
- **Magnitude:** 1,500 N each (downward, Y-direction)
- **Total Applied Load:** 7,500 N

### ⚙️ **Solver Settings**
- **Analysis Type:** Static Structural
- **Solver:** Mechanical APDL
- **Time Step:** 1 second
- **Large Deflection:** Off
- **Element Type:** Beam (BEAM188 equivalent)

---

## 📈 **Analysis Results Summary**

### 🎯 **Deformation Analysis**
- **Maximum Deformation:** 4.1589 mm (0.0041589 m)
- **Location:** Central region of top chord
- **Safety Factor (based on yield):** ~0.74 (critical condition)

### ⚠️ **Stress Analysis**
- **Maximum Tensile Stress:** 140.59 MPa
- **Maximum Compressive Stress:** -338.12 MPa
- **Stress Concentration:** At joints and supports
- **Yield Criterion:** Maximum stress exceeds yield strength (250 MPa) in compression

### 📊 **Reaction Analysis**
- **Support Reactions:** Symmetrical due to symmetric loading
- **Horizontal Reactions:** Indicate significant thrust forces
- **Vertical Reactions:** Equal to total applied load (7,500 N total)
## 👨‍💻 Author  
**Yazan Alzyuod**  
- **Mechanical Engineer**  
- 📧 Email: [yqlasem@gmail.com](mailto:yqlasem@gmail.com)  
- 🔗 LinkedIn: [Yazan Alzyuod](https://www.linkedin.com/in/yazan-alzyuod)  
- 💻 GitHub: [Yazan-Alzyuod](https://github.com/Yazan-Alzyuod)  
- 📞 Phone: +962 775 327 776 
