# Awesome-Deep-Learning-Video-Camera 🎥 🧠

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Deep Learning Video Camera Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Deep-Learning-Video-Camera"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Deep-Learning-Video-Camera?style=social" alt="GitHub Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Deep-Learning-Video-Camera/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Deep-Learning-Video-Camera?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Deep-Learning-Video-Camera/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Deep-Learning-Video-Camera?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Deep Learning Video Camera Ecosystem

**Curated Directory of Commercial AI Camera Platforms & Open-Source Edge Vision Frameworks**  
*Focused on Edge AI Inference, Video Analytics, Smart Surveillance, Hardware Accelerators, Privacy-Preserving Vision & Self-Hosted Camera Management*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary

Welcome to the ultimate curated directory of **deep learning video cameras**, **open-source edge vision frameworks**, and **AI-powered surveillance platforms**. Whether you are evaluating enterprise commercial hardware-SaaS solutions (*Verkada*, *Rhombus*, *Cisco Meraki MV*, *Spot AI*) or building self-hosted computer vision systems (*Frigate*, *OpenCV*, *DeepStream*, *Ultralytics YOLO*, *Carcara Vision*), this guide covers category leaders, hardware accelerators, and privacy-focused intelligent video platforms.

**Key Market Insights & Hardware Context:**
- ⚡ **Market Size & Structure:** The global AI Video Analytics & Smart Camera market is estimated at **$18.5 Billion** and projected to reach **$42 Billion by 2030**. The sector is **moderately fragmented**, with cloud-managed security giants leading enterprise deployment while open-source projects dominate custom edge AI and home NVR solutions.
- ⚠️ **AWS DeepLens EOL:** AWS DeepLens was officially retired on January 31, 2024. All device management and cloud APIs have been deleted.
- 🟡 **Google Coral Status:** Google Coral Edge TPU provides **4 TOPS of INT8 inference at ~2W**, but Google has released no new hardware since 2022. Modern deployments increasingly adopt **Hailo-8/Hailo-8L NPUs** or **NVIDIA Jetson Orin** modules.
- 🟩 **NVIDIA Jetson Ecosystem:** NVIDIA Jetson Platform Services provides containerized vision-language model (VLM) inference, zero-shot object detection, and DeepStream SDK pipelines on Jetson Orin modules (up to 275 TOPS).

---

## 📑 Table of Contents

- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS & Commercial Platforms

> [!NOTE]
> **Market Structure & Size:** The AI Video Camera and Smart Analytics sector is estimated at **$18.5 Billion** (growing to **$42 Billion by 2030**). The market is **moderately fragmented**: enterprise commercial SaaS platforms (Verkada, Cisco Meraki, Rhombus) lead turn-key physical security, while developer platforms (NVIDIA, Microsoft Azure, Google Cloud, Luxonis) power custom edge vision deployments.

