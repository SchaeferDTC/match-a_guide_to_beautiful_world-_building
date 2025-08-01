# Creating a New Gazebo World  
## Or: Creating New Objects and Adding Them to an Existing Gazebo World

![Example world](./images/preview.png)
<!-- Cool picture of a fancy Gazebo world -->

---

## 🛠️ Workflow Overview

1. Create a `.obj` file in **Autodesk Inventor** for accurate measurements and basic coloring.
2. Import the `.obj` into **Blender**; add textures (e.g., `.png` files) if needed.
3. Export the object from Blender as a `.dae` file.
4. Create a **Gazebo world**.
5. Add the exported object to your Gazebo world.

---

## 🔧 Autodesk Inventor

- Design your object using **millimeters (mm)**.
- Export the model as an `.obj` file — this format supports basic coloring.
- You can apply colors directly using Inventor’s materials or use different colors for texture groups that will later be textured in Blender.

---

## 🧊 Blender

### Step 0 – Set Blender to Use Millimeters by Default

1. Click on the **Scene** tab.
2. Open the **Units** section and change **Length** from *meters* to *millimeters*.
3. Save as default: `File → Defaults → Save Startup File`.

### Step 1 – Import the CAD Model from Inventor

- Go to `File → Import → Wavefront (.obj)` and select your exported file.

### Step 2 – Apply Textures and Colors

1. Switch to **UV Editing** mode — Blender will split the screen.
2. In the right panel:
   - Switch to **Edit Mode** and enable **Face Select**.
   - If needed, convert triangle meshes to quads with `Alt + J`.
   - Select all faces, press `U`, and choose **Smart UV Project**. This method tends to produce the least distortion.

### Step 3 – Open the Texture Image

- In the **left half** of the screen, near the top center, click **Open** and load your texture image (e.g., `texture.png`).

### Step 4 – Arrange the Unwrapped Mesh

- Use **Move** and **Rotate** tools to position your mesh over the texture.
- Hotkeys:
  - `1` – Vertex select  
  - `2` – Edge select  
  - `3` – Face select  
- Arrange the mesh as needed — patience is key here!

### Step 5 – Apply the Texture as Material

1. In the **right properties panel**, select the **Material** tab.
2. Click the **yellow dot** next to **Base Color** and choose **Image Texture** `I`.
3. Click the **image icon** and select your previously loaded texture.
4. If the preview doesn't update, try changing the shading mode in the top right (e.g., to **Material Preview**).

### Final Step – Export as `.dae`

- Go to `File → Export → Collada (.dae)`  
- Use the **legacy** export option if available.
:dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace:  :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace::dove_of_peace: :dove_of_peace::dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace: :dove_of_peace:
https://www.youtube.com/watch?v=1YCzHmPI7dM
decent tutorial
