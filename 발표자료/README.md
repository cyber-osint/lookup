
## 🕵️‍♂️ Cyber OSINT Lookup 도구 소개

> 오픈소스 인텔리전스(OSINT)를 쉽게 활용할 수 있는 웹 기반 검색 도구
> `https://cyber-osint.github.io/lookup/`

---

## ✅ 개발 목적

* 누구나 쉽게 사용할 수 있는 **IP / 도메인 기반 OSINT 검색 툴** 제공
* 다양한 무료 API를 통합하여 **실시간 정보 조회** 가능
* **Shodan, ipinfo, Certspotter, dns.google 등** 데이터를 간편하게 확인
* **CyberChef**와 같이 백엔드 없이 동작할 수 있는 도구

---

## 🧩 주요 기능

* 🔍 IP / 도메인 입력 시 실시간 조회
* 📡 IP 정보 조회 (ipinfo.io)
* 📜 인증서 발급 이력 (certspotter)
* 🌐 DNS 레코드 (Google DNS API)
* 🧠 ASN 정보 (ipinfo ASN)
* 🧾 결과 이력 저장 (LocalStorage 기반)

---

## 🖥️ UI 구성

* **단일 HTML + Tailwind CSS**
* 반응형 레이아웃, 직관적인 버튼/입력창 구성
* 좌측: 검색 이력
* 우측: 결과 출력 카드 형태
* 🎨 Google 스타일의 디자인 적용

---

## 🔌 사용된 주요 API

| API 출처         | 설명                          |
| -------------- | --------------------------- |
| ipinfo.io      | IP 기본 정보 및 ASN              |
| Certspotter    | 서브 도메인 |
| Google DNS API | 도메인 → IP A 레코드              |
| shodan      | ip, hostname, port, cpe, cve              |
| crt.sh      | 인증서 발급 이력              |
---

## 📦 기술 스택

* **Frontend**:

  * HTML + Tailwind CSS
  * Axios (API 호출용)
  * JavaScript (로컬 저장, 비동기 처리)

* **배포**:

  * GitHub Pages
  * 정적 페이지 기반 (서버 불필요)

---

## 💡 구현 포인트

* ✅ 브라우저 로컬스토리지로 검색 이력 저장
* ✅ 하나의 HTML 파일에 모든 기능 내장
* ✅ 비동기 fetch 및 예외처리 처리
* ✅ 다양한 도메인/IP 패턴 처리 지원

---

## 🎯 개선 방향 (계획 중)

* 🔐 Whois 정보 연동
* 📍 각종 무료OSINT 추가
* 📝 검색 결과 복사/다운로드 기능

---

## 🚀 데모

👉 바로가기:
[https://cyber-osint.github.io/lookup/](https://cyber-osint.github.io/lookup/)

---

## 👨‍💻 도구의 강력한 특징

* 보안 관련 실무자, 리서처, 대응자 모두에게
  **빠르고 가벼운 조사도구**로 유용
* 설치 불필요, API Key 없이도 기본 기능 가능
* 지속적인 기능 확장 및 코드 공개 예정

---

## 🙏 감사합니다

문의 또는 제안:
✉️ GitHub 이슈 또는 이메일로 연락 주세요.

---
