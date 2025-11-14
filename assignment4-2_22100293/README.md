# 도서 목록 관리 시스템 (React)

이 프로젝트는 React를 사용하여 제작된 도서 목록 관리 시스템입니다. 
Bootstrap Modal을 활용한 CRUD(Create, Read, Update, Delete) 기능을 제공합니다.

## 주요 기능

### ✨ 핵심 기능
- 📚 **도서 목록 조회**: 등록된 모든 도서를 카드 형태로 표시
- ➕ **도서 추가**: Modal을 통한 새로운 도서 등록
- ✏️ **도서 수정**: 기존 도서 정보 수정
- 🗑️ **도서 삭제**: 확인 dialog와 함께 도서 삭제
- 🎨 **반응형 디자인**: 모바일, 태블릿, 데스크톱 지원

### 🎯 기술적 특징
- **React Hooks**: useState, useEffect를 활용한 상태 관리
- **Bootstrap 5**: 모던하고 반응형 UI 디자인
- **Bootstrap Modal**: 도서 추가/수정을 위한 모달 인터페이스
- **Bootstrap Icons**: 직관적인 아이콘 시스템
- **폼 유효성 검사**: 실시간 입력 검증 및 에러 메시지
- **애니메이션 효과**: 부드러운 hover 및 transition 효과

### 📊 데이터 구조
각 도서는 다음 정보를 포함합니다:
- **ID**: 고유 식별자
- **제목**: 도서 제목
- **저자**: 저자명
- **출판년도**: 출판 연도
- **장르**: 9가지 장르 분류 (소설, 과학, 역사, 프로그래밍, 판타지, 로맨스, 미스터리, 디스토피아, 자기계발)

## 프로젝트 구조

```
src/
├── components/
│   ├── BookList.js      # 도서 목록 표시 컴포넌트
│   └── BookModal.js     # 도서 추가/수정 모달 컴포넌트
├── App.js               # 메인 애플리케이션 컴포넌트
├── App.css              # 커스텀 스타일
└── index.js             # 애플리케이션 진입점

public/
├── my_data.json         # 초기 도서 데이터 (12권)
└── index.html           # HTML 템플릿 (Bootstrap CDN 포함)
```

## 설치 및 실행

이 프로젝트는 [Create React App](https://github.com/facebook/create-react-app)으로 생성되었습니다.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
