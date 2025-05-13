# 832 Mount Insert – SolidWorks Project

This project contains the design of a precision insert block featuring 8-32 thru mounting holes with mounting slots. The insert is intended to replace selected holes from the ISE wafer mount grid to allow for alternate mounting configurations or tool integration.

---

## 📌 Overview

The insert provides a pair of 8-32 thru holes embedded in a recessed slot geometry, designed for compatibility with standardized 0.75" grid spacing. It is modeled as a separate part to allow modular use within the ISE wafer mount design.

---

## 🧰 Specifications

- **Units**: Inches  
- **Insert Thickness**: 0.25 in  
- **Slot Dimensions**: 0.7 in length × 1.0 in width  
- **Slot Depth**: 0.25 in (full-depth cut)  
- **Mounting Holes**: 2x 8-32 UNC thru holes  
- **Hole Spacing**: 1.35 in center-to-center (between holes)  
- **Material**: Aluminum 6061-T6 (recommended)  

---

## 📂 Folder Structure

- `Parts/` – SolidWorks `.SLDPRT` and `.STEP` model files  
- `Drawings/` – `.SLDDRW` and `.PDF` drawing files  
- `Images/` – Reference sketches and real-world photos  

---

## 🔁 Development Workflow

From `local_dev` branch:
```bash
git checkout 832-mount-insert
git checkout local_dev -- 832-mount-insert
git commit -am "Sync 832 insert design from local_dev"
git push origin 832-mount-insert
```