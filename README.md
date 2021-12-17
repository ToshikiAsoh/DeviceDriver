# Lチカデバイスドライバー
ターミナル入力によってledのオン・オフを制御できるデバイスドライバを作成  
# 環境
* マシン：Raspberry Pi 4　Model B 8GB
* OS：ubuntu20.04.3 LTS
* エディタ：vim
# 使用したもの
* Raspberry Pi 4　Model B 8GB
* ブレッドボード
* ジャンパー線(オスメス) x2
* 抵抗(200オーム)
* led (赤)
# 回路図
以下のような回路図を構築

![deviseDriver gpeg](https://user-images.githubusercontent.com/92129518/146563327-e8b30e4a-24e1-41f9-9b15-63aad8ad049f.png)
# 実行方法
ledのオンオフは以下のunixコマンドを入力することで実行可能  
 オン： `$ echo 1 /dev/myled0`  
 オフ： `$ echo 0 /dev/myled0`
# 動作テスト
実際の動作は以下リンクより視聴可能
YouTube： https://youtu.be/9Xc7GDbpYPU 
# ライセンス
GNU General Public License v2.0  
URL: https://github.com/ToshikiAsoh/DeviceDriver/blob/main/COPYING 
