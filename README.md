# 🧑‍💻 재윤의 GitHub 🌈


## 경력 🚀
**2019년 6월 ~ ING**  
- [25.01 ~ ING][Back-End] SpringBoot + Kotlin 이용한 Kooky(앱/웹),어드민 백엔드및 Db 전담, AWS 클라우드 전담
- [22.10 ~ 24.09][App]GSSHOP 앱 개발 /운영 (전시 영역 - 생방송 영역,채팅,카테고리,메인 매장)
- [21.10 ~ 22.09][Back-End]GS 내부 대시보드 개발/운영 (통계 및 차트,공통 API 개발, 개발/운영계 구축 및 배포 담당)
- [20.11 ~ 21.09][Back-End]GS 어바웃펫 개발/운영(회원,포인트,공통 API 및 배포 담당)
- [20.03 ~ 20.11][Back-End]삼성닷컴 개발(회원,배송카트리지 API 개발 )
- [19.07 ~ 19.12][Back-End]서울 시청 음성 인식 회의록 웹 플랫폼 개발

---

## 🎤 현재 — Kooky · 글로벌 K-pop 플랫폼 Backend (2025.01 ~)
> Kotlin/Spring Boot 기반 결제·구독·커머스·투표·펀딩 도메인 개발 및 AWS 운영.

### 주요 업무
- 결제·구독(IAP), 커머스, 투표, 펀딩 등 핵심 도메인 개발 및 운영
- AWS ECS 운영 · GitHub Actions 기반 CI/CD 구성
- Redis/MySQL 기반 성능 개선, 동시성 제어, 운영 안정화

### 🤖 AI 활용 — 개발 파이프라인 자동화 (Claude Code 커스텀 스킬 15종+)
- 기획 → 구현 → 리뷰 → 배포 → 운영 전 과정을 커스텀 스킬로 자동화 (Notion/Jira/GitHub/Slack 연계)
- 구현 모델(Claude)과 리뷰 모델(Codex)을 분리한 **교차 모델 코드 리뷰**로 단일 모델 편향 감소
- git worktree 형상 분리 + Detekt + 변경 전후 비교까지 자동화, 코드 작성 전 confirm으로 오구현 방지
- LLM의 추측·환각·컨텍스트 유실을 줄이는 검증 중심 워크플로 + 모든 작업의 Markdown 산출물화로 추적성·재현성 확보

