# 🎮 LearningUE  
> Unity 개발자의 시선으로 배우는 Unreal Engine 5

안녕하세요!  
저는 **Unity를 오래 사용해온 개발자**이며, 현재는 **Unreal Engine 프로젝트**로 이직/전환배치를 준비하면서 학습 내용을 정리하고 있습니다.  
이 저장소는 **C# → C++/Blueprint 관점 차이**를 코드 중심으로 기록한 학습 아카이브입니다.  

---

## 📌 목적
- Unity 개발자가 UE로 넘어갈 때 **헷갈리는 포인트**를 정리
- **로우레벨 코드와 BP 위젯**을 병행 학습
- 포트폴리오 + 스터디 공유용

---

## 🛠 환경
- **Unreal Engine 5.6**
- **Rider 2025**
- Layout : **UE4 Classic**
- OS : Windows 11

---

## 📂 주요 내용
- [메인 메뉴 만들기](https://www.notion.so/2709a52ec8ca8053bd48c4927c2dd353?pvs=21)  
  - UI 위젯 생성 및 배치
  - PlayerController 연결
  - 입력 모드 전환 (UI ↔ Game)
  - ESC로 메뉴 토글

- [Q&A 정리](https://www.notion.so/Q-A-2709a52ec8ca8000b010d74f897a700e?pvs=21)  
  - Unity와의 개념 차이
  - 라이브 코딩 vs 전체 컴파일
  - Public/Private 소스 구조

---

## 🧩 Unity → Unreal 대응표 (간단 버전)
| Unity | Unreal |
|-------|--------|
| `GameObject` | `Actor` |
| `MonoBehaviour` | `ActorComponent` / `UObject` |
| `Canvas / UI` | `UMG Widget` |
| `Input System (Action Map)` | `Enhanced Input` |
| `DontDestroyOnLoad` | `GameInstance` |

---

## 🚀 앞으로 추가할 내용 (계속 업데이트 예정)

### 🔧 언리얼 기초
- 라이브 코딩이란? (Live Coding vs 전체 빌드)
- Public / Private 소스 구조 차이
- PlayerController / GameMode / GameInstance 개념
- UCLASS / UPROPERTY / UFUNCTION (리플렉션과 generated.h)

### 🎨 UI & UX
- ESC로 메뉴 토글하기
- 옵션(설정) 메뉴 만들기
- 인게임 HUD (체력바, 미션 표시)
- 폰트/Localization 적용
- 애니메이션과 사운드 피드백 추가

### 🕹 입력 시스템
- Enhanced Input 소개
- 액션/축 매핑 구현
- 패드/키보드/마우스 동시 지원
- Unity Input System과 비교

### 🤖 게임플레이 로직
- 탕탕특공대 스타일 캐릭터 스폰/컨트롤
- 무기 시스템 (총알 발사, 재장전)
- 적 AI (간단한 추적/공격)
- Wave Spawner 구현

### 🌍 레벨 & 환경
- 레벨 전환 (메뉴 ↔ 인게임)
- 기본 맵 구조와 Streaming
- 라이트/포스트프로세싱 셋업
- NavMesh와 AI 이동

### 🔊 사운드 & 이펙트
- SoundCue / SoundClass 기초
- 총소리 / 폭발 / UI 사운드 추가
- Particle System (Niagara) 적용
- Wwise 연동 (심화)

### 📦 데이터 & 최적화
- DataTable / DataAsset 활용
- 객체 풀링 (Object Pool)
- Garbage Collection / 스마트 포인터
- 프로파일링 툴 사용법

### 🌐 멀티플레이 기초
- Replication 이해
- RPC (Server, Client 함수)
- PlayerState / GameState 개념
- 간단한 룸/로비 구현

---

## 🎯 탕탕특공대를 만들면서 배우는 UE5
이 프로젝트는 단순 샘플을 넘어서,  
**탕탕특공대(총 쏘고, 달리고, 웨이브 깨는 게임)** 를 직접 구현하면서  
UE5의 핵심 개념들을 단계별로 익히는 학습 여정입니다.

카테고리는 아래와 같이 확장됩니다:

1. **UI/메뉴 시스템** → 메인 메뉴, 옵션, HUD  
2. **플레이어 조작** → 이동, 발사, 입력 시스템  
3. **게임플레이** → 무기, 적 AI, Wave, 점수 시스템  
4. **레벨 디자인** → 환경 구성, 빛, 카메라  
5. **피드백 요소** → 사운드, VFX, 애니메이션  
6. **멀티플레이 확장** → 네트워크, 로비, 협동 플레이  

### ⚡ 심화 기능 (확장 예정)
- **실시간 랭킹 구현하기**
  - 온라인/오프라인 점수 저장
  - 서버 연동 or 로컬 DB
- **캐릭터 스킬 만들기**
  - 액티브 스킬 (예: 범위 공격, 버프)
  - 패시브 스킬 (공격 속도, 체력 증가)
- **캐릭터 스킬 테이블**
  - DataTable 기반 스킬 정의
  - 쿨타임, 데미지, 이펙트 설정
- **Quick Chat 만들기**
  - 사전 정의 메시지 전송
  - 멀티플레이어에서 텍스트/이모티콘 표시

---


## 📜 License
MIT License  

---

## 📧 Contact
- GitHub Issues 환영 🙌  
- cake@kakao.com
