# 🖼️ Gallery Reservation

미술관 갤러리 예약 및 관리 웹 애플리케이션입니다.
사용자는 갤러리를 조회하고 예약을 신청할 수 있으며, 관리자는 갤러리와 예약을 관리할 수 있습니다.

---

### ✅ 배포 주소

http://3.36.161.179

### ✅ 기획 배경

### 👤 회원

- 일반 회원가입 / 로그인
- **소셜 로그인** (카카오, 네이버)
- 일반 로그인 / 소셜 로그인 모두 동일한 기능 이용 가능

### 🗓️ 예약

- 갤러리 예약 신청 (날짜, 시간 선택)
- 내 예약 목록 조회
- 예약 취소
- 예약 상태: `대기중 → 승인 / 거절 / 취소`

### ✅ 할 일 (Todo)

- 개인 할 일 등록 / 수정 / 삭제
- 완료 여부, 마감일 관리
- 키워드 검색 및 완료 여부 필터링

### 🏛️ 갤러리 (관리자)

- 갤러리 등록 / 수정 / 비활성화
- 층/구역 정보, 수용 인원, 운영 시간 관리
- 예약 승인 / 거절 처리

---

## 🛠️ 기술 스택

> 미술관 갤러리 공간을 온라인으로 예약할 수 있는 플랫폼

- 갤러리 공간을 탐색하고 날짜·시간·인원을 선택해 갤러리를 예약 신청할 수 있다.
- 관리자는 갤러리를 등록/수정하고 예약을 승인/거절할 수 있다.
- 카카오, 네이버 소셜 로그인을 지원한다.

---

### 👥 서비스 대상

- 미술관 갤러리 공간을 대관하고 싶은 사람들
- 전시 공간을 편리하게 예약하고 싶은 사람들

---

## 🛠 기술 스택

### Backend

<p>
  <img src="https://img.shields.io/badge/Java 21-007396?style=flat-square&logo=OpenJDK&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring Boot 3-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring Security 6-6DB33F?style=flat-square&logo=springsecurity&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring Data JPA-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
  <img src="https://img.shields.io/badge/OAuth2-EB5424?style=flat-square&logo=auth0&logoColor=white"/>
</p>

### Frontend

<p>
  <img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black"/>
</p>

### Database

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white"/>
</p>

### Build & Deploy

<p>
  <img src="https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white"/>
</p>

### Collaboration

<p>
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white"/>
  <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white"/>
</p>

---

## 💌 서비스 화면 및 기능 소개

### ✅ 메인

![메인 페이지](readme_assets/main1.png)

![메인 페이지](readme_assets/main2.png)

![메인 페이지](readme_assets/main3.png)

---

### ✅ 회원

- **회원가입**
  > 이메일과 비밀번호로 회원가입 및 로그인할 수 있다.

![회원가입](readme_assets/join.png)

- **로그인 / 소셜 로그인**
  > 카카오, 네이버 OAuth2 소셜 로그인을 지원한다.

![로그인](readme_assets/login.png)

---

### ✅ 갤러리 조회

- **갤러리 목록 조회**

  > 전체 갤러리 목록을 커버 이미지, 위치, 수용 인원과 함께 확인할 수 있다.

![갤러리 목록](readme_assets/gallery-list1.png)
![갤러리 목록](readme_assets/gallery-list2.png)

- **갤러리 상세 조회 및 예약 신청**
  > 갤러리 상세 페이지에서 날짜, 30분 단위 시간 슬롯, 인원, 연락처를 선택해 바로 예약 신청할 수 있다.

![갤러리 예약 신청](readme_assets/gallery-detail1.png)
![갤러리 예약 신청](readme_assets/gallery-detail2.png)

---

### ✅ 예약 관리

- **내 예약 목록 조회**
  > 신청한 예약 목록을 페이지네이션과 갤러리명 검색으로 조회할 수 있고, 대기 중인 예약을 취소 신청할 수 있다.

![예약 조회](readme_assets/reservation-list.png)

> `대기중 → 승인 / 거절 / 취소`

- **예약 상세 조회**
  > 갤러리 커버 이미지와 함께 예약 정보를 상세하게 확인할 수 있다.

![예약 상세 보기](readme_assets/reservation-detail1.png)
![예약 상세 보기](readme_assets/reservation-detail2.png)
![예약 상세 보기](readme_assets/reservation-detail3.png)

---

### ✅ 관리자 페이지

- **갤러리 관리**
  > 갤러리 등록, 수정, 삭제 및 운영 상태(운영중/비활성화)를 관리할 수 있다.

![관리자 갤러리 관리](readme_assets/admin-gallery.png)

- **갤러리 등록**
  > 갤러리 등록, 수정, 삭제 및 운영 상태(운영중/비활성화)를 관리할 수 있다.

