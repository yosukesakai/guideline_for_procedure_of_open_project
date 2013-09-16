
#xivelyにおけるCC0の適用のしかた

xivelyではCC0を採用した(2013)。
デバイス、データをpublicにした場合、CC0が採用される。

```
xively Public and Private Feeds
https://xively.com/dev/docs/api/security/public_and_private_feeds/
“When a device is public, the device and its data are made available under the terms of the Creative Commons CC0 1.0 Universal license.”

xively Accounts, data, devices: An explanation
http://blog.xively.com/2013/05/15/accounts-data-devices-an-explanation/
“So, in Xively, if you make data public a Creative Commons CC0 1.0 Universal license is applied (both on its page and in headers when requested via the API), which expresses your ownership of your data but your desire to make it much more useful and usable to others that might access the data. Read more about CC0 here.”

Public and Private Feeds
https://xively.com/dev/docs/api/security/public_and_private_feeds/
Your data is your data. For full details please see the LogMeIn Terms of Service.
You can specify whether or not a Feed is private to you or publicly available to others, by configuring the privacy settings using the “private” attribute of the Feed.
When a device is private, the device and its data are only accessible to you and those to whom you selectively grant access. A private device is not listed in Xively’s online public directory.
When a device is public, the device and its data are made available under the terms of the Creative Commons CC0 1.0 Universal license. For detailed information, visit the Creative Commons website, http://creativecommons.org/publicdomain/zero/1.0/, but briefly this means that all data about and created by a public device can be copied, shared and modified by anyone, even for commercial gain. Public devices will be listed in Xively’s online public directory.


```

xivelyに対するCC0についての問い合わせへの返信

```
Subject: concerned in data of Public Device under CC0
JUL 31, 2013  |  03:50PM BST

Putting the information in the description would work. All public
devices on Xively have their data licensed under the CC0 1.0 license
(http://creativecommons.org/publicdomain/zero/1.0/). On each outgoing
request via our API we send a header called “X-License” which points
to the license for the data.


```



xivelyでデータを公開する方法、データをpublicにする方法

```
デバイスのメタデータ編集画面で、publicを選択する。
```

xivelyから送られるのデータのヘッダを確認

```
xivelyのサポート曰く、"On each outgoing request via our API we send a header
called “X-License” which points to the license for the data."。


firefoxのaddon”livehttpheaders”を用いて確認する。

これで、例えば以下を確認。
API Endpoint
https://api.xively.com/v2/feeds/176655154

CC0の表記を確認できる。
```


xivelyの各データのページにCC0を表記する

```
xivelyのメタデータを以下に更新するのが良いかと思います。
(xivelyにログオンして、Developを選び、目的のデバイスを選び、画面左下のメタデータを編集します。)
(CC0については、htmlによるメタデータを埋め込むのがベストなのですが、XivelyのDescriptionはhtmlを受け付けないため、プレーンテキスト版を作ってみました。)
(いまのところ、Creatorは"ycam"と表記されています。"YCAM InterLab"の方が良いかと思いました。)


Metadata

Description
CC0 1.0 Universal [http://creativecommons.org/publicdomain/zero/1.0/]
To the extent possible under law, YCAM InterLab has waived all
copyright and related or neighboring rights to bioelectric potential
data from trees in 'Forest Symphony'. This work is published from:
Japan.
For more detail, please refer to our website.

Creator
YCAM InterLab

Website
http://interlab.ycam.jp/en/projects/forestsymphony

```
