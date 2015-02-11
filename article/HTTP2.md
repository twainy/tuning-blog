知らないと死ぬ！！HTTP2.0について調べてみた
===========

HTTP2クライアントコネクション

ハンドシェイク
---------------
* https で NPN を用いる
* https で ALPN を用いる
* http で Upgrade を用いる
* http で Atl-Svc を用いる 
*http で事前知識を用いる

バイナリフレーム
---------------
* SETTINGSを最初に送り、ACKを受け取ります

* multiplexing
* server push
* alpn(Application Layer Protocol Negotiation)/upgrade
* 
* binary frames
* header compression

参考文献
---------------
* HTTP/2 入門
http://techblog.yahoo.co.jp/infrastructure/http2/introduction_to_http2/

* http://http2.info/

* HTTP2
http://www.slideshare.net/YoshihiroIwanaga/http2-35067536?next_slideshow=1
