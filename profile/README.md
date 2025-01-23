## 저기어때: 대규모 트래픽 처리 숙박예약 서비스 👋
![image](https://github.com/user-attachments/assets/0beeb4fe-af12-4d6d-b418-42172234f01f)
- **프로젝트 주제**: 대규모 트래픽 처리 E-Commerce 프로젝트: **`저기 어때`**
- 사용자가 다양한 숙소를 검색하고 예약하며 결제를 완료할 수 있도록 지원하는 플랫폼
- MSA(마이크로서비스 아키텍처)를 통해 각 기능을 독립적으로 관리하며 확장성, 유연성, 그리고 장애 복구 능력을 높임
<br></br>

## 🙋 Contributors
스파르타 내일배움캠프 Spring 심화 2기 <br>
TEAM 10 저기어때
|팀장<br/> 백엔드| <br/>백엔드 | <br/>백엔드| <br/>백엔드 | <br/>백엔드 |
|:---:|:---:|:---:|:---:|:---:|
| 김성훈 | 강찬욱 | 김지수 | 문시원 | 조우석 |

<br></br>

## 👑 서비스/프로젝트 목표
<aside>

- **대규모 트래픽 대응**
    - MSA 아키텍처 도입으로 각 기능 독립 관리, 확장성 및 장애 복구 능력 강화
    - Redis와 Kafka를 활용하여 대규모 트래픽에 안정적으로 대응
    - 주요 API 처리량 200.0/sec 이상 달성
    - 동시성 문제 해결로 안전한 서비스 제공
    - MSA를 통해 각 기능을 독립적으로 관리하며 확장성, 유연성, 그리고 장애 복구 능력을 높임
</aside>

<aside>

- **모니터링 시스템 구축**
    - Prometheus, Grafana로 실시간 메트릭 모니터링으로 안정성 있는 프로젝트 구축
    - Loki로 알람 상황에 맞춰 설정 → 빠른 파악
</aside>


## 📄 주요 기능

<aside>
🏠

**숙소 예약 서비스**
- 숙소 정보 검색 및 숙박 날짜 예약
- 예약 시 쿠폰 및 포인트 적용
</aside>

<aside>
💰

**결제 서비스**
- 포트원 API 연동으로 결제 처리
- 결제 성공, 취소 상태 관리
</aside>

<aside>
💵

**포인트 서비스**
- 포인트 적립, 사용 및 자동 만료 처리
- Redis Cache 로 포인트 사용/적립/만료 내역 관리
</aside>

<aside>
🎫

**쿠폰 서비스**: **Redis 및 Kafka를 통한 비동기 쿠폰 발급, 동시성 처리**
- 대용량 트래픽을 수용하기 위한 비동기 쿠폰 발급
- Redis의 Lua Script로 동시성 제어 및 쿠폰 발급 상태 관리
- Kafka 를 활용한 실시간 이벤트 & 병렬 처리 (시간 및 수량 제한)
</aside>

<aside>
💻

**리뷰 서비스**

- 숙소 리뷰 관리 서비스
- S3 이미지 업로드
</aside>
<br></br>

## 🔨 Project Architecture
![image](https://github.com/user-attachments/assets/fba4bfc3-89dd-47e8-a50c-32fb3979df1a)
<br></br>

## 💿 Repositories
세부 기술은 각 레포지토리를 참고하세요
### Backend

<br></br>
### Submodule

## 🖥️ 적용 기술
![image](https://github.com/user-attachments/assets/fc653441-ba71-4c95-a0a9-84aba69b444e)
![image](https://github.com/user-attachments/assets/5dab00da-a819-43fd-b672-8470ef42a08c)

## 📑 Documents



<!--
**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
