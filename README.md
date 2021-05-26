# pmmp-installer
ソースコードからPocketMine-MPを起動するためのPMMPインストーラー

このインストーラーを使用するとワンクリックでPMMPをソースコードから起動可能な環境が整います。

**依存関係パッケージのインストール**
```
sudo apt install composer php7.4-cli -y
```

**ダウンロードとインストール**
```
git clone https://github.com/BroccoliGG/pmmp-installer.git
cd pmmp-installer
chmod a+x install.sh
./install.sh
```

依存関係のComposerとPHPがインストールされていない場合はNot foundエラーが表示され、インストーラーが終了します。
