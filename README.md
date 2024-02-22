# SoraT2V
SoraT2V is an open-source project that simplifies video creation by allowing users to generate videos online with OpenAI's Sora model using text, featuring easy one-click website deployment.
👉 [SoraT2V](https://sora-text-to-video.app)

<div align="left">

English | [简体中文](https://github.com/SoraT2V/SoraT2V/blob/main/README.zh-CN.md)

</div>

## Quick Started

### Deploy on Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FSoraT2V%2FSoraT2V&project-name=SoraT2V&repository-name=SoraT2V&external-id=https%3A%2F%2Fgithub.com%2FSoraT2V%2FSoraT2V%2Ftree%2Fmain)

### 1. Clone project

```bash
git clone git@github.com:SoraT2V/SoraT2V.git
```

### 2. Install dependencies

```bash
cd SoraT2V && yarn
#or
cd SoraT2V && npm install
#or
cd SoraT2V && pnpm install
```

### 3. copy .env.example and rename it to .env.local

```bash
# website URL
NEXT_PUBLIC_SITE_URL=http://localhost

# openai config
OPENAI_API_KEY=sk-XXXXXX
OPENAI_API_BASE_URL=http://localhost:8081
OPENAI_API_MODEL=sora-1.0-turbo
```

### 4. Run it

```bash
yarn dev
#or
npm run dev
#or
pnpm dev
```

### 5. Open [http://localhost](http://localhost) with your browser to see it.
![success_deploy.jpg](https://sora-text-to-video.app/success_deploy.jpg)


### Important
SoraT2V requires [FakeSoraAPI](https://github.com/SoraT2V/FakeSoraAPI) to function properly.
