# react-js   
ReactJSは、ユーザインタフェース構築のためのJavaScriptライブラリです。          
ReactJSは、コンポーネントベースで、大規模なJavaScriptコードを部品化させることで保守性を高めたり、既存のReactコンポーネントを再利用したりできるため、マイクロサービスアーキテクチャに適しています。         
AIONにおいてReactJSは、エッジコンピューティング環境のクラスター化されたKubernetes上のマイクロサービスアーキテクチャを前提として、アウトプットをフロントエンドUIに表示したり、フロントエンドUIからの指示をバックエンド経由でAIONに伝えたりする役割を果たしています。   
また、AIONにおいてReactJSは、クラウドのリソースおよびネットワークから完全に遮断された状態において、安定的な稼働環境として動作します。

# Node.jsのインストール   
エッジコンピューティング環境におけるReactJSの構築にあたり、Node.jsのインストールが必要になります。   
以下のコマンドでNode.jsをインストールできます。（Ubuntuの場合）   

```
$ sudo apt-get install nodejs npm
```

これで、Node.jsとパッケージ管理ツールのnpmがインストールできます。   
任意のバージョンや最新版のNode.jsをインストールしたい場合は、NodeSourceからインストールしてください。   

```
$ curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash  -
 
$ sudo apt-get install nodejs npm
```