English follows

# 更新履歴 #

## 2012-05-19 ##
  * フルスクリーン表示にUSBデバイスがリセットされた際、一瞬デスクトップが表示されるのを抑制した

## 2012-05-12 ##
  * 設定ダイアログのフォントを変更した [issue 17](https://code.google.com/p/remote-joy-lite-fix/issues/detail?id=17)
  * セカンダリモニタでフルスクリーン表示ができるようにした [issue 18](https://code.google.com/p/remote-joy-lite-fix/issues/detail?id=18)

## 2012-05-04 ##
  * Lanczos4画像リサイズフィルタを実装した
  * PSP表示をOFFにしたままRemoteJoyLiteを終了した場合にPSPの表示が元に戻らないバグを修正した [issue 15](https://code.google.com/p/remote-joy-lite-fix/issues/detail?id=15)

## 2012-05-02 ##
  * フルスクリーンモードでPSPを取り外した際に応答不能になるバグを修正した [issue 10](https://code.google.com/p/remote-joy-lite-fix/issues/detail?id=10)
  * 画面更新時にクラッシュするバグを修正した
  * マウスカーソルを移動後1秒後に隠すようにした [issue 11](https://code.google.com/p/remote-joy-lite-fix/issues/detail?id=11)

## 2012-04-30 ##
  * Spline36モードで"waiting"の文字が出力されないバグを修正した
  * フルスクリーン表示時にPSPを接続しなおした場合にフリーズするバグを修正した

## 2012-04-29 ##
  * 多重起動を防止した
  * フルスクリーン表示中に設定画面を表示する場合にウィンドウモードに変更するようにした
  * 画像フィルタを切り替えられるようにした
  * ウィンドウを最小化した際にエラーダイアログが表示されるバグを修正した
  * Spline36画像拡大フィルタを実装した

## 2012-04-27 ##
  * 設定画面のバッファーオーバーフローを修正した
  * Makefile内のwindresコマンドをrcコマンドに置き換えた



# Change Log #

## 2012-05-19 ##
  * Suppressed the desktop is shown during USB reset on the fullscreen mode.

## 2012-05-12 ##
  * Fixed the font int the setting dialog. [issue 17](https://code.google.com/p/remote-joy-lite-fix/issues/detail?id=17)
  * Changed to be available the fullscreen mode in the secondary monitor. [issue 18](https://code.google.com/p/remote-joy-lite-fix/issues/detail?id=18)

## 2012-05-04 ##
  * Implemented Lanczos4 resize filter.
  * Fixed the bug that PSP does not show anything after RemoteJoyLite exits if PSP display setting is off. [issue 15](https://code.google.com/p/remote-joy-lite-fix/issues/detail?id=15)

## 2012-05-02 ##
  * Fixed a bug that RemoteJoyLite hangs up if PSP is removed during fullscreen mode. [issue 10](https://code.google.com/p/remote-joy-lite-fix/issues/detail?id=10)
  * Fixed a bug that RemoteJoyLite crashes during display update.
  * Changed the mouse cursor to hide one second after the last move. [issue 11](https://code.google.com/p/remote-joy-lite-fix/issues/detail?id=11)

## 2012-04-30 ##
  * Fixed a bug that spline36 mode does not show "waiting" correctly.
  * Fixed a bug that RemoteJoyLite freezes if PSP is connected on fullscreen mode.

## 2012-04-29 ##
  * Prevented multiple startup
  * Changed to move to windowed mode when the setting dialog is shown durting fullscreen mode.
  * Added a setting to switch image filters.
  * Fixed a bug that an error message is shown when the window is minimized.
  * Added Spline36 image scaling filter.

## 2012-04-27 ##
  * Fixed overflow in the setting dialog.
  * Replaced windres command to rc command in Makefile.