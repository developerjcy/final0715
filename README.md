# final0715
 
### 프로젝트명

드숑마숑 – (Spring MVC페이지 기반)

#### 프로젝트 기간

﻿2022.06.11 ~ 2022.07.15

##### 투입인원

3명

##### 프로젝트 소개

술에 대한 기호가 다양해지고, 혼술 문화가 늘어나고 있는 요즘 시대에 맞추어 특별하고 맛있는 술을 온라인 창구를 통해 보다 쉽게 발견할 수 있고, 커뮤니티 게시판을 이용하여 각자의 취향을 공유하고, 비대면 술자리를 마련하는 등 혼자서도 즐겁게 술을 즐길 수 있는 웹 페이지를 제작

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**주요역할 및 담당**

*공통역할*
1. 각각 생각해온 아이디어로 진행된 회의를 통해 프로젝트 기획 및 총괄
2. 총괄 후 데이터베이스 정의, 설계 및 구현
3. 프로젝트 시작하기 전 개개인의 역량에 맞춰 역할을 분배
4. 데이터베이스에 필요한 자료를 다 함께 수집하여 방대한 데이터를 수집함.

*엔지니어*
1. 회원 CRUD 기능
- 회원가입 및 회원정보수정, 회원탈퇴 구현.
- 회원가입 시 성인인증 절차를 거쳐 04년 이후에 출생한 고객의 경우 회원가입 절차가 거절됨.
- 로그인시 가상 session(변수)에 저장하여 유동적으로 설계됨. 로그아웃시 변수내 값을 삭제함.
- 각 회원은 고유의 포인트를 사용하며, 포인트는 입력한 금액에 따라서 포인트를 얻고 쇼핑몰에서 
포인트를 차감하여 사용할 수 있음.
- 회원은 모든 기능을 언제든지 사용할 수 있지만. 비회원의 경우는 목록을 열람하는 것밖에 할 수 없음.

2. 상품 상세페이지 제작
- 해당 상품에 대한 정보를 더 자세히 보여주고 해당 상품에 관련한 댓글을 작성할 수 있음.
- 페이지 내에 textarea에 상품평을 작성할 수 있음.
- session을 활용하여 회원이 아닐 경우에는 리뷰작성이 불가능하고 로그인 페이지로 이동함.
- th:if를 사용하여 작성한 댓글은 작성한 사람만 삭제할 수 있도록 처리함. 
- 상품 상세보기를 클릭하면 AJAX기능을 통하여 해당 상품정보와 그에 대한 상품평을 바로 살펴볼 수 있음. 

3. 장바구니 담기 기능
- 해당 상품을 장바구니에 담아 마이페이지에서 장바구니 목록을 확인할 수 있음. 
- 장바구니 담기 기능은 th:if기능과 session을 활용하여 로그인이 되어있지 않으면 ‘로그인 후에 이용할 수 있습니다.’라는 문구를 출력함. 로그인이 되어있을 경우, 해당 상품을 장바구니에 담았다면 ‘장바구니에 추가됨’을 출력함.

4. 장바구니 리스트페이지 제작
- 최근에 추가된 순서대로 리스트에 출력함.
- 리스트는 상품 사진, 상품명, 수량, 가격 등 저장된 정보를 출력함.
- JS를 사용하여 주문하려는 품목의 개수를 바꾸거나 체크박스를 누를 때마다 총 구매가가 바뀜.
- 장바구니에 담기 버튼을 누르면 체크된 품목을 session과 장바구니 테이블에 저장하여 
브라우저가 유지되는 동안 장바구니 내에 품목이 유지됨.

*통합관리*

-팀원들이 작성한 코드들을 하나로 합치고 그에 대한 에러코드 및 오류를 검출해 수정함. 

-팀원들의 작업 현황을 매일 조사하고 현황에 따라 스케줄이나 사양을 변경함.

-모든 프로젝트 관련 데이터베이스와 서류를 보관하고 관리함.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

**개발도구**

∙ 개발산출문서 – eXERD, Excel

∙ DB설계 - Oracle SQL Developer

∙ IDE 도구 - Eclipse

∙ 웹 서버 - Apache Tomcat 9.0

∙ 언어 - JAVA / JavaScript / HTML

∙ 주요 라이브러리 - jQuery / JSON / MyBatis 

∙ 프레임워크 - Spring
