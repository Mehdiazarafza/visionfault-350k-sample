# VisionFault-350K: Representative Sample for Double-Blind Review

This repository contains a representative sample of the VisionFault-350K dataset provided for double-blind peer review. It includes sample images and folder hierarchies across key visual fault categories.

---

## Dataset Overview

VisionFault-350K is a fault-augmented dataset built from real robotic camera images. Fault scenarios designed by an LLM were used to transform original image frames via Latent Diffusion Models (img2img) to simulate challenging real-world edge cases and environmental stress on edge perception systems.

## Technical Specifications

* **Primary Tasks:** Lane Following (LF) and Obstacle/Object Detection (OD)
* **LLM Engine:** Fault scenario prompts generated using GPT-OSS 120B
* **Synthesis Engine:** Visual faults synthesized using Stable Diffusion 2.1 Base
* **Fault Categories:** 
  * Camera Failures
  * Motion Blur
  * Extreme Weather (Ice, Heavy Rain, Fog)
  * Low Light (Tunnel, Night, Backlight)
  * Lens Distortions, Occlusions, and others

---

## Sample Directory Structure

The structure of this review sample mirrors the organization of the complete corpus:
