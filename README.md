# AR Car Showroom

An Augmented Reality (AR) car showroom built using **Unity** and **Vuforia Engine**.  
The application uses image-target recognition to detect physical car reference images and overlays corresponding 3D car models onto them in real time.

The project demonstrates marker-based AR, image recognition, 3D model integration, material/texturing, target tracking, and real-time rendering using Unity.

---
## Working Demonstration

The following video demonstrates the working AR Car Showroom application.

### Demo

[▶️ Watch the AR Car Showroom Demonstration](./Demo/AR-Car-Showroom-Demo.mp4)

## Overview

Traditional car showrooms require customers to physically visit a location to view different vehicles. This project explores how Augmented Reality can be used to create a virtual car showroom where users can view 3D vehicle models by simply pointing a camera toward predefined image targets.

The system uses **Vuforia Image Target tracking**. Each target image is associated with a specific 3D car model. When the camera recognizes a target, the corresponding vehicle model is rendered in the AR environment.

### Current AR Models

The showroom currently contains:

- Aston Martin

Each vehicle is associated with its own image target.

---

## Objectives

The main objectives of this project are:

- Implement image-target based Augmented Reality.
- Detect physical reference images using Vuforia.
- Display corresponding 3D vehicle models on detected targets.
- Integrate externally sourced 3D vehicle assets into Unity.
- Configure and apply materials and textures to 3D models.
- Position, rotate, and scale 3D models relative to their AR targets.
- Create a basic virtual car showroom experience.
- Demonstrate real-time AR tracking through a camera feed.

---

## ⚙️ Technology Stack

| Technology | Purpose |
|------------|---------|
| **Unity 2022.3.62f3** | AR application development and real-time 3D rendering |
| **C#** | Unity scripting and application logic |
| **Vuforia Engine** | Image recognition and AR target tracking |
| **Unity 3D** | Vehicle model rendering and scene management |
| **Vuforia Image Targets** | Physical reference points for AR content |
| **Blender / 3D Assets** | 3D vehicle model preparation |
| **Standard Shader** | Material and surface rendering |
| **Unity Camera / ARCamera** | Capturing and tracking the physical environment |

---

## System Architecture

The project follows a simple marker-based AR pipeline:

<img width="1536" height="853" alt="carshowroom system architcturw" src="https://github.com/user-attachments/assets/ceb76a6f-656f-49a7-81f2-6fbf0ecfcdcb" />


## Working Prototype
The following screenshot shows the AR car showroom running with the vehicle model tracked over the target image.

<img width="1467" height="724" alt="working prototype 1" src="https://github.com/user-attachments/assets/19cda4e7-d407-4595-ae69-646664633ddd" />
<img width="1393" height="726" alt="working prototype 2" src="https://github.com/user-attachments/assets/947a5971-4ef4-4bae-8cd0-e89bfdb0aaac" />

