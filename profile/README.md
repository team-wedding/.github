<div align="center">
  <h1>우결, 우리 결혼해요</h1>
  <p>💍 맞춤형 청첩장 제작 및 RSVP 관리 서비스 💍</p>
</div>

<br/>

<div align="center">
  <img src="https://github.com/user-attachments/assets/ebbff996-084a-4c42-9fda-f571f5b7699c" alt="Main" style="border-radius: 10px; width: 180px"/>
</div>

<br/>


<div align="center">
  <a href="https://woogyeol.site/">🔗 Service Link</a>
  &nbsp; | &nbsp;
  <a href="https://motley-sundae-448.notion.site/19e9673ec79780a3b17bed3825f5fa8c?pvs=74">📒 Notion</a>
  &nbsp; | &nbsp;
  <a href="https://app.swaggerhub.com/apis-docs/GHOONGHOON_1/wedding/1.0.0">📗 Swagger</a>
  &nbsp; | &nbsp;
  <a href="https://www.figma.com/design/Amij7OxsmnsATHkYM5PO52/Woo-Gyeol?t=urUor9ri0Uegu5pe-0">🎨 Figma</a>
  &nbsp; | &nbsp;
  <a href="https://dbdiagram.io/d/675804ade9daa85aca3a38e3">⛓️ ERD</a>
</div>

---

## ✍️ 프로젝트 개요

**💌 프로젝트 명** : 우결, 우리 결혼해요

**💌 프로젝트 기간** : 2025.01 ~ 2025.07

**💌 프로젝트 소개** : 우리 결혼해요는 사용자가 모바일 청첩장을 직접 커스터마이징할 수 있는 플랫폼입니다. 하객들은 청첩장에 참석 여부, 축하 메세지, 실시간 포토월을 남길 수 있으며, 사용자는 집계된 데이터들을 엑셀 파일로 확인할 수 있습니다.

---

## 📁 주요 기능

#### 1️⃣ 청첩장 관리
나만의 청첩장을 생성, 수정, 조회, 삭제할 수 있습니다.

#### 2️⃣ 청첩장 만들기: 3단계 입력과 8가지 선택 기능
3단계의 입력 과정을 거쳐 청첩장을 만들 수 있습니다.
입력 과정에서 캘린더, 지도/교통수단, 갤러리, 축의금, 연락하기, 공지사항, 글꼴, 배경음악 8가지의 선택 정보 중 원하는 기능을 골라 청첩장에 포함시킬 수 있습니다.

#### 3️⃣ 청첩장 공유
제작한 청첩장을 하객들에게 공유할 수 있습니다.
URL 복사, 카카오, QR 코드 3가지의 방법을 통해 공유할 수 있습니다.

#### 4️⃣ RSVP: 참석여부 관리
하객들로부터 참석여부 데이터를 받고 이를 관리할 수 있습니다. 
총 통계 데이터 및 상세 목록을 확인할 수 있으며, 해당 정보를 엑셀 파일로 다운로드할 수 있습니다.

#### 5️⃣ 포토톡: 실시간 포토월
하객들로부터 실시간 포토월 데이터를 받을 수 있습니다.
하객들은 사진과 축하메세지를 입력하여 포토월을 등록할 수 있고, 청첩장 제작자는 갤러리를 통해 이미지들을 다운로드하고 삭제할 수 있습니다.

#### 6️⃣ 다크 모드
다크 모드를 통해 청첩장의 색감 반전을 경험할 수 있습니다. 

---

## 💡 프로젝트 특징

 1️⃣ **다양한 기술 스택 활용**

  기존에 경험해보지 못한 라이브러리, 인프라, 번들러 등을 적극 활용하였습니다.
  프론트엔드는 Tailwind CSS, Storybook, Zustand 등 스타일링 및 상태 관리 라이브러리를 활용하였으며, 백엔드는 Sequelize ORM, AWS EC2/S3, CloudType 등의 다양한 인프라를 활용하였습니다.
    
 2️⃣ **사용자 친화적 서비스**
 
  사용자에게 친화적이고 편리한 서비스를 제공하기 위해 소셜 로그인, 자동 저장, 미리 보기 기능을 구현하였고, RSVP 데이터를 엑셀 파일로 다운로드할 수 있도록 하였습니다.
    
 3️⃣ **코드 그라운드 룰 기반 협업**

  커밋 컨벤션 및 ISSUE & PR 템플릿 지정, 코드 그라운드 룰 및 브랜치 전략을 사전에 정의 한 후 개발함으로써 원활한 협업을 진행하였습니다.
  주차 별 스프린트와 백로그를 작성하며 프로젝트의 진행 상황을 체계적으로 정리했습니다.

  💁🏻‍♂️ 프로젝트의 특징에 대한 더 자세한 사항은 <a href="https://motley-sundae-448.notion.site/19e9673ec79780a3b17bed3825f5fa8c?pvs=74"> 팀 노션 페이지</a>를 참고해 주세요!
    
