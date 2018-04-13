# electron-insertcss-in-preload

## 前提条件

* `webPreferences: {sandbox: true, preload: '...'}`
* `loadURL` で外部サイトを読み込む

## したいこと

* `mainWindow.webContents` の要素にたいして、 `insertCSS` などをしたい

## 動作条件

* Electron の次のリリースバージョンを引っ張ってくる (`97fb15a` 以降)
  1. `node_modules` 下で、 `git clone git@github.com:electron/electron.git`
  1. `cd electron`
  1. `python script\bootstrap.py -v`
  1. `python script\build.py`
* `.\node_modules\electron\out\R\electron.exe .`
