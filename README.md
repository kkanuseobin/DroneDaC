# EAI_droneDaC
딥러닝 기반 불법촬영목적 드론 실시간 감지 시스템 (Real-time detection system for illegal filming purpose drones based on deep learning)

-------------------------------------
### 2022-08-21 최초 Update
### 2022-12-01 추가기능 및 데이터셋 18:00 업데이트 예정
-------------------------------------
### ▶Introduction
> [0] 복잡한 배경의 드론을 검출하기 위해 이미지 합성처리 진행
> 
> [1] YOLOv5 model을 이용해 실시간 드론 검출
> 
> [2] VGG11 model로 드론 종류를 분류(DJI Air2S, Mini2, Phantom 4 Pro, Tello, Phatom3)
> 
> [3] 객체 검출 정보를 활용하여 ⓐ 불법 촬영목적 드론 구분(이동 거리 연산 및 배송 박스 검출), ⓑ 드론 모션 이미지화 및 ⓒ 방향정보 계산(8방위)
> 
> GOAL! 딥러닝 기반 불법촬영목적 드론 실시간 감지 시스템

-------------------------------------
### ▶ Experimental Environment
> [1] Python 3.8.13
> 
> [2] Pytorch 1.11.0
>
> [3] GPU NVIDIA GeForce RTX 3060

-------------------------------------
### ▶ Precautions
> YOLOv5 기반 환경이 설정되어 있어야합니다.
> 
> 웹캠 뿐만 아니라 동영상 입력처리로 학습이 가능합니다.
> 
> 사전 작업(이미지 증강, 합성 등)에 관한 코드도 업로드했습니다.(Pre-work folder)

