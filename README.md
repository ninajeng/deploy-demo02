# deploy-demo02

使用 gh-pages 套件進行部屬

# 步驟

1. 安裝套件
```sh
npm i gh-pages
```

2. vite.config.js 中， base 屬性設定為儲存庫名稱
```sh
base: "/<REPO>/"
```

3. 於 package.json 檔案設定 scripts
```sh
"deploy": "vite build && gh-pages -d dist"
```

4. 部屬指令
```sh
npm run deploy
```
