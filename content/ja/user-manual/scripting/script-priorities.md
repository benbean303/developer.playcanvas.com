---
title: Script Priority
template: usermanual-page.tmpl.html
position: 2
---

## スクリプトをロードする順番

状況によっては、スクリプトをあらかじめ決められた順番でロードすることが必要な場合があります。このような場合には、スクリプト優先度機能を使います。スクリプト優先度機能にアクセスするには、メインメニューを使います。

![スクリプト優先度メニュー][2]

このメニューから、空の優先度リストを開きます。

![スクリプト優先度][3]

プロジェクトのスクリプトフォルダから、このリストにスクリプトを追加します。

![スクリプト優先度][4]

PlayCanvasアプリケーションが実行されると、プログラムの実行前にロードするスクリプトのリストを生成します。これらのスクリプトは並列にロードされますが、設定された順番どおりに実行されます。これにより、あるスクリプトが別のスクリプトよりもリストの前にある場合、それが先に実行されます。スクリプトのリストは優先リストの中にあるもの(リストの上の項目から下の項目の順で)がまず含まれ、その後スクリプトアトリビュートに含まれる全てのスクリプトが続きます。

## ライブラリのロード

スクリプト優先度リストの中に含まれているスクリプトは、スクリプトコンポーネントから参照されなくてもプログラムに含まれることに注意してください。つまり、アプリケーションが実行される前に、使用したいライブラリを読み込むことができるということです。たとえば、[jquery][1]をアプリケーションのほかのスクリプトよりも前に読み込むといった具合です。

[1]: http://jquery.com
[2]: /images/user-manual/scripting/script-priorities-menu.jpg
[3]: /images/user-manual/scripting/script-priorities-empty.jpg
[4]: /images/user-manual/scripting/script-priorities-full.jpg

