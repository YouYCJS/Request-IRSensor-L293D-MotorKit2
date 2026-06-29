# IR Line-Tracing Car Controller
**IR 센서 기반 자율주행 카 제어 보드**

> IR 센서 입력으로 L293D 모터 드라이버를 구동해 자율주행하는 RC카용 커스텀 PCB.
> Altium으로 스키매틱부터 PCB 레이아웃, 3D 검증까지 전 과정 설계 후 실제 발주했습니다.
> (DORO 의뢰 프로젝트)

<img src="https://github.com/user-attachments/assets/0a7be633-5448-4390-aadc-039c09b71a25" alt="3D 앞면" width="45%">

## 개요
IR 센서로 감지한 신호에 따라 두 개의 모터(BLUE / WHITE)를 제어하는
자율주행 카 제어 보드입니다. 브레드보드 프로토타입을 커스텀 PCB로 발전시켰습니다.

## 구성
- **입력**: IR 센서 (OUT / GND / VCC)
- **모터 드라이버**: L293D
- **구동부**: DC 모터 ×2 (BLUE / WHITE)
- **전원**: 스위치 + 배터리, 로직/모터 전원 분리
- **설계 툴**: Altium Designer

## 완성된 보드

| 앞면 (3D) | 뒷면 (3D) |
|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/0a7be633-5448-4390-aadc-039c09b71a25" alt="3D 앞면" width="100%"> | <img src="https://github.com/user-attachments/assets/f6b51ad4-c63f-4f4e-9cbf-7d5da63dbfda" alt="PCB 레이아웃" width="100%"> |

## 설계 과정

1. 회로 설계 (스키매틱)
2. 브레드보드 프로토타입 검증
3. PCB 레이아웃 (양면 기판)
4. 3D 뷰로 부품 배치·풋프린트 검증
5. 제조 발주

| 회로 설계 (Schematic) | PCB 레이아웃 |
|:---:|:---:|
| <img src="https://github.com/user-attachments/assets/04e51519-4e94-49dd-b238-501d10d95811" alt="스키매틱" width="100%"> | <img src="https://github.com/user-attachments/assets/6fc122ee-54f6-44cf-9330-13200d12875c" alt="3D 뒷면" width="100%"> |

## 프로토타입

브레드보드로 먼저 회로를 검증한 뒤 커스텀 PCB로 발전시켰습니다.

<img src="https://github.com/user-attachments/assets/52f04b3c-5606-48ea-9674-03b94f72c257" alt="브레드보드 프로토타입" width="70%">

## 회고
- 브레드보드 → 커스텀 PCB 전환 과정을 직접 경험
- Altium으로 스키매틱부터 3D 검증까지 전체 워크플로우 수행
