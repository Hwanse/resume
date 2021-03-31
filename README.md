# 김환석

### 기본 정보
- 이메일: khsb2012@gmail.com
- github: https://github.com/Hwanse

<br><br>

### 학력
- 한남대학교 컴퓨터통신무인기술학과(컴퓨터공학과) 졸업
    - 2012.03 ~ 2020.02

<br><br>

### 외부활동
- 대덕인재개발원 응용 SW 엔지니어링 과정 수료
    - 2019.01 ~ 2019.09


<br><br>

### 경력

**티젠 소프트**
- 재직기간: 2019.11 ~ 2021.01
- 부서
    - 기술 1개발실 (2019.11 ~ 2020.11)
    - 온택트 개발팀 (2020.12 ~ 2021.01)
- 직책: 연구원
- 업무내용: 솔루션 개발

<br><br>

### 기술 스택
- 언어
    - Java(주 사용 언어)
    - javascript(jQeury)
    - HTML/CSS

- 백엔드
    - Spring
      - SpringBoot
      - MVC
      - eGovFramework
    - MyBatis
    - JPA

- 프론트엔드
    - 백엔드에서 가공된 데이터로 간단한 페이지  가능

- DB
    - Oracle
    - MySQL

- DevOps
    - tomcat
    - apache, nginx

- 기타
    - ffmpeg
    - Linux
    - Git, SVN
    - kotlin

<br><br>

## 프로젝트 경험

### 회사 프로젝트

<br>

**동영상 인코딩 솔루션 시스템 개발**     

- 설명: Web에서 동영상, 오디오를 인코딩하여 관리하고 사용자에게 플레이어를 제공하는 솔루션 유지보수 및 고도화 개발
- 사용 기술스택
    - Java, Jsp
    - Javascript
    - struts2, iBatis(구 버전)
    - Spring(eGovFramework), MyBatis(신 버전)
    - ffmpeg
    - Oracle, MySQL, MariaDB
    
- 역할
    - 동영상 편집 기능 개발
      - 각각의 이미지, 동영상 파일들을 합쳐서 하나의 동영상으로 만드는 기능 개발
      - 기존에 개발되어 있던 동영상 분할 기능의 오류 사항을 개선하여 안정화
    - 파일의 MymeType과 apache tika 라이브러리를 활용하여 파일 업로드 시 동영상이 아닌 파일 업로드를 차단하는 기능 개발
    
<br>

**라이브 스트리밍 시스템 개발**        

- 설명: 사용자가 등록한 방송일정 시간만큼 라이브 방송을 송출하는 시스템 개발
- 사용 기술스택
    - Java, Jsp
    - Spring(eGovFramework)
    - MyBatis/iBatis
    - MariaDB
    - ffmpeg
    
- 역할
    - 촬영중인 동영상을 Web 플레이어에서 송출하는 프로세스에서 비효율적인 처리과정을 단축
    - 라이브 송출 시 첫 송출하기까지의 딜레이 시간을 단축 (약 30초 -> 약 3초)
    - 라이브방송 종료 시 녹화된 영상을 편집하여 동영상을 분할하는 기능 추가
    - 타 시스템에 제공하기 위한 API 개발(라이브 플레이어, 동영상 편집 폼, 동영상 리스트 조회, 썸네일 이미지 조회 등등)
    - RTMP에서 송출되는 동영상 스트림을 HTTP 로 변환하는 기능 개발

<br>

**고객사 사내 통합 콘텐츠 관리용 시스템 개발(프로젝트명 대외비)**      

- 설명: 복합 콘텐츠(동영상, 오디오, 이미지, 문서)를 관리하는 관리자용 페이지 및 사용자용 사이트 개발
- 사용 기술스택
    - Java, Jsp
    - Spring(eGovFramework)
    - Javascript
    - nodejs
    - MyBatis/iBatis
    - MariaDB
    - ffmpeg
