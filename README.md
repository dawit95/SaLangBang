# SaLangBang(사랑방)

부동산 웹 프로젝트<br>
<b>기간 : 2021.05.17 ~ 2021.05.26(약 10일)</b><br>
<b>환경 : Apache Tomcat 8.0, Chrome 브라우저</b><br>
<b>주제 : 아파트 거래내역 제공 </b><br>
<b>개발 : Eclipse, springboot, vue.js</b><br>
<b>사용 언어 : JAVA(JDK 1.8), mySQL, vue.js, Javascript, springboot(REST API)</b><br>
<b>사용 기술 : JDBC, MVC모델2, Ajax, Open API(다음카카오), jwt</b><br>
<b>디자인 템플릿 : Vue Light Bootstrap Dashboard(https://www.creative-tim.com/templates/vuejs-free)</b><br>

# 프로젝트 상세내용

## 주제

<pre>
* 실제 거래된 아파트의 정보를 보기쉽게 제공해 사용자의 방 찾기를 돕는 웹 서비스<br>
</pre>

## 목적

<pre>
1. 매물 열람 시, 다른 매물과 세분화된 매물 비교 불편함<br>
 - 관심목록을 만들고 해당 아파트의 거래내역을 통한 비교 가능<br>
2. 관리자만 관리할 수 있는 게시판 리스트<br>
 - 신고된 허위정보, 사이트에러를 수정후 공지<br>
3. 기존 웹에서는 제공하지 않는 주변상권과 최근 거래내역 제공<br>
 - 실제 거래되 정부에 등록된 가격과 평수 주변상권을 보여줌<br>
</pre>

## 구현 목표

- 기능적 요구사항
<pre>
- 국토교통부 : 실거래가 정보 (xls) 활용 데이터 가공 후 DB 저장 및 API 연동을 통한 최신 데이터 갱신<br>
- 아파트 실거래가 검색 결과 데이터를 검색 정보에 따라 검색 결과 데이터 제공<br>
- 아파트 실거래가의 최근 변동 추이를 시각화하여 제공<br>
- 아파트 실거래가 검색 결과 데이터를 바탕으로 주변 상가 정보 제공<br>
- 사용자별 관심 매물을 설정하여 해당 매물의 정보를 확인하는 기능 제공<br>
- 로그인을 해야만 주요 기능과 추가 기능을 이용 가능하도록 한다.<br>
</pre>
- 비기능적 요구사항
<pre>
- 공공데이터 API를 활용함으로 인한 공공데이터의 정확성과 지속적인 갱신이 필요 함<br>
- 모든 브라우저에서 동일한 모습으로 서비스가 가능해야 함<br>
- 데이터 검색에 대한 결과를 일정시간 내에 빠르게 응답해야 함<br>
- 잘못된 입력에 대한 유효성 검사와 에러 발생 시 정상적인 동작을 계속 유지해야 함<br>
</pre>

## Exerd 테이블 명세

![Alt Text](ㅇ)

## 구동 화면

- 사랑방 메인화면<br><br>
  ![Alt text](https://user-images.githubusercontent.com/54837242/122635073-c0de0f80-d11c-11eb-969a-7921e6f28c1f.PNG)
- 방 검색 (세부필터)<br><br>
  ![Alt text](https://user-images.githubusercontent.com/54837242/122635095-e4a15580-d11c-11eb-902b-a9cc22a4c222.PNG)
- 검색 결과<br><br>
  ![Alt text](https://user-images.githubusercontent.com/54837242/122635213-92acff80-d11d-11eb-981a-ee5e1247ada2.PNG)
- 방 좋아요 등록목록<br><br>
  ![Alt text](https://user-images.githubusercontent.com/54837242/122635114-0c90b900-d11d-11eb-8b3c-8f98350fc3ec.PNG)
- 공지사항 (유저)<br><br>
  ![Alt text](https://user-images.githubusercontent.com/54837242/122635158-3ea21b00-d11d-11eb-810c-f52e0d792547.PNG)
- 공지사항 (관리자)<br><br>
  ![Alt text](https://user-images.githubusercontent.com/54837242/122635179-63968e00-d11d-11eb-91e0-f59adf8442b9.PNG)
- 아파트 실거래 상세 페이지<br><br>
  ![Alt text](https://user-images.githubusercontent.com/54837242/122635137-27fbc400-d11d-11eb-8a00-4308dbd66e7f.PNG)
