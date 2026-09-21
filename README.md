# 이도훈

안녕하세요, 이도훈입니다.
서비스를 직접 만들고, 배포와 운영까지 이어가는 개발자를 목표로 하고 있습니다.
해양컴퓨터공학을 전공했고, AI 서비스 개발과 클라우드·인프라를 공부하며 팀 프로젝트와 개인 서버 운영을 경험했습니다.

## 교육

| 과정 | 기간 | 배운 내용 |
|---|---|---|
| KT 에이블스쿨 9기 AI 트랙 | 2026.03.31~09.03 | Python·데이터 분석·AI 모델링, LLM 서비스 개발·클라우드 배포 |
| 광주인공지능사관학교 6기 · 자연어처리 | 2025.06.02~12.12 | 머신러닝·딥러닝·자연어처리·Transformer·LLM 활용 |
| 광주·전남 데이터센터 전문인력 양성 | 2025.09.15~09.26 | 데이터센터 운영·네트워크·클라우드, 가상화·Docker·AWS 실습 |

## 프로젝트에서 사용한 기술

- **백엔드:** Python · FastAPI · PostgreSQL
- **클라우드·배포:** AWS EKS/ECR · GCP Compute Engine · Docker · Kubernetes · GitHub Actions · CodeBuild
- **프런트엔드:** TypeScript · React · Next.js

## 대표 프로젝트

### [AI’s EYE · 매장 운영 지원 서비스](https://github.com/owlooo/ai-s-eye)
영상 분석 결과와 주문 데이터를 모아 매장 상황을 살펴보고, 직원 수에 따른 운영안을 비교하는 서비스입니다.

5인 팀의 팀장을 맡았습니다. 백엔드와 운영 분석 기능을 만들면서 팀원들이 개발한 영상 분석·대시보드·챗봇을 연결하고, 미니PC와 GCP의 배포 환경을 맡았습니다.

KT AIVLE Big Project Collaboration 수상 · 2026.09.03

### [BookShelf · AWS EKS 배포](https://github.com/owlooo/aws-eks-cicd-book-service)
팀에서 만든 도서 관리 서비스를 AWS EKS에 배포하는 프로젝트입니다.

Docker 이미지와 개발·운영 환경의 배포 설정을 맡았습니다. Pod가 늘어날 때 DB 연결도 함께 늘어나는 점을 고려해 HPA 상한을 조정했습니다.

### [ManuAI-talk · 제품 매뉴얼 AI 상담](https://github.com/owlooo/manuai-talk)
제품 매뉴얼을 찾아 읽는 대신 질문으로 필요한 내용을 확인할 수 있는 서비스입니다.

6인 팀에서 프런트엔드를 주로 맡아 채팅과 음성 입출력을 연결했습니다. 제품 선택부터 QR·AR을 거쳐 상담 화면으로 이어지는 부분도 작업했습니다.

광주인공지능사관학교 우수상 · 2025.12.11

[CStudy · AI 기반 CS 학습 서비스](https://github.com/aischool-cstudy/aiplus-cstudy)에서는 학습·실습 화면과 AI 사용량 모니터링을 만들고, DB 저장 오류를 수정했습니다.

## 개인 서버

프로젝트 밖에서도 Docker로 서비스를 올리고 모니터링과 백업 환경을 직접 다뤄 왔습니다.
접속 문제가 생겼을 때는 앱·컨테이너·프록시·DNS를 나눠 살펴보고, 원인과 복구 과정을 기록했습니다.
