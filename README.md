## dena-autumn2023-frontend

![cli](https://raw.githubusercontent.com/KakinokiKanta/dena-autumn2023-frontend/image/dena_CLI_ans.png)

株式会社DeNA様のオータムハッカソン2023で開発したWebアプリです。

このアプリは、在宅ワークが多く業務以外の交流が図りづらいエンジニア向けの「CLIで操作できる自己紹介リレー」アプリです。

エンジニアライクなアプリとするために、アプリの操作はCLIで行います。

TypeScriptとNext.jsで開発して、vercel でデプロイしていました。

現在は、バックエンドをデプロイしていないため、使用することはできません。（一応サイト内でhelpコマンドだけは使用できます...）

ハッカソンで発表したスライドは[こちら](https://docs.google.com/presentation/d/1aWybADme1O4EncY2zE7ORNhTWaweKGhEy2FZg8a80DM/edit?usp=sharing)。

**追記: このWebアプリでハッカソンを優勝できました!**

## 起動方法

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

## 技術スタック

- TypeScript
- Next.js (App Router)
- XTerm.js
- Vercel
