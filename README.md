# deploy-demo02

使用 gh-pages 套件

# 步驟

1. 安裝套件

```sh
npm i gh-pages
```

2. 於 package.json 檔案設定 scripts

```sh
"deploy": "vite build && gh-pages -d dist"
```

3. 部屬指令

```sh
npm run deploy
```
