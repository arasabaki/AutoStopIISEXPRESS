# AutoStopIISEXPRESS

## 機能

ビルド時に、IISEXPRESSのプロセスをkillします

## 使い方

1. Visual Studioのツールバーを右クリック
2. 「AutoStopIISEXPRESS」をクリックして、ツールバーに追加
3. ツールバーのボタンをクリックでON/OFF
4. ONにしておくと、ビルド開始時にプロセスをkillする

## 注意点

中身見てもらえばわかりますが、個人的な目的を満たすために作ったので、「iisexpress」でヒットしたプロセスを全部killする単純な作りになってます。
そのため、「iisexpress」を含むプロセス名のプロセスも一緒にkillされます。
巻き込み事故が発生する可能性がありますので、使用は自己責任でお願いします。