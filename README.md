# 🏎️ AI-Assisted Material Selection for Automotive Rims

![MATLAB](https://img.shields.io/badge/Made_with-MATLAB-blue.svg)
![Version](https://img.shields.io/badge/Version-1.0-brightgreen.svg)
![Engineering](https://img.shields.io/badge/Field-Mechanical_Engineering-orange.svg)

> **Watch the Presentation Video:** [Insert your Google Drive Video Link Here]

## 📖 Overview
Selecting the perfect material for automotive rims is vital for vehicle safety, performance, and manufacturing viability. This application is an advanced, interactive engineering tool designed to aid in choosing optimal materials (both existing and theoretical) for car rims. 

Powered by a comprehensive, custom-built CSV database of material properties, the app dynamically calculates loads, filters out unsafe materials, and ranks the best options based on real-world automotive constraints.

---

## ✨ Application Features (By Tab)

### 🚗 Tab 1: Selection & Overview
* **Car Type Presets:** Choose from Normal, Sport, Luxury, EV, or Custom profiles to automatically load the correct engineering weight distributions.
* **Top 10 Rankings:** Instantly displays the top-ranked materials tailored to your selected vehicle type.
* **Dynamic Stress-Strain Curve:** Click on any material to view a simulated stress-strain plot, accurately rendering the yield point, elastic modulus (slope), and fracture point (distinguishing between brittle composites and ductile metals).

### 📊 Tab 2: Screening & Ranking Engine
* **The Math Behind the Magic:** Dive into the exact methodology used to select the materials.
* **Pass/Fail Logic:** Displays the active screening table, highlighting surviving materials in green and eliminating failing materials in red based on strict safety constraints.
* **Weighted Scoring:** Shows the final decision matrix, calculating scores based on Ashby chart metrics, cost, manufacturing, and environmental factors.

### 📈 Tab 3: Interactive Ashby Chart
* **Strength vs. Density:** Explores the physical properties of the database visually.
* **Interactive Data Tips:** Hover over any point on the scatter plot to instantly identify the material name, its yield strength, and density.

### 📚 Tab 4: Reference Ashby Charts
* Includes static, real-world Ashby charts for broader materials science context and verification.

### 🛠️ Tab 5: 3D Model & Manufacturing Analysis
* **Interactive 3D View:** Features an interactive 3D model of the car rim, visualizing the geometry and the points where radial and lateral stresses are applied.
* **Real-World Constraints:** Displays detailed manufacturing processes (e.g., forging, autoclaving, CNC machining) and strict real-world constraints (e.g., toxicity, cycle times, tool wear) for the currently selected material.

### 🧮 Tab 6: Custom Load Calculator
* **Dynamic Physics Engine:** Enter custom values for the vehicle (e.g., total weight, cornering G-force) to instantly calculate the exact radial and lateral stresses on each rim.
* **Live System Updates:** The calculator actively communicates with the rest of the app. Changing the loads here automatically updates the Pass/Fail screening thresholds and generates a brand new Top 10 ranking on the first tab!
* **Custom Weights:** Use interactive sliders to manually define the importance of properties like Fatigue, Cost, and Impact resistance.

---

## 📸 Screenshots & Demo

*(Replace the links below with your actual uploaded images/videos)*

### Application Demo
![App Demo Video/GIF](https://drive.google.com/file/d/1N1BuNcwuFFrMN2Rs3A85YxV8IIV3cimt/view?usp=drive_link)
![presentation demo](https://drive.google.com/file/d/1tPsjXWnpGROBixqE_Eh3lXAzz7bm1eFl/view?usp=sharing)

### The Interface
![Tab 1 Interface](images/main-screen)
![Tab 1 Interface](images/screen2)
![Tab 1 Interface](images/screen3)
*Caption: The main selection dashboard and dynamic stress-strain generator.*

![Screening Table](images/screening)
*Caption: The advanced engineering screening and ranking matrix.*

![manufactring Table](images/manufactring)


![custom Table](images/custom2)
![Screening Table](images/screening3)

---

## 🚀 How to Run the App

**For Users (No MATLAB Required):**
1. Navigate to the **Releases** tab on the right side of this GitHub page.
2. Download the `.zip` file for the latest release.
3. Download and install the free **MATLAB Runtime** from the official MathWorks website (ensure you match the version used to compile this app).
4. Unzip the folder and double-click the `.exe` to launch the app!

**For Developers:**
1. Clone this repository to your local machine.
2. Open MATLAB.
3. Open the `Ai_Material_Selection_BiggerPrototype.mlapp` file in App Designer.
4. Ensure the `MaterialDatabase.csv` is in the same directory.
5. Click **Run**.

---

## 🔮 Future Roadmap
We are continuously looking to improve the realism and utility of this software. Upcoming features include:
- [ ] **FEA Heat Maps:** Integration of Finite Element Analysis visual heat maps to show stress concentrations directly on the 3D rim model.
- [ ] **Expanded Database:** Adding more theoretical nano-materials and advanced hypercar composites.
- [ ] **Fatigue Life Calculator:** Estimating the cycle life of the rim based on the selected material and custom loads.

---

## 👨‍💻 Authors & Acknowledgments
* Built by Ali Mohamed Ahmed Hassan 
* Developed at Ain Shams University - Faculty of Engineering.
