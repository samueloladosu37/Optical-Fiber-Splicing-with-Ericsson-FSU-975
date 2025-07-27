# Optical Fiber Fusion Splicing using the Ericsson FSU-975

This repository documents an experiment on **optical fiber fusion splicing** using the **Ericsson FSU-975 fusion splicer**. This exercise was conducted to gain hands-on experience with fiber optic preparation, splicing, and splice loss estimation.

---

## 🎯 Aim of the Experiment

To understand and execute a complete fiber optic welding process, including:
- Preparing optical fibers for fusion
- Operating the Ericsson FSU-975 fusion splicer
- Measuring welding quality through visual inspection and attenuation value.

---

## 🧪 Procedure

### 1. Introduction to the Equipment
- The **Ericsson FSU-975** is a single fiber fusion splicer used for precise fiber optic welding.
- It supports multiple splice types: **tape**, **gate**, and **lens** configurations.

### 2. Fiber Preparation
- Stripped ~30 mm of the outer protective coating
- Cleaned exposed fibers using isopropyl alcohol and cotton swabs
- Cleaved fibers with a high-precision cleaver ensuring perpendicular ends (~20 mm exposed)

### 3. Fusion Splicing Process
- Positioned fibers in the V-grooves visible on the monitor
- Closed the safety cover and initiated the **Auto Mode splicing**
- Pressed “Fuse” to start automatic alignment and fusion
- Monitored loss (target: < 0.2 dB) and verified splice quality via the built-in viewer

---
## 🧰 Tools & Equipment Used

- Ericsson FSU-975 Fusion Splicer  
- Optical Fiber Cleaver  
- Fiber Strippers  
- Isopropyl Alcohol & Cotton Swabs  
- Waste Disposal Unit for Fiber Ends  
- Heat-shrink Sleeves and Oven (for splice protection)

---

## 📊 Parameter Settings Used
Note that there are default programs or you can decide to define your parameters like I did.

### 📌 Splice Parameters (Tape Configuration)

| Parameter        | Value    |
|------------------|----------|
| Pull 1           | Yes      |
| Pull 2           | Yes      |
| Pull 3           | Yes      |
| Fusion Time 1    | 15.0 s   |
| Fusion Current 1 | 9.0 mA   |
| Fusion Time 2    | 5.0 s    |
| Fusion Current 2 | 7.0 mA   |
| Fusion Time 3    | 4.0 s    |
| Fusion Current 3 | 4.0 mA   |

### 📌 Splice Parameters (Lens Configuration)

| Parameter        | Value    |
|------------------|----------|
| Pull 1           | Yes      |
| Pull 2           | Yes      |
| Pull 3           | Yes      |
| Fusion Time 1    | 15.0 s   |
| Fusion Current 1 | 12.0 mA  |
| Fusion Time 2    | 5.0 s    |
| Fusion Current 2 | 10.0 mA  |
| Fusion Time 3    | 4.0 s    |
| Fusion Current 3 | 4.0 mA   |

---

## 🧠 Weld Types and Use Cases

| Weld Type | Use Case             | Typical Application                    | Loss       | Notes                                     |
|-----------|----------------------|----------------------------------------|------------|-------------------------------------------|
| **Tape**  | Standard fusion       | Long-haul telecom, fiber repair        | Very low   | Default method for most installations     |
| **Gate**  | Offset/transition     | Mismatched fibers, parameter tuning    | Low–moderate | Useful in experimental/test environments  |
| **Lens**  | Focusing/microlens   | Fiber sensors, laser/diode coupling    | Controlled | Requires pulling; used in precision optics|

---

## 🖼️ Splice Images

### 🔹 Tape Weld 
![Tape Weld](https://github.com/samueloladosu37/Optical-Fiber-Splicing-with-Ericsson-FSU-975/blob/main/Tape%20Weld.png)

### 🔹 Lens Weld : Fiber inserted from one end of the V-groove
![Lens Weld](https://github.com/samueloladosu37/Optical-Fiber-Splicing-with-Ericsson-FSU-975/blob/main/Lens.png)

---

## ✅ Conclusion

This experiment successfully demonstrated the process of fusion splicing, where two optical fibers are welded together under controlled heat using the Ericsson FSU-975 splicer. The quality of the splice is highly dependent on proper fiber preparation — including stripping, cleaning, and precise cleaving — followed by accurate alignment and welding.

### Key Results:
- Achieved an **attenuation (splice loss) of less than 0.2 dB**
- This is within the typical **industry standard** range, which accepts:
  - **≤ 0.10 dB** for high-performance telecom applications
  - **0.2–0.50 dB** as acceptable in many field installations

### Additional Observations:
- Visual inspection on the splicer was the first checkpoint for splice quality before measuring loss.
- Understanding the weld types (tape, lens) helped in recognizing their application-specific uses.
- The parameter tuning for different splice types (tape, lens, gate) required careful and control tuning.
- Proper fiber cleaving and cleanliness were critical stage to achieving low-loss connections.
---
