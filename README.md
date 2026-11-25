# Hi, I'm Lucas 👋

I'm a developer from the Netherlands 🇳🇱 interested in everything AI-related. Most of my time goes into **fine-tuning small vision-language models** and running them locally. I also build web apps with React and TypeScript.

[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Lucasgitguy--co-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/Lucasgitguy-co)
[![X](https://img.shields.io/badge/X-@lucasvandeweerd-000000?logo=x&logoColor=white)](https://x.com/lucasvandeweerd)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-lucasvandeweerd-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucasvandeweerd)

---

## 🧜 Current focus: diagram → Mermaid

I'm training compact models that take a picture of a diagram and turn it back into editable [Mermaid](https://mermaid.js.org/) code, small enough to run on a laptop.

**Models** ([all models](https://huggingface.co/Lucasgitguy-co))

| Model | What it is |
|---|---|
| [minicpm-mermaid-gguf](https://huggingface.co/Lucasgitguy-co/minicpm-mermaid-gguf) | MiniCPM-V 4.7 1B tuned for diagram → Mermaid, GGUF (Q4_K_M + vision projector) for llama.cpp |
| [minicpm-mermaid-heretic](https://huggingface.co/Lucasgitguy-co/minicpm-mermaid-heretic) | BF16 Safetensors checkpoint for Transformers / vLLM, with a [GGUF version](https://huggingface.co/Lucasgitguy-co/minicpm-mermaid-heretic-gguf) |
| [minicpm-v-4-7-1b-mermaid-adapter](https://huggingface.co/Lucasgitguy-co/minicpm-v-4-7-1b-mermaid-adapter) | The Mermaid adapter on its own |
| [Qwen3.5-2B-Mermaid-MLX-LoRA](https://huggingface.co/Lucasgitguy-co/Qwen3.5-2B-Mermaid-MLX-LoRA) | Qwen3.5 2B LoRA trained with MLX on Apple Silicon |
| [lfm3-vl-2b-heretic-mlx-4bit](https://huggingface.co/Lucasgitguy-co/lfm3-vl-2b-heretic-mlx-4bit) | 4-bit MLX build of LFM3-VL 2B |

**Datasets**

| Dataset | What's in it |
|---|---|
| [mermaid-diagram-text-images](https://huggingface.co/datasets/Lucasgitguy-co/mermaid-diagram-text-images) | ~5.7k prompt → Mermaid code pairs plus 537 rendered diagram images (classic + hand-drawn styles), deduplicated, Parquet |
| [mermaid-text-en-nl](https://huggingface.co/datasets/Lucasgitguy-co/mermaid-text-en-nl) | English and Dutch Mermaid text data |

### Quick start

```bash
hf download Lucasgitguy-co/minicpm-mermaid-gguf

llama-mtmd-cli \
  -m model-Q4_K_M.gguf \
  --mmproj mmproj-model-f16.gguf \
  --image diagram.png \
  -p "Convert this diagram into Mermaid code."
```

> You need a llama.cpp build with MiniCPM-V 4.7 support. Check the generated Mermaid before you rely on it.

---

## 🛠️ Projects

- **[BlackLabSpotsShop](https://github.com/Gitguy268/BlackLabSpotsShop)**: online store for Black Lab Spots, built with React, Vite, TypeScript, shadcn/ui and Supabase.

---

## 🧰 Tools I use

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-FFD21E?logo=huggingface&logoColor=black)
![MLX](https://img.shields.io/badge/MLX-000000?logo=apple&logoColor=white)
![llama.cpp](https://img.shields.io/badge/llama.cpp-GGUF-555555)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white)

---

💬 Ask me about small VLMs, fine-tuning on a Mac, or turning diagrams into code.
