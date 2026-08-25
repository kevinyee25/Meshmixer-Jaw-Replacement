# Meshmixer-Jaw-Replacement

This project demonstrates the development of a **3D jaw replacement model using Autodesk Meshmixer**, beginning with a scanned human lower jaw and progressing through mesh preparation, anatomical modification, surgical guide creation, and final STL export.

# 🦷 Jaw Replacement 3D Modelling – Meshmixer

## 📌 Project Overview

This project demonstrates the development of a **3D jaw replacement model using Autodesk Meshmixer**, starting from a human lower jaw scan.

The workflow involved processing the anatomical mesh, separating the teeth from the jaw, repairing and refining the geometry, and creating surgical guide holes before exporting the final model as an STL file.

---

## 🛠️ Tools & Techniques

- **Autodesk Meshmixer**
- STL mesh manipulation
- Anatomical mesh selection and separation
- Mesh repair and solidification
- Surface smoothing
- 3D transformation and positioning
- Boolean operations
- Design for additive manufacturing

---

## 🔄 Modelling Workflow

### 1. Original Lower Jaw Scan

The project began by importing `Human_Lower_Jaw.stl` into Meshmixer. A duplicate of the original scan was created as a backup before any modifications were performed.

### 📷 Original Human Lower Jaw — `Human_Lower_Jaw.stl`


<p align="center"> <img width="500" alt="Screen Shot 2026-08-25 at 9 37 07 pm" src="https://github.com/user-attachments/assets/e83114dd-1832-4d92-bf7f-129f96cacfb9" />


<p align="center">
  <img src="Human_Lower_Jaw.stl" width="650" alt="Original Human Lower Jaw Scan">
</p>

  <img src="images/original-lower-jaw.png" width="650" alt="Original Human Lower Jaw Scan">
</p>

---

### 2. Jaw Isolation & Mesh Preparation

The teeth were isolated from the mandibular structure using Meshmixer's selection and separation tools.

The remaining jaw geometry was then converted into a solid mesh using **Make Solid**, followed by surface refinement using the **Flatten** sculpting tool to smooth rough edges.

**Key operations:**
- Lasso Selection
- Smooth Boundary
- Invert Selection
- Separate
- Make Solid
- Flatten/Sculpt

---

### 3. Surgical Guide Development

Cylindrical geometry was created and modified to form surgical guide tubes.

The guide was duplicated and positioned symmetrically across the jaw, resulting in **six surgical guide locations**.

The guide tubes were then combined and a **Boolean Difference** operation was applied to create the corresponding holes within the jaw model.

---

### 4. Final Jaw Replacement Model

After completing the mesh modifications and surgical guide holes, the finished model was exported from Meshmixer as `JawReplacement_Kevin_Final.stl`.

### 📷 Final Jaw Replacement — `JawReplacement_Kevin_Final.stl`

<p align="center"> <img width="500" alt="Screen Shot 2026-08-25 at 9 41 15 pm" src="https://github.com/user-attachments/assets/6e7f31fb-5847-41cf-a8a8-802b80c0b1ad" />


<p align="center">
  <img src="JawReplacement_Kevin_Final.stl" width="650" alt="Final Jaw Replacement Model">
</p>

---

## 📂 Repository Contents

| File | Description |
|---|---|
| `Human_Lower_Jaw.stl` | Original human lower jaw scan used as the starting model. |
| `JawReplacement_PRT1.mix` | Intermediate Meshmixer file containing jaw isolation and mesh preparation. |
| `JawReplacement_PRT2.mix` | Intermediate Meshmixer file containing surgical guide development and positioning. |
| `JawReplacement_Kevin_Final.stl` | Final jaw replacement model exported as an STL file. |

---

## 💡 Skills Demonstrated

- Biomedical 3D modelling
- Anatomical mesh manipulation
- Autodesk Meshmixer
- Mesh repair and refinement
- Boolean modelling
- STL processing
- Design for additive manufacturing
- Git & Git LFS

