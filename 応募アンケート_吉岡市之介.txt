 作品名　　：
 跳弾
 とまれない 
 
 作成期間　：
 跳弾 2025年10月～2026年2月（週に３回７時間）
 とまれない  2026年3月～2026年6月（週に３回７時間）
Project Duration:
 跳弾 October 2025 to February 2026
 とまれない  March 2026 to June 2026
 チーム制作の場合
 制作メンバー :
 プログラマー1名
For Group Projects
Project Members:
1 Programmers

-----------------------------------------------------------------------------
 プログラム作品の開発環境についてご記入ください
 Please enter the following details regarding your development environment.
-----------------------------------------------------------------------------
・動作確認したOS名とそのバージョン
  OS used, including the version:
    Windows 11 Pro

・開発に使用したライブラリ、ミドルウェアとそのバージョン
  AQUA Game Library 7.17,ＤＸライブラリ Ver 3.24f

・開発に使用したエンジンのバージョン
  なし

・開発に使用した開発環境のバージョン
  Visual Studio 2022


-----------------------------------------------------------------------------
 プログラムを作成する上で大変だった所はどこですか？
 Please tell us what you found difficult about this project.
-----------------------------------------------------------------------------
跳弾
弾を敵に当てた際に、敵が受けた方向から適切に弾を跳ね返す処理の実装に苦労しました。単純に弾の進行方向を反転させるだけでは、壁や敵との位置関係によって意図しない方向へ跳ね返ってしまうことがありました。そこで、衝突した位置や弾の進行方向を確認し、反射方向を計算する処理を実装しました。また、複数の弾が同時に存在する場合でも正しく処理できるよう、弾ごとの状態を管理することにも注意しました。

とまれない
各オブジェクト同士が接触した後の処理の実装に苦労しました。接触するオブジェクトの組み合わせによって、ダメージや消滅など異なる処理が発生するため、それぞれの状態を適切に判定する必要がありました。そこで、オブジェクトごとの役割を整理し、接触判定と接触後の処理を分けて実装しました。また、新しいオブジェクトを追加する際に既存の処理を大きく変更せずに済むよう、共通する処理をまとめ、拡張しやすい構成を意識しました。
-----------------------------------------------------------------------------
 力をいれて作った部分で、「プログラム上」で特に注意してみてもらいたい所はどこですか？
 What would you like us to focus on when examining your work?
-----------------------------------------------------------------------------
跳弾
特に見ていただきたいのは、弾の跳ね返り処理です。弾が壁やオブジェクトに接触した際に、接触した場所や方向をもとに跳ね返る方向を計算し、自然な軌道になるように実装しました。また、弾の移動処理と当たり判定を適切に組み合わせ、連続して壁に当たった場合でも意図した動作になるよう注意して制作しました。実際のゲーム中での弾の挙動と、それを実現するための処理に注目していただきたいです。

とまれない
特に見ていただきたいのは、各オブジェクトの接触処理を、できるだけ個別のオブジェクトに依存しないように設計した部分です。オブジェクトごとに処理を分けつつ、共通する接触処理をまとめることで、新しいオブジェクトを追加する際に既存の処理を大きく変更せずに対応できるよう意識しました。また、各オブジェクトの役割を明確にすることで、処理の流れを追いやすくし、修正や機能追加がしやすい構成にしています。
-----------------------------------------------------------------------------
 参考にしたソースファイルがあるのなら、 どの様なところを参考にしましたか？
 またその部分のファイル名を書いてください。
 If you used external source code as reference, please tell us which portions you referenced.
 Please also indicate the file names of said code.
-----------------------------------------------------------------------------
なし

※ 注意 ※
IMPORTANT
他の人が作成したライブラリ、関数等を使っている場合は、
その部分を「別ファイル」に分けて、そのファイル名を書いてください。
If you have used a library or function created by someone else:
Please create a separate file containing that portion of the code and enter its file name below.

 ＜以下のような場合が該当します＞
　*　他人の作った関数を使用した場合
　*　何かを参考にし参考元のソースが半分以上残っている場合
　*　フリーのライブラリを使用した場合（ライブラリ名を明記してください。）
　*　他人の作ったライブラリを使用した場合（ライブラリ名を明記してください。）
　*　「チーム」で作成した作品の場合
　　（自分の担当した箇所やソースファイル名がわかるよう明記してください。）
This is applicable if:
　*　You have used a function made by someone else
　*　You have used something as a reference, and have kept more than half of it intact.
　*　You have used a free library (please indicate the library name)
　*　You have used a library made by others (please indicate the library name)
　*　The project you submitted was a group project
     (Please indicate clearly the source file name and which portion of the code was your own work.)
 
 学校から配布されたAQUA Game Libraryを使用しています。
 AQUA Game LibraryはDXLibを利用したゲーム制作向けのライブラリです。
 配布されたのは[aqua]というフォルダです。
-----------------------------------------------------------------------------
生成AIを使用しているところがあれば、どの部分に利用したのか明記してください。
アセット、ソースだけではなく、ポートフォリオなどの資料も対象です。
Please clearly indicate any portions of your code that was created using Generative AI.
This applies not only to your code and assets, but to your portfolio and any documents you may have submitted.
-----------------------------------------------------------------------------
画像生成、プログラム制作時の関数・機能の検索および確認、ソースコードのコメントアウトの作成・整理、考えられるバグや問題点の洗い出し、
ポートフォリオのレイアウトや構成の検討、文章の添削・表現の整理に生成AIを使用しました。ゲームの主要なプログラム処理については自身で実装しています。
-----------------------------------------------------------------------------
 再応募していただいた方へ。前回からの変更点を挙げてください。
 なぜその部分を改善しようとしたかと、変更点の詳細は別資料を添えてください。
If this is not your first time applying to our company, please indicate any changes you've made to your submitted code/projects.
Please also note the reasons you've made those changes and their details as a separate document.
-----------------------------------------------------------------------------