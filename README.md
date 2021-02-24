
IoT Fish app
===========================

This repo used [github.com/googlearchive/android-Camera2Basic][1] for reference. Please check also that repo. 

[1]: https://github.com/googlearchive/android-Camera2Basic

This Android app is made for iot fish monitoring.
It includes characteristical time lapse capture function.
Capturing is doned at set intervals.
Also, not only one, but two additional shoots will be done.
In addition to one interval capturing at regular intervals, two images are acquired 0.5 seconds before and after the original shooting.

On the application screen, it is possible to set the time interval of shooting, whether or not to use flash, and to display the estimated time of completion and the latest shooting status. 

In addition, on the source code of the application, we made it possible to set the interval of the three-shot burst, focal length, and white balance.
By setting the focal length to infinity, it was possible to capture images suitable for post image processing.
A function to change exposure settings according to the season and time was implemented.

このレポジトリは [github.com/googlearchive/android-Camera2Basic][2] を参考にしています。そちらのレポジトリもご確認ください。

[2]: https://github.com/googlearchive/android-Camera2Basic

このアプリはIoT魚モニタリングのためのアンドロイドアプリです。
特徴的なタイムラプスキャプチャ機能を搭載しています。
キャプチャは設定された間隔で行われますが、1回の撮影だけでなく、2回の撮影も追加で実施されます。
一定間隔での1回撮影に加え、元の撮影の0.5秒前と0.5秒後の2回撮影を行えます。

アプリ画面では、撮影間隔の設定やフラッシュ使用の有無、終了予定時刻や最新の撮影状況の表示などが可能です。

また、アプリケーションのソースコード上では、3連バーストの撮影間隔、焦点距離、ホワイトバランスを設定できるようにしました。
焦点距離を無限遠に設定することで、後処理に適した画像を撮影することが可能となっています。
さらに、季節や時間に応じて露出設定を変更する機能が実装されています。
