<div align="center">

# 🧠 Entry AI From Scratch

### 인공지능을 **사용하는 것**을 넘어, **직접 구현하는 것**으로.

**Machine Learning · Deep Learning · Reinforcement Learning — built with Entry blocks**

<p>
  <img src="https://img.shields.io/badge/Platform-Entry-00A9E0?style=for-the-badge" alt="Entry" />
  <img src="https://img.shields.io/badge/Approach-From%20Scratch-6C63FF?style=for-the-badge" alt="From Scratch" />
  <img src="https://img.shields.io/badge/Projects-.ent-2E8B57?style=for-the-badge" alt="Entry Project Files" />
</p>

**[프로젝트 둘러보기](#-알고리즘-아카이브) · [실행 방법](#-프로젝트-열어보기) · [English](#-english)**

</div>

---

## 🔍 프로젝트 소개

**Entry AI From Scratch**는 블록 코딩 플랫폼 **[엔트리(Entry)](https://playentry.org/)** 를 이용해 머신러닝과 인공지능 알고리즘의 핵심 동작을 직접 구현해 보는 개인 학습 프로젝트입니다.

고수준 머신러닝 프레임워크의 완성된 학습·추론 기능에 의존하는 대신, 가능한 범위에서 **변수, 리스트, 조건문, 반복문, 함수(블록)** 를 조합해 알고리즘이 작동하는 과정을 표현합니다.

> **왜 엔트리인가요?**  
> 알고리즘을 단순히 실행하는 데서 끝나지 않고, 계산 과정과 데이터 흐름을 하나씩 직접 설계하며 이해하기 위해서입니다. 또한 대화형 AI에 구현을 맡기기보다는 스스로 작성한 코드를 기록하고 싶어 이 방식을 선택했습니다.

| 🎯 이해 | 🧩 구현 | 🔬 실험 |
|:---:|:---:|:---:|
| 수식과 원리 파악 | 계산 절차를 블록으로 구성 | 동작을 관찰하고 수정 |

## 📚 알고리즘 아카이브

저장소는 알고리즘과 실험 주제별 폴더로 구성되어 있습니다. 아래 링크를 클릭하면 해당 파일들을 확인할 수 있습니다.

### 01 · 머신러닝과 군집화

| 구분 | 구현한 알고리즘 | 프로젝트 폴더 |
|---|---|---|
| 회귀 | Linear Regression, Logistic Regression | [선형회귀](./선형회귀/) · [로지스틱회귀](./로지스틱회귀/) |
| 분류 | K-Nearest Neighbors (KNN) | [KNN](./KNN/) |
| 군집화 | K-Means, DBSCAN, OPTICS, AGNES, DIANA, PAM, ROCK | [군집알고리즘들](./군집알고리즘들/) · [기타](./기타/) |
| 경쟁학습·자기조직화 | Self-Organizing Map (SOM), Learning Vector Quantization (LVQ) | [기타](./기타/) |
| 진화 연산 | Genetic Algorithm | [유전 알고리즘](./유전%20알고리즘/) |

### 02 · 신경망과 생성 모델

| 구분 | 구현한 알고리즘 | 프로젝트 폴더 |
|---|---|---|
| 기본 신경망 | Artificial Neural Network (ANN) | [인공신경망](./인공신경망/) · [기타](./기타/) |
| 합성곱 신경망 | Convolutional Neural Network (CNN) | [CNN](./CNN/) |
| 순환 신경망 | Recurrent Neural Network (RNN) | [RNN](./RNN/) · [기타](./기타/) |
| 생성적 적대 신경망 | GAN, DCGAN | [GAN](./GAN/) · [DCGAN](./DCGAN/) |
| 변분 오토인코더 | VAE, β-VAE, CVAE, HVAE | [VAE](./VAE/) · [Beta-VAE](./Beta-VAE/) · [CVAE](./CVAE/) · [HVAE](./HVAE/) |

### 03 · 강화학습과 기타 실험

| 구분 | 구현한 내용 | 프로젝트 폴더 |
|---|---|---|
| 강화학습 | Q-Learning, Deep Q-Network (DQN) | [Q러닝](./Q러닝/) · [DQN](./DQN/) |
| 컴퓨터 비전 | 이미지 처리 및 픽셀 정보 활용 실험 | [컴퓨터비전](./컴퓨터비전/) |
| 활성화 함수 | ReLU, Leaky ReLU, ELU, Sigmoid, Tanh, Softplus, SiLU, GELU, Mish, SELU, Step 등 | [활성화 함수들](./활성화%20함수들/) |
| 추가 실험 | 알고리즘별 변형·검증·테스트 작품 | [기타](./기타/) |

<details>
<summary><b>🗂️ 추가된 군집화·신경망 실험 파일 살펴보기</b></summary>

새로 추가한 `기타/` 폴더에는 `AGNES.ent`, `DBSCAN.ent`, `OPTICS.ent`, `ROCK.ent`, `DIANA.ent`, `PAM.ent` 등 군집화 실험과 SOM, LVQ, RNN, ANN, Q-Learning 관련 작품 및 작업 중 생성된 검증 파일이 포함되어 있습니다.

실험용 파일과 최종 작품은 파일 이름으로 구분될 수 있으므로, 목적에 맞는 파일을 선택해 열어 주세요.

</details>

## 🚀 프로젝트 열어보기

이 저장소의 주요 결과물은 파이썬 소스나 실행 파일이 아니라 **엔트리 작품 파일(`.ent`)** 입니다. 별도의 Python·PyTorch 설치는 필요하지 않습니다.

1. 위 목록에서 원하는 알고리즘의 폴더를 엽니다.
2. `.ent` 파일을 선택한 다음 **Download raw file**로 다운로드합니다.
3. **[엔트리](https://playentry.org/)** 에 접속해 **작품 만들기**를 엽니다.
4. 메뉴에서 **오프라인 작품 불러오기** 기능을 선택합니다.
5. 다운로드한 `.ent` 파일을 불러와 블록 구성과 실행 결과를 확인합니다.

> **참고:** 엔트리의 메뉴명과 위치는 서비스 업데이트에 따라 달라질 수 있습니다. 이 프로젝트는 학습과 실험을 목적으로 하므로 작품마다 인터페이스나 완성도가 다를 수 있습니다.

## 🖼️ 컴퓨터 비전 실험 기록

<div align="center">
  <img src="./이미지%20픽셀%20정보%20를엔트리로%20불러오기.png" alt="엔트리로 이미지 픽셀 정보를 불러오는 실험 관련 이미지" width="680" />
  <sub>저장소에 포함된 이미지 픽셀 정보 활용 실험 자료</sub>
</div>

## 💡 프로젝트가 지향하는 것

- **원리 중심 학습** — 알고리즘의 이름보다 실제 계산 흐름에 집중합니다.
- **직접 구현** — 준비된 모델 API를 호출하는 대신 핵심 연산을 단계적으로 구성합니다.
- **실험 기록** — 여러 구조와 알고리즘을 시도한 `.ent` 파일을 보관합니다.
- **접근성** — 블록 코드를 통해 알고리즘의 구조를 시각적으로 살펴볼 수 있도록 합니다.

이 저장소는 범용 AI 라이브러리나 제품이 아니라, **인공지능을 밑바닥부터 이해하기 위한 개인적인 구현·탐구 아카이브**입니다.

---

## 🌐 English

**Entry AI From Scratch** is a collection of machine learning, deep learning, and reinforcement learning experiments implemented using **[Entry](https://playentry.org/)**, a visual block-based programming platform.

Rather than relying on ready-made model APIs in frameworks such as PyTorch or TensorFlow, the project focuses on expressing core algorithmic steps through variables, lists, loops, conditions, and custom blocks.

**What's inside:** regression and classification, clustering algorithms, neural networks, generative models (GANs and VAEs), Q-Learning, DQN, computer vision experiments, and activation functions.

**How to explore:** download an `.ent` project file, open the Entry editor, and import it as an offline project. Each file is a learning experiment, not necessarily a production-ready implementation.

---

<div align="center">

**Built to understand AI, one block at a time.** 🧩

Created by **[@oyueo-mm](https://github.com/oyueo-mm)**

</div>
