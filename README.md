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

```text
VisionFault-350K-Sample/
├── README.md
├── lane_following_sample/
│   ├── BATTERY_DROPOUT_001/
│   ├── BLOOM_EFFECT_001/
│   ├── BLUR_004/
│   ├── BLUR_005/
│   ├── BLUR_007/
│   ├── BLUR_GAUSSIAN_001/
│   ├── BLUR_RAIN_002/
│   ├── BLUR_SATURATION_001/
│   ├── BRIGHT_GLARE_001/
│   ├── BRIGHT_REFLECTION_015/
│   ├── brightness_flicker_led_001/
│   ├── brightness_spike_001/
│   ├── CAMERA_DROPLETS_001/
│   ├── CAMERA_DUSTMIST_001/
│   ├── CAMERA_DYNAMIC_FOCUS_001/
│   ├── CAMERA_DYNAMIC_NOISE_001/
│   ├── CAMERA_ECHO_001/
│   ├── CAMERA_ELECTRICAL_INTERFERENCE_001/
│   ├── CAMERA_ELECTRICINTERFERENCE_001/
│   ├── CAMERA_EMI_001/
│   ├── FRAME_DROP_RANDOM_009/
│   ├── FRAME_JITTER_001/
│   ├── FROST_COATING_001/
│   ├── GAUSSIAN_NOISE_MED_001/
│   ├── IMAGE_NOISE_001/
│   ├── LENS_DISTORTION_005/
│   ├── LIGHTING_CHANGE_002/
│   ├── LOW_LIGHT_GLASSES_001/
│   ├── MOTION_BLUR_SLOW_009/
│   ├── MULTI_FOG_RAIN_001/
│   ├── NOISE_INJECTION_019/
│   ├── NOISE_SPIKE_020/
│   ├── RAIN_OCCLUSION_LIGHT_SNOW_021/
│   ├── SENSOR_DIRT_SMUDGE_001/
│   ├── SENSOR_FOG_020/
│   ├── SNOW_FOG_001/
│   ├── TEMPORAL_NOISE_001/
│   ├── WIND_LOW_001/
│   └── WIND_SHAKE_001/
└── obstacle_detection_sample/
    ├── BATTERY_DRAIN_001/
    ├── BATTERY_DROP_001/
    ├── BRIGHT_GLARE_003/
    ├── BRIGHT_LIGHTS_002/
    ├── CAMERA_COMPRESSION_ARTIFACT_001/
    ├── CAMERA_DARKENING_001/
    ├── CAMERA_DEAD_PIXELS_003/
    ├── DUST_001/
    ├── EXPOSURE_VARIATION_011/
    ├── EYE_GLASS_REFLECTION_001/
    ├── FOG_HAZE_002/
    ├── FOG_OCCLUSION_003/
    ├── GAUSSIAN_NOISE_LOW_014/
    ├── HARDWARE_FAILURE_DEADPIXEL_001/
    ├── HUE_001/
    ├── IMAGE_NOISE_002/
    ├── IMU_IMPAIRED_001/
    ├── INTERFERENCE_ELECTRIC_002/
    ├── LASER_SPECKLE_001/
    ├── LED_FAILURE_002/
    ├── LED_FLASHING_001/
    ├── LENS_DIRT_010/
    ├── LENS_DIRT_STATIC_001/
    ├── LENS_DISTORTION_013/
    ├── LENS_FOG_002/
    ├── LIDAR_ECHO_OVERLAP_001/
    ├── LIDAR_MULTIPLE_OBSTACLES_001/
    ├── MOTION_BLUR_SLOW_001/
    ├── PIXEL_STUCK_011/
    ├── RAIN_LIGHT_001/
    ├── SENSOR_NOISE_001/
    ├── SHADOW_FADE_001/
    ├── SNOW_LIGHT_002/
    ├── SNOW_OVERLAY_002/
    ├── SUN_DUSK_001/
    ├── SUN_GLAZE_002/
    ├── THERMAL_NOISE_025/
    ├── WATER_SPLASH_002/
    └── WIND_RAIN_006/


---
## Disclaimer

This dataset is generated via a combined LLM+LDM pipeline and is provided "as-is" for research purposes, robotic vision system stress testing, safety verification, and hardware resilience profiling.