# cs-form-mtn-013-vs2022

## 🔴 ソース分割されているソリューションを読み込んだ場合必ず最初に以下の設定が必要です

### 入れ子機能( Web ) を使用した機能のソース分割( partial )

![image](https://github.com/winofsql/cs-form-mtn-009-vs2022/assets/1501327/da790ac1-c0f5-4883-882a-69ab3b30a068)

- ### 構成
  - Form1.cs 
    - グローバルメソッド
  - Form1.Action.cs
    - ボタンによる処理イベント
  - Form1.Taskbar.cs
    - Validating によるチェック
  - Form1.Events.cs
    - 特殊なイベント処理( キーボード 関係等 )
  - Form1.Taskbar.cs
    - ステータスバーのメッセージ処理
