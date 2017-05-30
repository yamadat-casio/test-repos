# EXILIM プラグイン

デバイスWeb APIで使用するカシオカメラEXILIMシリーズを制御するためのプラグインです。

EXILIM 無線対応カメラに接続して操作することができます。

Android版オープンβ版のAPKファイルの公開です。

(Android Ver.4.4以上対応)

動作確認カメラ：EX-FR200, EX-FR100, EX-ZR3200


# ファイル構成

* apk : EXILIM Android用のAPKファイル

	* exilimplugin.apk : EXILIMプラグイン

	* sample.apk : サンプルアプリ

* sample : EXILIM プラグインを操作するサンプルアプリのプロジェクト

* spec : EXILIM プラグインに実装されているプロファイルおよびAPI仕様

# インストール方法

Device Web API Managerをインストール済みの Android 端末に、EXILIM プラグインのAPKファイルをインストールしてください。


# 使用方法

* Device Web API Managerの設定を変更し、Device Web API Managerを有効にしてください
	
	1. Device Web API ManagerをOFFの状態で設定を変更してください

	1. Origin有効化のチェックボックスを外してください

	1. Device Web API ManagerをONにしてください

* EXILIMカメラを起動し、リモート撮影状態で待機してください

	* カメラの操作方法はカメラのマニュアルを参照してください[(オンラインマニュアル)](http://support.casio.jp/manual.php?cid=001)

* EXILIM プラグインをインストールした端末を Wi-Fiでカメラに接続してください

* 操作用アプリから Device Web API Manager に Device Connect API仕様に基づいたHTTPリクエストを送ってください


詳細な使用方法は[こちら](https://github.com/yamadat-casio/test-repos/wiki)を参照してください。

# サンプルアプリ

動作確認用のサンプルアプリをAndroid用のAPKファイルとプロジェクトで用意しました。

[APK](https://github.com/yamadat-casio/test-repos/tree/master/sample)

[プロジェクト](https://github.com/yamadat-casio/test-repos/tree/master/sample)
