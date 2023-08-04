# ナレッジ管理アプリ「KBアプリ ライト版」
Power Apps モデル駆動型アプリによって作成されたKBアプリのライト版です。
Azure OpenAI Service への接続フローも含まれています。

![image](https://github.com/geekfujiwara/KBAppLite/assets/96101315/d309749e-8f3f-43e8-8f8d-df49cf0f4f86)

## ナレッジ承認
ナレッの承認を行うことが出来ます。コマンドバーの「ナレッジ承認」からクリックするとカスタムページが起動します。

![image](https://github.com/geekfujiwara/KBAppLite/assets/96101315/db43c44a-c658-4307-b1ce-97a1c29ea82a)


![image](https://github.com/geekfujiwara/KBAppLite/assets/96101315/eae9cbc5-73ef-4366-9c94-c98716ae3ef6)


## ナレッジの自動生成 (Azure OpenAI Service)
ナレッジの自動生成は、製品とナレッジのタイトルのみ入力すると自動的に内容を生成してくれる機能です。

![image](https://github.com/geekfujiwara/KBAppLite/assets/96101315/af4c863b-785c-44d0-b402-e72e66f25e6d)


以下のフローが利用されています。

![image](https://github.com/geekfujiwara/KBAppLite/assets/96101315/f3f4fa51-cace-463b-92f4-6c4c0a1aebf2)


![image](https://github.com/geekfujiwara/KBAppLite/assets/96101315/93ace82f-3703-418f-a9ca-00bd5c88850e)


![image](https://github.com/geekfujiwara/KBAppLite/assets/96101315/b2da70b1-4a52-40ad-9300-dc6835acc4e7)

# 設定方法
## ソリューションのインポート方法
ソリューションのインポート方法は以下にて説明があります。Microsoft Learnの情報を参照してください。

## Azure OpenAI Serivce の利用
Azure OpenAI Serivce の利用を行うには、エンドポイントURIとAPI-KEYを指定する必要があります。
ソリューション内に入っておりますのでこちらから値を設定するようにしてください。
![image](https://github.com/geekfujiwara/KBAppLite/assets/96101315/4a52713e-d611-4d4a-9591-88147a1358a9)

環境変数の値の設定方法は以下のMicrosoft Learnの情報を参照してください。
