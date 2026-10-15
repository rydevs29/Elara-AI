<p align="center">
  <img src="ElaraAI.png" alt="Elara AI Logo" width="120" style="border-radius: 50%; box-shadow: 0 10px 25px rgba(99, 102, 241, 0.4);" />
</p>

<p align="center">
  <strong>Platform Asisten Virtual, Pusat Evaluasi Cerdas & API Gateway Multi-Tier dengan Sinkronisasi Omni-Channel</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-4.0_Ultra-6366f1?style=for-the-badge" alt="Version 4.0 Ultra" />
  <img src="https://img.shields.io/badge/Architecture-Monster_Engine-8b5cf6?style=for-the-badge" alt="Monster Engine" />
  <img src="https://img.shields.io/badge/Author-RifqyDev-10b981?style=for-the-badge" alt="RifqyDev" />
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Android%20%7C%20Telegram-38bdf8?style=for-the-badge" alt="Platforms" />
  <img src="https://img.shields.io/badge/License-Proprietary-ef4444?style=for-the-badge" alt="License" />
</p>

---

## Pengenalan Ekosistem (Overview)

**Elara AI** adalah ekosistem kecerdasan buatan berlapis (*Multi-Layer Monster Engine*) yang dirancang dan dikembangkan sepenuhnya oleh **RifqyDev** dari Indonesia. Dibangun di atas infrastruktur *serverless* modern dan disinkronkan secara *real-time* dan Elara menggabungkan puluhan model bahasa besar (LLM), generator visual, sintetis suara, pusat riset akademik, hingga sistem evaluasi ujian berintegritas tinggi dalam satu antarmuka terpadu.

---

## Modul Utama Ekosistem Elara (Elara Ecosystem)

| Modul | Deskripsi & Kemampuan |
| :--- | :--- |
| **Elara Chat** | Asisten utama multi-model dengan *Long-Term Memory*, *Agent Mode*, *Elara Canvas*, *Anti-Slop Mode (To-The-Point)*, dan *File Vault* sesi otomatis. |
| **Elara Quiz & CBT** |  Pusat evaluasi adaptif dan ujian bersama (*Multiplayer Room* via PIN/Link), dilengkapi *Strict Proctoring Mode*, *App-Only Gate*, *Socratic Tutor*, dan *Radar Analitik*. |
| **Elara Quiz Admin** | Panel pengawas ujian *real-time* untuk memantau peserta aktif, audit pelanggaran pindah tab, diskualifikasi langsung, dan manajemen bank soal kurikulum. |
| **Elara Studio** | Studio kreatif penghasil gambar dan video resolusi tinggi berbasis AI. |
| **Elara MathLab** | Laboratorium komputasi matematika, aljabar, dan kalkulus dengan dukungan *rendering* rumus KaTeX/LaTeX instan. |
| **Elara VoiceLab** | Sintesis suara natural (*Text-to-Speech*) dan interaksi percakapan audio dua arah. |
| **Elara Scholar** | Asisten riset akademik, bedah jurnal ilmiah, dan penyusunan literatur terstruktur. |
| **Elara Blueprint** | Perancang arsitektur sistem, pembuatan diagram alur (*Mermaid.js* ke PNG/PDF), dan prototipe proyek. |
| **Elara Odyssey & Stealth** | Eksplorasi skenario mendalam dan mode privasi berlapis dengan enkripsi sisi klien. |
| **Community Hub** | Ruang kolaborasi pengguna, berbagi *prompt*, dan diskusi publik. |
| **Developer & MCP Portal** | Dokumentasi API eksternal dan integrasi *Remote Model Context Protocol (MCP)* untuk **Gemini Spark**. |

---

## Arsitektur Mesin AI (Multi-Layer Monster Engine)

Elara menggunakan sistem *Smart Classification & Direct Routing* yang secara otomatis memilih atau mengizinkan pemilihan langsung dari berbagai keluarga model kelas dunia:

### 1. Elara Ensemble (5-AI Multi-Model Fusion)
Menjalankan kueri secara paralel ke **Qwen 3.8 Max**, **GLM 5.3**, **DeepSeek V4 Pro 0813**, **Gemini 3.8 Flash**, dan **Nemo Ultra 550B**, lalu menyintesis poin-poin terbaik menjadi satu jawaban komprehensif yang terverifikasi.

### 2. Alibaba (17 Model Generasi Terbaru)
* **Ultra & Flagship:** `qwen3.8-2.4t-a95b`, `qwen3.8-max`, `qwen3.8-max-0902`, `qwen3.8-27b`
* **Reasoning & Coding:** `kimi-k3`, `deepseek-v4-pro-0813`, `glm-5.3`
* **High-Speed Flash:** `qwen3.8-flash`, `qwen3.7-flash`, `qwen3.7-flash-2026-07-15`, `deepseek-v4.1-flash`, `deepseek-v4-flash-0731`
* **Multimodal & Vision/Video:** `qwen3.8-omni-flash`, `qwen3.8-omni-flash-realtime`, `qwen-image-2.1-turbo`, `wan3.0-video`, `wan3.0-video-prime`

### 3. Google Gemini
* `gemini-3.8-flash`, `gemini-3.5-flash`, `gemini-3.5-flash-lite`, `gemini-3.1-flash-lite`, `gemini-2.5-flash-lite`
* **Audio & Specialized:** `gemini-3.1-flash-tts`, `gemini-2.5-flash-audio`, `gemini-robotics-er-1.6-preview`, `gemma` (Gemma 4)

