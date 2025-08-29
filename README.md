# InOutManager  
스프링 부트 + JSP 기반 입출고 관리 시스템

---

##  프로젝트 소개  
기업의 입출고 및 재고 관리를 효율적으로 처리할 수 있는 웹 기반 시스템입니다.  
직관적인 UI를 통해 누구나 쉽게 사용할 수 있으며,  
관리자와 일반 사용자 권환을 분리해 각자의 작업을 효과적으로 해결할 수 있다.
###  화면의 흐름 
  <details>
  <summary>화면의 흐름및 구성</summary> <br>
  <img src="https://github.com/jongha8422-sketch/inoutmanager/blob/main/PICTURES/%ED%99%94%EB%A9%B4%EC%9D%98%20%ED%9D%90%EB%A6%84.png" alt="로그인 UI" width="400"/> 
  </details>

---

##  개발 기간  
- **2025.08.26 ~ 진행 중**

---

##  개발 환경  

- **Programming Languages** : `Java 17`  
- **Build Tool** : `Gradle`  
- **IDE** : `IntelliJ`  
- **Framework** : `Spring Boot (3.5.5)`  
- **Database** : `Oracle 18c` 
- **ORM** : `JPA`  
- **Front** : `html5`, `CSS`, `JavaScript`  
---

##  주요 기능  

###  로그인 & 회원가입 [상세보기](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/login.md)
- 아이디/비밀번호 DB 검증  
- 로그인 시 세션 생성  
- 관리자 / 일반 사용자 권한 분리  
- 신규등록 시 정보를 다양성 있도록 사용하는 것이 가능

---

###  마이 페이지 [상세보기](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/mypage.md)
- 내 정보 조회 및 수정 (ID 고정, 비밀번호 제외)  
- 입출고 기록 및 담당 내역 확인 (신규등록 시 이름을 적은 것 바탕) 
- Excel 추출 기능 및 작업 기록 시각화  

---

###  입고 등록/조회 [상세보기](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/ibpage.md)
- 제품 코드, 수량, 공급처 등 상세 정보 입력  
- 입고 상태 확인  
- 입출고량 추적 및 Excel 출력  

---

###  출고 등록/조회 [상세보기](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/obpage.md)
- 입고 상품 선택 후 출고 처리  
- 출고 정보 입력 및 발송 처리  
- 입출고량 추적 및 Excel 출력  

---

###  관리자 페이지 [상세보기](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/admin.md)
- 모든 입출고 기록 확인가능 
- 모든 게시글 수정 및 삭제가능 
- 사용자의 정보 확인/유저삭제 가능

---

###  메인 페이지 [상세보기](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/mainpage.md)
- 모든 기능을 한 눈에 확인 가능 
- 심플한 디자인으로 누구나 싶게 적응 가능

---

###  게시판 [상세보기](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/boardpage.md)
- 고객 문의 및 피드백 관리  
- 관리자 게시글 수정/삭제 기능  
- 게시글 제목 및 히스토리 확인  

---

##  기술적 특징  

-  **UI**: 누구나 쉽게 사용할 수 있는 사용자 친화적 디자인  
-  **권한 관리**: 사용자별 접근 권한 설정 및 제어  
-  **Excel 출력**: 입출고 내역 및 재고 정보를 문서로 저장 가능  
