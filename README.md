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

## 기술적 기능 및 최적화
- 🔀 **CI/CD 자동화 파이프라인 구축**  
  - GitHub Actions를 활용하여 **CI/CD 자동화**  
  - **배포 전 코드 lint, stylelint 및 빌드 오류 자동 검출**  
  - `develop` 브랜치 동기화 시 vercel을 통한 **자동 배포 실행**  

- 🥪 **Context API 기반 토스트 컴포넌트 구현**  
  - 커스텀 토스트 컴포넌트 직접 구현
  - **Context API**를 활용한 **전역 상태 관리**  
  - 어디서든 쉽게 호출 가능하도록 최적화
 
- 🔀 **rollup-plugin-visualizer을 이용한 번들링 최적화 진행**  
  - **rollup-plugin-visualizer**를 활용하여 번들 사이즈를 시각적으로 확인
  - react-quill-new 라이브러리의 텍스트 에디터를 컴포넌트화하여 **lazy import 적용**
  - **초기 빌드 시간 단축 및 번들 크기 감소**
 
- 🔀 **react-helmet-async를 활용한 SEO 최적화**  
  - `react-helmet-async`를 사용하여 페이지별로 **제목(title), 설명(description), Open Graph(OG) 메타태그 동적 적용**  

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

## 채택한 개발 기술과 브랜치 전략
### React (TypeScript), SCSS
- React (TypeScript)
  - TypeScript를 사용하여 타입 안전성을 확보하고, 코드의 안정성을 높였습니다.
  - 컴포넌트화를 통해 추후 유지보수와 재사용성을 고려했습니다.
- SCSS
  - SCSS는 클래스 이름을 고유하게 부여할 수 있어, 일관된 네이밍 컨벤션을 유지하는 데 필요한 비용을 절약할 수 있어 채택하였습니다.
   
### React Query, Axios

### eslint, prettier
- 정해진 규칙에 따라 자동적으로 코드 스타일을 정리해 코드의 일관성을 유지하고자 하고 있습니다.
- 코드 품질 관리는 eslint에, 코드 포맷팅은 prettier에 일임해 사용하고 있습니다.
- airbnb의 코딩 컨벤션을 참고하고 있습니다.
- 협업 시 매번 컨벤션을 신경 쓸 필요 없이 빠르게 개발하는 데에 목적에 두었습니다.

### 브랜치 전략
- Git-flow 전략을 기반으로 main, develop 브랜치를 운용했습니다.
- main, develop 브랜치로 나누어 개발을 하였습니다.
  - **main** 브랜치는 배포 단계에서만 사용하는 브랜치입니다.
  - **develop** 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치입니다.

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
<br>
```


