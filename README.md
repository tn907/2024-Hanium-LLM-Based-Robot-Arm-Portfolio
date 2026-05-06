# 2024-Hanium-LLM-Based-Robot-Arm-Portfolio
2024 Hanium ICT Mentoring award-winning robot arm project: LLM interaction, ROS control, and Pick &amp; Place performance improvement

<img width="1063" height="598" alt="image" src="https://github.com/user-attachments/assets/4f990e83-34f5-4647-9f94-19e77a67eaaf" />
<img width="1098" height="617" alt="image" src="https://github.com/user-attachments/assets/b5cc63b1-c0eb-4c91-9b92-8de894e22e49" />


# 2024 Hanium ICT Mentoring - LLM-Based Robot Arm Interaction System

## 1. Project Overview

본 프로젝트는 사용자의 음성 명령을 인식하고, LLM을 통해 의도를 해석한 뒤, 로봇팔이 Pick & Place 작업을 수행하도록 구성한 LLM 기반 로봇팔 상호작용 시스템입니다.

OpenManipulator-X를 기반으로 ROS 환경에서 로봇 제어를 구현했으며, Python 기반 STT → LLM → TTS 파이프라인을 연동하여 사용자가 자연어로 로봇팔을 제어할 수 있도록 개발했습니다.

---

## 2. Award

- 2024 한이음 ICT 멘토링
- 한국정보산업연합회장상 수상
- 2024 WE-Meet 프로젝트 우수상
- DDP 전시 참여

---

## 3. My Role

- Python 기반 STT → LLM → TTS 파이프라인 구현
- ROS1 Noetic 환경에서 OpenManipulator-X 제어 연동
- 자연어 명령을 로봇팔 동작 명령으로 변환하는 구조 설계
- OpenManipulator-X 오픈소스 분석
- Pick & Place 동작 테스트 및 성능 개선
- 로봇팔 하단 모터 진동 및 오버슈트 문제 분석
- PID 제어 튜닝을 통한 동작 안정성 개선

---

## 4. Key Technologies

- Python
- OpenAI API
- STT
- TTS
- ROS1 Noetic
- C++
- OpenManipulator-X
- OpenCV
- PID Control
- Robot Arm Kinematics

---

## 5. System Architecture

```text
User Voice Input
        ↓
Speech-to-Text
        ↓
LLM Command Interpretation
        ↓
Robot Command Parsing
        ↓
ROS Node
        ↓
OpenManipulator-X Control
        ↓
Pick & Place Execution
        ↓
Text-to-Speech Feedback
