# 날: 숨
실어증 환자 분들이 자연스럽게 말을 하는 그 날까지 함께 하겠습니다.

## 목차
1. 개요
2. 주요 기능
3. 서비스 화면
4. 개발 환경
5. 아키텍처
6. ERD
7. 팀원 소개 및 역할

## 개요
실어증은 뇌질환 또는 우울증 등으로 뇌 언어 영역에 문제가 발생하여 언어 영역이 떨어지는 질병입니다. 실어증의 치료 방안 중 언어 재활이 있으며, 언어 재활은 조기 치료
가 중요합니다. 하지만 실어증 환자 옆에 언어 치료사가 항상 있을 수 없습니다. 그래서 저희는 실어증 환자분들이 시간과 공간의 제약을 받지 않고 재활 치료에 전념할 수 있도록
이 서비스를 기획했습니다. 내쉬는 숨이 말로 이어질 수 있도록 돕고 싶습니다.

## 주요 기능
### 1️⃣ 재활 프로그램
- 이름 대기, 따라 말하기, 듣기 이해력, 유창성 4개 영역에 대한 문제를 제공합니다.
- 환자분들은 문제를 반복해서 품으로써 재활 치료를 진행합니다.
- 유창성 문제의 경우, LLM 모델이 환자분들의 답이 문제(질문)에 대해 문법적으로, 문맥적으로 맞는지 판단합니다.
- 틀린 문제의 경우, 자동으로 복습 문제집에 추가됩니다. 복습 문제집에서 복습을 할 수 있습니다.
### 2️⃣ 실어증 커뮤니티
- 실어증 환자분들이 치료 과정, 정보 등을 서로 공유할 수 있도록 커뮤니티 기능을 제공합니다.
- 커뮤니티는 3개의 카테고리(정보 글, 환자 이야기, 치료 후기)로 구분됩니다.
### 3️⃣ 통계
- 최근 한 달간 주 별로 푼 문제 수, 맞은 문제 수, 틀린 문제 수를 확인할 수 있습니다.
- 따라 말하기의 문제를 풀었을 경우, 많이 틀린 발음(초,중,성)을 확인할 수 있습니다.

