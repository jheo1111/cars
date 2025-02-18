# 슈퍼카 판매 웹사이트 프로젝트

## 📖 프로젝트 개요
이 프로젝트는 SSR 기반의 Spring Boot 애플리케이션입니다.
Spring Data JPA, Thymeleaf, Spring Security 등을 활용하여 실제 운영 가능한 수준의 웹 애플리케이션을 구현하는 데 초점을 맞췄습니다.

### 주요 기능 및 특징
- 서버 사이드 렌더링(SSR) 방식 구현
- Spring Data JPA를 활용한 데이터베이스 처리
- JUnit 기반 테스트 코드 작성
- Thymeleaf를 활용한 UI 템플릿 엔진
- Spring Security로 회원 인증 및 권한 관리

---

## 💻 사용 기술 스택

|   Java   |   Spring Framework   |   Spring Boot   |   Spring Security   |   MySQL   |   Thymeleaf   |
| :----------------------------------------------------------: | :----------------------------------------------------------: | :----------------------------------------------------------: | :-----------------------------------------------------------------------------------------------: | :----------------------------------------------------------: |  :----------------------------------------------------------: |
| <img src="https://techstack-generator.vercel.app/java-icon.svg" alt="Java Icon" width="65" height="65" /> | <img src="https://www.vectorlogo.zone/logos/springio/springio-icon.svg" alt="Spring Framework Icon" width="50" height="50" /> | <img src="https://t1.daumcdn.net/cfile/tistory/27034D4F58E660F616" alt="Spring Boot Icon" width="65" height="65" /> | <img src="./image/spring_security_logo.png" alt="Spring Security Logo" width="85" /> | <img src="https://techstack-generator.vercel.app/mysql-icon.svg" alt="MySQL Icon" width="65" height="65" /> | <img src="https://www.thymeleaf.org/images/thymeleaf.png" alt="Thymeleaf Icon" width="65" height="65" /> |

---

## 📌 프로젝트 주요 기능

### 1. 회원 관리
- **회원가입**: 유효성 검사 및 데이터 저장
- **로그인**: Spring Security를 이용한 인증 및 세션 관리

### 2. 차량 관리
- **차량 등록**: 관리자 전용 차량 추가 기능
- **차량 관리**: 차량 정보 수정 및 삭제
- **차량 상세**: 차량별 상세 페이지 제공

### 3. 주문 기능
- **장바구니**: 차량 담기 및 수량 조정 기능
- **주문 처리**: 장바구니 상품 주문 및 결제

### 4. 메인 화면
- 최신 상품 및 인기 차량 노출

---

## 📢 Git 관리 규칙

### 1. 커밋 컨벤션

|  커밋 메시지 유형   | 설명                                                  |
| :-----------------: | :--------------------------------------------------- |
| `add`               | 새로운 프로젝트, 파일, 기능 추가                     |
| `feat`              | 신규 기능 구현                                       |
| `fix`               | 버그 수정                                            |
| `refactor`          | 코드 리팩토링                                        |
| `style`             | 코드 스타일 변경 (포매팅, 세미콜론 추가 등)          |
| `remove`            | 불필요한 파일 및 폴더 삭제                           |
| `rename`            | 파일 및 폴더 이름 변경                               |
| `chore`             | 빌드 설정 수정 및 기타 사소한 작업                   |

---

**더 많은 정보는 프로젝트 소스 코드에서 확인할 수 있습니다. 감사합니다!**
