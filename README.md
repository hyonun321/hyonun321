## 🔍 More About Me 

- [🖌️ Portfolio](https://hyonun321.github.io/2025_portfolio_1/)
- [✏️ 기술 블로그](https://velog.io/@hyonun)

 
## 🛠 Tech Stack

![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=Git&logoColor=white)



## 🏢 Experience
<details>
  <summary>
    네이버 부스트캠프 Web 9기 Front-End Engineer【24.8 ~ 24.12】 
  </summary>
  
> 2024 Naver Boostcamp Web Development Course

**주요 활동**:
- 웹 프로그래밍 심화 학습 및 실무 프로젝트 수행
- 팀 프로젝트를 통한 협업 경험 강화
- 코드 리뷰와 페어 프로그래밍을 통한 코드 품질 향상

## 💻 Projects

### Nocta - 실시간 동시편집 마크다운 에디터
> A real-time collaborative Markdown editor powered by CRDT

[🔗 Live Demo](https://nocta.site) | [📘 GitHub Repository](https://github.com/boostcampwm-2024/web33-Nocta)

![Nocta Preview](https://github.com/user-attachments/assets/05fef68a-1308-4953-9ecd-8f60cb0ab157)

**프로젝트 소개**:
실시간으로 여러 사용자가 동시에 마크다운 문서를 편집할 수 있는 웹 애플리케이션입니다. CRDT 알고리즘을 활용하여 동시성 문제를 해결하고, 실시간 협업 기능을 구현했습니다.

**담당 업무 및 성과**:
- [CRDT 라이브러리 설계 및 구현](https://velog.io/@hyonun/CRDT-%EA%B5%AC%ED%98%84-%EC%97%AC%EC%A0%95%EA%B8%B0-1-CRDT%EB%A5%BC-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B3%A0-%EA%B5%AC%ED%98%84%EB%B0%A9%EC%8B%9D%EC%9D%84-%EC%A0%95%ED%95%B4%EB%B3%B4%EC%9E%90)
  - RGA 기반 이중 링크드리스트로 CRDT 설계
  - EditorCRDT와 BlockCRDT 분리하여 확장성 부여
  - 기존 단일 CRDT에서 다중 분리 구조로 변경하여 텍스트 동기화 성능 개선
- [워크스페이스 실시간 상호작용 및 권한 관리 기능 개발](https://velog.io/@hyonun/Socket.io-Workspace-%EA%B5%AC%ED%98%84-%EC%97%AC%EC%A0%95%EA%B8%B0-1-%EA%B2%8C%EC%8A%A4%ED%8A%B8-%EC%9C%A0%EC%A0%80-Workspace-%EB%B6%84%EB%A6%AC%ED%99%94)
  - 사용자별 워크스페이스 접근 권한 시스템 설계 및 구현
  - WebSocket 기반 페이지별 실시간 다중 접속 관리 및 상태 동기화
  - Socket.io를 활용한 실시간 알림 시스템(Toast)으로 협업 경험 개선
- [개발위키 트러블슈팅 포함 40개 작성](https://abrupt-feta-9a9.notion.site/12a9ff1b21c380f2a490deae65256639?pvs=4)
- [Nocta Icon 로티 애니메이션 제작](https://abrupt-feta-9a9.notion.site/cb9b795665e940779ea2e57e1fe81776?pvs=4)
  
  ![nocta Day](https://github.com/user-attachments/assets/81ddb6a4-a280-4750-98c1-27bf46ef7688)
  - 디자인: 피그마
  - 애니메이션: Phase, Lotties
- [기술 시연 영상 제작](https://youtu.be/0AZAixGrMbo?si=qjJJbB8QWp_S4VL_)

**문제 해결 경험**:
- [다중 문서 캐럿 동기화 문제 해결](https://abrupt-feta-9a9.notion.site/ab1b87f31ec5459eb72f4241293fe8fa?pvs=4)
  - 여러 문서를 동시에 편집할 때 유저들의 캐럿이 의도치 않게 다른 위치로 이동하는 현상 발생
  - 해결 방법:
    - 글로벌 상태로 관리되는 캐럿 위치가 모든 문서에 영향을 미치는 것을 확인
    - 문서별로 독립적인 캐럿 상태 관리의 필요성 도출
    - 로컬상태에서 페이지별 독립 캐럿 상태 관리 시스템 구현(setCaretPosition)
  - 결과:
    - 실시간 다중 사용자 편집 시에도 일관된 사용자 경험 제공

- [실시간 동시편집 성능 최적화](https://abrupt-feta-9a9.notion.site/CRDT-d96629bf4f3045209508e5f3f55d8f36?pvs=4)
  - 다수 사용자의 동시 입력 시 과도한 소켓 통신으로 인한 서버 부하 발생
  - 과도한 통신량으로 인한 실시간 동기화 지연 및 동기화 누락 현상 발생
  - 해결 방법:
    - 사용자 입력 패턴 분석 (평균 0.5초당 3회 타이핑) 기반 배치 처리 도입
  - 결과:
    - 초당 소켓 통신량 70% 감소로 서버 리소스 효율화
    - 네트워크 대역폭 사용량 최적화로 안정적인 동기화 성능 확보

</details>
<details>
  <summary>
    LG유플러스 유레카 2기 Front-End 과정【25.1 ~ 25.8】 
  </summary>

  
  > 2025 LG Uplus Ureca Front-end Course

**주요 활동**:
- 웹 아키텍처 기본 및 웹 보안 기초 교육
- 코딩테스트 및 자바 기본역량 
- 코드 리뷰와 페어 프로그래밍을 통한 코드 품질 향상


## 💻 Projects

### Doss! - 웹뷰 기반 주식 정보 열람 서비스
> Mobile-View Stock Web Service

[📘 GitHub Repository](https://github.com/hyonun321/toss_copy)

🔗[Video](https://youtu.be/vD-YFp99zmY?si=hNS5s9xW3LVr1I0m)

**프로젝트 소개**:
앱처럼 동작하는 모바일뷰 기반 주식확인 증권 웹 서비스

![1-ezgif com-speed](https://github.com/user-attachments/assets/6ff69ebf-d04a-4fdf-95ce-c4d856097de5)


**담당 업무**:
- Figma를 통해 컴포넌트 및 전체 유저시나리오 워크 플로우 디자인
- Nextjs- App router 를 통한 페이지 라우팅
- 앱 디자인 컴포저블 UI 형식으로 화면 설계
- 디바운싱 & 엘라스틱 서치를 통한 주식정보 조회 (국내, 미국 총 6000개 추가)
- Backend 연동하여 한국투자증권 실시간 주식(국내,미국) 정보 조회 기능 구현
- 시연 영상 제작 (Adobe Premiere Pro)

</details>



<p align="left"> <img src="https://komarev.com/ghpvc/?username=hyonun321&label=Profile%20views&color=0e75b6&style=flat" alt="hyonun321" /> </p>
