# ISE Wafer Mount Plate – SolidWorks Project

This project contains the CAD design of a wafer mount plate used for experimental setups. It is designed to fit precisely below the previously created fixture base and aligns via a standardized 0.75 inch hole matrix.

---

## 📌 Overview

The mount plate is intended to support wafer-level experimentation. It provides alignment holes and cutouts for electrical access or thermal contact, while maintaining mechanical stability.

---

## 🧰 Specifications

- **Units**: Inches  
- **Plate Dimensions**: 3.25" × 4"  
- **Hole Matrix Spacing**: 0.75" center-to-center  
- **Hole Type**: 4-40 through counterbore  
- **Bracket Depth**: 0.2" (top lip)  
- **Total Plate Depth**: 0.4"  
- **Additional Cutout**: 1.35" × 0.7" (if not anchored to the bracket)

---

## 📂 Folder Structure

- `Parts/` – SolidWorks `.SLDPRT` and `.STEP` files  
- `Drawings/` – Associated `.SLDDRW` and `.PDF` drawing files  
- `Images/` – Reference photos, sketches, and screenshots

---

## 🔁 Development Workflow

From `local_dev` branch:
```bash
git checkout ise_wafer_mount_plate
git checkout local_dev -- ise-wafer-mount-plate
git commit -am "Update ISE Wafer Mount Plate from local_dev"
git push origin ise_wafer_mount_plate
