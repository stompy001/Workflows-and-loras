\# 🎨 ComfyUI Workflows \& Custom LoRAs



A curated collection of production-grade ComfyUI workflows paired with custom-trained LoRAs across multiple state-of-the-art diffusion architectures (\*\*SDXL\*\*, \*\*FLUX\*\*, \*\*Klein\*\*, and \*\*Z-Image Turbo\*\*).



Due to file size limits on GitHub, all heavy model weights (`.safetensors`) are hosted for free on \*\*Hugging Face\*\*, while execution workflows (`.json`) and installation guides are stored directly in this repository.



\---



\## 📁 Repository \& Directory Layout



To keep your local ComfyUI setup organized, models and workflows are categorized into dedicated subfolders by architecture:



```text

├── workflows/

│   ├── sdxl/               # SDXL ComfyUI workflow JSONs

│   ├── flux/               # FLUX ComfyUI workflow JSONs

│   ├── klein/              # Klein ComfyUI workflow JSONs

│   └── z\_image\_turbo/      # Z-Image Turbo ComfyUI workflow JSONs

└── README.md

```



\---



\## 🤗 Hugging Face Model Downloads



Download the `.safetensors` model weights directly from the official \*\*Hugging Face Repository\*\*:



👉 \*\*\[Hugging Face Repository Hub](https://huggingface.co/YOUR\_USERNAME/YOUR\_HF\_REPO)\*\*



\### 📦 Available LoRA Models \& Paths



| Architecture | Model Name | Description | ComfyUI Placement Path | HF Download Link |

| :--- | :--- | :--- | :--- | :--- |

| \*\*SDXL\*\* | `your\_sdxl\_lora.safetensors` | Custom SDXL style/concept LoRA | `ComfyUI/models/loras/sdxl/` | \[Download](https://huggingface.co/YOUR\_USERNAME/YOUR\_HF\_REPO/blob/main/sdxl/your\_sdxl\_lora.safetensors) |

| \*\*FLUX\*\* | `your\_flux\_lora.safetensors` | High-detail FLUX generation LoRA | `ComfyUI/models/loras/flux/` | \[Download](https://huggingface.co/YOUR\_USERNAME/YOUR\_HF\_REPO/blob/main/flux/your\_flux\_lora.safetensors) |

| \*\*Klein\*\* | `your\_klein\_lora.safetensors` | Specialized Klein architecture LoRA | `ComfyUI/models/loras/klein/` | \[Download](https://huggingface.co/YOUR\_USERNAME/YOUR\_HF\_REPO/blob/main/klein/your\_klein\_lora.safetensors) |

| \*\*Z-Image Turbo\*\* | `your\_zturbo\_lora.safetensors` | Ultra-fast Z-Image Turbo iteration LoRA | `ComfyUI/models/loras/z\_image\_turbo/` | \[Download](https://huggingface.co/YOUR\_USERNAME/YOUR\_HF\_REPO/blob/main/z\_image\_turbo/your\_zturbo\_lora.safetensors) |



\---



\## ⚡ How to Use


\[TRIGGER WORD SAME AS MODEL NAME]



\### 1. Download Model Weights

1\. Visit the \*\*Hugging Face\*\* repository linked above.

2\. Download the `.safetensors` files for the architectures you wish to use.

3\. Place them into your local ComfyUI setup under `ComfyUI/models/loras/` (you can keep them organized in subfolders like `loras/sdxl/`, `loras/flux/`, etc.).



\### 2. Load Workflows

1\. Open your local \*\*ComfyUI\*\*.

2\. Navigate to the `workflows/` folder in this repository.

3\. Drag and drop any `.json` workflow file directly onto your ComfyUI canvas workspace.

4\. Ensure your \*\*Load LoRA\*\* nodes are pointed to the correct subfolder path for the model you downloaded.

5\. Click \*\*Queue Prompt\*\* to generate!



\---



\## 🛠️ Recommended Custom Nodes



To ensure all included workflows run smoothly without missing node errors, make sure you have the following custom nodes installed via \*\*ComfyUI Manager\*\*:



\* \[ComfyUI-Manager](https://github.com/ltdrdata/ComfyUI-Manager) (To resolve missing nodes automatically)

\* \[ComfyUI-Quick-Merge](https://github.com/stompy001/ComfyUI-Quick-Merge) (For automated batching and image layering)



\---



\## 📜 License \& Usage Rules



\* Workflows contained in this repository are open for personal and commercial use under the \*\*MIT License\*\*.

\* Individual LoRA model licenses (e.g., FLUX, SDXL non-commercial restrictions) apply based on their underlying base model terms. Check the Hugging Face repository model card for individual commercial licensing details.