---

## 🚨 트러블 슈팅

1️⃣ **배포 시 보안 프로토콜 문제**

문제: 서비스 배포 시 http 프로토콜로 인해 브라우저 요청이 차단되는 문제

해결: SSL 인증서 발급을 통해 http를 https로 리디렉션하여 해결

2️⃣ **package-lock.json 충돌 문제**

문제: 새로운 라이브러리 설치 시 package-lock.json이 의도치 않게 변경되는 문제

해결: 팀원 간 node, npm 버전 통일로 해결

3️⃣ **AWS S3 이미지 업로드 시간 단축**

문제: AWS S3에 업로드된 이미지 로딩 시간 지연 문제

해결: 픽셀 단위로 이미지를 줄여 관리함으로써 이미지 업로드 시간 단축

---

## ⚙️ 기술 스택

<table>
  <thead>
    <tr>
      <th style="width: 160px;">분류</th>
      <th style="width: 1000px;">기술 스택</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>프론트엔드</td>
      <td>
        <img src="https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB"/>
        <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white"/>
        <img src="https://img.shields.io/badge/-React%20Query-FF4154?style=for-the-badge&logo=react%20query&logoColor=white"/>
        <img src="https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white"/>
        <img src="https://img.shields.io/badge/Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white"/>
        <img src="https://img.shields.io/badge/Zustand-%23F8E71C?style=for-the-badge&logo=&logoColor=black"/>
      </td>
    </tr>
    <tr>
      <td>백엔드</td>
      <td>
        <img src="https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB"/>
        <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"/>
        <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white"/>
        <img src="https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white"/>
        <img src="https://img.shields.io/badge/JWT-black?style=for-the-badge&logo=JSON%20web%20tokens"/>
      </td>
    </tr>
    <tr>
      <td>데이터베이스</td>
      <td>
        <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white"/>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
      </td>
    </tr>
    <tr>
      <td>인프라</td>
      <td>
        <img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazon-ec2&logoColor=white"/>
        <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white"/>
        <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=Docker&logoColor=white"/>
      </td>
    </tr>
    <tr>
      <td>모니터링</td>
      <td>
        <img src="https://img.shields.io/badge/Sentry-362D59?style=for-the-badge&logo=sentry&logoColor=white"/>
      </td>
    </tr>
    <tr>
      <td>협업 & 문서화</td>
      <td>
        <img src="https://img.shields.io/badge/Figma-%23F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
        <img src="https://img.shields.io/badge/Zep-000000?style=for-the-badge&logo=&logoColor=white"/>
        <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"/>
        <img src="https://img.shields.io/badge/swagger-%2385EA2D?style=for-the-badge&logo=swagger&logoColor=black"/>
        <img src="https://img.shields.io/badge/GitHub%20Projects-181717?style=for-the-badge&logo=github&logoColor=white"/>
        <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"/>
      </td>
    </tr>
  </tbody>
</table>

---

## 🧑‍💻 팀원 소개

<table>
  <tr>
    <td>
      <img src="https://avatars.githubusercontent.com/u/102416278?v=4" width="120px" height="120px"/>
    </td>
    <td>
      <img src="https://avatars.githubusercontent.com/u/55120757?v=4" width="120px" height="120px"/>
    </td>
    <td>
      <img src="https://avatars.githubusercontent.com/u/128888732?v=4" width="120px" height="120px"/>
    </td>
    <td>
      <img src="https://avatars.githubusercontent.com/u/120161508?v=4" width="120px" height="120px"/>
    </td>
  </tr>

  <tr>
    <td>
      <a href="https://github.com/eesoyeon">
        이소연
      </a>
    </td>
    <td>
      <a href="https://github.com/heebeom-song">
        송희범
      </a>
    </td>
    <td>
      <a href="https://github.com/chaeon1">
        황채연
      </a>
    </td>
    <td>
      <a href="https://github.com/jonghoon-L">
        이종훈
      </a>
    </td>
 
</table>
  <table>
    <tr>
        <td>
        <img src="https://avatars.githubusercontent.com/u/102887277?v=4" width="120px" height="120px"/>
        </td>
        <td>
        <img src="https://avatars.githubusercontent.com/u/101189924?v=4" width="120px" height="120px"/>
        </td>
        <td>
        <img src="https://avatars.githubusercontent.com/u/121949750?v=4" width="120px" height="120px"/>
        </td>
    </tr>
    <tr>
        <td>
        <a href="https://github.com/meteorqz6">
            남유성
        </a>
        </td>
        <td>
        <a href="https://github.com/nowrobin">
            한정욱
        </a>
        </td>
        <td>
        <a href="https://github.com/wlqgkrry">
            오지현
        </a>
        </td>
    </tr>
  </table>