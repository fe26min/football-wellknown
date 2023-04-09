# 자율프로젝트 : 축잘알

<div align="center">
  <br />
  <img src="./assets/logo.png" alt="FootBall Well known" />
  <br />
  <h1>서비스 개요</h1>
  <br />
</div>

## 목차

1. [**서비스 소개**](#1)
2. [**기술 스택**](#2)
3. [**시스템 아키텍처**](#3)
4. [**주요기능 및 데모영상**](#4)
5. [**UCC 보러가기**](#5)
6. [**협업 관리**](#6)
7. [**개발 멤버 소개**](#7)
8. [**프로젝트 기간**](#8)
9. [**프로젝트 관련 문서**](#9)

<br/>

<div id="1"></div>

## 💡 서비스 소개

### 서비스 모토

> 축구를 안다고 하는 이들 모두 모여 최고를 가려라

#### 서비스에 대한 한마디

축구 경기와 선수들을 사용자가 추측을 하여 재미를 챙길 수 있는 서비스입니다.

특정 시간에 과도한 트래픽이 몰리는 스포츠 사이트의 문제점을 해결하기 위하여 대규모 트래픽을 소화할 수 있는 서버를 구축하였습니다.

<br/>

<div id="2"></div>

## 🛠️ 기술 스택

<img src="https://img.shields.io/badge/Amazon EC2-FF9900?style=for-the-badge&logo=Amazon EC2&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=Ubuntu&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<br>

<img src="https://img.shields.io/badge/React-FF9900?style=for-the-badge&logo=React&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=Redux&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/CSS3-D24939?style=for-the-badge&logo=CSS3&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=JavaScript&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<br>

<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=for-the-badge&logo=Spring Security&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=Gradle&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/Socket.io-E34F26?style=for-the-badge&logo=Socket.io&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>

<br>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=Redis&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/Amazon S3-569A31?style=for-the-badge&logo=Amazon S3&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<img src="https://img.shields.io/badge/Amazon RDS-527FFF?style=for-the-badge&logo=Amazon RDS&logoColor=white" style="height : auto; margin-left : 10px; margin-right : 10px;"/>
<br/>

<details><summary> <b> 상세 기술스택 및 버전</b> </summary>

| 구분            | 기술스택            | 상세내용               | 버전        |
| ------------- | --------------- | ------------------ | --------- |
| 공통            | 형상관리            | Gitlab             | \-        |
|               | 이슈관리            | Jira               | \-        |
|               | 커뮤니케이션          | Mattermost, Notion | \-        |
| BackEnd       | DB              | RDS(MySQL)         | -         |
|               |                 | MySQL              | -         |
|               |                 | JPA                | \-        |
|               |                 | MongoDB            | 6.0.2     |
|               |                 | Redis              | 7.0.5     |
|               | Java            | Zulu               | 8.33.0.1  |
|               | Spring          | Spring             | 5.3.6     |
|               |                 | Spring Boot        | 2.4.5     |
|               | IDE             | IntelliJ           | 2022.1.3  |
|               | Cloud Storage   | AWS S3             | \-        |
|               | Build           | Gradle             | 7.3.2     |
|               | API Docs        | Postman            |           |
| SmartContract |                 | Solidity           | ^0.8.4    |
|               | IDE             | Remix              | 0.26.3    |
| FrontEnd      | HTML5           |                    | \-        |
|               | CSS3            |                    | \-        |
|               | JavaScript(ES6) |                    | \-        |
|               | React           | React              | 18.2.0    |
|               |                 | Redux              | 8.0.4     |
|               | Node.js         |                    | 16.17.0   |
|               | Web3.js         |                    | ^1.8.0    |
|               | IDE             | Visual Studio Code | 1.70.0    |
| Server        | 서버              | AWS EC2(기본)        | \-        |
|               |                 | AWS EC2(추가)        | -         |
|               | 플랫폼             | Ubuntu             | 20.04 LTS |
|               | CI/CD           | Docker             | 20.10.21  |
|               |                 | Jenkins            | 2.361.2   |

</details>

<br />

<div id="3"></div>

## 🗂️ 시스템 아키텍처

| 시스템 구성                      |
|:---------------------------:|
| ![image](./assets/아키텍쳐.png) |

<br />

<div id="4"></div>

## 🖥️ 주요기능

### 소셜 로그인

- 

### 마이페이지

- 

### 게시글 쓰기
- 

| 마이페이지                      |
|:--------------------------:|
| ![마이페이지](./assets/마이페이지.gif) |

### 경기 정보 페이지

- 

### 팀 정보 페이지

-

### 선수 정보 페이지

-

## 성능 개선

###  Jmeter 결과
 ![image](./assets/test.png)

### MySQL vs MongoDB
 ![image](./assets/mongoTest.png)

<div id="5"></div>

## 🎥 [UCC 보러가기](./assets/자율PJT_서울_2반_A203_UCC경진대회.MP4)

<br />

## 👥 협업 관리

| Jira BurnDown Chart          |
|:----------------------------:|
| ![image](./assets/번다운차트.png) |

| Notion                                                  |
|:-------------------------------------------------------:|
| ![image](./assets/API명세서.png)![image](./assets/회의록.png) |

<br />

## 👪 개발 멤버 소개

<table>
    <tr>
        <td height="140px" align="center"> <a href="https://github.com/깃허브 링크">
            <img src="/assets/고동훤.png" width="140px" /> <br><br> 👑 고동훤 <br>(Back-End) </a> <br></td>
        <td height="140px" align="center"> <a href="https://github.com/깃허브 링크">
            <img src="/assets/고태희.png" width="140px" /> <br><br> 🙂 고태희 <br>(Back-End) </a> <br></td>
        <td height="140px" align="center"> <a href="https://github.com/깃허브 링크">
            <img src="/assets/김경환.png" width="140px" /> <br><br> 😆 김경환 <br>(Back-End) </a> <br></td>
        <td height="140px" align="center"> <a href="https://github.com/fe26min">
            <img src="/assets/박철민.png" width="140px" /> <br><br> 😁 박철민 <br>(Back-End) </a> <br></td>
        <td height="140px" align="center"> <a href="https://github.com/깃허브 링크">
            <img src="/assets/양택훈.png" width="140px" /> <br><br> 😶 양택훈 <br>(Back-End) </a> <br></td>
           <td height="140px" align="center"> <a href="https://github.com/깃허브 링크">
            <img src="/assets/홍석인.png" width="140px" /> <br><br> 😶 홍석인 <br>(Back-End) </a> <br></td>    
</tr>
    <tr>
        <td align="center">FULL STACK<br/>React<br/>Spring<br/></td>
        <td align="center">FULL STACK<br/>React<br/>Spring<br/></td>
        <td align="center">FULL STACK<br/>React<br/>Spring<br/></td>
        <td align="center">FULL STACK<br/>React<br/>Spring</td>
        <td align="center">FULL STACK<br/>React<br/>Spring<br/><br/></td>
        <td align="center">FULL STACK<br/>React<br/>Spring<br/><br/></td>
  </tr>
</table>d>
    </tr>
</table>

<br />

<div id="8"></div>

<div id="8"></div>

## 📆 프로젝트 기간

### 22.10.11 ~ 22.11.21

- 기획 및 설계 : 22.10.11 ~ 22.10.09
- 프로젝트 구현 : 22.10.10 ~ 22.11.11
- 버그 수정 및 산출물 정리 : 22.11.11 ~ 22.11.21

<br />

<div id="9"></div>

## 📋 프로젝트 관련 문서

| 구분      | 링크                                                                                                                      |
|:------- |:-----------------------------------------------------------------------------------------------------------------------:|
| 피그마  | [피그마 바로가기](https://www.figma.com/file/PexqqvH6QoK6HjDrh46UGj/%EC%9E%90%EC%9C%A8?node-id=0%3A1) |
| ERD     | [ERD 바로가기](https://www.erdcloud.com/d/S5d5kSgr8RE7bzMLb)                                                                |
| 빌드/배포   | [빌드/배포 바로가기](/exec/포팅매뉴얼.pdf)                                                                                |
| 시연 시나리오 | [시연 시나리오 바로가기](/exec/시연 시나리오.pdf)                                                                                       |
| 발표자료    | [발표자료 바로가기](/exec/발표자료.pptx)                                                                                            |
