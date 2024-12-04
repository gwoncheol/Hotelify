# Hotelify 프로젝트

이 프로젝트는 **호텔 예약 시스템**을 구현한 웹 애플리케이션입니다. 사용자는 호텔의 객실을 검색하고 예약할 수 있으며, 예약 조회 및 호텔에 대한 자세한 정보를 확인할 수 있습니다. 이 프로젝트는 **JSP(JavaServer Pages)**와 **Servlet**을 기반으로 구축되었습니다.

## 기능

- **호텔 소개**: 호텔에 대한 기본적인 정보 제공
- **객실 타입 검색**: 사용자가 원하는 객실을 선택하고 예약할 수 있도록 도와줌
- **예약**: 사용자가 객실을 예약할 수 있는 기능
- **예약 조회**: 사용자가 자신의 예약 내역을 조회할 수 있는 기능

## 설치 방법

### 1. 프로젝트 클론

먼저 이 프로젝트를 클론합니다:
```bash
git clone https://github.com/gwoncheol/Hotelify.git
```

### 2. 필요한 라이브러리 추가

- **JSP** 및 **Servlet**을 사용하여 웹 애플리케이션을 만들기 위해 **Apache Tomcat**을 서버로 사용합니다.
- **JSP 파일**과 **Servlet** 파일을 프로젝트의 **webapp** 폴더에 배치합니다.

### 3. 서버 설정

- **Apache Tomcat**을 설치한 후, 해당 서버를 사용하여 이 프로젝트를 실행할 수 있습니다.
- Tomcat의 `webapps` 디렉터리에 `Hotelify` 폴더를 배치합니다.

### 4. 데이터베이스 설정

- 데이터베이스 설정에 필요한 파일과 SQL 스크립트를 포함시켜야 합니다. 데이터베이스 연결을 위해 **JDBC**를 사용합니다.

### 5. 웹 애플리케이션 실행

Tomcat 서버를 실행하고, `http://localhost:8080/Hotelify` 주소로 접속하여 웹 애플리케이션을 실행합니다.

## 기술 스택

- **JSP (JavaServer Pages)**: 서버 측에서 동적으로 HTML을 생성하는 데 사용됩니다.
- **Servlet**: 클라이언트의 요청을 처리하고 JSP 페이지로 전달하는 역할을 합니다.
- **Java**: 서버 측 언어로 JSP와 Servlet을 처리합니다.
- **HTML5 & CSS3**: 웹 페이지 구조 및 스타일링을 담당합니다.
- **JavaScript**: 동적 기능을 제공합니다.
- **MySQL 또는 PostgreSQL**: 데이터베이스 관리 시스템
- **Apache Tomcat**: JSP와 Servlet을 처리하는 웹 서버

## 사용법

1. 호텔 메인 페이지에 접속하여 원하는 날짜와 인원 수를 입력합니다.
2. 객실 검색 결과를 확인하고 예약을 진행합니다.
3. 예약한 객실을 조회하거나, 예약 상태를 확인할 수 있습니다.

## 기여 방법

이 프로젝트에 기여하려면 먼저 포크한 후, 변경 사항을 제안해 주세요. `Pull Request`를 보내면 검토 후 병합됩니다.

1. 포크합니다.
2. 새 브랜치를 생성합니다: `git checkout -b feature-name`
3. 변경 사항을 커밋합니다: `git commit -m 'Add new feature'`
4. 브랜치를 푸시합니다: `git push origin feature-name`
5. Pull Request를 생성하여 변경 사항을 제출합니다.

## 라이센스

이 프로젝트는 [MIT 라이센스](https://opensource.org/licenses/MIT) 하에 라이센스됩니다.

## 연락처

- 이메일: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)
```


