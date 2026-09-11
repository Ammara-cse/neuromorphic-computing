
# Neuromorphic Computing: Hardware Inspired by the Human Brain

This repository contains the complete **LaTeX source code** for the seminar report and Beamer presentation on **Neuromorphic Computing**, submitted for the Department of Computer Engineering at **Dr. Babasaheb Ambedkar Technological University (BATU)**.

---

## 📁 Repository Structure

* `main.tex` — Full Seminar Report LaTeX source code.
* `presentation.tex` — Beamer Slideshow LaTeX source code.
* `references.bib` — Bibliography dataset for references.
* `BATU_logo.png` — University logo image.
* `*.png` / `*.jpg` — Architectural diagrams and chip visual assets.

---

## 🛠️ Prerequisites & Setup

To compile the LaTeX files locally, ensure you have the following installed:

* **LaTeX Distribution**: TeX Live, MiKTeX, or MacTeX
* **LaTeX Engine**: `pdfLaTeX`
* **Bibliography Tool**: `biber`

> **Note:** You can also upload these files directly to [Overleaf](https://www.overleaf.com) and set the compiler to `pdfLaTeX`.

---

## 🚀 How to Compile

### 1. Seminar Report (`main.tex`)
Run the following commands in your terminal:

```bash
pdflatex main.tex
biber main
pdflatex main.tex
pdflatex main.tex

```

### 2. Beamer Presentation (`presentation.tex`)

Run:

```bash
pdflatex presentation.tex
pdflatex presentation.tex

```

---

## 📌 Project Overview

* **Topic**: Neuromorphic Computing (Brain-inspired hardware architecture)
* **Key Topics Covered**:
* Spiking Neural Networks (SNNs) & Synaptic Plasticity
* Memristors & In-Memory Computing
* Hardware Implementations (Intel Loihi, IBM TrueNorth, BrainChip Akida)
* Software Frameworks (Intel Lava)
* Edge AI Applications & Future Scope



---

## 👤 Author & Details

* **Author**: Ammara Fairoz Sirkhot
* **PRN**: 24030332905059
* **Branch**: Integrated Computer Science and Engineering
* **University**: Dr. Babasaheb Ambedkar Technological University, Lonere
* **Guide**: Prof. Uzma Munde
* **Academic Year**: 2025–2026