![관리자 갤러리 등록](readme_assets/admin-gallery-add.png)

- **갤러리 수정**
  > 갤러리 등록, 수정, 삭제 및 운영 상태(운영중/비활성화)를 관리할 수 있다.

![관리자 갤러리 수정](readme_assets/admin-gallery-edit.png)

- **예약 승인/거절**
  > 전체 예약 목록을 조회하고 예약을 승인하거나 거절할 수 있다.

![관리자 예약 관리](readme_assets/admin-reservation.png)

---

### ✅ 할일 페이지

- **할일 등록/수정**
  > 전체 예약 목록을 조회하고 예약을 승인하거나 거절할 수 있다.

![할일 리스트](readme_assets/todo-list.png)
![할일 등록](readme_assets/todo-add.png)
![할일 수정](readme_assets/todo-edit.png)

---

## 📡 API 명세서

![API 명세서](readme_assets/api.png)

---

## 🏗 시스템 아키텍처

![아키텍처 설계](readme_assets/architecture.png)

---

## 🗂 프로젝트 구조

```
src/main/java/com/study/galleryreservation/
├── config/                         # 설정 클래스
│   ├── SecurityConfig.java         # Spring Security 설정
│   ├── CustomAuthenticationSuccessHandler.java
│   └── OAuthAttributes.java        # OAuth2 속성 매핑
│
├── controller/                     # 컨트롤러
│   ├── AdminController.java        # 관리자 전용 (갤러리 관리, 예약 승인)
│   ├── GalleryController.java      # 갤러리 상세 / 예약 신청
│   ├── MemberController.java       # 회원가입 / 로그인
│   ├── ReservationController.java  # 예약 신청 / 조회 / 취소
│   ├── TodoController.java         # 할 일 CRUD
│   └── ViewController.java         # 공통 뷰 라우팅
│
├── domain/                         # 엔티티
│   ├── gallery/Gallery.java
│   ├── member/Member.java
│   ├── member/MemberRole.java
│   ├── reservation/Reservation.java
│   ├── reservation/ReservationStatus.java
│   ├── session/SessionUser.java
│   ├── session/SnsUser.java
│   ├── session/UserRole.java
│   └── todo/Todo.java
│
├── dto/                            # DTO
│   ├── gallery/
│   ├── member/
│   ├── reservation/
│   └── todo/
│
├── repository/                     # JPA 레포지토리
│   ├── GalleryRepository.java
│   ├── MemberRepository.java
│   ├── ReservationRepository.java
│   ├── SnsUserRepository.java
│   └── TodoRepository.java
│
└── service/                        # 서비스
    ├── CustomOAuth2UserService.java
    ├── CustomUserDetailsService.java
    ├── GalleryService.java
    ├── MemberService.java
    ├── ReservationService.java
    └── TodoService.java

src/main/resources/
├── templates/
│   ├── index.html                  # 메인 페이지
│   ├── admin/                      # 관리자 페이지 (갤러리 관리·예약 승인)
│   ├── gallery/                    # 갤러리 목록/상세
│   ├── member/                     # 로그인/회원가입
│   ├── reservation/                # 예약 목록/상세
│   ├── todo/                       # 할 일 목록/폼/수정
│   └── visit/                      # 관람시간/오시는길
├── static/
│   ├── css/common.css
│   ├── admin/ gallery/ member/ reservation/ todo/  # 페이지별 CSS
│   └── favicon.png
├── application.yml
└── application-secret.yml
```

---

## 🗄️ ERD

```
member (1) ──────< todo (N)
member (1) ──────< reservation (N)
gallery (1) ─────< reservation (N)
```

| 테이블      | 주요 컬럼                                                                 |
| ----------- | ------------------------------------------------------------------------- |
| member      | id, username, password, email, role, created_at                           |
| gallery     | id, name, location, floor_zone, capacity, is_active                       |
| reservation | id, member_id, gallery_id, reservation_date, start_time, end_time, status |
| todo        | id, member_id, title, content, is_done, due_date                          |

---

## 🔐 권한 구조

| 김태혁(팀장👑)               | 김민준                   | 이유리                  | 박준현             |
| ---------------------------- | ------------------------ | ----------------------- | ------------------ |
| Back-End                     | Back-End                 | Back-End                | Back-End           |
| 회원가입 / 로그인            | 할 일(Todo) 기능 구현    | Front-End / UX,UI       | 갤러리 기능 구현   |
| 소셜 로그인 (카카오, 네이버) | 할 일 등록 / 수정 / 삭제 | 예약 기능 구현          | 갤러리 목록 / 상세 |
| Spring Security 설정         |                          | 예약 목록 / 상세 / 취소 |                    |
| 관리자 페이지                |                          |                         |                    |
