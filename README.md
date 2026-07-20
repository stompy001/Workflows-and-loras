---
license: mit
pipeline_tag: text-to-image
tags:
  - comfyui
  - lora
  - flux
  - sdxl
  - image-generation
library_name: comfyui
---

# 🎨 ComfyUI Workflows & Custom LoRAs

A curated collection of production-grade ComfyUI workflows paired with custom-trained LoRAs across multiple state-of-the-art diffusion architectures (**SDXL**, **FLUX**, **Klein**, and **Z-Image Turbo**).

Due to file size limits on GitHub, all heavy model weights (`.safetensors`) are hosted for free on **Hugging Face**, while execution workflows (`.json`) and installation guides are stored directly in this repository.

---

## 🌟 Featured Showcase

<div align="center">
  <img src="https://github.com/user-attachments/assets/a0d5ad44-6677-4b7a-89f5-7dbff33430b1" width="100%" />
</div>

<br/>

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/c488fa85-b963-4f7a-aef8-f9fe797eff1b" width="100%" />
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/6e7600b8-5a8b-40f3-a51e-4d2c073e16f9" width="100%" />
    </td>
  </tr>
</table>

---

## 💡 Model & Checkpoint Recommendations

* **Trigger Words:** Set your trigger word to the **exact model filename** (e.g., if the file is `character_name.safetensors`, use `character_name` in your prompt).
* **Weights & Ranks:** The LoRAs vary in network rank and weight—adjust the LoRA strength between `0.6` and `1.0` depending on prompt complexity.
* **Recommended SDXL Checkpoints:** 
  * [WAI Illustrative](https://civitai.com)
  * [AnythingXL](https://civitai.com)
  * [MeinaMix](https://civitai.com)
  *(Note: Compatible with virtually all SDXL base checkpoints!)*

---

## 🖼️ Sample Gallery

<div align="center">
  <img src="https://github.com/user-attachments/assets/ae06684b-fb2d-492f-93c7-dcac8aa58168" width="100%" />
</div>

<br/>

<table>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/42777ca6-237f-46cf-acf8-7598c64d9ab2" width="100%" />
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/37cebc91-60c2-44db-ba4a-b7f2d84ca531" width="100%" />
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/22c3c10a-a52d-4ffd-9385-680dc6227662" width="100%" />
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/76c49092-6e5e-4873-9c24-bc496a565d0c" width="100%" />
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/53fceffa-8d81-49df-8aef-d70b2a634b2a" width="100%" />
    </td>
    <td align="center" width="50%">
      <img src="https://github.com/user-attachments/assets/967b4856-fb51-4d68-bec9-606b23fc4dbe" width="100%" />
    </td>
  </tr>
</table>

<div align="center">
  <img src="https://github.com/user-attachments/assets/9a65a2da-4477-4461-a6a4-f7dc054b82f4" width="60%" />
</div>

---

## 📁 Repository & Directory Layout

To keep your local ComfyUI setup organized, models and workflows are categorized into dedicated subfolders:

```text
├── workflows/
│   ├── sdxl/               # SDXL ComfyUI workflow JSONs
│   ├── flux/               # FLUX ComfyUI workflow JSONs
│   └── z_image_turbo/      # Z-Image Turbo ComfyUI workflow JSONs
└── README.md

