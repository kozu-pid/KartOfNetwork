# KartOfNetwork

## 概要
 1. ここでは研究で使うカートプログラムにネットワークを適応する．
 2. カートの操作はコントローラー入力

## 目的
 ゲームにおいて，QoSを制御してQoEを下げない実装の研究
 
## 実装方針
 ### 1. 端末1つを入力機，もう一つを出力機として遅延をかける
 　出力機の映像をそのままみる方針
 
 ### 2. 端末1つをサーバー，もう一つをクライアントとする
   クライアントはサーバーから帰ってきた映像をみる
   こちらの方がより現実に近いため，こちらを目指す
