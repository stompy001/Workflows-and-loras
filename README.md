---
license: mit
pipeline_tag: text-to-image
tags:
  - comfyui
  - lora
  - flux
  - sdxl
library_name: comfyui
---

# 🎨 ComfyUI Workflows & Custom LoRAs

<div align="center">
  <img src="https://github.com/user-attachments/assets/a0d5ad44-6677-4b7a-89f5-7dbff33430b1" width="31%" />
  <img src="https://github.com/user-attachments/assets/c488fa85-b963-4f7a-aef8-f9fe797eff1b" width="31%" />
  <img src="https://github.com/user-attachments/assets/6e7600b8-5a8b-40f3-a51e-4d2c073e16f9" width="31%" />
</div>

A curated collection of production-grade ComfyUI workflows paired with custom-trained LoRAs across multiple state-of-the-art diffusion architectures (**SDXL**, **FLUX**, **Klein**, and **Z-Image Turbo**).

Due to file size limits on GitHub, all heavy model weights (`.safetensors`) are hosted for free on **Hugging Face**, while execution workflows (`.json`) and installation guides are stored directly in this repository.

---

## 📁 Repository & Directory Layout

To keep your local ComfyUI setup organized, models and workflows are categorized into dedicated subfolders by architecture:

    ├── workflows/
    │   ├── sdxl/               # SDXL ComfyUI workflow JSONs
    │   ├── flux/               # FLUX ComfyUI workflow JSONs
    │   └── z_image_turbo/      # Z-Image Turbo ComfyUI workflow JSONs
    └── README.md

Additional notes- the loras are all different weights and rank, some may output better quality on certain prompts. 
For sdxl loras, recommended checkpoints are wai illustrative, anythingxl and meinamix [but it works with almost all sdxl checkpoints, try it out :)]

Samples-

<img src="https://github.com/user-attachments/assets/ae06684b-fb2d-492f-93c7-dcac8aa58168" width="100%" />
<img src="https://github.com/user-attachments/assets/42777ca6-237f-46cf-acf8-7598c64d9ab2" width="32%" />
<img src="https://github.com/user-attachments/assets/37cebc91-60c2-44db-ba4a-b7f2d84ca531" width="32%" />
<img src="https://github.com/user-attachments/assets/22c3c10a-a52d-4ffd-9385-680dc6227662" width="32%" />
<img src="https://github.com/user-attachments/assets/76c49092-6e5e-4873-9c24-bc496a565d0c" width="32%" />
<img src="https://github.com/user-attachments/assets/53fceffa-8d81-49df-8aef-d70b2a634b2a" width="32%" />
<img src="https://github.com/user-attachments/assets/967b4856-fb51-4d68-bec9-606b23fc4dbe" width="32%" />
<img src="https://github.com/user-attachments/assets/9a65a2da-4477-4461-a6a4-f7dc054b82f4" width="32%" />

---

## 🤗 Hugging Face Model Downloads

Download the `.safetensors` model weights directly from the official **Hugging Face Repository**:

👉 **[Hugging Face Repository Hub](https://huggingface.co/stomp001/free-character-models/tree/main)**

---

## ⚡ How to Use

[TRIGGER WORD SAME AS MODEL NAME]

### 1. Download Model Weights- https://huggingface.co/stomp001/free-character-models/tree/main
1. Visit the **Hugging Face** repository linked above.
2. Download the `.safetensors` files for the architectures you wish to use.
3. Place them into your local ComfyUI setup under `ComfyUI/models/loras/` (you can keep them organized in subfolders like `loras/sdxl/`, `loras/flux/`, etc.).

### 2. Load Workflows
1. Open your local **ComfyUI**.
2. Navigate to the `workflows/` folder in this repository.
3. Drag and drop any `.json` workflow file directly onto your ComfyUI canvas workspace.
4. Ensure your **Load LoRA** nodes are pointed to the correct subfolder path for the model you downloaded.
5. Click **Queue Prompt** to generate!

---

## 🛠️ Recommended Custom Nodes

To ensure all included workflows run smoothly without missing node errors, make sure you have the following custom nodes installed via **ComfyUI Manager**:

* [ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager) (To resolve missing nodes automatically)
* [ComfyUI-Quick-Merge](https://github.com/stompy001/ComfyUI-Quick-Merge) (For automated batching and image layering)

---

## 📜 License & Usage Rules

* Workflows contained in this repository are open for personal and commercial use under the **MIT License**.
* Individual LoRA model licenses (e.g., FLUX, SDXL non-commercial restrictions) apply based on their underlying base model terms. Check the Hugging Face repository model card for individual commercial licensing details.
