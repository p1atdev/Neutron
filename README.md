# Neutron

7zip で dmg を解凍した際に、Electron 製のアプリが起動できないバグを修正するパッチ。

## 使い方

対象のアプリの`Electron Framework.framework`をこのプロジェクトに含まれる`Electron Framework.framework`に置き換えることで起動できるようになります。
例えば、対象のアプリケーションが`~/Applications/Discord.app`の場合、`~/Applications/Discord.app/Contents/Frameworks/Electron Framework.framework`をこのプロジェクトのものに置き換えます。
