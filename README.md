````markdown
# 👁️ Object Detection From Scratch: 2-Month Challenge

![Status](https://img.shields.io/badge/Status-In%20Progress-yellow?style=flat)
![Goal](https://img.shields.io/badge/Goal-Implementation%20from%20Scratch-blue?style=flat)

> **"From Traditional Computer Vision to Modern Deep Learning"** > 컴퓨터 비전의 근본 원리부터 최신 딥러닝 모델(YOLO)까지 학습하고, 핵심 알고리즘(NMS, IoU)을 C++로 직접 구현하기 위한 **8주간의 학습 기록**입니다.

---

## 📌 Motivation
이 프로젝트는 Object Detection 기술의 **'근본 원리'**를 이해하기 위해 시작했습니다.  
단순히 라이브러리를 사용하는 것을 넘어, **핵심 로직을 C++로 밑바닥부터 구현(Implementation from scratch)** 하여 렌더링 엔진 등 실시간 시스템에 적용할 수 있는 최적화 역량을 기르는 것이 목표입니다.

## 🛠 Tech Stack Goals
- **Languages:** Python (Prototyping), C++ (Core Algorithm Implementation)
- **Libraries:** PyTorch, OpenCV, NumPy
- **Deployment:** CoreML (iOS), ONNX

---

## 📂 Repository Structure (Planned)

이 레포지토리는 학습 단계별로 폴더가 구분되어 있습니다.

```bash
📦 Object-Detection-Study
 ├── 📂 01_Traditional_CV       # [W1] 고전 컴퓨터 비전 (Convolution, Edge Detection)
 ├── 📂 02_Deep_Learning_Basic  # [W2] CNN 기초 구조 및 MNIST 분류기
 ├── 📂 03_Core_Implementation  # [W5] C++ 핵심 알고리즘 구현 (NMS, IoU)
 ├── 📂 04_YOLO_Experiments     # [W6] YOLO 모델 구조 분석 및 실습
 └── 📜 README.md
````

-----

## 🚀 Learning Roadmap & Key Features

이 프로젝트에서 구현할 핵심 기능들입니다. 학습이 진행됨에 따라 코드가 채워질 예정입니다.

### 1\. Non-Maximum Suppression (NMS) in C++

Object Detection 후처리 과정의 병목이 되는 NMS 알고리즘을 C++로 직접 구현하여 최적화합니다.

  - **Goal:** STL 컨테이너를 활용한 메모리 최적화 구현
  - **Status:** `[Waiting for Week 5]`
  - **Code:** *(Coming Soon)*

### 2\. Intersection over Union (IoU) Logic

두 Bounding Box의 겹치는 영역을 계산하는 기하학적 로직을 구현합니다.

  - **Status:** `[Waiting for Week 5]`

### 3\. Edge Detection (Traditional CV)

딥러닝 이전, 필터(Kernel) 연산을 통해 물체의 윤곽선을 검출하는 원리를 실습합니다.

  - **Status:** `[Waiting for Week 1]`

-----

## 📝 Weekly Progress Log

| Week | Topic | Key Activities | Status |
| :--- | :--- | :--- | :--- |
| **W1** | Traditional CV | Convolution 연산 손계산, Edge Detection 구현 | ⬜️ |
| **W2** | CNN Basics | CNN 구조 이해, Receptive Field 개념 정리 | ⬜️ |
| **W3** | 2-Stage Detectors | R-CNN, Fast/Faster R-CNN 논문 리뷰 | ⬜️ |
| **W4** | 1-Stage (YOLO v1) | YOLO v1 논문 정독, Grid Cell 분석 | ⬜️ |
| **W5** | **C++ Impl** | **NMS, IoU 알고리즘 C++ 구현 (Key Goal)** | ⬜️ |
| **W6** | Modern YOLO | YOLO v8 실습, Webcam Inference | ⬜️ |
| **W7** | Deployment | CoreML 변환, Quantization 테스트 | ⬜️ |
| **W8** | Wrap-up | 전체 파이프라인 정리, 포트폴리오 완성 | ⬜️ |

-----

## 🔗 Study References

  - **Paper:** [You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/abs/1506.02640)
  - **Course:** CS231n: Deep Learning for Computer Vision

<!-- end list -->

```
```
