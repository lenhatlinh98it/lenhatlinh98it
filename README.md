<div align="center">

# Lê Nhật Linh

**Full-stack developer** — web APIs & CMS by day, desktop tools for video workflows on the side.

📍 Vietnam · 🤝 Open to collaboration · ✉️ [lenhatlinh98it@gmail.com](mailto:lenhatlinh98it@gmail.com)

</div>

---

## About me

- 🛠️ I build **REST APIs** and backends with **Laravel**, **NestJS** and **WordPress**, and frontends with **React / Next.js**.
- 🎬 My public repos focus on **social video workflows**: batch downloading, editing, OCR + translation of on-screen text, and automated stats reports.
- 🖥️ When a browser isn't enough, I ship **Windows desktop apps** (pywebview, Electron) packaged so they run with a single `setup.bat`.

## Tech stack

**Backend**
<br>
<img alt="PHP" src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white">
<img alt="Laravel" src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white">
<img alt="WordPress" src="https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white">
<img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white">
<img alt="NestJS" src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white">
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img alt="REST API" src="https://img.shields.io/badge/REST_API-02569B?style=flat-square">

**Frontend**
<br>
<img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
<img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
<img alt="HTML5 Canvas" src="https://img.shields.io/badge/HTML5_Canvas-E34F26?style=flat-square&logo=html5&logoColor=white">
<img alt="CSS" src="https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white">

**Databases**
<br>
<img alt="MySQL" src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white">
<img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white">
<img alt="Redis" src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">

**Desktop, video & vision**
<br>
<img alt="Electron" src="https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white">
<img alt="pywebview" src="https://img.shields.io/badge/pywebview-3776AB?style=flat-square&logo=python&logoColor=white">
<img alt="FFmpeg" src="https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white">
<img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white">
<img alt="ONNX Runtime" src="https://img.shields.io/badge/ONNX_Runtime-005CED?style=flat-square&logo=onnx&logoColor=white">
<img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white">
<img alt="yt-dlp" src="https://img.shields.io/badge/yt--dlp-FF0000?style=flat-square&logo=youtube&logoColor=white">
<img alt="PyInstaller" src="https://img.shields.io/badge/PyInstaller-1F425F?style=flat-square&logo=python&logoColor=white">

**Automation, DevOps & testing**
<br>
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
<img alt="Cloudflare Workers" src="https://img.shields.io/badge/Cloudflare_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white">
<img alt="Slack API" src="https://img.shields.io/badge/Slack_API-4A154B?style=flat-square&logo=slack&logoColor=white">
<img alt="PowerShell" src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white">
<img alt="Jest" src="https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white">
<img alt="E2E testing" src="https://img.shields.io/badge/E2E_testing-2EAD33?style=flat-square">

## Featured projects

### 🎞️ [Grabber — Shorts & Reels downloader + editor](https://github.com/lenhatlinh98it/social-download-edit)
Windows desktop app to list and batch-download **YouTube Shorts, Facebook Reels and Douyin** from a channel or page, then edit them.
- Remembers what was already downloaded and hides it on the next fetch; parallel downloads with cancel.
- Built-in editor: crop / zoom / rotate, color grading with a live preview that matches the export, text & logo, background music, presets applied to a whole batch, clip merging with crossfades.
- FFmpeg with automatic GPU encoder selection (NVENC → Quick Sync → AMF → software); one-click `setup.bat`.

`Python` · `pywebview` · `Playwright` · `yt-dlp` · `FFmpeg` · `PyInstaller`

### 🈶 [Video Text Translator](https://github.com/lenhatlinh98it/video-translator)
Desktop app that finds **hard-coded Chinese text** in a video, works out when each caption is on screen, translates it, then erases the original and draws the translation in its place.
- OCR with RapidOCR (PaddleOCR models on ONNX Runtime), caption grouping and frame-accurate timing.
- Editable translations, frame / clip previews, OpenCV inpainting, optional CUDA / DirectML OCR and NVENC / Quick Sync / AMF encoding.

`Electron` · `Python` · `OpenCV` · `ONNX Runtime` · `FFmpeg`

### 📊 [Social Morning Report](https://github.com/lenhatlinh98it/social-report)
Yesterday's **YouTube and TikTok** stats posted to Slack every morning — Slack slash commands, a Cloudflare Worker and GitHub Actions, no always-on machine.

`Python` · `GitHub Actions` · `Cloudflare Workers` · `Slack API`

## GitHub stats

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=lenhatlinh98it&show_icons=true&theme=transparent&hide_border=true&count_private=true&include_all_commits=true" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=lenhatlinh98it&layout=compact&theme=transparent&hide_border=true&langs_count=6" alt="Top languages">
</div>

---

<div align="center">

💬 Have a project in mind? **[lenhatlinh98it@gmail.com](mailto:lenhatlinh98it@gmail.com)**

</div>
