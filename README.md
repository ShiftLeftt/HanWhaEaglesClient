# HanWhaEaglesClient

한화이글스 클라이언트 프로젝트

## 🚀 시작하기

### 1. 프로젝트 클론

```bash
git clone https://github.com/ShiftLeftt/HanWhaEaglesClient.git

```

### 2. 의존성 설치

```bash
npm install
```

### 3. TypeScript 전역 설치 (선택사항)

```bash
npm install -g typescript
```

## 📁 프로젝트 구조

```
HanWhaEaglesClient/
├── project/
│   └── src/
│       └── index.ts        # 메인 TypeScript 파일
├── dist/                   # 컴파일된 JavaScript 파일들
├── index.html              # 메인 HTML 파일
├── package.json
├── tsconfig.json           # TypeScript 설정
└── README.md
```

## 🛠️ 개발 명령어

### 빌드

```bash
npm run build
```

- TypeScript 파일을 JavaScript로 컴파일
- 결과물은 `dist/` 폴더에 생성

### 개발 모드 (자동 빌드)

```bash
npm run dev
```

- `project/src/` 폴더의 TypeScript 파일 변경을 감시
- 파일 수정 시 자동으로 빌드 후 실행
- 개발 중에는 이 명령어 사용 권장

## 💻 개발 환경 설정

1. **코드 작성**: `project/src/index.ts` 파일에서 TypeScript 코드 작성
2. **자동 빌드**: `npm run dev` 실행 후 파일 수정하면 자동으로 컴파일됨
3. **브라우저 확인**: `index.html` 파일을 브라우저에서 열어 결과 확인

## 📋 요구사항

- Node.js (v14 이상)
- npm

## 🔧 기술 스택

- TypeScript
- Node.js
- Nodemon (개발용)
- ts-node (개발용)
