# InOutManager  
Spring Boot + JSP ベースの入出庫管理システム

---

##  プロジェクト紹介  
企業の入出庫および在庫管理を効率的に処理できるウェブベースのシステム。  
誰でも簡単に利用  
管理者と一般ユーザーの権限を分離することで、それぞれの作業を効果的に実行。  

###  画面の流れ 
<details>
  <summary>詳細を見る</summary> <br>
  <img src="https://github.com/jongha8422-sketch/inoutmanager/blob/main/PICTURES/%ED%99%94%EB%A9%B4%EC%9D%98%20%EC%A7%84%EC%9E%90%ED%9D%90%EB%A6%84.png" alt="画面フロー" width="800"/> 
</details>

###  DBテーブル設計 
<details>
  <summary>詳細を見る</summary> <br>
  <img src="https://github.com/jongha8422-sketch/inoutmanager/blob/main/PICTURES/%ED%99%94%EB%A9%B4%EC%9D%98%20%EC%A7%84%EC%9E%90%ED%9D%90%EB%A6%84.png" alt="画面フロー" width="800"/> 
</details>

### ERD 
<details>
  <summary>詳細を見る</summary> <br>
  <img src="https://github.com/jongha8422-sketch/inoutmanager/blob/main/PICTURES/erd1.png" width="800"/> 
</details>


---

##  開発期間  
- **2025.08.26 ～ 開発中**

---

##  開発環境  

- **プログラミング言語** : `Java 17`  
- **ビルドツール** : `Gradle`  
- **IDE** : `IntelliJ`  
- **フレームワーク** : `Spring Boot (3.5.5)`  
- **データベース** : `Oracle 18c` 
- **ORM** : `JPA`  
- **フロントエンド** : `HTML5`, `CSS`, `JavaScript`  

---

##  主な機能  

###  ログイン & 新規登録 [詳細を見る](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/login.md)
- ID / パスワードのDB検証  
- ログイン時にセッション生成  
- 管理者 / 一般ユーザーの権限分離  
- 新規登録時に多様な情報を利用可能  

---

###  マイページ [詳細を見る](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/mypage.md)
- 自分の情報の確認および修正（ID固定、パスワード除く）  
- 入出庫記録および担当履歴の確認（新規登録時の氏名を基に表示）  
- Excel出力機能および作業記録の可視化  

---

###  入庫登録/照会 [詳細を見る](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/ibpage.md)
- 製品コード、数量、供給元などの詳細情報入力  
- 入庫状態の確認  
- 入出庫量の追跡およびExcel出力  

---

###  出庫登録/照会 [詳細を見る](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/obpage.md)
- 入庫済み商品の選択後に出庫処理  
- 出庫情報入力および発送処理  
- 入出庫量の追跡およびExcel出力  

---

###  管理者ページ [詳細を見る](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/admin.md)
- すべての入出庫記録の確認  
- すべての掲示板投稿の修正および削除  
- ユーザー情報の確認およびユーザー削除  

---

###  メインページ [詳細を見る](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/mainpage.md)
- すべての機能を一目で確認可能  
- シンプルなデザインで誰でも簡単に操作可能  

---

###  掲示板 [詳細を見る](https://github.com/jongha8422-sketch/inoutmanager/blob/main/project/boardpage.md)
- 顧客からの問い合わせおよびフィードバック管理  
- 管理者による投稿の修正/削除機能  
- 投稿タイトルおよび履歴の確認  

---

##  技術的特徴  

- **UI**: 誰でも簡単に利用できるユーザーフレンドリーなデザイン  
- **権限管理**: ユーザーごとのアクセス権限設定と制御  
- **Excel出力**: 入出庫履歴および在庫情報をドキュメントとして保存可能  
