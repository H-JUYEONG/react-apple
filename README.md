🍏 Apple 웹 서비스 클론 개발

📌 프로젝트 개요

프로젝트명: Apple (Apple 웹 서비스 클론 개발)

개발 기간: 2024.10.01 ~ 2024.10.14 (2주)

팀 구성: 5명

소개: Apple 웹 서비스의 관리자 기능을 구현하여 매장 및 상품 관리를 지원하고 운영의 효율성을 제공합니다.

🛠 사용 기술

Frontend





Backend





Database



DevOps





🚀 주요 기능

관리자 기능

매장 및 상품 관리

주문 및 재고 관리

사용자 권한 관리

상품 관리

상품 등록, 수정, 삭제

카테고리별 상품 정리

할인 및 프로모션 설정

매장 관리

오프라인 매장 등록 및 정보 수정

매장별 재고 및 판매 관리

📂 프로젝트 구조

📦 apple-clone
├── frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── services
│   │   ├── App.js
│   │   ├── index.js
├── backend
│   ├── src
│   │   ├── main
│   │   │   ├── java
│   │   │   │   ├── com.appleclone
│   │   │   │   │   ├── controller
│   │   │   │   │   ├── service
│   │   │   │   │   ├── repository
│   │   │   │   │   ├── model
│   │   │   │   │   ├── dto
│   │   │   ├── resources
│   │   │   │   ├── application.yml
├── docker-compose.yml
├── README.md

🔧 설치 및 실행 방법

1️⃣ 백엔드 실행 (Spring Boot)

cd backend
./mvnw spring-boot:run

2️⃣ 프론트엔드 실행 (React)

cd frontend
npm install
npm start

3️⃣ Docker를 이용한 배포

docker-compose up -d

📜 라이선스

이 프로젝트는 개인 학습 목적으로 개발되었습니다.

📞 문의

이름: H-JUYEONG

이메일: your-email@example.com

블로그: Tistory

