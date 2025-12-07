# Object_Detection_from_scratch
```markdown
# 👁️ Object Detection From Scratch: Theory to Implementation

![Python](https://img.shields.io/badge/Python-3.9%2B-3776AB?style=flat&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-14%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-2.0-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-4.0-5C3EE8?style=flat&logo=opencv&logoColor=white)

> **"From Traditional Computer Vision to Modern Deep Learning"** > 컴퓨터 비전의 근본 원리(Convolution, Edge Detection)부터 최신 딥러닝 모델(YOLO)까지 학습하며, 핵심 알고리즘(NMS, IoU)을 C++로 직접 구현한 학습 기록입니다.

---

## 📌 Introduction
이 프로젝트는 Object Detection 기술의 **'근본 원리'**를 이해하기 위해 시작했습니다.  
단순히 라이브러리를 사용하는 것을 넘어, **핵심 로직을 C++로 밑바닥부터 구현(Implementation from scratch)** 하여 렌더링 엔진 등 실시간 시스템에 적용할 수 있는 최적화 역량을 기르는 데 초점을 맞췄습니다.

## 🛠 Tech Stack
- **Languages:** Python (Prototyping/Training), C++ (Core Algorithm Implementation)
- **Libraries:** PyTorch, OpenCV, NumPy
- **Deployment:** CoreML (iOS), ONNX

---

## 📂 Repository Structure

```bash
📦 Object-Detection-Study
 ├── 📂 01_Traditional_CV       # Convolution 손계산 및 Edge Detection (OpenCV)
 ├── 📂 02_Deep_Learning_Basic  # CNN 기초 구조 및 MNIST 분류기
 ├── 📂 03_Core_Implementation  # [Core] NMS, IoU 알고리즘 C++ 밑바닥 구현
 ├── 📂 04_YOLO_Experiments     # YOLO 모델 구조 분석 및 Custom Training
 └── 📂 05_Deployment           # CoreML 변환 및 모바일 경량화 테스트

---

## 🚀 Key Implementations (Core Features)

### 1. Non-Maximum Suppression (NMS) in C++
Object Detection 후처리 과정의 병목이 되는 NMS 알고리즘을 C++로 직접 구현하여 최적화했습니다.
- **Path:** `/03_Core_Implementation/nms.cpp`
- **Result:**
> *(여기에 NMS 적용 전/후 비교 이미지나 GIF를 넣어주세요)*
> `![NMS Result](./images/nms_result_placeholder.png)`

### 2. Intersection over Union (IoU) Logic
두 Bounding Box의 겹치는 영역을 계산하는 기하학적 로직을 구현했습니다.
```cpp
// (자신이 짠 C++ 코드의 핵심 부분을 여기에 복사해 넣으세요)
float calculateIoU(const Rect& boxA, const Rect& boxB) {
    float xA = std::max(boxA.x1, boxB.x1);
    float yA = std::max(boxA.y1, boxB.y1);
    // ...
    return interArea / (boxAArea + boxBArea - interArea);
}
````

### 3\. Edge Detection (Traditional CV)

딥러닝 이전, 필터(Kernel) 연산을 통해 물체의 윤곽선을 검출하는 원리를 학습하고 구현했습니다.

> *(Sobel 또는 Canny Edge Detection 결과 이미지를 넣어주세요)*

-----

## 📝 Weekly Learning Log

| Week | Topic | Key Activities | Status |
| :--- | :--- | :--- | :--- |
| **W1** | Traditional CV | Convolution 연산 손계산, Edge Detection(Sobel/Canny) 구현 | ⬜️ |
| **W2** | CNN Basics | CNN 구조(Conv-Pool-FC) 이해, Receptive Field 개념 정리 | ⬜️ |
| **W3** | 2-Stage Detectors | R-CNN, Fast/Faster R-CNN 논문 리뷰 및 RPN 구조 파악 | ⬜️ |
| **W4** | 1-Stage (YOLO v1) | YOLO v1 논문 정독, Grid Cell & Loss Function 분석 | ⬜️ |
| **W5** | **C++ Impl** | **NMS(Non-Max Suppression), IoU 알고리즘 C++ 구현 (★)** | ⬜️ |
| **W6** | Modern YOLO | YOLO v3\~v8 발전사 정리, Webcam Inference 실습 | ⬜️ |
| **W7** | Deployment | PyTorch 모델 → CoreML 변환, Quantization(양자화) 테스트 | ⬜️ |
| **W8** | Wrap-up | 전체 파이프라인(Input\~Output) 정리, 포트폴리오 마무리 | ⬜️ |

-----

## 🔗 References

  - **Paper:** [You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/abs/1506.02640)
  - **Paper:** [Faster R-CNN: Towards Real-Time Object Detection with RPN](https://arxiv.org/abs/1506.01497)
  - **Course:** CS231n: Deep Learning for Computer Vision

<!-- end list -->

```
```
