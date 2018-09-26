# kagerou-doc

## 導入方法

### 準備

まずOverlayPluginの最新版を[ここ](https://github.com/hibiyasleep/OverlayPlugin/releases/latest)からダウンロードする。  
(例えば、Windows10 64bitならOverlayPlugin-0.3.4.0-x64-full.zip)  
ダウンロードしたzipファイルを右クリック->プロパティを選択。

![security](https://raw.githubusercontent.com/xkainanai/kagerou-doc/master/img/security.png)

セキュリティ項目の"許可する"にチェックを入れてOKボタンを押す。  
解凍してできたフォルダをACT本体(Advanced Combat Tracker.exe)のある場所に置く。

### インストール

ACTを起動し、メニューからPlugins->Plugin Listingを選択。  
"Browse..."ボタンを押して、OverlayPlugin-0.3.4.0-x64-fullフォルダにあるOverlayPlugin.dllを選択。  
"Add/Enable Plugin"ボタンを押す。

### 設定

![settings](https://raw.githubusercontent.com/xkainanai/kagerou-doc/master/img/settings.png)

詳細：  
Plugins->OverlayPlugin.dll->Mini Parseを選択。  
"オーバーレイを表示する"にチェックが入っていることを確認。  
"表示するURL"に下記のURLを入れる。  
`https://hibiyasleep.github.io/kagerou/overlay`  
"非アクティブのときに自動的にオーバーレイを隠す"にチェック(任意)。

Plugins->OverlayPlugin.dll->Spell Timerを選択。  
"オーバーレイを表示する"のチェックを外す(任意)。  
使わない場合は、"Spell Timer"を選択して"削除"ボタンを押す。(任意)  
削除しても後から追加することができる。
