# 🪨 Rock Classification with ResNet18

A simple PyTorch project that classifies rocks by image using a ResNet18 model. The model can predict both:

- **Main class**: Igneous, Metamorphic, Sedimentary
- **Subclass**: Basalt, Granite, Marble, Quartzite, Coal, Limestone, Sandstone

---

📁 Folder Structure

- `Dataset/` → Rock image dataset
- `archive/Dataset/` → Backup copy of the dataset
- `models/`
  - `rock_resnet18_mainclass.pth` → predicts main rock classes (3)
  - `rock_resnet18_subclass.pth` → predicts detailed subclasses (7)
- `notebooks/`
  - `resnet18.ipynb` → model training
  - `preprocessing.ipynb` → resizing, normalization, splitting
  - `data_augmentation.ipynb` → flipping, rotation, brightness

---

## 🧪 How to Use

Open the notebooks in Jupyter or VS Code and run:
- `resnet18.ipynb` to train or evaluate
- Make sure you have the dataset and models in place

---

## 🔧 Requirements

Install required libs with:

```bash
pip install torch torchvision matplotlib
