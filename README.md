PyJEM
=====================

概要
--------------
　PyJEMはJEOL製TEMの外部制御を行うためのpythonのライブラリです。スクリプト言語であるpythonで制御ができるため、インタラクティブにTEMの制御をすることを可能にしています。また、TEMの標準構成以外のPCにPyJEMをセットアップすることで、リモートからの制御を可能としています。

依存環境
--------------
 **OS**:
  * Windows 7 64bit
  * Windows 10 64bit
 
 **依存ソフト**:
  * Python 3.5.2 64bit

対応機種
----------------
* NEOARM
* JEM-ARM200F
* JEM-ARM300F
* JEM-F200
* JEM-2800
* JEM-1400Plus
* JEM-1400Flash
* JEM-2100Plus
* JEM-2200FS (by SightX)
* JEM-2100   (by SightX)
* JEM-3200FS (by SightX)
* JEM-3100F  (by SightX)
* JEM-2100F  (by SightX)


PyJEMでできること
----------------------------
PyJEMでは、TEM本体の制御や画像の取得を比較的簡単に行うことができます。これをPythonの豊富なライブラリと組合わせることで、
様々なアプリケーションを作成することができます。

* **電子光学系制御**： 
  
  ビーム制御、検出器In/Out、倍率変更、ブライトネス変更 など

* **ステージ制御**：

  絶対位置移動、相対位置移動、ピエゾ移動 など

* **画像取得**：

  STEM、TEM画像取得、画像保存種変更、解像度指定 など

* **自動機能**：

  Auto Focus、Auto Contrast Brightness、Auto Stigmator　など


本サイトについて
------------------------------------
　本サイトでは、PyJEMについての質問にのみ質問・回答を行います。
 装置不具合等のお問い合わせは、こちらよりお願いいたします。