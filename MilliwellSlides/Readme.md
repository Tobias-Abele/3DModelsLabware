# Milliwell Slides

![Rendered image of the favorite milliwell slides of my lab](https://github.com/Tobias-Abele/3DModelsLabware/blob/main/MilliwellSlides/MilliWellSlides.png)

Design and print custom milliwell slides for laboratory experiments. This repository provides STL files for commonly used slide layouts in our lab, along with a fully customizable **Blender-based slide generator** using geometry nodes.

---

## 🔧 General Use

These milliwell slides are designed for standard use in a wet lab. They were printed with a filament 3D printer using PLA. No harmful effects were observed when used with lipid vesicles or standard cell culture lines. However, **PLA is not guaranteed to be non-(cyto)toxic**. Use at your own discretion.

- Download ready-to-print STL files from the [STL folder](https://github.com/Tobias-Abele/3DModelsLabware/tree/main/MilliwellSlides).
- Customize your own designs using the `Slidegenerator.blend` file in [Blender](https://www.blender.org/download/).

---

## ⚡ Quick Start

You can use this project in two ways:

### ➤ **Option 1: Use Predefined Slides**

1. Go to the [MilliwellSlides folder](https://github.com/Tobias-Abele/3DModelsLabware/tree/main/MilliwellSlides).
2. Download any of the `.stl` files for your preferred layout.
3. Import the STL into your 3D printer software and print.

### ➤ **Option 2: Customize Your Own Slides**

1. Download and install [Blender 4.3.2](https://www.blender.org/download/).
2. Open `Slidegenerator.blend` in Blender.
3. Adjust slide parameters in the *Modifiers* tab or via geometry nodes.
4. Export your custom design as an STL for printing.

---

## 🧪 Slide Generator

The file `Slidegenerator.blend` was created using **Blender 4.3.2** with geometry nodes. Using other versions may result in compatibility issues.

### Customization
- Modify slide layout in the *Modifiers* tab.
- Use geometry node parameters for more advanced adjustments (e.g., spacing, well count, dimensions).

**Visual aids:**

<img src="https://github.com/Tobias-Abele/3DModelsLabware/blob/main/MilliwellSlides/GeometryNodes.png" width="400" alt="Geometry nodes setup of the slide generator">
<img src="https://github.com/Tobias-Abele/3DModelsLabware/blob/main/MilliwellSlides/ModifiersTab.png" height="300" alt="Modifiers tab in Blender of the slide for changing parameters">

---

## ⭐ Lab Favorites

These are the milliwell configurations most commonly used in our lab:

### General Dimensions
- **Base:** 60.0 mm × 24.0 mm × 1.0 mm  
- **Walls:** 50.0 mm × 23.0 mm × 4.0 mm

### Well Layouts

| Slide Type     | Well Size (mm) | Margins (mm) |
|----------------|----------------|---------------|
| 2 well slide   | 22.0 × 20.0     | 2.0           |
| 4 well slide   | 10.0 × 20.0     | 2.0           |
| 18 well slide  | 5.5 × 5.5       | 1.5           |
| 36 well slide  | 4.0 × 4.0       | 1.0           |
| 72 well slide  | 3.0 × 3.0       | 1.0           |

---

## 📜 License

This project is open-source under the [MIT License](LICENSE).

---

## 🧾 Citation

If you use this generator in your research, feel free to cite it as:

> Abele, T. (2025). *Milliwell Slide Generator*. GitHub repository: [https://github.com/Tobias-Abele/3DModelsLabware](https://github.com/Tobias-Abele/3DModelsLabware)

---

## 🙋‍♂️ Contributions

Issues and pull requests are welcome! Feel free to open a discussion if you'd like to collaborate or suggest improvements.

---
