# Air-Clean 프로젝트
![image](https://github.com/user-attachments/assets/c58832ee-2bc9-4ae8-a714-d257ca88be88)



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
      <a href="https://github.com/Absensing">
        <img src="https://avatars.githubusercontent.com/u/158137158?v=4" width="100" style="max-width: 100%;">
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
      <a href="https://github.com/Absensing">김재중</a>
    </td>
    <td align="center">
      <a href="https://github.com/tmddbs9313">조승윤</a>
    </td>
        </tr>
    <tr>
        <td align="center">팀장</td>
        <td align="center">Backend</td>
        <td align="center">Backend</td>
        <td align="center">Frontend</td>
    </tr>
</table>

## 1. ✔개발 환경

<table>
    <tr>
        <th>Front</th>
        <td>HTML/CSS, Bootstrap, Thymeleaf</td>
    </tr>
    <tr>
        <th>Back</th>
        <td>java/javaScript</td>
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
        <td>기능에 오류 수정</td>
    </tr>
</table>

브랜치 별로 커밋을 한 후 충돌이 발생하지 않거나 충돌을 해결한 후 master 브랜치에 merge 하는 방식을 채택했습니다

## 3. 프로젝트 구조

```
└─psmc
    ├─auth
    ├─common
    │  ├─exception
    │  └─model
    │      ├─dto
    │      └─method
    ├─configuration
    │  └─handler
    ├─mainPage
    ├─mediConnect
    ├─mypage
    ├─staff
    ├─theraLink
    └─user
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
        <td>첫화면, 회원가입, 비밀번호 수정, main page 환자 등록, 예약하기, scheduler, theralink, DB 작성</td>
    </tr>
    <tr>
        <th>서정민</th>
        <td>mediconnect, DB 작성, ppt 제작, github 형상 관리, 노션 작성</td>
    </tr>
    <tr>
        <th>조승윤</th>
        <td>mainpage css, mypage css 및 회원정보 수정, header 컴포넌트, navigation 컴포넌트, ppt 제작</td>
    </tr>
    <tr>
        <th>김재중</th>
        <td>staff, DB 작성, 오류 테스트, 노션 작성</td>
    </tr>
</table>
    


## 📅프로젝트 기간

<table>
    <tr>
        <th>전체 개발 기간</th>
        <td>2024.04.25 ~ 2024.06.02</td>
    </tr>
    <tr>
        <th>DB 작성</th>
        <td>2024.04.25 ~ 2024.05.02</td>
    </tr>
    <tr>
        <th>UI 구현</th>
        <td>2024.05.03 ~ 2024.05.23</td>
    </tr>
    <tr>
        <th>기능 구현</th>
        <td>2024.05.04 ~ 2024.05.30</td>
    </tr>
</table>

## 작업관리

1. [discussion 을 통해 팀 전체적으로 오늘 할 일을 정합니다](https://github.com/semi-project-team/PSMC/discussions)
2. [disscussion 을 통해 할당 받은 오늘의 과업에 대해 issue를 작성합니다](https://github.com/semi-project-team/PSMC/issues)
3. [기능을 완수하면 각각의 기능에 맞게 브랜치를 생성후 충돌을 모두 해결한 후 master 브랜치에 merge ](https://github.com/semi-project-team/PSMC/pulls?q=is%3Apr+is%3Aclosed)

   

## ERD

![asdadfasdfdsaf](https://github.com/semi-project-team/PSMC/assets/158137025/622cefcb-b247-41fd-8d21-5261461ce243)


## 기능 설명

### 1. 첫페이지

![1](https://github.com/semi-project-team/PSMC/assets/158137025/17b1888e-8225-40f8-96ae-afe6f1f3e492)


## 구체적인 코드 리뷰
- [예약 및 수정 시간 관련 방식](https://github.com/semi-project-team/PSMC/wiki/진료-시간-및-재활-치료시간-예약하기)
