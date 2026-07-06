# genai-coding
GnAI driven coding

## 🛠️ 기술 스택 (Tech Stack)
### 백엔드 (Back-end)
 * **언어 및 프레임워크:** Kotlin / Spring Boot (기반)
 * **데이터베이스:** PostgreSQL (pg)
### 프론트엔드 (Front-end)
 * **명칭:** integrated-host
 * **아키텍처:** Micro Frontends (MFE)
 * **라이브러리:** React

## 🤖 Claude AI 기반 개발 및 코딩 컨벤션
본 프로젝트는 Claude의 코드를 기준으로 작성되었으며, AI와의 효율적인 협업 및 일관성 있는 코드 생성을 위해 각 레이어별로 claude.md 규칙을 정의하고 있습니다.
### 1. 루트 컨벤션 (./claude.md)
 * 전체 프로젝트의 통합 설계 방향성과 AI 프롬프트 가이드라인을 포함합니다.
 * 전역 도메인 모델 정의 및 공통 아키텍처 원칙을 서술합니다.
### 2. 백엔드 컨벤션 (./{back-end}/claude.md)
 * Kotlin 기반 코드 생성 시 Claude가 준수해야 할 정적 타이핑, Null-Safety, 객체 지향 및 함수형 패러다임 규칙을 정의합니다.
 * JPA/Exposed 등 PostgreSQL 연동을 위한 데이터 매핑 컨벤션을 포함합니다.
## 📄 설계 및 산출물 문서 (./{back-end}/docs/)
백엔드 폴더 하위의 docs/ 디렉토리에는 시스템의 뼈대가 되는 설계 자산이 포함되어 있습니다.
 * **클래스 다이어그램:** 도메인 핵심 객체 간의 관계와 비즈니스 로직의 구조를 시각화합니다.
 * **와이어프레임 (HTML 기준):** 화면 구조 및 사용자의 인터랙션 흐름을 HTML 프로토타입 기준으로 정의하여 프론트엔드 개발 및 AI 코드 생성의 기준점으로 활용합니다.
 
