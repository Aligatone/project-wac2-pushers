# Swack
<img width="1908" height="905" alt="demo1" src="https://github.com/user-attachments/assets/e7cf5ec5-0930-4136-9244-ceeac500d035" />


## 概要
**Swack** は、チームやグループでのコミュニケーションと情報共有を円滑にする  
**グループウェアアプリケーション**です。

プロジェクト単位や目的ごとにルームを作成し、メンバー同士が効率よくやり取りできる環境を提供します。

---

## 主な機能

## ログイン機能

Swack では、ユーザーごとにアカウントを作成し、安全にアプリを利用できる  
**ログイン機能**を実装しています。

https://github.com/user-attachments/assets/29c1195a-1473-4c4e-9fd8-59029b284595

### ルーム作成機能


- グループやプロジェクトごとに **ルームを作成**
- 目的に応じたコミュニケーションの整理が可能
- メンバー単位での利用を想定



https://github.com/user-attachments/assets/11ae313b-4828-47b4-b351-86b9f0dd3154


---

### 写真作成・共有機能
- ルーム内で画像の共有が可能
- チーム内でのアイデア共有や記録に活用できる


https://github.com/user-attachments/assets/744e7b06-7275-4084-9c60-63cd8b6049d3


---

### テーマカラー変更機能
- アプリ全体の **テーマカラーを自由に変更**
- 利用者の好みや気分に合わせたカスタマイズが可能
- 視認性や使いやすさの向上


https://github.com/user-attachments/assets/a170d271-58b7-46e9-8a89-2647b1506de3


---

## PostgreSQL DB への接続

### PostgreSQL 拡張機能の活用

1. VSCode 左側のアイコンの中から「Database」を開く

2. 「Create Connection」を押す

3. 「Connect」内で以下の設定を入力し、下部の「＋ Connect」ボタンを押す

- Name : DB
- Host : 127.0.0.1 ※デフォルト
- Port : 5432 ※デフォルト
- Username : postgres ※デフォルト
- Password : postgres
- Database : postgres ※デフォルト

4. PostgreSQL の DB に接続されれば準備完了

- ※エラーになった場合は、PostgreSQL のインストール状況を確認する
