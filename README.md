<div align="center">

# BD-DF-OptiWhisper Web Application Demonstration

### Robust Bengali Deepfake Audio Detection Using a Calibrated Parameter-Efficient Whisper Transformer

<br>

[![Repository](https://img.shields.io/badge/Repository-Demonstration%20Only-0B1F3A?style=for-the-badge)](#repository-scope)
[![Model](https://img.shields.io/badge/Model-BD--DF--OptiWhisper-00A6B4?style=for-the-badge)](#proposed-framework)
[![Backbone](https://img.shields.io/badge/Backbone-Whisper--Base-5B4BDB?style=for-the-badge)](#proposed-framework)
[![Adaptation](https://img.shields.io/badge/Adaptation-LoRA-7A3E9D?style=for-the-badge)](#proposed-framework)
[![Task](https://img.shields.io/badge/Task-Real%20vs.%20Deepfake%20Audio-008C95?style=for-the-badge)](#system-capabilities)
[![Demo](https://img.shields.io/badge/Application-Real--Time%20Web%20Demo-087F8C?style=for-the-badge)](#demo-video)

<br>

<b>Publication-oriented demonstration repository for the BD-DF-OptiWhisper Bengali deepfake audio detection web application.</b>

<br>

[Purpose](#purpose) •
[Demo Video](#demo-video) •
[Interface](#application-interface) •

</div>

---

## Purpose

This repository presents the **screen-recorded web application demonstration** of **BD-DF-OptiWhisper**, a calibrated and parameter-efficient Transformer-based framework developed for **Bengali deepfake audio detection**.

The repository is prepared as supporting demonstration evidence for the research manuscript provisionally titled:

> **Robust Bengali Deepfake Audio Detection Using a Calibrated Parameter-Efficient Whisper Transformer**

The demonstration shows how the proposed system performs audio-level and segment-level analysis through an interactive web interface. It is intended to complement the methodological, experimental, and deployment discussions reported in the associated research paper.

---

## Demo Video

The complete screen-recorded demonstration of the developed web application is available below.

<div align="center">

[![Watch BD-DF-OptiWhisper Demo](https://img.shields.io/badge/Watch%20Application%20Demo-YouTube-BF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtu.be/oQRm8Slis3o?si=-uw8MGvZv8C-JMnl)

</div>

---

## Application Interface

<div align="center">

<img src="real%20time%20web%20application.png" alt="BD-DF-OptiWhisper Real-Time Bengali Deepfake Audio Detection Web Application" width="950">

<br>

<sub><b>Figure:</b> Real-time web interface developed for Bengali deepfake audio detection using BD-DF-OptiWhisper.</sub>

</div>

---

## Demonstrated Workflow

| Step | Operation | Demonstrated Output |
|---:|---|---|
| 1 | A Bengali audio clip is submitted through the web interface. | Selected audio and playback information |
| 2 | The audio is standardized and converted into Whisper-compatible acoustic features. | Model-ready audio representation |
| 3 | BD-DF-OptiWhisper performs clip-level inference. | Real and fake probabilities |
| 4 | The application performs segment-level analysis across the audio timeline. | Segment-wise prediction scores |
| 5 | Calibrated probabilities are evaluated using the finalized decision threshold. | Final Real or Deepfake classification |
| 6 | The interface summarizes the temporal evidence. | Highest segment score, suspicious-segment count, and temporal prediction map |

---





## Contact

For questions concerning the research methodology, application demonstration, or future artifact availability, please contact the authors through the contact information provided in the associated manuscript.

---

## Note

This repository provides visual and video-based evidence of the deployed web application interface and inference workflow associated with the proposed BD-DF-OptiWhisper framework.


<div align="center">

<b>BD-DF-OptiWhisper</b>

Robust and Calibrated Parameter-Efficient Whisper Transformer for Bengali Deepfake Audio Detection

<br><br>



</div>
