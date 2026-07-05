# [전기차 토탈 관리 플랫폼 - EON]

### 프로젝트 소개

성남시 청소년재단에서 진행한 SW 캠프 팀 프로젝트입니다.  
EON은 전기차 사용자에게 구매·관리·운행 정보를 통합 제공하는 웹 서비스입니다.

개발 기간 : 2025.08 - 2025.11

프로젝트 담당 역할 : 프론트엔드

팀원 소개 : 
<table>
<thead>
<tr>
<th align="center"><a target="_blank" href="https://github.com/euuuuning"><img src="https://github.com/euuuuning.png" width="150" height="150" style="border-radius: 6px"></a></th>
<th align="center"><a target="_blank" href="https://github.com/cherrybbang"><img src="https://github.com/cherrybbang.png" width="150" height="150" style="border-radius: 6px"></a></th>
<th align="center"><a target="_blank" href="https://github.com/CoderGogh"><img src="https://github.com/CoderGogh.png" width="150" height="150" style="border-radius: 6px"></a></th>
</tr>
</thead>
<tbody>
<tr>
<td align="center">이상은<br>팀 대표 및 PM<br><a href="https://github.com/euuuuning">@euuuuning</a></td>
<td align="center">박지유<br>프론트엔드<br><a href="https://github.com/cherrybbang">@cherrybbang</a></td>
<td align="center">정하람<br>백엔드<br><a href="https://github.com/CoderGogh">@CoderGogh</a></td>
</tr>
</tbody>
</table>

팀 깃헙 주소 : https://github.com/orgs/Get-Your-Eon/repositories

:rocket:배포 주소 : https://get-your-eon.vercel.app

### 주요 기능

- 차량별 보조금 검색 및 비교  
- 지역별 보조금(국비, 지방비) 정보 필터링  
- 유저 위치기반을 기준으로 가까운 전기차 충전소 검색  
- 전기차 충전소 운영정보, 충전타입 등의 정보 제공  
- 실시간 API 연동하여 최신 데이터 제공  
- VIte 기반 빠른 빌드

### 상세 기능

- 지역별, 차종별 전기차 보조금 조회
- 차량 모델별 보조금 금액 비교

  <img width="800" height="500" alt="보조금 조회 이미지" src="https://github.com/user-attachments/assets/4f619586-38f0-4536-89ad-3d0bf72898f9" />

   
- 현재 위치 주변의 가까운 전기차 충전소 조회
- 실시간 충전 현황 정보 제공

  <img width="800" height="500" alt="실시간 충전 이미지" src="https://github.com/user-attachments/assets/fa6e09c5-ca21-49c8-8653-7948ad1261bc" />

<br/>

### 개발 환경 설정

1. Node.js (권장 LTS) 설치
2. 의존성 설치
```js
npm install
```
3. 환경 변수 설정
```js
루트 디렉토리에 .env 파일 생성 후 값 입력

VITE_API_BASE_URL=api_base_url
VITE_API_KEY=api_key
VITE_KAKAO_MAP_KEY=kakao_map_api_key
```
4. 개발 서버 실행
```js
npm run dev
```

### 기술 스택

[ Frontend Framework ] - React  
[ Language ] - Javascript  
[ Bundler ] - Vite  
[ Deploy ] - Vercel  

### 디렉토리 구조

```
get-your-eon
    ├──📁public
    │   ├──📁css
    │   └──📁img
    ├──📁src
    │   ├──📁api
    │   ├──📁data
    │   ├──📁pages
    │   ├──📁widgets
    │   ├──📄App.jsx
    │   ├──📄main.jsx
    │   └──📄routes.jsx
    ├── .gitignore
    ├── CHANGELOG.md
    ├── index.html
    ├── ISSUE_TEMPLATE.md
    ├── jsconfig.json
    ├── LICENSE
    ├── package.json
    ├── postcsss.config.cjs
    ├── prettier.config.cjs
    ├── README.md
    ├── tailwind.config.cjs
    ├── vercel.json
    └── vite.config.js

```
