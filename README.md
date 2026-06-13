# EASYLENS: AI-Driven Smart Glasses for Multilingual Support Navigation Using Hyper Object Detection Awareness

## About the Project
**EASYLENS** is a thesis project developed at the **School of Computing, Holy Angel University** in partial fulfillment of the requirements for the degree **Bachelor of Science in Computer Science** (March 2026).

This project focuses on improving independent mobility for visually impaired individuals through smart glasses that provide real-time, multilingual audio guidance.

## Proponents
- Graciella Mhervie D. Jimenez
- Jian Kalel D. Marquez
- Arron Kian M. Parejas
- Jenica Sarah B. Tongol

## Project Background
Visual impairment affects billions of people worldwide and millions in the Philippines, creating major challenges in safe and independent navigation. Traditional mobility aids such as white canes remain essential, but they are limited because they mainly detect obstacles through physical contact and may miss hazards above waist level or at a distance.

EASYLENS addresses these gaps by combining:
- **Offline-first AI processing** for reliability without constant internet access
- **Hyper object detection awareness** on-device (e.g., MobileNet-based approach)
- **Rapid Wi-Fi IoT communication** between components
- **Audio Augmented Reality (AR)** guidance in **Filipino and English**

The system aims to deliver timely audio alerts for hazards such as vehicles, stairs, and other obstacles while remaining practical and culturally relevant for Filipino users.

## Research Design
The study uses a **quantitative experimental design** with two groups:
- **Control Group:** Uses traditional mobility aids only
- **Experimental Group:** Uses traditional mobility aids plus EASYLENS

Measured variables include:
- Object detection accuracy
- Processing delay (milliseconds)
- Battery consumption rate

Usability and software quality are assessed using structured instruments aligned with **ISO/IEC 25010:2023** standards. Development follows a **Rapid Application Development (RAD)** cycle to iteratively build, test, and refine both hardware and software.

## Sources of Data
### Primary Data
- Custom, localized image datasets (e.g., jeepneys, tricycles, pedestrian lanes, open canals)
- Structured usability surveys from visually impaired participants and IT experts
- ISO/IEC 25010:2023-based evaluation checklists

> Data collection excludes facial recognition and personally identifiable information (PII).

### Secondary Data
- Kaggle datasets, including:
  - CIFAR-10 Object Recognition
  - Intel Image Classification
  - Road Damage Detection
  - Pedestrian Detection
  - Traffic Sign Detection
  - Fire Detection
  - Smoke Detection
- Baseline benchmarks from:
  - COCO (Common Objects in Context)
  - LVIS (Large Vocabulary Instance Segmentation)

## Repository Context
This repository is the organization-level `.github` repository used for shared documentation and project-level communication. This README provides the core background and research context for the EASYLENS initiative.
