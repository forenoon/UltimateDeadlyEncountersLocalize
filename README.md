UltimateDeadlyEncounters_jp

# ■About
Skyrim MOD "Ultimate Deadly Encounters" 日本語ローカライズ。（以下、UDEとする）<br>
現状はLoose File版にのみ対応している。

MOD本体は以下

* [Nexus mods](http://www.nexusmods.com/skyrimspecialedition/mods/3093/?)
* [Skyrim Mod データベース](http://skyrim.2game.info/detail.php?id=12452)

以下の箇所はまだ翻訳が終わっていない

* MCM　※翻訳箇所をミスるとMCMが機能しなくなるから怖い…
* 本　※文量が半端なく多くて、小説表現（？）がわからん…

# ■インストール
**※※※ 注意！！！ ※※※<br>
絶対に、自分が使うバージョンが無かった場合に違うバージョンのespとpexを使用しないこと！<br>
MODが破損してCTDするか、最悪ゲームがおかしくなる可能性がある。 <br>
バージョンが無かった場合は、自分でSkyrimにインストールされているMODに翻訳データを当てて対応する。**

事前にSkyrim本体の「Data」フォルダ中のMODデータをバックアップしておくといい。<br>
ミスっても戻せるから安心

* Data/SleepingDangers-SandsofTime.esp
* Data/scripts
   * 他のMODのスクリプトも含まれるが気にせずバックアップしておく

## 自分が使うUDEのバージョンの翻訳があった場合
翻訳済みのespとpexを上書きするだけなので楽。

1. Githubのページの「Branch」を自分のUDEバージョンに切り替える。
1. Githubのページの「Clone or download」から「Download ZIP」をクリックする。
1. ダウンロードされたZIPを解凍する。
1. 解凍されたフォルダ中の「Data」フォルダの中身をSkyrim本体の「Data」フォルダに上書きする。
1. ENJOY YOUR SKYRIM !

## 自分が使うUDEのバージョンの翻訳が無かった場合
自分で翻訳データをMODへ当てていく。少し面倒だが大部分は翻訳されるはず。

1. Githubのページの「Branch」を自分のUDEバージョンに*比較的近いもの*に切り替える。
1. Githubのページの「Clone or download」から「Download ZIP」をクリックする。
1. ダウンロードされたZIPを解凍する。
1. 翻訳ツールをダウンロードする。sseTranslatorを使ったが、tesvTranslatorでもおそらく問題ない。
   * sseTranslator
      * [[MODデータベース] sseTranslator](http://skyrimspecialedition.2game.info/detail.php?id=134)
      * [[Nexus] sseTranslator](http://www.nexusmods.com/skyrimspecialedition/mods/134/?tab=1&navtag=http%3A%2F%2Fwww.nexusmods.com%2Fskyrimspecialedition%2Fajax%2Fmoddescription%2F%3Fid%3D134%26preview%3D&pUp=1)
      * ※sseTranslatorはダウンロード時にNortonに誤検地削除されてしまう模様。<br>回避方法もあるがわからなければtesvTranslatorを使う。
   * tesvTranslator
      * [[MODデータベース] tesvTranslator](http://skyrim.2game.info/detail.php?id=29148)
      * [[Nexus] tesvTranslator](http://www.nexusmods.com/skyrim/mods/29148/?)
1. Skyrim本体の「Data」フォルダにあるespとscripts/*.pexに解凍した「Data_xml」フォルダのxmlを適用する。
   * sseTranslatorやtesvTranslatorのセットアップや使い方は以下を参考。どちらもほぼ同じ。
   * [TESVTranslatorの導入から使い方まで解説（STRINGSファイルの抽出方法も）](http://nerdhayayo.blog.fc2.com/blog-entry-13.html)
   * [ど素人減量ライダー始末記 > いまさらの TESVTranslator](http://mantarou-dengana.cocolog-nifty.com/yosenabe/2015/01/tesvtranslator2.html)
   * [sseTranslatorの準備について](http://speakeir.hatenadiary.jp/entry/2016/11/20/215155)
1. ENJOY YOUR SKYRIM !

## 間違ったバージョンの翻訳を当ててしまった場合
事前にSkyrim本体の Data/SleepingDangers-SandsofTime.esp と Data/scripts をバックアップしていたらそれを上書きコピーしなおす。

バックアップも取っていなければ、MODをインストールしなおす。(oh...)


# ■翻訳が間違っていたり変な訳があった場合

## おかしいところを私に教える
[UltimateDeadlyEncounters_jp Issues](https://github.com/forenoon/UltimateDeadlyEncounters_jp/issues) から教えてほしい。
（※Githubのアカウント登録がいるけど…）

その場合は以下の情報がほしい。

* どんなテキストだったか。
* どうおかしかったか。
   * ※訳がかたいのは仕様な(´･ω･`)　でも良い訳があるなら教えて欲しい…
* テキストはいつどこで表示されたものか。
   * ※翻訳したもののどこででるか確認できていないものもある…
   * ※ルミールアクエストがちゃんとクリアできるとか、人種デスナイトとか翻訳するまで知らなかった…

## 自分で翻訳してMODに適用する
[UltimateDeadlyEncounters_jp Wiki](https://github.com/forenoon/UltimateDeadlyEncounters_jp/wiki) にガイドライン的なものを載せている。
是非頑張って欲しい。

# ■新しいバージョンの対応はまだ？
暇だったらね…(´･ω･`)<br>
あと本家のMODのバージョンが変わったか気づかない事が多いから、[Issues](https://github.com/forenoon/UltimateDeadlyEncounters_jp/issues) で教えてくれてもいい。

でもpexが200個以上あってチェックも大変なんだよなぁ…
