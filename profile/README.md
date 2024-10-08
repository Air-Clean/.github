# Air-Clean 프로젝트
![image](https://github.com/user-attachments/assets/c58832ee-2bc9-4ae8-a714-d257ca88be88)

<br>

## 목차
- [프로젝트 배경](#프로젝트-배경)
- [🗣프로젝트 소개](#프로젝트-소개)
- [👨🏻‍💻👩🏻‍💻 팀 구성원 및 역할](#팀-구성원-및-역할)
- [✔ 개발 환경](#개발-환경)
- [🌳 브랜치 전략](#브랜치-전략)
- [📌 프로젝트 및 기능 소개](#프로젝트-및-기능-소개)

<br>

## 프로젝트 배경

![image](https://github.com/user-attachments/assets/f7091e14-6401-4055-b131-ee29b4a0e5f1)



    
## 🗣프로젝트 소개

![image](https://github.com/user-attachments/assets/77e2287f-8140-48e6-bd84-5c4f21a6d5b0)


## 팀 구성원 및 역할

<table align="center">
  <tr>
    <td>
      <a href="https://github.com/comaserious">
        <img src="https://avatars.githubusercontent.com/u/158137025?v=4" width="100" style="max-width: 100%;">
      </a>
    </td>
    <td>
      <a href="https://github.com/wjdals83">
          <img src="https://avatars.githubusercontent.com/u/107474713?v=4" width="100" style="max-width: 100%;">
      </a>
    </td>
    <td>
      <a href="https://github.com/gyuhyeok0">
        <img src="https://avatars.githubusercontent.com/u/153148788?v=4" width="100" style="max-width: 100%;">
      </a>
    </td>
    <td>
      <a href="https://github.com/doa0819">
        <img src="https://avatars.githubusercontent.com/u/158136952?v=4" width="100" style="max-width: 100%;">
      </a>
    </td>
    <td>
      <a href="https://github.com/tmddbs9313">
          <img src="https://avatars.githubusercontent.com/u/127907841?v=4" width="100" style="max-width: 100%;">
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/comaserious">이호준</a>
    </td>
    <td align="center">
      <a href="https://github.com/wjdals83">서정민</a>
    </td>
    <td align="center">
      <a href="https://github.com/gyuhyeok0">최규혁</a>
    </td>
    <td align="center">
      <a href="https://github.com/doa0819">이도아</a>
    </td>
    <td align="center">
      <a href="https://github.com/tmddbs9313">조승윤</a>
    </td>
        </tr>
    <tr>
        <td align="center">팀장</td>
        <td align="center">Backend</td>
        <td align="center">Backend</td>
        <td align="center">Backend</td>
        <td align="center">Frontend</td>
    </tr>
</table>

## 1. ✔개발 환경

<table>
    <tr>
        <th>Front</th>
        <td>React, CSS, Bootstrap</td>
    </tr>
    <tr>
        <th>Back</th>
        <td>java/jsx, jpa</td>
    </tr>
    <tr>
        <th>DB</th>
        <td>mySql</td>
    </tr>
    <tr>
        <th>버전 및 이슈 관리</th>
        <td>Github</td>
    </tr>
    <tr>
        <th>협업 툴</th>
        <td>Notion, Miro, Figma</td>
    </tr>
    <tr>
        <th>서비스 배포 환경</th>
        <td>jar</td>
    </tr>
</table>

## 2.🌳 브랜치 전략
 기능 별로 이름을 정하여 브랜치를 생성했습니다

<table>
    <tr>
        <th>🎨Html&css</th>
        <td>뷰포트의 이미지를 생성하는 기능</td>
    </tr>
    <tr>
        <th>✨Feature</th>
        <td>CRUD 등 backend 관련 기능</td>
    </tr>
    <tr>
        <th>:page_with_curl: DB</th>
        <td>DB 업데이트</td>
    </tr>
    <tr>
        <th>🐞Bug</th>
        <td>기능 오류 수정</td>
    </tr>
</table>

브랜치 별로 커밋을 한 후 충돌이 발생하지 않거나 충돌을 해결한 후 master 브랜치에 merge 하는 방식을 채택했습니다

## 3. 프로젝트 구조

```
Spring Boot (Backend)
----------------------
├── build/
├── gradle/
├── gradlew, gradlew.bat
├── settings.gradle
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── aircleanprojectback/
│   │   │       ├── AirCleanProjectBackApplication.java 
│   │   │       └── restapi/
│   │   │           ├── auth/        
│   │   │           ├── branch/    
│   │   │           ├── branchOrigin/
│   │   │           ├── car/         
│   │   │           ├── common/     
│   │   │           ├── facility/   
│   │   │           ├── laundry/   
│   │   │           ├── mainpage/   
│   │   │           ├── member/     
│   │   │           ├── report/    
│   │   │           ├── stock/       
│   │   │           ├── util/      
│   │   │           └── water/   
│   │   └── resources/
│   │       ├── application.yml      
│   │       └── static/              
└── uploads/       
                 
React (Frontend)
-----------------
├── README.md
├── node_modules/               
├── package-lock.json               
├── package.json                  
├── public/
│   └── index.html                
└── src/
    ├── App.js                       
    ├── AuthContext.js               
    ├── Store.js                     
    ├── api/                        
    ├── apis/                      
    ├── assets/                    
    ├── common/                   
    ├── components/                 
    ├── data/                       
    ├── hooks/                    
    ├── index.js                   
    ├── layouts/                  
    ├── modules/                   
    ├── pages/                    
    ├── styles/                    
    └── utils/                     

```

충돌을 방지하기 위해서 기능 별로 역할을 분담하고 기능별로 패키지를 구성하였습니다


## 🙆‍♂️ 역할 분담

<table>
    <tr>
        <th>이름</th>
        <th></th>
    </tr>
    <tr>
        <th>이호준</th>
        <td>재무관리, 인적자원, 차량관리, 시설물관리(back), 지점관리(front)</td>
    </tr>
    <tr>
        <th>서정민</th>
        <td>재고관리, 시설물관리(front)</td>
    </tr>
    <tr>
        <th>조승윤</th>
        <td>물류시스템관리</td>
    </tr>
    <tr>
        <th>이도아</th>
        <td>보고서관리</td>
    </tr>
    <tr>
        <th>최규혁</th>
        <td>지점관리(back), 세탁물관리, 서버 준비 및 배포</td>
    </tr>
</table>
    


## 📅프로젝트 기간

<table>
    <tr>
        <th>전체 개발 기간</th>
        <td>2024.07.02 ~ 2024.08.13</td>
    </tr>
    <tr>
        <th>문서 작성 및 피그마</th>
        <td>2024.07.02 ~ 2024.07.08</td>
    </tr>
    <tr>
        <th>엔티티 작성</th>
        <td>2024.07.08 ~ 2024.07.11</td>
    </tr>
    <tr>
        <th>UI 구현</th>
        <td>2024.07.11 ~ 2024.08.12</td>
    </tr>
    <tr>
        <th>기능 구현</th>
        <td>2024.07.11 ~ 2024.08.12</td>
    </tr>
</table>

## 작업관리

1. [Wiki를 활용하여 매일 오전 팀원이 모여 회의록 목록을 작성니다](https://github.com/Air-Clean/airclean-spring/wiki/%ED%9A%8C%EC%9D%98%EB%A1%9D-%EB%AA%A9%EB%A1%9D)
2. [회의를 통해 할당 받은 오늘의 과업에 대해 issue를 작성합니다 - airclean-spring](https://github.com/Air-Clean/airclean-spring/issues)
3. [회의를 통해 할당 받은 오늘의 과업에 대해 issue를 작성합니다 - airclean-react](https://github.com/Air-Clean/airclean-reactjs/issues)
4. [기능을 완수하면 각각의 기능에 맞게 브랜치를 생성하여 충돌을 모두 해결한 후 master 브랜치에 merge합니다 - airclean-spring](https://github.com/Air-Clean/airclean-spring/pulls)
5. [기능을 완수하면 각각의 기능에 맞게 브랜치를 생성하여 충돌을 모두 해결한 후 master 브랜치에 merge합니다 - airclean-react](https://github.com/Air-Clean/airclean-reactjs/pulls)

   

## ERD

<img width="1089" alt="주제영역1_LOG" src="https://github.com/user-attachments/assets/70c88b7b-30f1-4a09-bd85-062b99b3788a">



## 기능 설명
#### 기능 한눈에 보기
![image](https://github.com/user-attachments/assets/f233fffd-a739-4031-80f1-14c92081ff39)

