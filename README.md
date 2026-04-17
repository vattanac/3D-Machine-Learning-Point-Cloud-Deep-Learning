# 3D Machine Learning & Point Cloud Deep Learning

> A comprehensive technical reference for beginners — covering 3D representations, point cloud processing, segmentation, object detection, classification, Neural Radiance Fields, 3D Gaussian Splatting, and state-of-the-art architectures through 2025.

**Version:** 2026.04 · **Format:** Interactive HTML site · **Source:** PDF Technical Reference (35 pages)

---

## Overview

This repository contains an interactive web-based version of the 3D Machine Learning & Point Cloud Deep Learning technical reference. It transforms the original PDF into a modern, navigable documentation site with a left sidebar, scroll-spy navigation, embedded figures from the source PDF, and custom animated SVG illustrations.

## Contents

| File / Folder | Description |
|---|---|
| `3d-ml-reference.html` | Main interactive documentation site (single-file, self-contained) |
| `images/` | All figures extracted from the original PDF (32 images) |
| `README.md` | This file |

## Preview

Open `3d-ml-reference.html` in any modern browser to explore the interactive reference.

## Features

- **Modern 2026 UI** — dark glassmorphism theme with violet → cyan → pink gradient accents
- **Sticky left sidebar** with grouped navigation (Foundations · Architectures · Tasks · Frontier · Practice)
- **Scroll-spy** active-section highlighting as you read
- **Search bar** — live filter across all chapters
- **24 embedded figures** extracted from the original PDF
- **4 custom animated SVGs** — rotating point cloud, sweeping LiDAR beam, dynamic EdgeConv graph, floating particles
- **Hover effects** — shimmer sweep, lift, and glow on every figure
- **Lazy-loaded images** for fast initial render
- **Responsive** — collapses to mobile layout on narrow screens

## Chapter Index

1. **Introduction and Motivation** — Why 3D deep learning matters
2. **3D Data Representations** — Point clouds · voxels · meshes · multi-view · implicit
3. **Sensing Technologies** — LiDAR · RGB-D · SfM/photogrammetry · radar
4. **Foundational Architectures** — PointNet · PointNet++ · DGCNN · Point Transformer · **LitePT (2025)** · Sparse Convolutions
5. **3D Point Cloud Segmentation** — Semantic · instance · panoptic · part
6. **3D Object Detection & Classification** — VoteNet · PointRCNN · VoxelNet · CenterPoint · PV-RCNN · BEVFusion
7. **Point Cloud Enhancement** — Denoising · completion · upsampling · registration
8. **Neural Radiance Fields & 3D Gaussian Splatting** — NeRF · Instant-NGP · Mip-NeRF · 3DGS · 2DGS · GS-SLAM
9. **Self-Supervised & Label-Efficient Learning** — Point-MAE · Point-BERT · PointContrast · CLIP-guided 3D · Point-LLM
10. **Benchmark Datasets & Evaluation Metrics** — ModelNet · ShapeNet · ScanNet · SemanticKITTI · nuScenes · Waymo · mIoU · mAP · PQ
11. **Practical Implementation Guide** — PyTorch3D · Open3D · MinkowskiEngine · MMDetection3D · Nerfstudio
12. **Applications** — Autonomous driving · robotics · medical imaging · digital twins · cultural heritage
13. **Current Challenges & Future Directions** — Scalability · domain adaptation · 3D foundation models · 4D perception · embodied AI
14. **Key References** — 23 foundational and SOTA papers

## Highlighted: LitePT (2025)

**Lite Point Transformer** by Yue et al. — a hybrid architecture that strategically decouples sparse convolutions (early stages for geometry) and self-attention (deep layers for context), with a novel training-free **PointROPE** positional encoding:

- **3.6×** fewer parameters than PTv3
- **2×** faster inference
- **½** the memory footprint
- Matching or exceeding SOTA accuracy on major 3D semantic and instance segmentation benchmarks

## Tech Stack

- Pure HTML5 / CSS3 / vanilla JavaScript — no build step, no dependencies
- Google Fonts (Inter + JetBrains Mono)
- SVG animations via native `<animate>` and CSS keyframes
- CSS Grid + Flexbox layout
- Backdrop-filter glassmorphism effects

## How to Use

1. Open `3d-ml-reference.html` directly in your browser (Chrome, Firefox, Safari, Edge)
2. Use the left sidebar to jump between chapters
3. Use the search bar to filter the navigation
4. Hover over figures to see shimmer and glow effects
5. The active section auto-highlights as you scroll

## Author

**Nirvana Fanaelahi** — AI Security Specialist & Machine Learning Engineer
M.Sc. Computer Vision & Data Science — NHL Stenden University
Research focus: cross-attention fusion architectures for complex image analysis

## License

This documentation is provided as a technical reference for educational purposes. Original content and figures are from the source PDF (April 2026 edition).

---

*Built with modern web standards · v2026.04*
