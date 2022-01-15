# Neutron

7zip で dmg を解凍した際に、Electron 製のアプリが起動できないバグを修正するパッチ。

※ファイルサイズが大きいので、インターネット環境に注意してダウンロードしてください。

## 使い方

まず、プロジェクト内の`Electron Framework.framework.zip`を解凍し、`Electron Framework.framework`を取得します。

対象のアプリの`Electron Framework.framework`をこのプロジェクトの`Electron Framework.framework`に置き換えることで起動できるようになります。
例えば、対象のアプリケーションが`~/Applications/Discord.app`の場合、`~/Applications/Discord.app/Contents/Frameworks/Electron Framework.framework`をこのプロジェクトのものに置き換えます。
