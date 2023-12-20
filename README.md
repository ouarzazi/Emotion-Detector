# Emotion Detector Project

This repository contains the code and documentation for the Emotion Detector project developed during the first year of the engineering cycle at ENSEA. The project involves the creation of a system capable of detecting emotions using a microphone, Raspberry Pi, and a Printed Circuit Board (PCB) with LEDs.

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
3. [Hardware Setup](#hardware-setup)
4. [Software Implementation](#software-implementation)
5. [Results and Validation](#results-and-validation)
6. [Project Refinement](#project-refinement)
7. [Conclusion](#conclusion)

## Introduction

In the context of our engineering studies at ENSEA, we embarked on a project to develop an Emotion Detector system. This README provides an overview of the project, its components, and the steps taken to implement it.

## Project Overview

The Emotion Detector project aims to create a system that can detect emotions using a microphone, Raspberry Pi, and a PCB with LEDs representing different emotions. The project was undertaken during a 44-hour, 6-week period as part of our coursework.

## Hardware Setup

### Microphone
We selected a microphone as the primary input for capturing audio signals.

### PCB (Printed Circuit Board)
A PCB was designed and printed using Eagle software to accommodate LEDs representing different emotions.

### Raspberry Pi
The Raspberry Pi serves as the central processing unit, acquiring and processing inputs through a Natural Language Processing (NLP) model.

### LED Montage
The LEDs were mounted on the PCB to visually represent the detected emotions.

For detailed hardware setup instructions, please refer to the [Partie électronique](#partie-électronique) section in the project documentation.

## Software Implementation

### Voice2text
A Python code converts audio signals captured by the microphone into text using Voice2text.

### NLP Model
The Natural Language Processing (NLP) model was trained on emotion datasets to predict emotions based on processed text inputs.

For detailed software implementation instructions, please refer to the [Partie informatique](#partie-informatique) section in the project documentation.

## Results and Validation

The model was trained and validated, and the results were analyzed using various metrics. The correlation between predicted and actual labels was visualized through confusion matrices.

For detailed results and validation information, please refer to the [Résultat et validation du modèle](#résultat-et-validation-du-modèle) section in the project documentation.

## Project Refinement

Future improvements to the project may include integrating additional sensors such as facial recognition and remote heart rate monitoring. Enhancements to the output display, such as showing emotion types and intensities on a screen, are also potential refinements.

For more ideas on project refinement, please refer to the [Affinement du projet](#affinement-du-projet) section in the project documentation.

## Conclusion

Participating in the Emotion Detector project gave me significant hands on experience in engineering, covering tasks from designing a PCB to implementing a Natural Language Processing model. Additionally, using LaTeX for documentation aimed to enhance my skills in writing research papers.
