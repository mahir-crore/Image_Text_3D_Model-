# 🖼️ Image to 3D Mesh Generator

This project transforms a simple 2D image into a 3D mesh using image processing and geometry generation techniques. It uses the alpha channel of an image (after background removal) to generate a height map and then converts that into a renderable 3D mesh.

---

## 🚀 Features

- 📷 Load any image (PNG or JPG)
- 🧼 Automatically remove background using AI (`rembg`)
- 🌄 Generate a grayscale height map from the image's alpha channel
- 🧱 Create a 3D mesh from the height map using `trimesh`
- 🌀 Render the mesh interactively using `pyrender`

---

## 🔧 Tech Stack

- **Language:** Python
- **Libraries:** `numpy`, `opencv-python`, `Pillow`, `rembg`, `trimesh`, `pyrender`, `matplotlib`, `torch`, `tqdm`

---

## 📦 Installation & Usage

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/image-to-3d-mesh.git
cd image-to-3d-mesh

# 2. (Optional) Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# 3. Install dependencies
pip install numpy opencv-python pillow rembg trimesh pyrender matplotlib torch tqdm

# 4. Launch the notebook
jupyter notebook Untitled-checkpoint.ipynb
