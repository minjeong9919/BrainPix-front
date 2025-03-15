# 창의적인 사람들의 공간 BrainPIX

![image](https://github.com/user-attachments/assets/11a611df-9b77-4596-b2cf-ec299d1242a7)

</br>

## 배포 URL
🔗 https://www.brainpix.net </br>
> 테스트 ID: a1sw110 </br>
> 테스트 PW: aa123123 </br>

<br/>

## 프로젝트 실행
```
// 1️⃣ 저장소 클론
git clone https://github.com/yourusername/brainpix.git

// 2️⃣ 패키지 설치
npm install

// 3️⃣ 개발 서버 실행
npm run dev
```

✨ 실행 전 환경 변수를 설정해주세요!
> 프로젝트 루트 폴더에 '.env'을 생성 후, 아래를 붙여넣어주세요.
> 
```
VITE_BASE_URL=https://api.brainpix.net
VITE_S3_URL=https://brainpix.s3.ap-northeast-2.amazonaws.com
```
<br/>

## 프로젝트 소개
> **BrainPIX**는 사람들이 자신의 아이디어를 공유하고 판매하거나, 협력자를 찾을 수 있는 플랫폼입니다. <br/>
> 기업과 개인 모두 아이디어를 제안하여 협력자를 찾거나 거래할 수 있습니다.

<br/>

## 사용자 기능
- 💡 **아이디어 거래**: 자신의 아이디어를 사고팔 수 있습니다.
- 👥 **협업 찾기**: 프로젝트에 적합한 팀원을 찾을 수 있습니다.
- 🚀 **요청 과제**: 직원 채용 없이 요청 과제를 등록하고, 신청할 수 있습니다.

<br/>

## 구현 내용
[ **전반적인 프로젝트 세팅** ]
  - GitHub Actions를 활용하여 CI/CD 자동화 
  - stylint, eslint, prettier을 적용하여 코드의 일관성, 통일성 유지
  - 특정 색상, 폰트 사이즈를 지정하여 글로벌 변수로 설정
    
[ **공통 컴포넌트 구현** ]
  1. Toast
     - 토스트 컴포넌트를 타입별로 구현 ( 에러, 성공, 일반 )
     - 토스트의 상태를 Context API로 관리
     - 토스트의 사용 로직이 단순해짐
  2. Image
     - 이미지 url 에러 상황 및 빈 url 문자열일 경우 처리를 위한 함수 구현
     - 모든 코드에는 img 태그 대신 Image 컴포넌트를 적용
  3. 캐러셀
     - 버튼이 위, 가운데 있을 경우 두 가지 타입을 하나의 컴포넌트로 구현
     - 재사용성을 높이고, 코드의 중복 감소
  4. 헤더
     - 로컬 스토리지를 활용한 최근 검색어 기능 구현
     - 검색창에 디바운스 적용하여 빈번한 이벤트 발생 제어
    
[ **페이지 구현** ]
  1. 마이페이지 - 메인 (최근 기록, 알림)
     - intersectionObserverAPI 커스텀 훅을 구현하여 무한 스크롤 구현
  2. 마이페이지 - 내 정보
  3. 마이페이지 - 포트폴리오
  4. 마이페이지 - 메신저
  5. 로그인/회원가입 페이지
     - react-hook-form을 이용해 폼데이터를 관리 및 유효성 검사를 적용하여 리렌더링 횟수 감소
<br/>

## 기술적 기능 및 최적화
- 🔀 **CI/CD 자동화 파이프라인 구축**  
  - GitHub Actions를 활용하여 CI/CD 자동화
  - 배포 전 코드 lint, stylelint 및 빌드 오류 자동 검출
  - `develop` 브랜치 동기화 시 vercel을 통한 자동 배포 실행 
- 🥪 **Context API 기반 토스트 컴포넌트 구현**  
  - 커스텀 토스트 컴포넌트 직접 구현
  - Context API를 활용한 전역 상태 관리
  - 어디서든 쉽게 호출 가능하도록 최적화
- 🔀 **rollup-plugin-visualizer을 이용한 번들링 최적화 진행**  
  - rollup-plugin-visualizer를 활용하여 번들 사이즈를 시각적으로 확인
  - react-quill-new 라이브러리의 텍스트 에디터를 컴포넌트화하여 lazy import 적용
  - 초기 빌드 시간 단축 및 번들 크기 감소
- 🔀 **react-helmet-async를 활용한 SEO 최적화**  
  - `react-helmet-async`를 사용하여 페이지별로 제목(title), 설명(description), Open Graph(OG) 메타태그 동적 적용 

<br/>

## 팀원 소개
<table>
  <tbody>
    <tr>
      <td width="200" align="center"><img width="200" src="https://github.com/user-attachments/assets/a22e8df2-2819-4fd5-a077-3f357ce4b0d8"></td>
      <td width="200" align="center"><img width="200" src="https://github.com/user-attachments/assets/a47f316f-e0a1-4a3e-bb88-3ad5e8ad1cd0"></td>
      <td width="200" align="center"><img width="200" src="https://github.com/user-attachments/assets/6693bc2d-3613-45ab-98fa-1ed93c5d6b36"></td>
      <td width="200" align="center"><img width="200" src="https://github.com/user-attachments/assets/65cd81e6-9125-42f6-ae5f-c85d61a128d6"></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/ggjiny">권소현</td>
      <td align="center"><a href="https://github.com/Young2un">김민정</td>
      <td align="center"><a href="https://github.com/minjeong9919">임가희</td>
      <td align="center"><a href="https://github.com/bokeeeey">최규호</td>
    </tr>
  </tbody>
</table>

<br/>

## 개발 환경
### 기술스택 <br/>
<div>
  <img src="https://img.shields.io/badge/React-000000?style=flat-square&logo=React&logoColor=#61DAFB" height="25"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" height="25"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" height="25"/>
  <img src="https://img.shields.io/badge/ESLint-4B32C3?style=flat-square&logo=eslint&logoColor=white" height="25"/>
  <img src="https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=white" height="25" />
  <img src="https://img.shields.io/badge/Stylelint-263238?style=flat-square&logo=stylelint&logoColor=white" height="25"/>
 <br>
  <img src="https://img.shields.io/badge/Sass-CC6699?style=flat-square&logo=Sass&logoColor=white" height="25"/>
  <img src="https://img.shields.io/badge/CSS%20Modules-000000?style=flat-square&logo=css-modules&logoColor=white" height="25"/>
 <br>
  <img src="https://img.shields.io/badge/Tanstack%20Query-FF4154?style=flat-square&logo=react-query&logoColor=white" height="25"/>
  <img src="https://img.shields.io/badge/React%20Hook%20Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white" height="25"/>
  <img src="https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=Axios&logoColor=white" height="25"/>
  <img src="https://img.shields.io/badge/React%20Router-CA4245?style=flat-square&logo=react-router&logoColor=white" height="25"/>
</div>

### 협업 툴
<div>
  <a href="https://www.notion.so/New-BrainPIX-1696f0b09f0d80288d6df53aa166d2f3">
    <img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white" height="25"/>
  </a>
  <a href="https://www.figma.com/design/JhG7OHDn01aHjB1JR7sygy/BrainPIX-%ED%8C%80-%EC%9E%91%EC%97%85(%ED%8C%80-%EC%A0%84%EC%B2%B4)?node-id=3-68&p=f&t=EWjQGtZ4p1ntjL0R-0">
    <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white" height="25"/>
  </a>
  <img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=Discord&logoColor=white" height="25"/>
</div>

### CI/CD
<div>
  <img src="https://img.shields.io/badge/githubActions-2088FF?style=flat-square&logo=githubactions&logoColor=white" height="25"/>
  <img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=Vercel&logoColor=white" height="25"/>
</div>

<br/>

## 채택한 개발 기술과 선정 이유
### React (TypeScript)
- React (TypeScript)
  - 사용자와의 상호작용이 많은 프로젝트이기에 react를 선정
  - TypeScript를 사용하여 타입 안전성을 확보하고, 코드의 안정성 향상
  - 또한 기업과 개인, 두 개의 비슷하지만 다른 두 개의 데이터 구조의 명확한 구분을 위해 typescript를 선택
### SCSS(sass)
  - 추가적인 학습 필요 없이 기존의 css에서 향상된 라이브러리이기에, css 라이브러리 관련 경험이 모두 달랐던 저희 팀원 모두 어렵지 않게 사용할 수 있을 것 같아 선정
  - scss(sass)의 적용을 선택하여 글로벌 변수 적용을 통해 일관된 스타일 유지 및 유지보수 편의성 증가, 다양한 내장 기능을 통해 가독성 향상 
### React Query, Axios
  - 무한 스크롤을 적용할 상황이 많기 때문에 이를 편하게 구현하고자 선택
  - 데이터 캐싱을 통해 불필요한 네트워크 요청 수의 감소로 효율성 향상
  - axios와 React query를 함께 사용함으로써 더욱 간단한 데이터 요청 구조 유지
### eslint, prettier, stylint
- 정해진 규칙에 따라 자동적으로 코드 스타일을 정리해 코드의 일관성을 유지

<br/>

## 간단한 컨벤션 소개
**[ 코드 컨벤션 ]**
- type 말고 interface로 통일 (특정한 상황 외)
- 변수는 camelCase, 상수는 SNAKE_CASE 사용
- 스타일링 단위는 px, className은 camelCase로 통일
**[ 깃 컨벤션 ]**
- fork 떠서 각자 작업 진행
- 이름
> 이슈는 **`feat: 기능 추가`** 로 이름 생성 <br/>
> PR은 **`feat / 기능 추가`** 로 이름 생성 <br/>
> 커밋 메시지는 **`feat: 기능 추가`** 처럼 작성 <br/>
> 브랜치 이름은 **`feat/createInput`** 처럼 타입/기능 구성으로 생성, 기능의 경우 camelCase로 작성 <br/>

<br/>

## 프로젝트 구조

```
BRAINPIX-front
┣ 📜README.md
┣ 📜.eslintrc.js
┣ 📜.gitignore
┣ 📜.prettierrc
┣ 📜.stylelintrc.json
┣ 📜package-lock.json
┣ 📜package.json
┣ 📜tsconfig.json
┣ 📜tsconfig.app.json
┣ 📜tsconfig.node.json
┣ 📜vite.config.ts
📦src
 ┣ 📂apis
 ┣ 📂assets
 ┃ ┣ 📂icons
 ┃ ┗ 📂images
 ┣ 📂components
 ┃ ┣ 📂common
 ┃ ┃ ┣ 📂button
 ┃ ┃ ┃ ┣ 📜ButtonGroup.tsx
 ┃ ┃ ┃ ┗ 📜buttonGroup.module.scss
 ┃ ┃ ┣  ...
 ┃ ┣ 📂my-page
 ┃ ┃ ┣ 📂info
 ┃ ┃ ┣ 📂message
 ┃ ┃ ┣ ...
 ┣ 📂constants
 ┣ 📂contexts
 ┣ 📂hooks
 ┣ 📂pages
 ┃ ┣ 📂collaboration
 ┃ ┃ ┣ 📜CollaborationMain.tsx
 ┃ ┃ ┣ 📜collaborationMain.module.scss
 ┃ ┃ ┣ ...
 ┃ ┣ 📂errorPage
 ┃ ┣ 📂idea-market
 ┃ ┣ ...
 ┣ 📂styles
 ┃ ┣ 📜_buttons.scss
 ┃ ┣ 📜_colors.scss
 ┃ ┣ 📜_components.scss
 ┃ ┣ 📜_fonts.scss
 ┃ ┣ 📜_layout.scss
 ┃ ┣ 📜_mixins.scss
 ┃ ┣ 📜_reset.scss
 ┃ ┣ 📜global.scss
 ┃ ┣ 📜main.scss
 ┃ ┗ 📜quillStyles.css
 ┣ 📂types
 ┣ 📜App.tsx
 ┣ 📜global.d.ts
 ┣ 📜main.tsx
 ┣ 📜routes.tsx
 ┣ 📜seoMetaTag.tsx
 ┗ 📜vite-env.d.ts
```


