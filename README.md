# Prediction of 5GC Data Using a Tiny LLM

## Overview
This project explores predicting **5G Core (5GC) metrics** using a **tiny Large Language Model (LLM)**.

We deploy **OPEN5GS** on a local **Kubernetes (kind)** cluster, collect metrics using **Prometheus**, and apply **Chronos-bolt-tiny** for time-series prediction (e.g., CPU usage).

This repository is in the **very early stage** of development.

---

## Current Plan
- Deploy a Kubernetes cluster using **kind**
- Deploy **OPEN5GS**
- Deploy **Prometheus** to collect metrics
- Extract and preprocess time-series data
- Predict metrics using **Chronos-bolt-tiny**

---

## Bonus (Planned)
- Compare results with **TimeGPT**  
  https://github.com/Nixtla/nixtla

---

## Status
🚧 Work in progress

