## Azure Red Hat OpenShift (ARO) Workshops

Azure Red Hat OpenShift (ARO) Workshops プロジェクトは、インストラクター主導のデモ紹介またはセルフペースの演習で、AROを効果的に紹介及び体感していただくことを目的としています。

最初に受講者は、コンテナ/Kubernetes/OpenShift/AROの概要を学習します。

<embed src="docs/pdf/2022-aro-workshop-lecture.pdf#&scrollbar=0&view=Fit&viewrect=0,0,570,0" width="640" height="360" hspace="0" vspace="0">

資料のPDFは[こちら](docs/pdf/2022-aro-workshop-lecture.pdf)からダウンロードできます。


下記は、この資料の説明動画です。機械音声に読み上げさせているトークスクリプトは、[こちら](docs/pdf/talkscripts.zip)からダウンロードできます。

<iframe width="640" height="360" src="https://www.youtube.com/embed/hX73pBlfBFw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


次に下記のデモ紹介及び演習を実施します。コンテンツは以下の種類に分かれます。

- \[デモ\]: インストラクターによるデモ紹介です。受講者は、コマンド実行やGUIの操作をする必要はありません。
- \[ハンズオン\]: セルフペースの演習です。受講者は、コマンド実行やGUIの操作をしてワークショップを進めます。
- \[デモとハンズオン\]: 上記の両方を含みます。

### 演習の前提要件

- Azureにアクセス可能なネットワーク環境
- AROクラスターにアクセス可能なWebブラウザ
   - [「Browsers and Client Tools」表](https://access.redhat.com/articles/4763741)にある、最新版のOpenShiftに対応したWebブラウザ(Firefox/MS Edge/Chrome/Safari)のいずれかを利用します。

[オプションの演習](docs/aro-sample-app-develop)を進める際に必要な要件(オプションの演習をしない場合は不要)
- RHELサーバにSSHログインして、コマンドが実行可能
   - OpenShift CLI(ocコマンド)がインストールされているRHELサーバを利用するために、SSHログインが必要です。
- GitHubにアクセス可能なネットワーク環境とGitHubの個人アカウント

補足事項: 次のものを用意することで、下記コンテンツの自習も可能です。

- 有償サービスを利用可能なAzureアカウント
- 無料で作成可能な[Red Hatアカウント](https://cloud.redhat.com/) (「Create an account」から作成)

### コンテンツ

1. [\[デモ\] AROクラスターの作成](docs/aro-create)
1. [\[ハンズオン\] アプリケーションのデプロイのクイックスタート](docs/aro-app-deploy-quickstart)
1. [\[デモとハンズオン\] 永続ボリュームとしての Azure Disk/Files の利用設定](docs/aro-volume)
1. [\[デモとハンズオン\] Azure Service Operator による Azureリソースの利用](docs/aro-azure-resource)
1. [\[ハンズオン\] コンピュートノードの追加/削除とオートスケールの設定](docs/aro-nodes)
1. [\[デモ\] AROクラスターのアップグレード](docs/aro-upgrade)
1. [\[デモ\] AROクラスターの削除](docs/aro-delete)
2. [\[ハンズオン\] (オプション)AROクラスターでのJavaアプリケーション開発 スターターラボ](docs/aro-sample-app-develop)
