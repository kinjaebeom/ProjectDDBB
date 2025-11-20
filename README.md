# 초보 개발자의 팀 프로젝트를 도와주는 Mini Github Web

<h2>🎯 Project DDBB: Mini-GitHub</h2>

<h3>버전 관리 + 협업 기능을 갖춘 Mini GitHub 플랫폼</h3>

<br/> <p align="center"> <img src="https://img.shields.io/badge/Version-Control_System-181717?style=for-the-badge&logo=git&logoColor=white" /> <img src="https://img.shields.io/badge/Fullstack-4A90E2?style=for-the-badge&logo=stackshare&logoColor=white" /> <img src="https://img.shields.io/badge/Self_Designed_Architecture-006699?style=for-the-badge" /> </p> <p align="center"><b>Git과 유사한 버전 관리 시스템(VCS)을 직접 설계·구현한 미니 협업 플랫폼입니다.</b></p>
<br/>
🚀 Tech Stack
🔧 Backend & Core
<p align="center"> <img src="https://img.shields.io/badge/Java_17-007396?style=for-the-badge&logo=openjdk&logoColor=white" /> <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white" /> <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apachemaven&logoColor=white" /> <img src="https://img.shields.io/badge/RDBMS-4479A1?style=for-the-badge&logo=mysql&logoColor=white" /> </p>
🎨 Frontend & Optimization
<p align="center"> <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" /> <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" /> <img src="https://img.shields.io/badge/React_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white" /> </p>
☁️ Infra & Tools
<p align="center"> <img src="https://img.shields.io/badge/AWS_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white" /> </p>

<h2>⚡ 주요 기능 및 기술적 하이라이트</h2>
<h3>🔥 1. 버전 제어 시스템(VCS) 직접 구현</h3>

<h4>✔ Diff 알고리즘 구현 (라인 단위 비교)
✔ Pull Request + Code Review 워크플로우
✔ Git과 유사한 Blob / Tree / Commit 모델링
✔ RDBMS 기반 버전 기록 최적 구조 설계

단순 CRUD가 아니라 시스템 설계 + 알고리즘 구현 역량을 보여주는 핵심 포인트</h4>

<h3>💎 2. 프론트엔드 성능 및 UX 최적화</h3>
<h4>📌 Server State (React-Query)

useInfiniteQuery 기반 무한 스크롤

staleTime, cacheTime 설정 → 즉각응답 + API 부하 감소

SWR 방식으로 최신 데이터 반영

📌 이벤트 최적화

useDebounce → 입력이 멈춘 후 300ms 뒤에 검색 API 호출

useThrottle → 스크롤 이벤트 최적화 (300ms)

📌 UI/UX 개선

ESC로 사이드바 닫기

스크롤 락 처리

이미지 업로드 상태를 명확하게 표시 (업로드 / 업데이트 분리)</h4>

<h4>🧱 3. 아키텍처 설계

Layered Architecture (Controller / Service / Repository)

SRP 원칙 기반 관심사 분리

OOP 기반 도메인 모델링

TypeScript 기반 타입 안정성 확보

</h4>

<h3>📦 실행 방법</h3>

<h4>🔹 1. Repository Clone
git clone https://github.com/kinjaebeom/ProjectDDBB.git
cd ProjectDDBB

🔹 2. Backend 설치 & 실행

mvn clean install

mvn spring-boot:run

🔹 3. Frontend 설치 & 실행
cd frontend

npm install

npm run dev


</h4>


<h2 style="font-size: 28px; font-weight: bold;">📝 실제 github에서 영감을 받아 진행하게 된 프로젝트</h2>
<h2 style="font-size: 28px; font-weight: bold;">📝 팀 프로젝트 웹 사이트로 코드비교와 현황 조회 뿐만 아니라 코멘트와 팀원들끼리 소통할 수 있는 게시판과 커뮤니티를 형성</h2>
<h2 style="font-size: 28px; font-weight: bold;">📝 방장 제도를 통해 팀원을 초대하거나 강퇴 할 수있는 권한을 부여</h2>
<h2 style="font-size: 28px; font-weight: bold;">📝 로그인과 회원가입 그리고 계정찾기 까지 세밀하게 구현.</h2>
<img src="https://github.com/user-attachments/assets/993b661f-d3e6-4bd2-b9fb-e5632615a7b4" width="100%" alt="진행사항1" />
<img src="https://github.com/user-attachments/assets/26e69a3a-8a89-4b92-a158-5cb3e27fb65d" width="100%" alt="진행사항2" />
<img src="https://github.com/user-attachments/assets/5b7709ae-e137-4dd3-bcf6-dadda0b3fc74" width="100%" alt="진행사항3" />
<img src="https://github.com/user-attachments/assets/2ad8f8a0-c0cb-4751-ba99-11bac3b4f677" width="100%" alt="진행사항4" />
