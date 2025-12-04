# 자기 소개

저는 성능과 프레임 단위에서 느껴지는 플레이 감각을 중시합니다.

DirectX11 기반 엔진에서 리소스 로딩 시간을 58초에서 8초로 단축했고,  
인스턴싱을 도입해 렌더링 성능을 40.9 FPS에서 112.1 FPS(약 174% 향상)까지 개선한 경험이 있습니다.

어려운 문제를 마주하면 여러 가설을 세우고 끝까지 추적해 해결하는 편입니다.  
이 과정에서 얻어지는 이해와 경험이 비로소 제 것이 된다고 믿기 때문에,  
문제를 피하기보다 원인 단위로 파고드는 태도를 중요하게 생각합니다.

팀 프로젝트에서는 팀장으로서 팀원 간 소통을 돕고, 역할 분담과 일정 조율을 맡았습니다.  
그 과정에서 의견을 조율하고 팀이 같은 방향을 바라보도록 이끄는 역량을 키웠습니다.


# 프로젝트

## 🎮 DX11 자체 엔진 프로젝트 [(상세보기)](https://github.com/Myoungcholho/DX_Portfolio/tree/main)

**개발 기간** | 2025.05 ~ 2025.10 (156일)  
**개발 인원** | 1인  

### 대표 미리보기
> 언리얼 아키텍처, 렌더링 파이프라인, 애니메이션 시스템, 인스턴싱, 멀티스레드 구조를 구현한 DX11 기반 자체 엔진 프로젝트입니다.
<p align="center">
  <img
    width="800"
    src="https://github.com/user-attachments/assets/dffc2176-d743-4aae-90b8-446c3935ae4a"
    alt="DirectX 11 Engine Editor Screenshot" />
</p>

### 🔧사용 기술 및 툴

- 언어 : C++, HLSL
- 엔진/그래픽스 : DirectX11, SimpleMath
- 에디터/UI : ImGui Docking
- 디버깅/툴링 : RenderDoc, Deleaker, IBLMaker
- 에셋 처리 : Assimp
- IDE : Visual Studio 2022

### 📌핵심 기술 구현 내용

- GT/RT MailBox 기반 스냅샷 소비 모델 렌더링 코어 아키텍처 구축
- Actor / Component / SceneComponent 기반 월드 객체 구조 & Transform 시스템 설계
- 렌더링 파이프라인 구축
- Instancing 및 GPU 드로우콜 최적화
- 스켈레탈 애니메이션 시스템
- FBX Import Pipeline 및 Asset / Resource Manager 개발
- ImGui Docking 기반 에디터 & 툴링 시스템
- CPU/GPU 프로파일링 시스템 구현 및 프레임 드랍 원인 분석

</br></br>

## 🎮서버 개발 프로젝트 [(상세보기)](https://github.com/Myoungcholho/TCPFightServer)

**개발 기간** | 개발 기간 : 2023.02 ~ 2023.03 (40일)  
**개발 인원** | 1인  

### 대표 미리보기
> TCP 기반 통신 구조를 이해하고, 패킷 직렬화·역직렬화 모듈과 링버퍼 기반 패킷 처리 구조를 구현한 서버 사이드 프로젝트입니다.
<p align="center">
  <img
    width="800"
    src="https://github.com/user-attachments/assets/fa86d4bc-949f-45dd-81ea-27795a1911d1"
    alt="Server"
    style="pointer-events: none;"/>
</p>

### 🔧사용 기술 및 툴

- 언어 : C
- 환경 : Windows, Socket API, Visual Studio 2022
- 기타 : WireShark (패킷 캡처·분석)

### 📌담당 업무 및 경험

- TCP 통신용 경량 패킷 모듈 구현 (고정 버퍼 기반 << / >> 연산자 직렬화·역직렬화)
- 패킷 처리를 위한 링버퍼 자료구조 구현
- 패킷 헤더 파싱, 이동·공격·데미지 처리 및 브로드캐스트 기능
- 좌표 연타 등 비정상 입력 유효성 검증 로직 구현

</br></br>

## 🎮언리얼 3D 액션 게임 프로젝트 [(상세보기)](https://github.com/Myoungcholho/UnrealPortfolioSource/tree/master)

**개발 기간** | 2025.01.06 ~ 2025.04.02 (87일)  
**개발 인원** | 1인  