## 서비스 화면
### 인트로 화면
![initialPage](https://github.com/hana-nana/Exhale/assets/80585489/085e11ac-a0e0-4097-b7cb-ff7f39220a33)

### 날숨 설명 화면
![whatIsExhale](https://github.com/hana-nana/Exhale/assets/80585489/937e595d-1cdf-49cd-a323-c6efd7963898)

### 로그인, 회원가입 화면
![loginAndSignup](https://github.com/hana-nana/Exhale/assets/80585489/d763330d-b911-499a-a851-e429a285c263)

### 이메일 인증 화면
![emailAuthentication](https://github.com/hana-nana/Exhale/assets/80585489/19194945-61a5-4ee2-8608-f6620977733d)

### 로그인 후 재활코스 메인 화면
![mainPage](https://github.com/hana-nana/Exhale/assets/80585489/0ff5079b-eea9-4a4c-813e-0831391da4ee)

### 이름 대기 문제 화면
![sayObject](https://github.com/hana-nana/Exhale/assets/80585489/0c902a1f-6b1c-45ce-83ff-f78460545877)

### 따라 말하기 문제 화면
![followUpSpeech](https://github.com/hana-nana/Exhale/assets/80585489/11bd2c4b-d596-44b0-9278-bcfb31d1a0b7)

### 듣기 이해력 문제 화면
![listeningComprehension](https://github.com/hana-nana/Exhale/assets/80585489/fdb2212f-5293-434f-b422-f987f2aa6a95)

### 유창성 문제 화면
![fluency](https://github.com/hana-nana/Exhale/assets/80585489/1b5fb4f4-b4a3-4b90-bb2f-d3dfdc91d346)

### 커뮤니티 화면
![communityMain](https://github.com/hana-nana/Exhale/assets/80585489/8c529c4d-10fe-4a3a-b8ff-c57dbc40997b)

### 커뮤니티 글쓰기 화면
![postCreate](https://github.com/hana-nana/Exhale/assets/80585489/8fef8e32-6d69-4d1c-a62b-4d67d58cd713)

### 내 정보(통계) 화면
![mypage](https://github.com/hana-nana/Exhale/assets/80585489/a0ec5f7d-d780-42f4-8832-e0f46d87776e)

## 개발 환경
<table>
<tr>
 <td align="center">언어</td>
 <td>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/Java-orange?style=for-the-badge&logo=Java&logoColor=white"/>
 </td>
</tr>
<tr>
 <td align="center">프레임워크</td>
 <td>
  <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=ffffff"/>
	<img src="https://img.shields.io/badge/Vue-61DAFB?style=for-the-badge&logo=vuedotjs&logoColor=ffffff"/>
 </td>
</tr>
<tr>
 <td align="center">라이브러리</td>
 <td>  
  <img src="https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=SpringBoot&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/springsecurity-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/jwt-6DB33F?style=for-the-badge&logo=jwt&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/gpt-6DB33F?style=for-the-badge&logo=gpt&logoColor=ffffff"/>
 </td>
</tr>
<tr>
 <td align="center">패키지 매니저</td>
 <td>
    <img src="https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm&logoColor=white">
    <img src="https://img.shields.io/badge/maven-02303A?style=for-the-badge&logo=maven&logoColor=white">
</td>
</tr>
<tr>
 <td align="center">인프라</td>
 <td>
  <img src="https://img.shields.io/badge/MYSQL-4479A1?style=for-the-badge&logo=MYSQL&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/mongodb-47A248?style=for-the-badge&logo=mongodb&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/amazons3-569A31?style=for-the-badge&logo=amazons3&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/sonarQube-181717?style=for-the-badge&logo=sonarqube&logoColor=ffffff"/>
 </td>
</tr>
<tr>
 <td align="center">협업툴</td>
 <td>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Gitlab-FC6D26?style=for-the-badge&logo=Gitlab&logoColor=white"/> 
  <img src="https://img.shields.io/badge/Mattermost-0058CC?style=for-the-badge&logo=Mattermost&logoColor=white"/> 
  <img src="https://img.shields.io/badge/jira-0052CC?style=for-the-badge&logo=jira&logoColor=white"/>
 </td>
</tr>
<tr>
 <td align="center">기타</td>
 <td>
  <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white"/>
  <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"/> 
  <img src="https://img.shields.io/badge/postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
 </td>
</tr>
</table>

## 아키텍처
![인프라](https://github.com/hana-nana/Exhale/assets/80585489/ad388d2e-b565-48da-a194-32313e959825)
![백엔드 구조](https://github.com/hana-nana/Exhale/assets/80585489/eddde3b8-245c-4efa-a822-c6f7ef2fa736)

## ERD
![ERD](https://github.com/hana-nana/Exhale/assets/80585489/004bd5e5-e6d1-4b9a-b179-52bacab7860d)

## 와이어프레임
![와이어프레임](https://github.com/hana-nana/Exhale/assets/80585489/77b273bb-77ac-4b11-9f5c-afa141a5fbe4)

## 팀원 소개 및 역할
| 이름   | 기능 및 역할 |
| ----|--------------------------------------------------------------------------- |
| 정건준 |  팀장, Backend </br> PM, 인프라(docker, CI/CD), 재활 게임 API, 통계 API, S3, ChatGPT 적용|
| 김희중 |  팀원, Backend </br> API 명세, 소셜로그인, 커뮤니티 API
| 나하나 |  팀원, Frontend </br> 기능 구현(게시판 CRUD), UI/UX 설계 및 디자인, 와이어프레임, 퍼블리싱(HTML, CSS, JS) |
| 신예지 |  팀원, Backend </br> DB, Spring Security(인증,인가), 사용자 관련 API, 재활 게임 API |
| 조상민 |  팀원, Frontend </br> 기능 구현(회원가입, 로그인, 게시판), 컴포넌트 구조 설계, API 요청, UCC 제작|
