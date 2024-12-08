# dividend-tracker

미국 주식 배당금 정보를 제공하는 API 서비스


---

## 📋 서비스 소개

**dividend-tracker**는 미국 주식의 배당금 정보를 스크래핑하여 사용자에게 제공하는 API 서비스입니다.  
이 프로젝트는 사용자별 데이터를 관리하고 예상 배당금을 계산하여 개인화된 서비스를 제공합니다.

---

## 🚀 주요 기능

- 스크래핑 기법을 활용하여 데이터를 추출/저장
- 사용자 데이터를 관리하고 배당금 계산 API 구현
- Spring Boot로 프로젝트를 설정하고 H2 및 Redis 연동
- 데이터 모델링 및 JPA 연관관계 매핑
- RESTful API 설계 및 구현
- Redis를 활용하여 캐시 서버 구성 및 데이터 캐싱 최적화
- 적합한 로그 레벨로 정보 기록 및 에러 처리

---

## 🛠️ 기술 스택

- **Backend**: Spring Boot, Java
- **Database**: H2 (인메모리 DB)
- **Scraping**: Jsoup
- **Caching**: Redis
- **Deployment**: Docker
- **Build Tool**: Gradle