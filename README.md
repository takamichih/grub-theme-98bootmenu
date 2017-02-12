# 98bootmenu
GRUB2 用のテーマ

## 見た目
(註: PC-98 のフォントを吸い取って PF2 に変換したものを使用)
![スクショ](/screenshot.png?raw=true)

## 使い方
* 98bootmenu ディレクトリを /boot/grub/themes/ の中とかに置く
* /etc/defaut/grub を編集して、
  * `GRUB_THEME="/boot/grub/themes/98bootmenu/theme.txt"`
  * `GRUB_PRELOAD_MODULES` に `tga` を追加する

## 注意点
* 所々用語が不正確ですが、PC-98 の起動メニューの雰囲気を感じさせるための文学的な表現です。
* GRUB の解像度がどんなに大きくてもレイアウトがスケールしたりはせず 640x400 以内の部分しか使用しません。
* 左側の固定ディスク選択メニューはダミーです。終了して N-88 BASIC を起動することはできません。
* メニューが 16 個以上あってスクロールしても左の数字は変化しません。
