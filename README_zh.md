# Awesome CursorRules [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<p align="center">
  <a href="https://patrickjs.com" target="_blank">
    <img src="/cursor-ai-logo.png" alt="Awesome CursorRules" />
  </a>
</p>

精心策划的 `.cursorrules` 文件集合，用于增强您的 Cursor AI 体验。

[Cursor AI](https://cursor.sh/) 是一款由人工智能驱动的代码编辑器。`.cursorrules` 文件为 Cursor AI 在生成代码时定义自定义规则，使您能够根据特定需求和偏好定制其行为。

## 为什么使用 .cursorrules？

`.cursorrules` 是 Cursor AI 中的一项强大功能，允许开发者为 AI 定义项目特定的指令。以下是您可能想要使用它的原因：

1. **定制化 AI 行为**：`.cursorrules` 文件帮助将 AI 的响应调整为您项目的特定需求，确保更相关和准确的代码建议。

2. **一致性**：通过在您的 `.cursorrules` 文件中定义编码标准和最佳实践，您可以确保 AI 生成的代码符合您项目的风格指南。

3. **上下文感知**：您可以为 AI 提供关于您项目的重要上下文，例如常用方法、架构决策或特定库，从而实现更明智的代码生成。

4. **提高生产力**：通过定义良好的规则，AI 可以生成需要更少手动编辑的代码，加快您的开发过程。

5. **团队协调**：对于团队项目，共享的 `.cursorrules` 文件确保所有团队成员都能获得一致的 AI 辅助，促进编码实践的凝聚力。

6. **项目特定知识**：您可以包含关于项目结构、依赖项或独特需求的信息，帮助 AI 提供更准确和相关的建议。

通过在项目根目录创建 `.cursorrules` 文件，您可以利用这些优势并增强您使用 Cursor AI 的编码体验。

## 目录

- [Awesome CursorRules ](#awesome-cursorrules-)
  - [为什么使用 .cursorrules？](#为什么使用-cursorrules)
  - [目录](#目录)
  - [规则](#规则)
    - [前端框架和库](#前端框架和库)
    - [后端和全栈](#后端和全栈)
    - [移动开发](#移动开发)
    - [CSS 和样式](#css-和样式)
    - [状态管理](#状态管理)
    - [数据库和 API](#数据库和-api)
    - [测试](#测试)
    - [托管和部署](#托管和部署)
    - [构建工具和开发](#构建工具和开发)
    - [语言特定](#语言特定)
    - [其他](#其他)
    - [实用工具](#实用工具)
  - [目录网站](#目录网站)
  - [如何使用](#如何使用)
    - [方法一](#方法一)
    - [方法二](#方法二)
  - [贡献](#贡献)
  - [许可证](#许可证)

## 规则

### 前端框架和库

- [Angular (Novo Elements)](./rules/angular-novo-elements-cursorrules-prompt-file/.cursorrules) - Angular 与 Novo Elements 组件库集成的规则
- [Angular (TypeScript)](./rules/angular-typescript-cursorrules-prompt-file/.cursorrules) - 基于 TypeScript 的 Angular 开发规则
- [Astro (TypeScript)](./rules/astro-typescript-cursorrules-prompt-file/.cursorrules) - 使用 TypeScript 进行 Astro 框架开发
- [Cursor AI (React, TypeScript, shadcn/ui)](./rules/cursor-ai-react-typescript-shadcn-ui-cursorrules-p/.cursorrules) - 针对 Cursor AI 的 React、TypeScript 和 shadcn/ui 集成
- [Next.js 15 (React 19, Vercel AI, Tailwind)](./rules/nextjs15-react19-vercelai-tailwind-cursorrules-prompt-file/.cursorrules) - 适用于 Next.js 15、React 19 与 Vercel AI 的规则
- [Next.js 14 (Tailwind, SEO)](./rules/cursorrules-cursor-ai-nextjs-14-tailwind-seo-setup/.cursorrules) - Next.js 14 与 Tailwind 和 SEO 优化
- [Next.js (React, Tailwind)](./rules/nextjs-react-tailwind-cursorrules-prompt-file/.cursorrules) - Next.js 与 React 和 Tailwind 集成
- [Next.js (React, TypeScript)](./rules/nextjs-react-typescript-cursorrules-prompt-file/.cursorrules) - 使用 TypeScript 的 Next.js 和 React 开发
- [Next.js (SEO Development)](./rules/nextjs-seo-dev-cursorrules-prompt-file/.cursorrules) - Next.js SEO 开发优化规则
- [Next.js (Supabase Todo App)](./rules/nextjs-supabase-todo-app-cursorrules-prompt-file/.cursorrules) - 使用 Supabase 的 Next.js Todo 应用规则
- [Next.js (Tailwind, TypeScript)](./rules/nextjs-tailwind-typescript-apps-cursorrules-prompt/.cursorrules) - Next.js 与 Tailwind 和 TypeScript 集成
- [Next.js (TypeScript App)](./rules/nextjs-typescript-app-cursorrules-prompt-file/.cursorrules) - 基于 TypeScript 的 Next.js 应用开发
- [Next.js (TypeScript)](./rules/nextjs-typescript-cursorrules-prompt-file/.cursorrules) - Next.js 与 TypeScript 集成的规则
- [Next.js (TypeScript, Tailwind)](./rules/nextjs-typescript-tailwind-cursorrules-prompt-file/.cursorrules) - Next.js 与 TypeScript 和 Tailwind 的集成规则
- [Next.js (Vercel, Supabase)](./rules/nextjs-vercel-supabase-cursorrules-prompt-file/.cursorrules) - Next.js 与 Vercel 和 Supabase 集成
- [Next.js (Vercel, TypeScript)](./rules/nextjs-vercel-typescript-cursorrules-prompt-file/.cursorrules) - Next.js 与 Vercel 和 TypeScript 开发规则
- [Next.js (App Router)](./rules/nextjs-app-router-cursorrules-prompt-file/.cursorrules) - Next.js App Router 开发规则
- [Next.js (Material UI, Tailwind CSS)](./rules/nextjs-material-ui-tailwind-css-cursorrules-prompt/.cursorrules) - Next.js 与 Material UI 和 Tailwind CSS 集成
- [Qwik (Basic Setup with TypeScript and Vite)](./rules/qwik-basic-cursorrules-prompt-file/.cursorrules) - 基于 TypeScript 和 Vite 的 Qwik 基础设置
- [Qwik (with Tailwind CSS)](./rules/qwik-tailwind-cursorrules-prompt-file/.cursorrules) - Qwik 与 Tailwind CSS 集成
- [React Components Creation](./rules/react-components-creation-cursorrules-prompt-file/.cursorrules) - React 组件创建的最佳实践
- [React (Next.js UI Development)](./rules/react-nextjs-ui-development-cursorrules-prompt-fil/.cursorrules) - 基于 Next.js 的 React UI 开发
- [React (TypeScript, Next.js, Node.js)](./rules/react-typescript-nextjs-nodejs-cursorrules-prompt-/.cursorrules) - React 与 TypeScript、Next.js 和 Node.js 集成
- [React (TypeScript, Symfony)](./rules/react-typescript-symfony-cursorrules-prompt-file/.cursorrules) - React 与 TypeScript 和 Symfony 后端集成
- [Solid.js (Basic Setup)](./rules/solidjs-basic-cursorrules-prompt-file/.cursorrules) - Solid.js 基础设置和使用规则
- [Solid.js (TypeScript)](./rules/solidjs-typescript-cursorrules-prompt-file/.cursorrules) - 使用 TypeScript 的 Solid.js 开发规则
- [Solid.js (Tailwind CSS)](./rules/solidjs-tailwind-cursorrules-prompt-file/.cursorrules) - Solid.js 与 Tailwind CSS 集成
- [Svelte 5 vs Svelte 4](./rules/svelte-5-vs-svelte-4-cursorrules-prompt-file/.cursorrules) - Svelte 5 与 Svelte 4 比较和最佳实践
- [SvelteKit (RESTful API, Tailwind CSS)](./rules/sveltekit-restful-api-tailwind-css-cursorrules-pro/.cursorrules) - SvelteKit 与 RESTful API 和 Tailwind CSS 集成
- [SvelteKit (Tailwind CSS, TypeScript)](./rules/sveltekit-tailwindcss-typescript-cursorrules-promp/.cursorrules) - SvelteKit 与 Tailwind CSS 和 TypeScript 集成
- [SvelteKit (TypeScript Guide)](./rules/sveltekit-typescript-guide-cursorrules-prompt-file/.cursorrules) - 基于 TypeScript 的 SvelteKit 开发指南
- [Vue 3 (Nuxt 3 Development)](./rules/vue-3-nuxt-3-development-cursorrules-prompt-file/.cursorrules) - Vue 3 与 Nuxt 3 开发规则
- [Vue 3 (Nuxt 3, TypeScript)](./rules/vue-3-nuxt-3-typescript-cursorrules-prompt-file/.cursorrules) - Vue 3 与 Nuxt 3 和 TypeScript 集成
- [Vue 3 (Composition API)](./rules/vue3-composition-api-cursorrules-prompt-file/.cursorrules) - Vue 3 Composition API 开发规则

### 后端和全栈

- [Convex 最佳实践](./rules/convex-cursorrules-prompt-file/.cursorrules) - Convex 后端开发的最佳实践
- [Deno 集成](./rules/deno-integration-techniques-cursorrules-prompt-fil/.cursorrules) - Deno 集成技术和最佳实践
- [Elixir 工程师指南](./rules/elixir-engineer-guidelines-cursorrules-prompt-file/.cursorrules) - Elixir 开发工程师指南
- [Elixir (Phoenix, Docker)](./rules/elixir-phoenix-docker-setup-cursorrules-prompt-fil/.cursorrules) - Elixir Phoenix 框架与 Docker 集成
- [ES Module (Node.js)](./rules/es-module-nodejs-guidelines-cursorrules-prompt-fil/.cursorrules) - Node.js ES 模块开发指南
- [Go 后端可扩展性](./rules/go-backend-scalability-cursorrules-prompt-file/.cursorrules) - Go 后端可扩展性设计规则
- [Go ServeMux REST API](./rules/go-servemux-rest-api-cursorrules-prompt-file/.cursorrules) - 使用 Go ServeMux 构建 REST API
- [Go (基础设置)](./rules/htmx-go-basic-cursorrules-prompt-file/.cursorrules) - Go 语言基础设置规则
- [Go with Fiber](./rules/htmx-go-fiber-cursorrules-prompt-file/.cursorrules) - Go Fiber 框架开发规则
- [HTMX (基础设置)](./rules/htmx-basic-cursorrules-prompt-file/.cursorrules) - HTMX 基础设置与使用方法
- [HTMX (Flask)](./rules/htmx-flask-cursorrules-prompt-file/.cursorrules) - HTMX 与 Flask 集成
- [HTMX (Django)](./rules/htmx-django-cursorrules-prompt-file/.cursorrules) - HTMX 与 Django 集成
- [Java (Springboot, JPA)](./rules/java-springboot-jpa-cursorrules-prompt-file/.cursorrules) - Java Springboot 与 JPA 开发规则
- [Knative (Istio, Typesense, GPU)](./rules/knative-istio-typesense-gpu-cursorrules-prompt-fil/.cursorrules) - Knative 与 Istio、Typesense 和 GPU 集成
- [Laravel (PHP 8.3)](./rules/laravel-php-83-cursorrules-prompt-file/.cursorrules) - 基于 PHP 8.3 的 Laravel 开发规则
- [Laravel (TALL Stack)](./rules/laravel-tall-stack-best-practices-cursorrules-prom/.cursorrules) - Laravel TALL Stack (Tailwind, Alpine.js, Laravel, Livewire) 最佳实践
- [Node.js (MongoDB)](./rules/nodejs-mongodb-cursorrules-prompt-file-tutorial/.cursorrules) - Node.js 与 MongoDB 集成教程
- [Node.js (MongoDB, JWT, Express, React)](./rules/nodejs-mongodb-jwt-express-react-cursorrules-promp/.cursorrules) - Node.js 全栈应用，包含 MongoDB、JWT、Express 和 React
- [Python (FastAPI)](./rules/py-fast-api/.cursorrules) - Python FastAPI 框架开发规则
- [Python (FastAPI)](./rules/cursorrules-file-cursor-ai-python-fastapi-api/.cursorrules) - Python FastAPI 开发的另一种规则集
- [Python 3.12 (FastAPI 最佳实践)](./rules/python-312-fastapi-best-practices-cursorrules-prom/.cursorrules) - Python 3.12 与 FastAPI 的最佳实践
- [Python (Django 最佳实践)](./rules/python-django-best-practices-cursorrules-prompt-fi/.cursorrules) - Python Django 框架开发最佳实践
- [Python (FastAPI 最佳实践)](./rules/python-fastapi-best-practices-cursorrules-prompt-f/.cursorrules) - Python FastAPI 开发最佳实践
- [Python (FastAPI 可扩展 API)](./rules/python-fastapi-scalable-api-cursorrules-prompt-fil/.cursorrules) - 使用 FastAPI 构建可扩展 API
- [Python (Flask JSON 指南)](./rules/python-flask-json-guide-cursorrules-prompt-file/.cursorrules) - Python Flask JSON 处理指南
- [TypeScript (NestJS 最佳实践)](./rules/typescript-nestjs-best-practices-cursorrules-promp/.cursorrules) - TypeScript NestJS 开发最佳实践
- [WordPress (PHP, Guzzle, Gutenberg)](./rules/wordpress-php-guzzle-gutenberg-cursorrules-prompt-/.cursorrules) - WordPress 开发，包含 PHP、Guzzle 和 Gutenberg
- [WordPress (macOS)](./rules/cursorrules-cursor-ai-wordpress-draft-macos-prompt/.cursorrules) - macOS 环境下的 WordPress 开发
- [Python LLM & ML 工作流](./rules/python-llm-ml-workflow-cursorrules-prompt-file/.cursorrules) - Python 大语言模型和机器学习工作流

### 移动开发

- [React Native Expo](./rules/react-native-expo-cursorrules-prompt-file/.cursorrules) - React Native 与 Expo 开发规则
- [SwiftUI 指南](./rules/swiftui-guidelines-cursorrules-prompt-file/.cursorrules) - SwiftUI 开发指南和最佳实践
- [TypeScript (Expo, Jest, Detox)](./rules/typescript-expo-jest-detox-cursorrules-prompt-file/.cursorrules) - 使用 TypeScript、Expo、Jest 和 Detox 进行移动应用开发
- [Android Native (Jetpack Compose)](./rules/android-jetpack-compose-cursorrules-prompt-file/.cursorrules) - 原生 Android 开发与 Jetpack Compose
- [Flutter 专家](./rules/flutter-app-expert-cursorrules-prompt-file/.cursorrules) - Flutter 应用开发专家指南

### CSS 和样式

- [Tailwind CSS (Next.js 指南)](./rules/tailwind-css-nextjs-guide-cursorrules-prompt-file/.cursorrules) - Tailwind CSS 与 Next.js 集成指南
- [Tailwind (React, Firebase)](./rules/tailwind-react-firebase-cursorrules-prompt-file/.cursorrules) - Tailwind 与 React 和 Firebase 集成
- [Tailwind (shadcn/ui 集成)](./rules/tailwind-shadcn-ui-integration-cursorrules-prompt-/.cursorrules) - Tailwind 与 shadcn/ui 组件库集成
- [HTML (Tailwind CSS, JavaScript)](./rules/html-tailwind-css-javascript-cursorrules-prompt-fi/.cursorrules) - HTML 与 Tailwind CSS 和 JavaScript 集成
- [JavaScript (Astro, Tailwind CSS)](./rules/javascript-astro-tailwind-css-cursorrules-prompt-f/.cursorrules) - JavaScript 与 Astro 和 Tailwind CSS 集成
- [React (Styled Components)](./rules/react-styled-components-cursorrules-prompt-file/.cursorrules) - React 与 Styled Components 样式方案
- [React (Chakra UI)](./rules/react-chakra-ui-cursorrules-prompt-file/.cursorrules) - React 与 Chakra UI 组件库集成

### 状态管理

- [React (Redux, TypeScript)](./rules/react-redux-typescript-cursorrules-prompt-file/.cursorrules) - React 与 Redux 和 TypeScript 状态管理
- [React (MobX)](./rules/react-mobx-cursorrules-prompt-file/.cursorrules) - React 与 MobX 状态管理
- [React (React Query)](./rules/react-query-cursorrules-prompt-file/.cursorrules) - React 与 React Query 数据管理

### 数据库和 API

- [GraphQL (Apollo Client)](./rules/react-graphql-apollo-client-cursorrules-prompt-file/.cursorrules) - GraphQL 与 Apollo Client 客户端集成
- [TypeScript (Axios)](./rules/typescript-axios-cursorrules-prompt-file/.cursorrules) - TypeScript 与 Axios HTTP 请求库集成

### 测试

- [TypeScript (Expo, Jest, Detox)](./rules/typescript-expo-jest-detox-cursorrules-prompt-file/.cursorrules) - 使用 TypeScript、Jest 和 Detox 进行 Expo 应用测试

### 托管和部署

- [Netlify](./rules/netlify-official-cursorrules-prompt-file/.cursorrules) - Netlify 部署服务最佳实践

### 构建工具和开发

- [Chrome 扩展 (JavaScript/TypeScript)](./rules/chrome-extension-dev-js-typescript-cursorrules-pro/.cursorrules) - Chrome 扩展开发，使用 JavaScript 或 TypeScript
- [GitHub 代码质量](./rules/github-code-quality-cursorrules-prompt-file/.cursorrules) - GitHub 项目代码质量最佳实践
- [GitHub 指南](./rules/github-cursorrules-prompt-file-instructions/.cursorrules) - GitHub 使用指南
- [Git 提交消息](./rules/git-conventional-commit-messages/.cursorrules) - Git 规范化提交消息指南
- [Kubernetes (MkDocs 文档)](./rules/kubernetes-mkdocs-documentation-cursorrules-prompt/.cursorrules) - Kubernetes MkDocs 文档编写规则
- [Linux (NVIDIA CUDA, Python)](./rules/linux-nvidia-cuda-python-cursorrules-prompt-file/.cursorrules) - Linux 环境下 NVIDIA CUDA 与 Python 集成
- [优化 (DRY, SOLID 原则)](./rules/optimize-dry-solid-principles-cursorrules-prompt-f/.cursorrules) - 代码优化，应用 DRY 和 SOLID 原则
- [Python 容器化](./rules/python-containerization-cursorrules-prompt-file/.cursorrules) - Python 应用容器化最佳实践
- [Python (GitHub 设置)](./rules/python-github-setup-cursorrules-prompt-file/.cursorrules) - Python 项目的 GitHub 设置指南
- [Tauri (Svelte, TypeScript 指南)](./rules/tauri-svelte-typescript-guide-cursorrules-prompt-f/.cursorrules) - Tauri 与 Svelte 和 TypeScript 集成指南
- [TypeScript 代码规范](./rules/typescript-code-convention-cursorrules-prompt-file/.cursorrules) - TypeScript 代码编写规范

### 语言特定

- [JavaScript/TypeScript 代码质量](./rules/javascript-typescript-code-quality-cursorrules-pro/.cursorrules) - JavaScript 和 TypeScript 代码质量最佳实践
- [JavaScript (Chrome APIs)](./rules/javascript-chrome-apis-cursorrules-prompt-file/.cursorrules) - JavaScript 使用 Chrome API 的指南
- [优化 (Rell 区块链代码)](./rules/optimize-rell-blockchain-code-cursorrules-prompt-f/.cursorrules) - Rell 区块链代码优化
- [Pandas (scikit-learn 指南)](./rules/pandas-scikit-learn-guide-cursorrules-prompt-file/.cursorrules) - Pandas 与 scikit-learn 数据科学工具使用指南
- [Plasticode (Telegram API)](./rules/plasticode-telegram-api-cursorrules-prompt-file/.cursorrules) - Plasticode 与 Telegram API 集成
- [PyQt6 (EEG 处理)](./rules/pyqt6-eeg-processing-cursorrules-prompt-file/.cursorrules) - 使用 PyQt6 进行 EEG 数据处理
- [Python/TypeScript 指南](./rules/python--typescript-guide-cursorrules-prompt-file/.cursorrules) - Python 和 TypeScript 混合开发指南
- [Python 最佳实践](./rules/python-cursorrules-prompt-file-best-practices/.cursorrules) - Python 编程最佳实践
- [Python 开发者](./rules/python-developer-cursorrules-prompt-file/.cursorrules) - Python 开发者编码规范
- [Python 项目指南](./rules/python-projects-guide-cursorrules-prompt-file/.cursorrules) - Python 项目组织和开发指南
- [PyTorch (scikit-learn)](./rules/pytorch-scikit-learn-cursorrules-prompt-file/.cursorrules) - PyTorch 与 scikit-learn 机器学习集成
- [Solidity (Foundry)](./rules/solidity-foundry-cursorrules-prompt-file/.cursorrules) - Solidity 智能合约与 Foundry 开发框架
- [Solidity (Hardhat)](./rules/solidity-hardhat-cursorrules-prompt-file/.cursorrules) - Solidity 智能合约与 Hardhat 开发环境
- [Solidity (React 区块链应用)](./rules/solidity-react-blockchain-apps-cursorrules-prompt-/.cursorrules) - Solidity 与 React 开发区块链应用
- [TypeScript (LLM 技术栈)](./rules/typescript-llm-tech-stack-cursorrules-prompt-file/.cursorrules) - TypeScript 大语言模型技术栈
- [TypeScript (Node.js, Next.js, AI)](./rules/typescript-nodejs-nextjs-ai-cursorrules-prompt-fil/.cursorrules) - TypeScript 与 Node.js、Next.js 和 AI 集成
- [TypeScript (Node.js, Next.js, React, UI, CSS)](./rules/typescript-nodejs-nextjs-react-ui-css-cursorrules-/.cursorrules) - TypeScript 全栈开发
- [TypeScript (Node.js, React, Vite)](./rules/typescript-nodejs-react-vite-cursorrules-prompt-fi/.cursorrules) - TypeScript 与 Node.js、React 和 Vite 开发环境
- [TypeScript (React, Next.js, Cloudflare)](./rules/typescript-react-nextjs-cloudflare-cursorrules-pro/.cursorrules) - TypeScript 与 React、Next.js 和 Cloudflare 集成
- [TypeScript (React, NextUI, Supabase)](./rules/typescript-react-nextui-supabase-cursorrules-promp/.cursorrules) - TypeScript 与 React、NextUI 和 Supabase 集成
- [TypeScript (shadcn/ui, Next.js)](./rules/typescript-shadcn-ui-nextjs-cursorrules-prompt-fil/.cursorrules) - TypeScript 与 shadcn/ui 和 Next.js 集成
- [TypeScript (Vite, Tailwind)](./rules/typescript-vite-tailwind-cursorrules-prompt-file/.cursorrules) - TypeScript 与 Vite 和 Tailwind 开发环境
- [TypeScript (Vue.js)](./rules/typescript-vuejs-cursorrules-prompt-file/.cursorrules) - TypeScript 与 Vue.js 集成
- [TypeScript (Zod, Tailwind, Next.js)](./rules/typescript-zod-tailwind-nextjs-cursorrules-prompt-/.cursorrules) - TypeScript 与 Zod、Tailwind 和 Next.js 集成
- [WebAssembly (Z80 细胞自动机)](./rules/webassembly-z80-cellular-automata-cursorrules-prom/.cursorrules) - WebAssembly Z80 细胞自动机开发
- [TypeScript (Next.js)](./rules/typescript-nextjs-cursorrules-prompt-file/.cursorrules) - TypeScript 与 Next.js 开发规则
- [TypeScript (Next.js, React)](./rules/typescript-nextjs-react-cursorrules-prompt-file/.cursorrules) - TypeScript 与 Next.js 和 React 集成
- [TypeScript (Next.js, React, Tailwind, Supabase)](./rules/typescript-nextjs-react-tailwind-supabase-cursorru/.cursorrules) - TypeScript 全栈应用
- [TypeScript (Next.js, Supabase)](./rules/typescript-nextjs-supabase-cursorrules-prompt-file/.cursorrules) - TypeScript 与 Next.js 和 Supabase 集成
- [TypeScript (Node.js, Next.js App)](./rules/typescript-nodejs-nextjs-app-cursorrules-prompt-fi/.cursorrules) - TypeScript 与 Node.js 和 Next.js 应用开发
- [TypeScript (React)](./rules/typescript-react-cursorrules-prompt-file/.cursorrules) - TypeScript 与 React 集成
- [TypeScript (Clasp App Script)](./rules/typescript-clasp-cursorrules-prompt-file/.cursorrules) - TypeScript 与 Google Apps Script 和 Clasp 集成
- [C++ 编程指南](./rules/cpp-programming-guidelines-cursorrules-prompt-file/.cursorrules) - C++ 编程指南和最佳实践

### 其他

- [ASCII 模拟游戏](./rules/ascii-simulation-game-cursorrules-prompt-file/.cursorrules) - ASCII 字符模拟游戏开发
- [代码指南](./rules/code-guidelines-cursorrules-prompt-file/.cursorrules) - 通用代码编写指南
- [DragonRuby 最佳实践](./rules/dragonruby-best-practices-cursorrules-prompt-file/.cursorrules) - DragonRuby 游戏开发最佳实践
- [图形应用开发](./rules/graphical-apps-development-cursorrules-prompt-file/.cursorrules) - 图形应用程序开发指南
- [元提示](./rules/meta-prompt-cursorrules-prompt-file/.cursorrules) - Cursor AI 元提示优化技巧
- [Next.js (Type LLM)](./rules/next-type-llm/.cursorrules) - Next.js 与类型化 LLM 开发
- [Unity (C#)](./rules/unity-cursor-ai-c-cursorrules-prompt-file/.cursorrules) - Unity 游戏引擎与 C# 开发
- [Web 应用优化](./rules/web-app-optimization-cursorrules-prompt-file/.cursorrules) - Web 应用性能优化技巧

### 实用工具

- [Cursor Watchful Headers](https://github.com/johnbenac/cursor-watchful-headers) - 一个基于 Python 的文件监视系统，可自动管理文本文件中的头部信息并维护清晰、专注的项目树结构。非常适合在整个项目中保持一致的文件头和文档，并具有特殊功能帮助大语言模型保持更好的项目感知。

## 目录网站

- [CursorList](https://cursorlist.com)
- [CursorDirectory](https://cursor.directory/)

## 如何使用

### 方法一

1. 如果您尚未安装，请安装 [Cursor AI](https://cursor.sh/)。
2. 浏览上面的规则，找到适合您需求的 `.cursorrules` 文件。
3. 将选定的 `.cursorrules` 文件复制到您项目的根目录。
4. 根据您的特定项目需求自定义规则。

### 方法二

1. 如果您尚未安装，请安装 [Cursor AI](https://cursor.sh/)。
2. 安装 [vscode-cursor-rules](https://marketplace.visualstudio.com/items?itemName=BeilunYang.cursor-rules) 扩展。
3. 打开命令面板（Cmd+Shift+P 或 Ctrl+Shift+P）并输入 `Cursor Rules: Add .cursorrules`。
4. 选择并下载适合您需求的 `.cursorrules` 文件。
5. 根据您的特定项目需求自定义规则。

## 贡献

欢迎贡献！如果您有一个很棒的 `.cursorrules` 文件要分享：

1. Fork 这个仓库。
2. 在 `rules` 目录中创建一个新文件夹。文件夹名称应该遵循以下模式：
   `technology-focus-cursorrules-prompt-file`
   例如：`react-typescript-cursorrules-prompt-file`
3. 将您的 `.cursorrules` 文件添加到新文件夹。
4. 可选地，在文件夹中包含一个 README.md 以提供信用和简短描述。
5. 更新主 README.md 文件，将您的贡献添加到适当的类别中。
6. 确保您的贡献遵循本仓库根目录中 [`.cursorrules`](./.cursorrules) 文件中的指南。
7. 提交拉取请求。

请确保您的贡献是原创的，或者如果基于现有工作，请适当地注明出处。有关格式化、命名约定和贡献最佳实践的详细指南，请参阅本仓库根目录中的 `.cursorrules` 文件。

---

## 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)