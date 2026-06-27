<<<<<<< HEAD
# ICROS2026
=======
# ICROS2026 Project Page

Static GitHub Pages website for:

**LLM-Based Inductive Synthesis of a Local Behavior Tree for Decentralized Multi-Robot Cooperation**

## Local preview

```bash
cd ~/ICROS2026
python3 -m http.server 8000
```

Open:

```text
http://localhost:8000
```

## Recommended asset structure

```text
assets/
├── docs/
│   ├── paper.pdf
│   └── poster_draft.pdf
├── images/
│   ├── poster_preview.png
│   └── identical_bt_architecture.svg
└── videos/
    ├── bt_synthesis_process.mp4
    ├── comparison_overview.mp4
    ├── comparison_4x4_2cubes.mp4
    ├── comparison_4x4_3cubes.mp4
    ├── comparison_4x4_4cubes.mp4
    ├── comparison_5x5_2cubes.mp4
    ├── comparison_5x5_3cubes.mp4
    ├── comparison_5x5_4cubes.mp4
    ├── comparison_6x6_2cubes.mp4
    ├── comparison_6x6_3cubes.mp4
    ├── comparison_6x6_4cubes.mp4
    ├── scalability_overview.mp4
    ├── scalability_7x7_16cubes.mp4
    └── scalability_5x5_disturbances.mp4
```

The `Experiment Videos` section is designed as a 3-card gallery:

1. **BT Synthesis Process**
2. **Comparison: One-Step vs. Ours**
3. **Scalability Test (Ours)**

The comparison card shows one overview video first. The detailed 4x4, 5x5, and 6x6 cases are placed in an expandable panel under the gallery.

## Push to GitHub

```bash
cd ~/ICROS2026

git init
git branch -M main
git add .
git commit -m "Initial ICROS2026 project page"

git remote add origin https://github.com/boss123516/ICROS2026.git
git push -u origin main
```

Then enable GitHub Pages from repository settings:

`Settings → Pages → Deploy from a branch → main → /root`
>>>>>>> dc1ebfc (Initial ICROS2026 website)
