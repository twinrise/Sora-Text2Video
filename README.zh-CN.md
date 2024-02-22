# SoraT2V
SoraT2V 是一个开源项目，允许用户使用 OpenAI 的 Sora 模型使用文本在线生成视频，从而简化视频创建，并具有轻松的一键网站部署功能。
👉 [SoraT2V](https://sora-text-to-video.app)

<div align="left">

[English](https://github.com/SoraT2V/SoraT2V/blob/main/README.md) | 简体中文

</div>

## 快速开始

### 在 Vercel 上部署
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FSoraT2V%2FSoraT2V&project-name=SoraT2V&repository-name=SoraT2V&external-id=https%3A%2F%2Fgithub.com%2FSoraT2V%2FSoraT2V%2Ftree%2Fmain)

### 1. 克隆项目

```bash
git clone git@github.com:SoraT2V/SoraT2V.git
```

### 2. 安装依赖

```bash
cd SoraT2V && yarn
#or
cd SoraT2V && npm install
#or
cd SoraT2V && pnpm install
```

### 3. 复制 .env.example 并将其重命名为 .env.local

```bash
# website URL
NEXT_PUBLIC_SITE_URL=http://localhost

# openai config
OPENAI_API_KEY=sk-XXXXXX
OPENAI_API_BASE_URL=http://localhost:8081
OPENAI_API_MODEL=sora-1.0-turbo
```

### 4. 运行

```bash
yarn dev
#or
npm run dev
#or
pnpm dev
```

### 4. 在浏览器打开 [http://localhost](http://localhost)
![success_deploy.jpg](https://sora-text-to-video.app/success_deploy.jpg)


### 重要事项
SoraT2V 需要 [FakeSoraAPI](https://github.com/SoraT2V/FakeSoraAPI) 才能正常运行。
