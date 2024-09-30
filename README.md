This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

# 사업자 등록번호 진위여부 확인 Next.js 프로젝트

이 프로젝트는 사용자가 사업자 등록번호를 입력하여 해당 사업자 등록번호의 진위여부를 공공 API를 통해 확인하는 기능을 제공하는 Next.js 애플리케이션입니다.

## 프로젝트 개요

이 애플리케이션은 Next.js로 개발되었으며, Axios를 사용하여 외부 공공 API와 통신합니다. 사용자는 사업자 등록번호를 입력하고, 입력한 번호의 진위여부를 API를 통해 확인할 수 있습니다.

## 기술 스택

- **프레임워크**: Next.js
- **언어**: TypeScript (ES6+)
- **API 통신**: Axios
- **스타일링**: 기본 CSS/SCSS
- **환경 변수**: dotenv

## 프로젝트 설정 및 실행

### 1. 사전 요구 사항

- Node.js (v14 이상 권장)
- npm 또는 yarn 패키지 매니저

### 2. 클론 및 종속성 설치

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
npm install  # 또는 yarn install
```