The table below lists leading SaaS and commercial deep learning video platforms, **sorted by Company Market Cap / Valuation (Descending)**:

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Azure AI Vision](https://azure.microsoft.com/en-us/products/ai-services/ai-vision/)** 🔷 | Microsoft | **~$3.90 Trillion** | **$1.00 per 1,000 transactions** (Spatial Analysis) / **$0.50 per 1,000 images** | **5,000 transactions/month free forever** + $200 free credit (30 days) | **Cloud & Edge Spatial Analysis** — Real-time people counting, social distancing, optical flow, and spatial presence analytics for enterprise cameras. |
| **[NVIDIA Jetson & Metropolis](https://developer.nvidia.com/embedded/jetson)** 🟩 | NVIDIA | **~$3.00 Trillion** | **$149** (Jetson Orin Nano Developer Kit hardware purchase) | **DeepStream SDK & Jetson Platform Services 100% free** for unlimited local edge nodes | **Edge AI Computing Platform** — Delivers up to 275 TOPS of AI performance for multi-stream vision analytics, VLM inference, zero-shot detection, and containerized microservices. |
| **[Google Cloud Video Intelligence](https://cloud.google.com/video-intelligence-api)** 🟡 | Alphabet | **~$2.00 Trillion** | **$0.10 per minute** of video analyzed | **First 1,000 minutes/month free forever** in Google Cloud Free Tier | **AI Video Processing API** — Streaming object tracking, explicit content detection, shot change analysis, and automated text detection across video feeds. |
| **[AWS Panorama & Video Analytics](https://aws.amazon.com/panorama/)** 🟧 | Amazon | **~$2.00 Trillion** | **$8.33/month per stream** + **$0.10/hour device license** | **60-day free trial** supporting up to 5 concurrent camera streams | **Computer Vision at the Edge** — Edge appliance and SDK that brings computer vision applications to existing on-premises IP cameras with automated cloud orchestration. |
| **[Cisco Meraki MV Smart Cameras](https://meraki.cisco.com/)** 🔵 | Cisco | **~$200 Billion** | **$500–$1,500/camera hardware** + **$150/year cloud license** | **14-day free trial kit** with full hardware evaluation & free shipping | **Cloud-Managed Smart Cameras** — Enterprise smart cameras with onboard machine learning for person detection, heatmaps, vehicle tracking, and seamless Meraki ecosystem integration. |
| **[Intel RealSense Vision](https://www.intelrealsense.com/)** 🔵 | Intel | **~$100 Billion** | **$249** (Intel RealSense D455 depth camera hardware purchase) | **Intel RealSense SDK 2.0 100% free forever** for unlimited local depth streams | **Spatial Depth & Vision Hardware** — High-precision stereo depth cameras and tracking modules paired with open-source SDKs for robotics, drone navigation, and 3D spatial vision. |
| **[Verkada AI Security Cameras](https://www.verkada.com/)** 🎥 | Verkada | **~$3.50 Billion** | **$999/camera hardware** + **$199/year enterprise cloud subscription** | **30-day free trial** with 2 free trial cameras shipped to qualified organizations | **Enterprise Cloud Physical Security** — Hybrid cloud cameras featuring edge AI processing for face recognition, vehicle/license plate detection, and centralized multi-site management. |
| **[Rhombus Systems](https://www.rhombus.com/)** 🔷 | Rhombus | **~$300 Million** | **$499/camera hardware** + **$120/year cloud license** | **14-day free trial kit** with live demo hardware & cloud access | **Cloud-Managed Smart Surveillance** — Enterprise AI camera platform offering real-time motion alerts, facial matching, color/clothing filtering, open REST APIs, and edge caching. |
| **[Spot AI Video Intelligence](https://www.spot.ai/)** 🟢 | Spot AI | **~$150 Million** | **$1,500/appliance** + **$200/year per connected camera stream** | **30-day risk-free pilot** with pre-configured hardware included | **AI Video Intelligence Platform** — Plugs into existing RTSP camera setups to enable natural language video search, safety incident analytics, and vehicle/person indexing. |
| **[Luxonis OAK-D / DepthAI](https://www.luxonis.com/)** 🌳 | Luxonis | **~$50 Million** | **$149** (OAK-D Lite spatial AI camera hardware purchase) | **5 GB free DepthAI Cloud storage** + 100% free local SDK compilation | **Spatial AI & On-Device Neural Cameras** — Stereo depth perception combined with on-board VPU hardware for real-time neural inference, object tracking, and robotics vision. |

---

## 🔓 Open-Source GitHub Projects

> [!TIP]
> Open-source edge vision projects enable fully local, privacy-respecting AI video surveillance without monthly cloud fees. Below projects are **sorted by GitHub Star Count (Descending)**:

- **[OpenCV](https://github.com/opencv/opencv)** [![Stars](https://img.shields.io/github/stars/opencv/opencv?style=social&color=white)](https://github.com/opencv/opencv/stargazers)  
  **The world's leading open-source computer vision & machine learning software library**, Apache-2.0 licensed. **Fundamental foundation for real-time camera image processing**, feature extraction, video decoding, DNN module acceleration, and edge vision pipelines. 👁️

- **[Ultralytics YOLO](https://github.com/ultralytics/ultralytics)** [![Stars](https://img.shields.io/github/stars/ultralytics/ultralytics?style=social&color=white)](https://github.com/ultralytics/ultralytics/stargazers)  
  **State-of-the-art real-time object detection, segmentation, and pose estimation framework**, AGPL-3.0 licensed. **Powers YOLOv8, YOLOv9, and YOLO11 models** optimized for real-time camera inference across CUDA, TensorRT, CoreML, NPU, and ONNX Runtimes. ⚡

- **[Frigate NVR](https://github.com/blakeblackshear/frigate)** [![Stars](https://img.shields.io/github/stars/blakeblackshear/frigate?style=social&color=white)](https://github.com/blakeblackshear/frigate/stargazers)  
  **NVR with real-time AI object detection for IP cameras**, MIT licensed. **The premier open-source AI video surveillance platform** — **local object detection using TensorFlow, Coral Edge TPU, Hailo-8, OpenVINO, and NVIDIA GPUs** . **Seamless Home Assistant integration**, WebRTC low-latency viewing, and event-based recording. 🎥

- **[ZoneMinder](https://github.com/ZoneMinder/zoneminder)** [![Stars](https://img.shields.io/github/stars/ZoneMinder/zoneminder?style=social&color=white)](https://github.com/ZoneMinder/zoneminder/stargazers)  
  **Full-featured, open-source video surveillance camera management system**, GPL-2.0 licensed. **Supports IP, USB, and analog cameras** with deep learning plugin support for event detection, zone monitoring, and high-density camera installations. 🛡️

- **[MotionEye](https://github.com/motioneye-project/motioneye)** [![Stars](https://img.shields.io/github/stars/motioneye-project/motioneye?style=social&color=white)](https://github.com/motioneye-project/motioneye/stargazers)  
  **Web frontend for motion video surveillance daemon**, GPL-3.0 licensed. **User-friendly web interface for managing IP cameras**, motion detection schedules, video recording storage, and notification webhooks. 🌐

- **[Kerberos Agent](https://github.com/kerberos-io/agent)** [![Stars](https://img.shields.io/github/stars/kerberos-io/agent?style=social&color=white)](https://github.com/kerberos-io/agent/stargazers)  
  **Lightweight open-source video surveillance and computer vision agent**, Apache-2.0 licensed. **Written in C++ for maximum performance** on low-power devices, Raspberry Pi, and edge hardware with cloud integration options. 🤖

- **[DeepStream Python Apps](https://github.com/NVIDIA-AI-IOT/deepstream_python_apps)** [![Stars](https://img.shields.io/github/stars/NVIDIA-AI-IOT/deepstream_python_apps?style=social&color=white)](https://github.com/NVIDIA-AI-IOT/deepstream_python_apps/stargazers)  
  **Python bindings and sample pipelines for NVIDIA DeepStream SDK**, MIT licensed. **GStreamer-based multi-camera video analytics framework** supporting hardware-accelerated decode, multi-model inference, PeopleNet, TrafficCamNet, and tracking on Jetson & NVIDIA GPUs. 🚀

- **[Carcara Vision](https://github.com/marcoscunha/carcara-vision)** [![Stars](https://img.shields.io/github/stars/marcoscunha/carcara-vision?style=social&color=white)](https://github.com/marcoscunha/carcara-vision/stargazers)  
  **Hardware-accelerated ML inference platform for video surveillance**, MIT licensed. **Multi-model AI architecture supporting YOLOv5/v8/v11 and Vision-Language Models (VLMs)** . Accelerates across CUDA, TensorRT, Coral TPU, Hailo-8, and Jetson with MediaMTX RTSP/WebRTC streams. 🦅

- **[AI Security Camera (Pi 5 + Hailo-8)](https://github.com/mi0iou/ai-security-camera)** [![Stars](https://img.shields.io/github/stars/mi0iou/ai-security-camera?style=social&color=white)](https://github.com/mi0iou/ai-security-camera/stargazers)  
  **High-speed AI security camera running on Raspberry Pi 5 + Hailo-8 NPU**, open-source. **Runs YOLOv8 object detection, plate localization, and EasyOCR ANPR at 40+ FPS with <100ms latency** under ~8W total power draw. Includes web dashboard and ntfy mobile alerts. 🚗

- **[RK3576 AI Demos](https://github.com/Hanzo-Huang/rk3576-ai-demos)** [![Stars](https://img.shields.io/github/stars/Hanzo-Huang/rk3576-ai-demos?style=social&color=white)](https://github.com/Hanzo-Huang/rk3576-ai-demos/stargazers)  
  **Zone-based alerting with YOLO11 on RK3576 NPU**, open-source. **Interactive web polygon restriction zones** trigger local alerts when objects cross boundaries using RKNN hardware NPU acceleration. 🎯

- **[AI Surveillance System](https://github.com/DumitruEstera/ai-surveillance-system)** [![Stars](https://img.shields.io/github/stars/DumitruEstera/ai-surveillance-system?style=social&color=white)](https://github.com/DumitruEstera/ai-surveillance-system/stargazers)  
  **Multi-detector AI surveillance platform**, open-source. **Runs 5 concurrent AI models on shared GPU**: InsightFace demographics, YOLOv8 ANPR, YOLOv10 fire/smoke detection, SlowFast action recognition, and weapon detection with temporal event validation. 🔬

---

## 🛠️ How to Contribute

Contributions are warmly welcome! Help keep this deep learning video camera registry up-to-date by submitting new commercial platforms, edge vision hardware, or open-source NVR tools:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` adhering to the table layout, star badges, and sorting criteria.
3. 🔗 Include official project website/GitHub link, exact starting pricing, free tier details, and clear technical descriptions.
4. 🚀 Open a **Pull Request** with a concise title and summary of changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Deep-Learning-Video-Camera&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Deep-Learning-Video-Camera&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If this deep learning video camera resource has been helpful to your research, engineering project, or smart home security setup, please consider supporting the curation work:

- ⭐ **Star** this repository on GitHub to boost visibility!
- 🔀 **Fork** and share this guide with computer vision engineers, security architects, and IoT builders.
- ☕ **Sponsor & Buy Me a Coffee**: Support open-source curation directly via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This directory is **community-curated** for educational and research purposes.
- **AWS DeepLens reached End of Life on January 31, 2024** — all services and support have been terminated.
- **Google Coral hardware has had no new releases since 2022** — consider modern active NPU architectures like **Hailo-8 / Hailo-8L** or **NVIDIA Jetson Orin** for new hardware designs.
- **Open-source video analytics systems (Frigate, DeepStream, Carcara Vision)** require proper hardware accelerator pairing and RTSP network tuning. Always perform real-world testing prior to production rollout. 🎥

---

<p align="center">
  <b>Made with ❤️ for computer vision engineers, edge AI developers, and open-source surveillance builders.</b>
</p>
