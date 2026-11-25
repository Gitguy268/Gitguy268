<h1 align="center">Hi, I'm Lucas 👋</h1>
 
<p align="center">
  Developer from the Netherlands 🇳🇱 · local-first apps, terminal tools and small AI models that run on your own machine
</p>
<p align="center">
  <a href="https://gitguy268.github.io"><img src="https://img.shields.io/badge/Portfolio-gitguy268.github.io-222222?logo=githubpages&logoColor=white" alt="Portfolio"></a>
  <a href="https://huggingface.co/Lucasgitguy-co"><img src="https://img.shields.io/badge/Hugging%20Face-Lucasgitguy--co-FFD21E?logo=huggingface&logoColor=black" alt="Hugging Face"></a>
  <a href="https://www.linkedin.com/in/lucasvandeweerd"><img src="https://img.shields.io/badge/LinkedIn-lucasvandeweerd-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://twitter.com/lucasvandeweerd"><img src="https://img.shields.io/badge/X-@lucasvandeweerd-000000?logo=x&logoColor=white" alt="X / Twitter"></a>
</p>
---
 
## About me
 
- 🔒 I like software that keeps your files, photos, voice and searches on your own computer
- ⌨️ I write terminal tools in Go and Rust, and web apps in TypeScript
- 🤖 I fine-tune and quantize small vision-language models to run locally (MLX, GGUF, llama.cpp)
- 🪟 Soft spot for retro interfaces: Windows 98, 8-bit, turntables, liquid glass
- 🐕 Many projects star **Spot**, a black labrador
My [portfolio](https://gitguy268.github.io) has a website, terminal and Windows 98 view, with a docs page for each project.
 
## 🤖 Local AI
 
| Project | What it does |
|---|---|
| [LvW-harness](https://github.com/Gitguy268/LvW-harness) | Local-first AI agent with a one-command model manager for Hugging Face, GitHub and GitLab. Terminal + web UI, built on Bun |
| [usb-llms](https://github.com/Gitguy268/usb-llms) | Run AI models from a USB stick on macOS, Windows and Linux, online or offline. Ollama, TUI, web UI and Open WebUI |
| [quicktalk](https://github.com/Gitguy268/quicktalk) | Local desktop dictation and meeting notes. Rust, Tauri 2 and Svelte 5 |
| [liquidframe](https://github.com/Gitguy268/liquidframe) | Photos-style media library where photos, edits and AI stay on your computer |
| [stem-player](https://github.com/Gitguy268/stem-player) | 3D browser replica of a four-stem music player; splits songs on your own machine with Demucs |
 
### On Hugging Face
 
- 🧩 **Image → Mermaid:** small vision-language models that read a diagram and write Mermaid code, such as [minicpm-mermaid-gguf](https://huggingface.co/Lucasgitguy-co/minicpm-mermaid-gguf) (MiniCPM-V 4.7 1B) and [Qwen3.5-2B-Mermaid-MLX-LoRA](https://huggingface.co/Lucasgitguy-co/Qwen3.5-2B-Mermaid-MLX-LoRA). Trained on my datasets [mermaid-diagram-text-images](https://huggingface.co/datasets/Lucasgitguy-co/mermaid-diagram-text-images) (~6.2k) and [mermaid-text-en-nl](https://huggingface.co/datasets/Lucasgitguy-co/mermaid-text-en-nl) (~5.7k, English and Dutch)
- 🧊 **Image → 3D:** [forma3d-tiny](https://huggingface.co/Lucasgitguy-co/forma3d-tiny), a ~306k-parameter research model that turns an object cutout into a Gaussian `.ply`, runs on a Mac
- 👁️ **Local VLMs:** [lfm3-vl-2b-heretic](https://huggingface.co/Lucasgitguy-co/lfm3-vl-2b-heretic) with [GGUF](https://huggingface.co/Lucasgitguy-co/lfm3-vl-2b-heretic-gguf) and [MLX 4-bit](https://huggingface.co/Lucasgitguy-co/lfm3-vl-2b-heretic-mlx-4bit) builds
👉 [All models and datasets](https://huggingface.co/Lucasgitguy-co)
 
## ⌨️ Terminal tools
 
| Project | What it does |
|---|---|
| [glyphium](https://github.com/Gitguy268/glyphium) | GPU-rendered terminal emulator in Rust, built on libghostty-vt (early development) |
| [textarea-cli](https://github.com/Gitguy268/textarea-cli) | `text buy milk` jots a note; Markdown files that sync with Obsidian and Apple Notes |
| [needle](https://github.com/Gitguy268/needle) | Terminal music player: full-screen TUI, background daemon, JSON-lines interface for scripts |
| [skyhold](https://github.com/Gitguy268/skyhold) | Back files up to any cloud via rclone into an age-encrypted vault, then free the local space |
| [tabshell](https://github.com/Gitguy268/tabshell) | A real Linux terminal in a browser tab (v86 or Docker), with a Reset button |
| [container](https://github.com/Gitguy268/container) | Fork of apple/container with `here` (a VM right in your terminal) and a `dash` TUI |
| [opencode](https://github.com/Gitguy268/opencode) · [superfile](https://github.com/Gitguy268/superfile) | Forks of the opencode coding agent and the superfile file manager with extra features and fixes |
 
## 🔒 Private browsing & search
 
| Project | What it does |
|---|---|
| [xiao](https://github.com/Gitguy268/xiao) | Calm, private browser built on Zen: blocking, randomized fingerprint, Tor tabs |
| [archium](https://github.com/Gitguy268/archium) | Arc/Zen-style Electron browser with sidebar tabs, spaces, a CLI and an MCP server |
| [hillium](https://github.com/Gitguy268/hillium) | Privacy layer for Helium: offline new tab, local SearXNG, Tor with a kill switch, URL cleaner |
| [retrofind](https://github.com/Gitguy268/retrofind) | Private web search on your Mac, styled like 1998, over a local SearXNG |
 
## 🎨 Apps that run in your browser
 
No server, no upload, no account.
 
| Project | What it does |
|---|---|
| [better-photocraft-web](https://github.com/Gitguy268/better-photocraft-web) | Image editor in pure Rust for the web: layers, masks, type, vectors, PSD files |
| [pikado](https://github.com/Gitguy268/pikado) · [GlassPaint](https://github.com/Gitguy268/GlassPaint) | Liquid-glass image editors, forks of pikado and miniPaint |
| [paint97](https://github.com/Gitguy268/paint97) | A Windows 9x desktop around an Excalidraw whiteboard, with JS Paint and on-device AI |
| [openfinder](https://github.com/Gitguy268/openfinder) | Finder-style file manager using the File System Access API |
| [audiocheck](https://github.com/Gitguy268/audiocheck) | Checks if a music file is as good as it claims: spectrogram, measurements, plain verdict |
| [convert](https://github.com/Gitguy268/convert) · [htmltopng](https://github.com/Gitguy268/htmltopng) · [qrer](https://github.com/Gitguy268/qrer) | File conversion, HTML → PNG, and a Windows 98-style QR tool |
| [edu-code-camp](https://github.com/Gitguy268/edu-code-camp) | 37 hands-on coding lessons with hidden tests, a real Linux terminal and Spot as tutor |
 
Also on the desktop: [videoina](https://github.com/Gitguy268/videoina), an IINA-style video player for Windows and Linux (Qt 6 + libmpv), and [web2app](https://github.com/Gitguy268/web2app), a GUI for Pake that turns websites into desktop apps.
 
## 🎵 Turntables & music players
 
- [ultra-realistic-vinyl-player](https://github.com/Gitguy268/ultra-realistic-vinyl-player): a 3D Thorens TD 115 MK II with a physically modelled motor, tonearm and playback chain
- [realistic-vinyl-player](https://github.com/Gitguy268/realistic-vinyl-player) · [8-bit-vinyl-player](https://github.com/Gitguy268/8-bit-vinyl-player) · [vinyl-player-for-spotify](https://github.com/Gitguy268/vinyl-player-for-spotify): turntables in a single HTML file for your own music or Spotify
- [ipod](https://github.com/Gitguy268/ipod): the iPod Classic in your browser, playing music from your own computer
## 🐕 Games
 
- [spot-fetch](https://github.com/Gitguy268/spot-fetch): throw a ball for Spot in a 3D park with weather, day and night, and a photo mode
- [spot-snake](https://github.com/Gitguy268/spot-snake): snake in one HTML file, with an optional AI player running on your GPU via WebGPU
- [spot-light](https://github.com/Gitguy268/spot-light): Spot chases a laser dot in 2D, 3D or 8-bit
- [retro-zip](https://github.com/Gitguy268/retro-zip): browser emulation with EmulatorJS and Doom, plus six original terminal games
- [rubber-hose-revue](https://github.com/Gitguy268/rubber-hose-revue) · [cozy-christmas-lab](https://github.com/Gitguy268/cozy-christmas-lab) · [axolotl-aqua-adventure](https://github.com/Gitguy268/axolotl-aqua-adventure)
## 🛍️ Black Lab Spots
 
Storefronts for a dog-inspired apparel brand: [blacklabspots-storefront](https://github.com/Gitguy268/blacklabspots-storefront) (Next.js, Printify and Stripe), [BlackLabSpotsShop](https://github.com/Gitguy268/BlackLabSpotsShop) (React + Supabase) and a minimal [Yeezy-inspired concept](https://github.com/Gitguy268/blacklab-store-yeezy).
 
[e2e-suite](https://github.com/Gitguy268/e2e-suite) runs Playwright smoke tests across 26 of my web apps with one command.
 
## 🛠️ Tech I use
 
**Languages:** Go · Rust · TypeScript · JavaScript · Python · Swift · C++
**Desktop & terminal:** Tauri · Electron · Qt 6 · Bubble Tea · libmpv · Bun
**Web:** React · Next.js · Svelte · Vite · Tailwind CSS · shadcn/ui · Supabase · Three.js · WebGPU · WebAssembly
**AI:** MLX · llama.cpp · GGUF · Ollama · ONNX · Whisper · Demucs · LoRA fine-tuning
 
## 📫 Get in touch
 
Reach me on [LinkedIn](https://www.linkedin.com/in/lucasvandeweerd) or [X](https://twitter.com/lucasvandeweerd), or open an issue on any repo.
