# Hi, I'm melody3212 👋

**데이터 분석 · IoT/임베디드 · 프론트엔드**를 잇는 구현형 포트폴리오입니다.  
문제를 데이터로 정의하고, 하드웨어·소프트웨어로 동작하는 결과물까지 만드는 경험을 쌓아 왔습니다.

> 이 프로필 README는 **제출용 포트폴리오 요약**입니다.  
> 상세 코드·문서는 아래 각 레포 링크에서 확인할 수 있습니다.

---

## Awards

| 프로젝트 | 성과 |
|----------|------|
| **[PuriSound](https://github.com/melody3212/PuriSound)** | **LG전자 DX School 최우수상** |
| **[NowRescue](https://github.com/melody3212/NowRescue)** | **2025 We-Meet 바이오헬스 부문 교육부장관상** |

---

## About

- **관심 영역**: VOC/센서 데이터 분석, 엣지 디바이스(Raspberry Pi · ESP32), 웹 프론트엔드  
- **일하는 방식**: 팀에서 역할을 명확히 나누고, 맡은 영역을 끝까지 책임  
- **강점**: 분석 실험 ↔ 현장 디바이스 ↔ 사용자 화면을 **한 줄로 연결**하는 경험  

---

## Featured Projects

### 1. [PuriSound](https://github.com/melody3212/PuriSound) — *대표 프로젝트*
**LG DX School** · 생활 밀착형 스마트 소음 케어  
🏆 **LG전자 DX School 최우수상**

#### 무엇을 만들었나
층간·생활 소음 VOC를 분석해 서비스 방향을 잡고,  
**Raspberry Pi**에서 실시간 감지 → 마스킹 사운드 재생 → LED 피드백 → Firebase·앱 연동까지 이어지는 파이프라인을 구현했습니다.

| 구분 | 내용 |
|------|------|
| **문제** | 소음을 완전히 없애기 어렵고, 대면·게시판 갈등으로 이어지기 쉬운 생활 환경 |
| **접근** | VOC 기반 액터·모드 기획 + 디바이스의 **맞춤 대응 사운드·자동 개입** |
| **한 줄 구조** | 마이크 → FFT(+YAMNet) → 마스킹 결정 → 재생/LED → Firebase · 앱 설정 폴링 |
| **데이터** | VOC 약 7만 건 규모 수집·분석 파이프라인 (팀 전체 채널 협업) |

#### My Contribution
- **크롤링**: 네이버 카페, 지식인 VOC 수집  
- **Raspberry Pi 전체 담당**: 마이크 입력, FFT 기반 분석, 마스킹 결정, 음원 재생, LED, Firebase 연동, 운영 프로세스(서비스·폴더 구조) 전반  
- 디바이스가 **앱 설정과 맞물려 동작**하도록 엣지 쪽 파이프라인 책임

#### Stack
`Python` · `Raspberry Pi` · `FFT` · `YAMNet` · `Firebase` · `Flutter`(프로토타입)

👉 레포: [github.com/melody3212/PuriSound](https://github.com/melody3212/PuriSound)

---

### 2. [KForest_AI](https://github.com/melody3212/KForest_AI)
**산림청 AI 경진대회** · 생태통로 설치 관련 분석 제출

#### 무엇을 했나
생태통로 입지·정책 의사결정을 돕기 위한 **데이터 분석·모델링 실험**을 팀 단위로 수행했습니다.

#### My Contribution
- **분석 전 과정에 참여** (전처리 → 모델링 → 비교·검증 흐름)  
- 팀원과 **경우의 수를 나누어** 실험 설계  
- 전 과정에서 **모델을 바꿔 가며** 학습·평가를 반복하고 결과 비교  

#### Stack
`Python` · 데이터 분석 · ML 실험

👉 레포: [github.com/melody3212/KForest_AI](https://github.com/melody3212/KForest_AI)

---

### 3. [NowRescue](https://github.com/melody3212/NowRescue)
**ESP32 기반 낙상 알림 시스템**  
🏆 **2025 We-Meet 바이오헬스 부문 교육부장관상**

#### 무엇을 만들었나
낙상 상황을 감지하고 알림으로 연결하는 **임베디드 중심 바이오헬스** 프로젝트입니다.

#### My Contribution
- 현재 레포에 올라와 있는 **코드 영역 전반에 참여**  
- 기획·현장 멘토링 등 비코드 영역은 팀원 역할 비중이 컸음  

#### Note
추가 자료(데모·기획 문서 등) 업로드 후 상세 소개를 보강할 예정입니다.  
수상 이력과 코드 참여 범위는 위에 명시된 내용이 기준입니다.

#### Stack
`ESP32` · `Python` · 임베디드 · 알림 연동

👉 레포: [github.com/melody3212/NowRescue](https://github.com/melody3212/NowRescue)

---

### 4. [REHAB](https://github.com/melody3212/REHAB)
재활·헬스케어 서비스 **프론트엔드**

#### 무엇을 했나
사용자가 직접 다루는 화면과 흐름을 중심으로 한 웹 프론트엔드를 담당했습니다.

#### My Contribution
- **프론트엔드 전담**: UI 구성, 사용자 흐름, 화면 구현  
- 백엔드·기획과 맞춰 서비스가 실제로 쓰이는 형태로 연결

#### Stack
`JavaScript` · 웹 프론트엔드

👉 레포: [github.com/melody3212/REHAB](https://github.com/melody3212/REHAB)

---

## Project map (한눈에)

| 프로젝트 | 한 줄 | 내 역할 | 성과 |
|----------|--------|---------|------|
| [PuriSound](https://github.com/melody3212/PuriSound) | 소음 감지·마스킹 IoT 파이프라인 | 카페·지식인 크롤링 + **Pi 전체** | LG DX School **최우수상** |
| [KForest_AI](https://github.com/melody3212/KForest_AI) | 생태통로 AI 분석 | 전 과정 분석·모델 실험 분담 | 산림청 AI 경진 제출 |
| [NowRescue](https://github.com/melody3212/NowRescue) | ESP32 낙상 알림 | 코드 전반 참여 | We-Meet 바이오헬스 **교육부장관상** |
| [REHAB](https://github.com/melody3212/REHAB) | 재활 서비스 웹 | **프론트엔드** | — |

---

## How to navigate this portfolio

1. **이 프로필**에서 역할·성과 파악  
2. 대표작 **[PuriSound](https://github.com/melody3212/PuriSound)** README·코드 구조 확인  
3. 관심 영역별로 [KForest_AI](https://github.com/melody3212/KForest_AI)(분석) · [REHAB](https://github.com/melody3212/REHAB)(프론트) · [NowRescue](https://github.com/melody3212/NowRescue)(임베디드) 순회  

---

## Contact / Links

- GitHub: [github.com/melody3212](https://github.com/melody3212)  
- Projects: [PuriSound](https://github.com/melody3212/PuriSound) · [KForest_AI](https://github.com/melody3212/KForest_AI) · [NowRescue](https://github.com/melody3212/NowRescue) · [REHAB](https://github.com/melody3212/REHAB)

---

<sub>제출용 프로필 README · 프로젝트별 상세는 각 저장소에서 확인하세요.</sub>
