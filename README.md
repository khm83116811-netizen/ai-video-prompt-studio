# AI Video Prompt Studio

AI 영상 제작을 위한 프롬프트 스튜디오 — 22개 카테고리, 150+ 프리셋

## 로컬 개발

```bash
npm install
npm run dev
```

## 빌드

```bash
npm run build
```

## Vercel 배포 방법

### 방법 1: GitHub 연동 (추천)

1. GitHub에 이 프로젝트를 push
2. [vercel.com](https://vercel.com) 에서 GitHub로 로그인
3. "Import Project" → 이 저장소 선택
4. Framework Preset: **Vite** 자동 감지됨
5. "Deploy" 클릭 → 완료!

### 방법 2: Vercel CLI

```bash
npm i -g vercel
vercel
```

배포 후 받게 되는 URL (예: `https://your-app.vercel.app`)을 다음 단계인 PWA 전환에서 사용합니다.