### 대표 미리보기
> 언리얼 엔진 기반 3D 액션 RPG로, 캐릭터·전투·AI·UI 등 핵심 게임플레이 시스템을 1인 개발로 구현한 프로젝트입니다.
<p align="center">
  <img
    width="800"
    src="https://github.com/user-attachments/assets/19a7d879-6a57-4b4d-961b-5254333bce36"
    alt="Unreal" />
</p>

### 🔧사용 기술 및 툴

- 언어 : C++
- 엔진 : Unreal Engine 5, Blueprint

### 📌담당 업무 및 경험

- 캐릭터 & 전투 시스템: 상태/무기/스테미나/피격/처형 로직 구현
- 아이템 & 인벤토리: 드랍·획득·사용 및 슬롯/인벤토리 구조 설계
- UI 시스템(MVVM): 체력/스테미나/아이템 슬롯 UI 및 데이터 바인딩 구조 구현
- AI & 전투 시스템: 적 계층 구조, 중앙 토큰 기반 전투 관리, 상태 머신 구현

</br></br>

## 🎮Unity3D 액션 게임 프로젝트 [(상세보기)](https://github.com/Myoungcholho/3D_Portfolio)

**개발 기간** | 2024.06.26 ~ 2024.11.04 (131일)  
**개발 인원** | 1인  

### 대표 미리보기
> Unity 기반 3D 액션 게임으로, 플레이어·전투·AI·UI 등 핵심 게임플레이 시스템을 1인 개발로 구현한 프로젝트입니다.
<p align="center">
  <img
    width="800"
    src="https://github.com/user-attachments/assets/ec6bebb4-e8f3-49d5-bb1b-de41042f192e"
    alt="Unity3D" />
</p>

### 🔧사용 기술 및 툴

- 언어 : C#
- 엔진 : Unity

### 📌담당 업무 및 경험

- 플레이어 & 전투 시스템: 이동, 근·원거리/듀얼 무기, 스킬, 저스트 회피, 암살, 잔상, 슬로우 연출
- AI & 보스 전투: 전투 패턴, 등장/사망 연출, 시네마틱 연계
- UI & 상호작용: 스테미너·스킬 UI, NPC/대화·퀘스트, 타겟팅 데미지 폰트, 카메라 연출

</br></br>

## 🎮Unity2D 퍼즐 게임 개발 프로젝트 [(상세보기)](https://github.com/Myoungcholho/2DGame_JonsIsland)

**개발 기간** | 2023.04.11 ~ 2023.10.11 (184일)  
**개발 인원** | 5인 개발 – 팀장 역할(코어 기능 기획, 역할 분배 및 작업 관리)  

### 대표 미리보기
> Unity 기반 2D 퍼즐 게임으로, 팀장으로 참여해 코어 기획부터 플레이어 상호작용, 게임 시스템, UI·저장까지 전반을 담당한 프로젝트입니다.
<p align="center">
  <img
    width="800"
    src="https://github.com/user-attachments/assets/c9d4e36b-e065-4732-8626-eded706918ba"
    alt="Unity2D" />
</p>

### 🔧사용 기술 및 툴

- 언어 : C#
- 엔진 : Unity

### 📌담당 업무 및 경험

- 플레이어 상호작용: 대화, 인터랙션 오브젝트, 박스 밀기, 1회성 이동, 덫, 탈출 등
- 게임 시스템: 스테미나, 아이템, 오브젝트 파괴, 시야 제한, 스테이지 전환
- UI·사운드 & 저장: 키/사운드 설정, 화면 UI·인벤토리·지도, JSON 기반 세이브/로드 시스템

</br></br>

## 🎮Win32 길찾기 알고리즘 프로젝트 [(상세보기)](https://github.com/Myoungcholho/JPS_Algorithm)

**개발 기간** | 2023.03.22 ~ 2023.04.03 (12일)  
**개발 인원** | 1인  

### 대표 미리보기
> Win32 환경에서 A 및 JPS 길찾기 알고리즘을 직접 구현하고 알고리즘 실행을 시각적으로 확인할 수 있도록 타일 기반 UI를 구축한 프로젝트입니다.
<p align="center">
  <img
    width="800"
    src="https://github.com/user-attachments/assets/3b6c3139-b4d0-4037-8176-a2af6bdd9d6d"
    alt="Algorithm" />
</p>

### 🔧사용 기술 및 툴

- 언어 : C
- 환경 : Win32 API, Visual Studio 2022

### 📌담당 업무 및 경험

- A* 및 JPS 길찾기 알고리즘 구현
- 알고리즘 실행을 위한 타일 색칠·시각화 및 실행 기능 구현