### 4. OpenRouter Free (14 Model Terkurasi)
* `nvidia/nemotron-3-ultra-550b-a55b:free` (`nemotron_super`)
* `nvidia/nemotron-3-nano-omni-30b-a3b-reasoning:free` (`nemotron_reasoning`)
* `nvidia/nemotron-3.5-lightning:free` (`nemotron_lightning`)
* `apodex/apodex-1.1-mini:free` (`apodex_mini`)
* `inception/mercury-decide:free` (`mercury_decide`)
* `respan/span-01-lite:free` (`span_lite`)
* `dots-studio/dots-3-note-preview:free` (`dots_note`)
* `liquid/lfm-2.5-2.6b:free` (`liquid`)
* `thinkingmachines/inkling:free` (`inkling`) & `inkling-small:free` (`inkling_small`)
* `fish-audio/s2.1-pro-free:free` (`fish_audio`)
* `poolside/laguna-s-2.1:free` (`laguna_s`) & `laguna-xs-2.1:free` (`laguna_xs`)
* `cohere/north-mini-code:free` (`cohere_code`)

### 5. Mesin Khusus & Generator Visual
* **Image Generation:** `flux`, `zimage` (Turbo), `klein` (Flux Realism), `gptimage` (DALL-E 3 Mini), `gptimage-large`, `wan-image`, `qwen-image`, `qwen-image-2.0-pro`.
* **Specialists:** `elara-knowledge` (Hybrid Local JSON RAG + Gemini Fallback), `elara-search` (Grounded Analytical Engine), `elara-translate` (DeepL-grade Syntax-Preserving Translator), dan `nofilter` (NoFilterGPT).

---

## Mega Omni-Search & Ekstraksi Dokumen

1. **Multi-Provider Web Search:** Menggabungkan **Search** (mode *basic* untuk Fast Search & *advanced* hingga 30 sumber untuk Deep Search), **SerpApi** (Google Search, Flights, Maps, Jobs, Shopping, Finance), dan **DuckDuckGo Fallback**.
2. **File Vault & Direct Exporter:** Setiap kodingan, tabel, diagram Mermaid (`.png` / `.pdf`), dokumen `.docx`, `.xlsx`, `.pdf`, dan proyek `.zip` yang dihasilkan selama percakapan otomatis diarsipkan ke dalam **File Vault** sesi untuk diunduh atau ditinjau kembali lewat *Live Preview*.

---

## Fitur Unggulan Elara Quiz & Sistem Anti-Curang

Dirancang untuk kebutuhan latihan mandiri maupun ujian serempak di kelas/institusi:
* **Kurikulum Terstruktur & Scan-to-Quiz:** Buat soal otomatis dari kategori mata pelajaran, topik bebas, maupun tempelan teks modul/catatan.
* **Dua Skema Pembatas Waktu:**
  * *Mode A (Countdown per Soal)* dengan bonus poin kecepatan.
  * *Mode B (Timer Paket Global)* tersinkronisasi dengan waktu server Firestore (kebal manipulasi jam perangkat).
* **Multiplayer Room (`?room=PIN`):** Bergabung instan lewat 6 digit PIN atau tautan undangan, lengkap dengan *Waiting Room*, *Pacing Control* (otomatis atau dikendalikan Host), dan *Podium Juara*.
* **Strict Proctoring & App-Only Gate:**
  * Opsi penguncian agar ujian hanya bisa dibuka dari **Aplikasi Elara Android**.
  * Blokir klik kanan, salin-tempel (`Ctrl+C`/`Ctrl+V`), pintasan *Inspect Element*, serta deteksi perpindahan tab/aplikasi dengan *auto-disqualify* jika melampaui batas toleransi.
  * *Dynamic Watermark* identitas peserta di atas lembar soal.
* **Socratic Tutor & Spaced Repetition:** Ulasan pedagogis otomatis saat menjawab salah dan penyimpanan soal keliru ke dalam daftar latihan ulang.

---

## Sistem Kasta Pengguna (User Tiers) & Kuota Real-Time

Elara menggunakan kalkulator beban server *real-time* yang otomatis memulihkan kuota pengguna sebesar **1% setiap menit** saat AI beristirahat:

| Kasta (Tier) | Akses Model | Batas Unggah Lampiran | Fitur Eksklusif |
| :--- | :--- | :--- | :--- |
| **Neon (Gratis)** | Seluruh Model Gratis, OpenRouter Free & Auto | Maks. 2 Foto / 3 Berkas | 5x Fast Web Search/Bulan, Memory AI, Export Dasar. |
| **Plasma (Pro)** | Model Neon + Kasta Plasma (Qwen 3.8 27B, Omni Flash, Gemini 3.5 Flash, Elara Search) | Maks. 15 Foto/Dokumen/Video | Deep Search Tanpa Batas, Agent Mode, Canvas. |
| **Supernova (Sultan)** | Seluruh Model Dewa (Qwen 3.8 2.4T, Max, Kimi K3, DeepSeek V4 Pro, Wan 3.0 Video Prime) | Maks. 50 Foto/Dokumen/Video | Prioritas API Tertinggi, Render Video AI, Kuota Maksimal. |

---

**Website Kami:** [Klik Disini](https://elara.rifqydev.my.id)
