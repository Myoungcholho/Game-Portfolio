# 자기 소개

저는 성능과 프레임 단위에서 느껴지는 플레이 감각을 중시하는 개발자입니다.  

DirectX11 기반 엔진에서 리소스 로딩 시간을 58초에서 8초로 단축했고,  
인스턴싱을 도입해 렌더링 성능을 40.9 FPS에서 112.1 FPS(약 174% 향상)까지 개선한 경험이 있습니다.

문제를 볼 때는 겉으로 드러난 증상에만 집중하기보다,  
왜 이런 현상이 발생했는지 측정하고 원인을 찾는 일에 먼저 집중합니다.

그래야 재사용 가능한 구조를 만들 수 있고,  
같은 문제가 다시 발생하는 것을 막을 수 있다고 생각합니다.

# 프로젝트

## 🎮 DX11 자체 엔진 개발 프로젝트 [(상세보기)](https://github.com/Myoungcholho/DX_Portfolio/tree/main)

[![Video](https://img.youtube.com/vi/CVj2y5PXsnw/0.jpg)](https://www.youtube.com/watch?v=CVj2y5PXsnw)

> 개발 기간 : 2025.05 ~ 2025.10 (156일)
> 
> 
> *DX11 기반으로 언리얼 엔진 구조를 참고해,
> 자체 게임 엔진을 구현한 프로젝트입니다.*
> 


### 🔧사용 기술 및 툴

- 언어 : C++, HLSL
- 엔진/그래픽스 : DirectX11, SimpleMath
- 에디터/UI : ImGui Docking
- 디버깅/툴링 : RenderDoc, Deleaker, IBLMaker
- 에셋 처리 : Assimp
- IDE : Visual Studio 2022

### 📌담당 업무 및 경험

- 1인 개발
- GT/RT MailBox 기반 스냅샷 소비 모델 렌더링 코어 아키텍처 구축
- Actor / Component / SceneComponent 기반 월드 객체 구조 & Transform 시스템 설계
- 렌더링 파이프라인 구축
- Instancing 및 GPU 드로우콜 최적화
- 스켈레탈 애니메이션 시스템
- FBX Import Pipeline 및 Asset / Resource Manager 개발
- ImGui Docking 기반 에디터 & 툴링 시스템
- CPU/GPU 프로파일링 시스템 구현 및 프레임 드랍 원인 분석

## 🎮언리얼 3D 액션 게임 프로젝트 [(상세보기)](https://github.com/Myoungcholho/UnrealPortfolioSource/tree/master)

[![Video](https://img.youtube.com/vi/xfAdjhyRtIA/0.jpg)](https://www.youtube.com/watch?v=xfAdjhyRtIA)

> 개발 기간 : 2025.01.06 ~ 2025.04.02 (87일)
> 
> 
> *언리얼 엔진 기반 3D 액션 RPG로, 캐릭터·전투·AI·UI 등
> 핵심 게임플레이 시스템을 1인 개발로 구현한 프로젝트입니다.*
> 

### 🔧사용 기술 및 툴

- 언어 : C++
- 엔진 : Unreal Engine 5, Blueprint

### 📌담당 업무 및 경험

- 1인 개발
- 캐릭터 & 전투 시스템: 상태/무기/스테미나/피격/처형 로직 구현
- 아이템 & 인벤토리: 드랍·획득·사용 및 슬롯/인벤토리 구조 설계
- UI 시스템(MVVM): 체력/스테미나/아이템 슬롯 UI 및 데이터 바인딩 구조 구현
- AI & 전투 시스템: 적 계층 구조, 중앙 토큰 기반 전투 관리, 상태 머신 구현

## 🎮Unity3D 액션 게임 프로젝트 [(상세보기)](https://github.com/Myoungcholho/3D_Portfolio)

[![Video](https://img.youtube.com/vi/rzw9Piw8OtU/0.jpg)](https://www.youtube.com/watch?v=rzw9Piw8OtU&t=10s)

> 개발 기간 : 2024.06.26 ~ 2024.11.04 (131일)
> 
> 
> *Unity 기반 3D 액션 게임으로, 플레이어·전투·AI·UI 등
> 핵심 게임플레이 시스템을 1인 개발로 구현한 프로젝트입니다.*
> 

### 🔧사용 기술 및 툴

- 언어 : **C#**
- 엔진 : **Unity**

### 📌담당 업무 및 경험

- 1인 개발
- 플레이어 & 전투 시스템: 이동, 근·원거리/듀얼 무기, 스킬, 저스트 회피, 암살, 잔상, 슬로우 연출
- AI & 보스 전투: 전투 패턴, 등장/사망 연출, 시네마틱 연계
- UI & 상호작용: 스테미너·스킬 UI, NPC/대화·퀘스트, 타겟팅 데미지 폰트, 카메라 연출

## 🎮Unity2D 퍼즐 게임 개발 프로젝트 [(상세보기)](https://github.com/Myoungcholho/2DGame_JonsIsland)

[![Video](https://img.youtube.com/vi/gmhPEFaor1c/0.jpg)](https://www.youtube.com/watch?v=gmhPEFaor1c&t=17s)

> 개발 기간 : 2023.04.11 ~ 2023.10.11 (184일)
> 
> 
> *Unity 기반 2D 퍼즐 게임으로, 팀장으로 참여해 코어 기획부터
> 플레이어 상호작용, 게임 시스템, UI·저장까지 전반을 담당한 프로젝트입니다.*
> 

### 🔧사용 기술 및 툴

- 언어 : C#
- 엔진 : Unity

### 📌담당 업무 및 경험

- 5인 개발 – 팀장 역할(코어 기능 기획, 역할 분배 및 작업 관리)
- 플레이어 상호작용: 대화, 인터랙션 오브젝트, 박스 밀기, 1회성 이동, 덫, 탈출 등
- 게임 시스템: 스테미나, 아이템, 오브젝트 파괴, 시야 제한, 스테이지 전환
- UI·사운드 & 저장: 키/사운드 설정, 화면 UI·인벤토리·지도, JSON 기반 세이브/로드 시스템

## 🎮Win32 길찾기 알고리즘 프로젝트 [(상세보기)](https://github.com/Myoungcholho/JPS_Algorithm)

[![Video](https://img.youtube.com/vi/qD_K3rB_-tY/0.jpg)](https://www.youtube.com/watch?v=qD_K3rB_-tY)

> 개발 기간 : 2023.03.22 ~ 2023.04.03 (12일)
> 
> 
> *Win32 환경에서 A* 및 JPS 길찾기 알고리즘을 직접 구현하고,
> 
> 알고리즘 실행을 시각적으로 확인할 수 있도록 타일 기반 UI를 구축한 프로젝트입니다.
> 

### 🔧사용 기술 및 툴

- 언어 : C
- 환경 : Win32 API, Visual Studio 2022

### 📌담당 업무 및 경험

- 1인 개발
- A* 및 JPS 길찾기 알고리즘 구현
- 알고리즘 실행을 위한 타일 색칠·시각화 및 실행 기능 구현

## 🎮서버 개발 프로젝트 [(상세보기)](https://github.com/Myoungcholho/TCPFightServer)

> 개발 기간 : 2023.02.24 ~ 2023.03.06 (10일)
> 
> 
> *TCP 기반 통신 구조를 이해하고, 패킷 직렬화·역직렬화 모듈과
> 링버퍼 기반 패킷 처리 구조를 구현한 서버 사이드 프로젝트입니다.*
> 

### 🔧사용 기술 및 툴

- 언어 : C
- 환경 : Windows, Socket API, Visual Studio 2022
- 기타 : WireShark (패킷 캡처·분석)

### 📌담당 업무 및 경험

- 1인 개발
- TCP 통신용 경량 패킷 모듈 구현 (고정 버퍼 기반 << / >> 연산자 직렬화·역직렬화)
- 패킷 처리를 위한 링버퍼 자료구조 구현
- 패킷 헤더 파싱, 이동·공격·데미지 처리 및 브로드캐스트 기능
- 좌표 연타 등 비정상 입력 유효성 검증 로직 구현
