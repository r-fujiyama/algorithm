# 環境構築

## 必要なソフトウェア

- [Visual Studio Code](https://code.visualstudio.com/)
- [Docker Engine](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## プロジェクトの構築

1. `Visual Studio Code`を起動します。
1. 以下の拡張機能を追加します。  
Remote - Containers (ms-vscode-remote.remote-containers)
1. `Visual Studio Code`でプロジェクトのカレントディレクトリを開きます。
1. コマンドパレットを開き、下記コマンドを実行します。  
`Remote-Containers: Reopen in Container`
1. 環境構築完了。

## デバッグ方法

1. buildフォルダを作成。
1. デバッグを実行したいmani関数が定義されているファイルを開く。
1. `ctrl + shift + b`を押下し`debug build`を実行。
1. `F5`を押下しデバッグを開始する。
