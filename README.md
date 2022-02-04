<p align="center">
    <img src="https://raw.githubusercontent.com/albertopoljak/Licensy/master/logo.png">
</p>

[![Licensy vAplha](https://img.shields.io/badge/Licensy-alpha-yellow)](#)
[![Activity](https://img.shields.io/github/commit-activity/w/albertopoljak/Licensy)](https://github.com/albertopoljak/Licensy/pulse)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](#)
[![Python 3.6+](https://img.shields.io/badge/python-3.6%2B-blue)](#)
[![License AGPL3](https://img.shields.io/github/license/albertopoljak/Licensy?color=red)](LICENSE.md)

# Replitで実行可能にしたLicensy.
Replitでtokenをenvに入力するだけで使えます。


# Replitでの設定
 - <h4> main.shで色々動かすので、Bashにしてください。普通にこのリポジトリをインポートすればBashになると思います。</h4>
 - <h4>Pythonのバージョンは8ぐらいがいいです。つまり、Replitで使うなら何もいじらなくていいという事です。</h4>
 - <h3>詳しくは、動画を見てやってください。</h3>

# 公式のでは無い、新規コマンド
- `!one_month`コマンドで今の1ヶ月後のタイムスタンプが貼られます。
- `!lifetime`コマンドで、今の200年後のタイムスタンプが貼られます。
</br>
</br>

## ここから下は公式のReadMeとほぼ一緒です。

# サブスクリプションで役割の有効期限を簡単に管理
ライセンスのコードを入力することでロールを付与可能。
複数のサーバーで独立して動作します。


## クイックスタート

ボットの機能を使うために、管理者権限を渡してください。

デフォルトのプレフィックスは `!`です。

デフォルトのライセンスの有効期限は**30日**(720時間)です。


`!generate`コマンドを利用して、期限付きでロールが取れるライセンスをジェネレートすることができます。
(例)
```
!generate 10 @subscription 1m
```

この場合だと、 `@subscription` ロールが1ヶ月だけ持てるライセンスを5個ジェネレートすることができます。
詳しくは公式のReadMeを見てください。



## License

This project is licensed under the GNU AGPLv3 License - see the [LICENSE.md](LICENSE.md) file for details
, for plain english you can check out [tldrlegal](https://tldrlegal.com/license/gnu-affero-general-public-license-v3-(agpl-3.0)).

If you fork/download the code and run your own bot instance **WITHOUT** changing the code then you don't have to worry
regarding the license as all is already implemented in the bot functionality (commands that link to this readme, state
authors etc..) 

But if you fork/download/host this bot and you **CHANGED** any of the code you **must** hold to this:

- Include copyright (see [Authors](#authors))
  - You cannot claim this code as yours.
- Include the same license (see [LICENSE.md](LICENSE.md))
- State changes
  - any changes to the source code must be disclosed (public).
- Disclose source
  - you cannot take the code and make it private.
- Include install instructions
  - You can link to this readme or to your own instructions.

Only and only if you adhere to all of the above points you **can**:

- Use the bot for commercial use
- Modify the source
- Distribute the bot
- Place Warranty
