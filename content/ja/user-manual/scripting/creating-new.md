---
title: スクリプトの作成および添付
template: usermanual-page.tmpl.html
position: 1
---

## 新しいスクリプトの作成

新しいスクリプトを作成するには、アセットパネルを使用してNew Scriptを選択します

![新規スクリプト][0]

## エンティティにスクリプトを追加

<img src="/images/user-manual/scenes/components/component-script.png" style="width: 300px; float: right; padding: 20px; padding-top: 0px;"/>

スクリプトコンポーネントは他のコンポーネントと同様、エンティティインスペクタの*Add Component*ボタンを使用してエンティティに添付されます。

スクリプトコンポーネントを追加したら、読み込むJavaScriptファイルを指定することができます。Add Scriptボタンを使用してアセットパネルからスクリプトを選択してください。またはアセットパネルからコンポーネント上にスクリプトをドラッグ＆ドロップします。

コードを格納するためにPlayCanvasのコードリポジトリを使用している場合、PlayCanvasコードエディタでコードを編集して、URL入力ボックスの下でスクリプトの名前をクリックすることができます。

<div class="alert alert-info">
GithubやBitbucketを使用している場合はソース管理システムを介してコミットを行う必要があり、PlayCanvasでスクリプトを編集することはできません。
</div>

スクリプトコンポーネントは、複数のスクリプトファイルを読み込むことができます。コンポーネントに複数のスクリプトを追加するだけです。スクリプトコンポーネントにスクリプトを追加した順番通り、スクリプトは初期化および更新されます。スクリプトの順序を変更したい場合は、スクリプトのタイトルの横にある上下矢印をクリックします。スクリプトを削除するにはXボタンを押します。

## Using Script Priorities

The second way to use a script in your application is to add them to the script priority list. This will load your script up front, before the rest of your application. See the [Script Priorities][4] page.

[0]: /images/user-manual/new_script.jpg
[2]: /user-manual/scripting/workflow
[3]: /images/user-manual/scenes/components/component-script.png "Add urls of scripts to the script component"
[4]: /user-manual/scripting/script-priorities

