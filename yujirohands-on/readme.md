## main
下記のAOAOIハンズオンで利用したファイルのメモ。
https://qiita.com/fe_js_engineer/items/4c11827906d38051ae51

+ ADO.yaml
Azure Dev Ops にデプロイするときに使ったyamlファイル
下記を参考に作成。
https://github.com/Azure/static-web-apps/issues/1277

+ .env.local
AOAIやADOとの設定に必要な情報
**.env.local は環境に合わせて記述をしてください。**

-----------------------------------------------------------
## 下記のようなbotができる。
https://ashy-meadow-05e3ae000.3.azurestaticapps.net/
![2023-09-18_22h18_54](https://github.com/aktsmm/AOAI/assets/71251920/aa279832-0465-48b5-a7a9-ea6ee0f68453)


### ローカル環境ではnodejs / next.jsが動く環境が必要です。
``` npm run dev```
上記コマンドを実施することでデプロイすることができます。

### Windws環境にnextjsをインストールする参考：
+ create-next-app test-next を実行するとエラー、npm ERR! ”enoent This is related to npm not being able to find a file” ＆ ”ENOENT: no such file or directory”
https://yamapan.tokyo/?p=2424

+ Windows に node.js を入れる方法
https://yamapan.tokyo/?p=2418

