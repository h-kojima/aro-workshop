## AROクラスターの削除

### Azure Portalを利用したAROクラスターの削除

Azure Portalにログインして、AROクラスターを作成したリソースグループを選択し、AROとAROが利用する仮想ネットワークを選択して、メニュー右上の「削除」からAROクラスターの削除操作が可能です。

![AROクラスターの削除](./images/portal-aro-delete.png)
<div style="text-align: center;">Azure Portalを利用したAROクラスターの削除</div>　　

### Azure CLIを利用したAROクラスターの削除

Azure CLIを利用したAROクラスターの削除コマンドによる、削除操作が可能です。この例では、リソースグループ「aro-handson-rg01」とAROクラスター名「testmyaro01」を指定して削除コマンドを実行しています。

```
$ az login
$ az aro delete --resource-group aro-handson-rg01 --name testmyaro01
Are you sure you want to perform this operation? (y/n): y
 \ Running ..
```

これで、AROクラスターの基本的な利用方法を学習する演習とデモ紹介は終了しました。時間に余裕がありましたら、オプションの演習である、[AROクラスターでのJavaアプリケーション開発 スターターラボ](../aro-sample-app-develop)に進んでください。


[HOME](../../README.md)
