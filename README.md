# EXILIM プラグイン(下書き)

デバイスWeb APIで使用するカシオカメラEXILIMシリーズを制御するためのプラグインです。

EXILIM FR100, FR200等の無線対応カメラに接続して操作することができます。
Android版のAPKファイルの公開です。

(OSバージョンなどの対応条件)

# ファイル構成

* apk : Android用のAPKファイル

	* exilimplugin.apk : EXILIM プラグイン

	* sample.apk : EXILIM プラグインを操作するサンプルアプリ

* spec : EXILIM プラグインに実装されているプロファイルおよびAPI仕様

# インストール方法

Device Web API Managerをインストール済みの Android 端末に、EXILIM プラグインのAPKファイルをインストールしてください。

(URL)

# 使用方法

* Device Web API Managerの設定を変更し、Device Web API Managerを有効にしてください

* EXILIMカメラを起動し、リモート撮影状態で待機してください

	* カメラの操作方法はカメラのマニュアルを参照してください

* EXILIM プラグインをインストールした端末を Wi-Fiでカメラに接続してください

* 操作用アプリから Device Web API Manager に Device Connect API仕様に基づいたHTTPリクエストを送ってください


詳細な使用方法は[こちら](https://github.com/yamadat-casio/test-repos/wiki)を参照してください。