- 역할
    - 주로 관리자용 페이지의 기능 개발을 담당하여 개발 진행 
    - 관리자 페이지에서 Dropzone을 활용한 복합 그룹 콘텐츠(동영상, 오디오, 이미지, 문서) 업로드 및 인코딩 기능 개발
    - 관리자 페이지에서 사용자 페이지에 출력할 메뉴들의 사용여부를 관리하는 기능 개발
    - 동영상 플레이어에서 고객사의 요청사항 커스텀 기능 개발
    - 관리자 페이지의 전체 관리자/중간 관리자/일반 사용자 등 각 유저의 권한별로 이용가능한 기능사항을 제한하는 기능 개발
 
<br>

**대학교 콘텐츠 관리 시스템 개발(프로젝트명 대외비)**     
- 설명: 대학교 사이버 강의용 목적으로 동영상, 이미지를 관리하는 관리자 페이지 및 사용자용 사이트 개발 
- 사용 기술스택
    - Java,Jsp
    - Spring(eGovFramework)
    - Javascript
    - nodejs
    - MyBatis/iBatis
    - Oracle
    - ffmpeg
- 역할
    - 주로 사용자용 사이트 개발을 담당
    - 사용자 페이지의 동영상 등록 및 등록된 동영상 게시글의 기능 개발
      - 업로드 시 동영상의 고유 QR 코드 생성
      - 대학교측 도메인의 고유 장비코드와 매칭되도록 개발
      - 동영상 등록 시 해당 동영상의 사용자가 커스텀 태그를 등록 가능
    - 사용자 페이지의 동적 Left Menu 기능 개발
      - 관리자가 관리자용 페이지에서 Menu 카테고리 편집하여 각 메뉴별로 사용자 페이지에서 사용여부를 선택
    - 대학교측 도메인의 사용자 데이터 동기화 스케줄러 개발
      - java Quartz 라이브러리를 활용
      - 대학교측 사용자 데이터를 동영상 시스템의 DB와 싱크를 맞추기 위해 데이터를 insert, update 작업 수행
      - 약 20만건의 데이터를 조회할 경우 다수의 데이터를 insert/update 작업 시 최악의 성능의 경우 약 30분~50분이 소요되던 시간을 iBatis의 batch api 를 활용하여 트랜잭션의 횟수를 줄여서 성능을 약 15초로 개선
    - 이중화 서버로 구성되어 있어 동영상 등록 시 동시성 상황에서 QR코드 키값의 중복 문제 개선
      - 고객사가 요청한 QR코드 키값 정책으로 인하여 동시에 동영상 등록 시 QR코드의 키값이 중복되는 현상 발생
      - 키값으로 활용할 채번 테이블을 추가 구성하고 비관적 Lock을 활용하여 QR코드 키값 중복 문제 개선
     
<br>

**동영상 인코딩 솔루션 구버전 시스템 전환 작업**     
- 설명: 기존의 Struts2 를 사용한 동영상 솔루션 시스템의 UI와 백엔드 프레임워크를 eGovFramework로 전환하는 작업
- 사용 기술스택
    - struts2
    - Spring(eGovFramework)
    - MariaDB
- 역할
    - 구 버전 시스템의 UI를 새로운 버전의 UI로 변경하는 작업을 진행
    - struts2 + iBatis로 구성되어 있던 시스템을 eGovFramework + MyBatis로 전환하는 작업
    - 기존에 하나의 프로젝트로 합쳐있었던 동영상 인코딩과 관련된 기능사항을 스케줄러로 모듈화 작업

<br>

**동영상 인코딩 스케줄러 리팩토링**     
- 설명: 기존 동영상 인코딩 로직 코드를 리팩토링
- Before
    - 기존 인코딩 로직은 문자열로 ffmpeg 명령어 커맨드 라인을 작성
    - 단점 
      - Type-Safe하지 못하다
      - 동적으로 커맨드 라인을 만들거나 명령어 라인이 길어지게 되면 가독성 저하
- After
    - ffmpeg-wrapper 라이브러리를 활용하여 기존 로직 개선
    - 개선사항
      - wrapper 라이브러리를 활용하여 커맨드 라인 조작을 메서드 체인 형태로 리팩토링
      - Type-Safe 해짐 (그러나 ffmpeg의 모든 명령어를 지원하는 것은 아니기 때문에 이외 명령어는 문자열로 커맨드 라인 작성)
      - 동적 커맨드 라인, 명령어가 길어져도 간결한 코드 작성이 가능해짐