### 🏆 주요 성과
| 영역 | 요약 | 설계 |
|---|---|---|
| 멀티 PG 결제·구독 | Apple/Google IAP + Toss/Stripe, SQS 비동기·FIFO 멱등으로 재화 이중 지급 방지 | [Shop 결제 플로우](https://app.notion.com/p/Shop-38e6de4f49108041bb79faf5e5b53505?source=copy_link) |
| 플래시 세일 동시성 | DB Row Lock → Redis + Lua 원자 연산, 운영 2,441개 옵션 재고 정합성 + 회귀 테스트 | [Shop 결제 플로우](https://app.notion.com/p/Shop-38e6de4f49108041bb79faf5e5b53505?source=copy_link) |
| 홈 API 성능 | Coroutine 병렬 + Redis 캐시 — 7~ 9초 → p50 63ms (약 110~140배, APM 실측) | — |
| 실시간 투표 | Redis INCR + Lua 실시간 카운터, Race Condition 제거 + Throttling 중복 방지 | [투표 플로우](https://app.notion.com/p/38e6de4f4910806685fcf305146c66e3?source=copy_link) |
| 인증·보안 | JWT Access/Refresh + Hexagonal RefreshToken 저장소 분리, APP/WEB 세션 분리, 로그인 실패·IP 차단 | [인증 플로우(토큰·로그인·이메일)](https://app.notion.com/p/38e6de4f491080358abfc900464bbc0d?source=copy_link) |
| 운영 아키텍처 | Kafka → SQS 재정립(무중단 전환), 멀티모듈 SQS Listener 분리 | — |
| 운영·품질 | Datadog·SignOz 모니터링, OTel 데몬 중계, Read/Write 분리·파티셔닝·Heap 튜닝 | — |
| E2E 자동화 | Playwright로 실제 API·프런트 이미지 기동 E2E + Fastify/React 대시보드 | — |

### 기술 스택
`Kotlin` · `Spring Boot` · `Spring Security` · `JPA(Hibernate)` · `MySQL` · `Redis(Lua)` · `AWS ECS/EC2/SQS` · `GitHub Actions` · `Datadog` · `SignOz` · `Firebase` · `Liquibase`

---

## 🏆 주요 업무 및 포지션
> 제가 맡아온 주요 역할과 업무들입니다.  

- **백엔드 개발 및 서버배포**: Spring 기반(SpringBoot,SpringFramework) 백엔드 개발(이커머스 - 회원,포인트,쿠폰) , Bamboo 이용한 서버 배포 및 설정
- **앱 CI/CD 구축 및 자동화**: Jenkins, Python, Fastlane, AWS 활용한 앱 배포 자동화  ( https://www.notion.so/GSSHOP-CI-CD-1436de4f49108013a9a3efd2ad2b4e7f?pvs=4 )
- **앱 개발**: Flutter를 이용한 크로스 플랫폼 모바일 앱 개발

---

## 📚 Tech
> 주로 사용하는 기술 스택

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)  
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)  
![Spring Framework](https://img.shields.io/badge/SpringFramework-6DB33F?style=for-the-badge&logo=spring&logoColor=white)  
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)  
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)  

---

## 🗄️ DataBase
> 프로젝트에 사용했던 데이터베이스들입니다.  

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)  
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)  
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)  
![Aurora](https://img.shields.io/badge/Aurora-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)  
![Redshift](https://img.shields.io/badge/Redshift-8C4FF0?style=for-the-badge&logo=amazonredshift&logoColor=white)

---

## ☁️ AWS
> 프로젝트에서 활용한 AWS 서비스들입니다.  

![EC2](https://img.shields.io/badge/EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white)  
![S3](https://img.shields.io/badge/S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)  
![API Gateway](https://img.shields.io/badge/API_Gateway-FF4F8B?style=for-the-badge&logo=amazonapigateway&logoColor=white)  
![CloudFront](https://img.shields.io/badge/CloudFront-30597F?style=for-the-badge&logo=amazoncloudfront&logoColor=white)  
![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)  

---

## 💻 그외 Tech
> 프로젝트에 활용해 본 주요 언어들입니다.  

![EgovFramework](https://img.shields.io/badge/EgovFramework-1572B6?style=for-the-badge&logo=java&logoColor=white)
![PHP (CodeIgniter)](https://img.shields.io/badge/PHP(CodeIgniter)-777BB4?style=for-the-badge&logo=php&logoColor=white)  

---

## 🛠️ Etc
> 개발에 사용한 도구들!  

![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)  
![Fastlane](https://img.shields.io/badge/Fastlane-4682B4?style=for-the-badge&logo=fastlane&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)  
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)  
![SVN](https://img.shields.io/badge/Subversion-809CC9?style=for-the-badge&logo=subversion&logoColor=white)  

---

## 🧰 Tools
> 협업과 모니터링에 사용했던 도구들!  

![Bamboo](https://img.shields.io/badge/Bamboo-0052CC?style=for-the-badge&logo=bamboo&logoColor=white)  
![Bitbucket](https://img.shields.io/badge/Bitbucket-0052CC?style=for-the-badge&logo=bitbucket&logoColor=white)  
![Jira](https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white)  
![Redmine](https://img.shields.io/badge/Redmine-B32024?style=for-the-badge&logo=redmine&logoColor=white)  
![Datadog](https://img.shields.io/badge/Datadog-632CA6?style=for-the-badge&logo=datadog&logoColor=white)  
![ElasticSearch](https://img.shields.io/badge/ElasticSearch-005571?style=for-the-badge&logo=elasticsearch&logoColor=white)  

---

🌈 **감사합니다**  


