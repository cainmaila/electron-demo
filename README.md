# Electron 使用筆記

[官方網站](https://electronjs.org)

## 安裝

```
yarn add electron
```

* [快速入門](https://electronjs.org/docs/tutorial/quick-start)

## 執行 dev

```
yarn dev
```

## 直接執行檔

[下載執行檔](https://github.com/electron/electron/releases)

> electron-v1.7.10-win32-x64.zip

```
//將以下三檔放入 /electron-v1.7.10-win32-x64/resources/app
package.json
index.html
main.js
//之後可直些執行 /electron-v1.7.10-win32-x64/electron.exe
```

[參考文檔](https://electronjs.org/docs/tutorial/application-distribution)

## 打包 window (產生 asar 封存檔)

[參考文檔](https://electronjs.org/docs/tutorial/application-packaging)

安裝 asar

```
yarn add asar
```

打包 asar

```
yarn asar
```

將生成的 `app.asar` 放入 `/electron-v1.7.10-win32-x64/resources/`
