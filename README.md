# attracts_ws
ATTRACTS向け開発ロボット用のROS2パッケージ群の環境構築用リポジトリ

## 事前準備
### RaspberryPi5+Ubuntu24.04+m.2SSDBoot
- これを参照
  - https://raspida.com/how2boot-nvme-ubuntu/

### ROS2 Jazzyのインストール
- これを参照
  - https://www.techlife-hacking.com/?p=2857

### windows10からubuntu24.04へのRDP接続
- これを参照
  - https://qiita.com/hitobb/items/b44e87e04133dc845265
  - https://engrmemo.jp/linux/ubuntu-remote-desktop/#google_vignette
  - https://knowledge.f5.si/open.knowledge/view/51
  - https://qiita.com/Olykoek/items/9956e375d06c69de4243

#### 他の方法
やったら追記、誰かやったら追記して欲しい

## 使い方
- `git clone git@github.com:robot-trainee/attracts_ws.git`
- `cd attracts_ws`
- `vcs import src < default_package_list.repos`
- `colcon build`

## その他
- このリポジトリで使っている`vcs`について
  - https://memoteki.net/archives/3296
- UbuntuにGitをインストール
  - https://qiita.com/tommy_g/items/771ac45b89b02e8a5d64
- ubuntuで日本語入力を有効にする
  - https://lilaboc.work/archives/29007972.html

## legacy
## 事前準備
### Ubuntu22.04のインストール
#### WSLを用いた方法
- Ubuntu22.04のインストールはこれを参照
  - https://zenn.dev/sunazukin/articles/8fe49e9dee7b7c
- ubuntu-desktopのインストールはこれを参照
  - https://qiita.com/Akaaku/items/31428b3478a1b58196a6

### ROS2 Humbleのインストール
- これを参照
  - https://qiita.com/porizou1/items/5dd915402e2990e4d95f