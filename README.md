# Minecraft-Server

こちらはMinecraftのワールドデータです。<br>

期間: 2021/09/03～2022/01/01

## version
- Forge 1.17.1
```
>java -version
java version "16.0.2"
```

## owner
- Unpelorin

## member
- akipipi
- asuberu
- koyasu1116
- LEOScarletGrace
- mochimochi49

## 使用MOD
- マインオール
- ディグオール
- カットオール

## 導入方法
1. Forge 1.17.1をインストール
2. インストールしたファイルを実行し、◉Server を選択しインストール
3. 2で選択したPathに移動後、batファイルを作成して実行
### batファイルの中身
```
@echo off
java -Xmx1024M -Xms1024M -jar minecraft_server.1.17.1.jar
pause
```
4. batファイルを作成して生成される __eula.txt__ の中身を```eula=TRUE```に編集
5. batファイルを再度実行して、ワールドが生成されてから```stop```をコマンドで打ち込む。
6. 解凍したこのフォルダの中身をbatファイルを作成したフォルダに上書き保存。
