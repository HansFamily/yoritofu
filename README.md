# 🍜 Yori Tofu Website | 요리 두부 웹사이트

**English** | **한국어**

This is the official website for Yori Tofu restaurant. This guide will help you maintain and update the website without needing to know how to code.

이것은 요리 두부 식당의 공식 웹사이트입니다. 이 가이드는 코딩을 모르는 분들도 웹사이트를 유지보수하고 업데이트할 수 있도록 도와드립니다.

## 📁 Important Folders | 중요한 폴더들

```
📂 yoritofu/
├── 📂 public/          ← Put photos here | 사진을 여기에 넣으세요
├── 📂 src/
│   └── 📂 pages/       ← Website pages | 웹사이트 페이지들
│       ├── index.astro     (Home page | 홈페이지)
│       ├── menu.astro      (Menu page | 메뉴 페이지)
│       └── about.astro     (About page | 소개 페이지)
└── 📄 package.json     ← Don't touch this | 건드리지 마세요
```

## 🚀 How to Start Working | 작업 시작하는 방법

### 1. Start the Server | 서버 시작하기
**English:** To see your website while you work on it:
**한국어:** 작업하면서 웹사이트를 보려면:

**Method 1 | 방법 1:**
- Open Terminal | 터미널 열기
- Type: `npm run dev`
- Press Enter | 엔터 키 누르기

**Method 2 | 방법 2:**
- Open `package.json` file
- Click the debug button next to "dev astro dev"

### 2. View Your Website | 웹사이트 보기
**English:** After starting the server:
**한국어:** 서버 시작 후:

- Hold `Cmd` and click: http://localhost:4321/
- Your website will open in the browser | 브라우저에서 웹사이트가 열립니다

### 3. Stop the Server | 서버 중지하기
**English:** When you're done working:
**한국어:** 작업이 끝나면:

- Press `Ctrl + C` in the Terminal | 터미널에서 Ctrl + C 누르기

## 📱 View on Mobile/Tablet | 모바일/태블릿으로 보기

**English:** To see how your website looks on phones and tablets:
**한국어:** 핸드폰이나 태블릿에서 어떻게 보이는지 확인하려면:

1. Open Chrome browser | 크롬 브라우저 열기
2. Go to: Help → Look up "dev" → Click "Open developer tools"
3. Click the mobile/tablet icon in the top-left of the menu
4. 도움말 → "dev" 검색 → "개발자 도구 열기" 클릭
5. 메뉴 왼쪽 상단의 모바일/태블릿 아이콘 클릭

## 📸 Adding Photos | 사진 추가하기

**English:** To add new photos to your website:
**한국어:** 웹사이트에 새 사진을 추가하려면:

1. Put your photo files in the `public/` folder
2. `public/` 폴더에 사진 파일을 넣으세요
3. The photos will be available at: `http://localhost:4321/your-photo-name.jpg`
4. 사진들은 다음 주소로 접근할 수 있습니다: `http://localhost:4321/사진이름.jpg`

## ✏️ Editing Pages | 페이지 편집하기

**English:** To change the content of your website:
**한국어:** 웹사이트 내용을 바꾸려면:

- Click on files in the `src/pages/` folder
- `src/pages/` 폴더의 파일들을 클릭하세요
- Each `.astro` file is a different page on your website
- 각 `.astro` 파일은 웹사이트의 다른 페이지입니다

## 💾 Saving to GitHub | GitHub에 저장하기

**English:** To save your changes and upload them:
**한국어:** 변경사항을 저장하고 업로드하려면:

### Step 1: Add files | 1단계: 파일 추가
```bash
git add .
```
**Or for specific files | 또는 특정 파일만:**
```bash
git add filename.astro
```

### Step 2: Save changes | 2단계: 변경사항 저장
```bash
git commit -m "Your message here"
```
**Example | 예시:**
```bash
git commit -m "Added new menu photos"
git commit -m "새 메뉴 사진 추가"
```

### Step 3: Upload to GitHub | 3단계: GitHub에 업로드
```bash
git push
```

To pull code:
```bash
git pull
```

## ⚠️ Important Rules | 중요한 규칙들

**English:**
- ❌ **DON'T** delete `package.json`, `node_modules/`, or `.git/` folder
- ❌ **DON'T** change file extensions (keep `.astro` files as `.astro`)
- ✅ **DO** put all photos in the `public/` folder
- ✅ **DO** save your work to GitHub regularly

**한국어:**
- ❌ `package.json`, `node_modules/`, `.git/` 폴더를 **절대 삭제하지 마세요**
- ❌ 파일 확장자를 **바꾸지 마세요** (`.astro` 파일은 `.astro`로 유지)
- ✅ 모든 사진을 `public/` 폴더에 **넣으세요**
- ✅ GitHub에 **정기적으로 저장**하세요

## 🆘 Need Help? | 도움이 필요하세요?

**English:** If something goes wrong:
**한국어:** 문제가 생겼다면:

1. Try stopping the server (`Ctrl + C`) and starting it again (`npm run dev`)
2. 서버를 중지(`Ctrl + C`)하고 다시 시작(`npm run dev`)해보세요
3. Make sure you're in the right folder in Terminal
4. 터미널에서 올바른 폴더에 있는지 확인하세요
5. Check that all your files are saved
6. 모든 파일이 저장되어 있는지 확인하세요
