# 🌱 SpringJpaJdk17Template

## 🛠 프로젝트 개요
Spring Boot와 JPA를 활용한 자바 17 기반의 템플릿 프로젝트입니다. 최신 Java 기능과 Spring Framework를 적용하여 JPA 실습을 간편하게 진행할 수 있도록 설계되었습니다.

---

## 📚 작성자 정보
- **한국폴리텍대학 서울강서캠퍼스 빅데이터과**
- **이협건 교수**
- ✉️ [hglee67@kopo.ac.kr](mailto:hglee67@kopo.ac.kr)
- 🔗 [빅데이터학과 입학 상담 오픈채팅방](https://open.kakao.com/o/some-link)

---

## 🚀 주요 실습 내용
- **Java 17 및 Record 타입** 적용
- **Spring Data JPA**를 이용한 데이터베이스 연동
- **MariaDB** 기반 서비스 구현 및 설정

---

## 🛠️ 환경 설정
- **Java**: OpenJDK 17 이상
- **Database**: MariaDB
- **Build Tool**: Maven

---

## 🧰 주요 적용 프레임워크
- **Spring Boot**: 3.x 버전
- **Spring Data JPA**: ORM 및 데이터 접근 계층 구성
- **Lombok**: 코드 간결화

---

## 📦 설치 및 실행 방법

### 1. 레포지토리 클론
```bash
git clone https://github.com/Hyeopgeon-Lee/SpringJpaJdk17Template.git
cd SpringJpaJdk17Template
```

### 2. MariaDB 설정
application.yml 또는 application.properties 파일에서 데이터베이스 설정 정보를 업데이트합니다.

```yaml
spring:
  datasource:
    url: jdbc:mariadb://localhost:3306/your_database
    username: your_username
    password: your_password
```

아래는 의존성 설치부터 시작하는 설치 및 실행 방법입니다.

### 3. 의존성 설치
아래 명령어를 실행하여 Maven 의존성을 설치합니다:
```bash
mvn clean install
```

### 4. 애플리케이션 실행
```bash
mvn spring-boot:run
```




