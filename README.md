# HandsOnMCU
DIY Business Card with CH552 Microcontroller

この名刺をお受け取りいただき、ありがとうございます。
HandsOnMCUは、従来の名刺の役割に加えて、電子工作やマイコンプログラミングを体験していただける教育用キットとして設計いたしました。

なお、組み立てには部品代が必要となりますことをご了承ください。

詳細な組み立て方法やプログラミングについては、Wikiをご参照ください。

# 特徴
HandsOnMCUは、最小限の部品でマイコン制御を学べる入門用プロジェクトです。

## 必要部品
以下の部品は、[秋月電子](https://akizukidenshi.com/)、[千石電商](https://www.sengoku.co.jp/)、[共立エレショップ](https://eleshop.jp/)、[Aliexpress](https://ja.aliexpress.com/)、[Aitendo](https://www.aitendo.com/)などでお求めいただけます。

メインのマイコンCH552については、実装のしやすさを考慮してSOP16パッケージのCH552Gを採用しています。このICは主にAliexpressで10個単位、もしくは[Aitendo](https://www.aitendo.com/product/20923)での1個の販売のみとなっております。ご了承ください。

|部品名|価格(約)|販売先|
|-----|----|-----|
|ピンヘッダ 1x07 2.54mmピッチ|10円 x 2|[秋月電子](https://akizukidenshi.com/catalog/g/g100167/)、[千石電商](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=25CH-53LJ)、[Amazon*](https://www.amazon.co.jp/KKHMF-2-54mm-40-Pin-DIY%E5%8D%98%E4%B8%80%E5%88%97%E7%AB%AF%E5%AD%90%E3%83%94%E3%83%B3-Ardunio%E3%81%AB%E5%AF%BE%E5%BF%9C/dp/B0829W3T8Q/ref=sr_1_6?__mk_ja_JP=%E3%82%AB%E3%82%BF%E3%82%AB%E3%83%8A&crid=28A6UVURLMZ4L&dib=eyJ2IjoiMSJ9.hNP8HU7wobRqwMJlpOQoz0cE58UpYGM68-eyU5zF73zH6YPrdaikmOtE0G7qyXw0gPZ4aRQiNYvgbiXgdtc0SUfBYvP7QxQ4PCQmS6sNs7kE3p0ee-JBiayRTfCj2_XQ7a9rq4Px8vp2Zd8QuAWnQY8-3oRQHLfs87Cdrl4A6KcSpwHkzQHBHBvMMBDko5eTFbw9d5do081s8D2nviTpwSIX51zrJgjm0KgxTiB5cyD50d0syFszKGCtjIWEFrkWwkEdwnBRYPCuQ94XXxBJLn95-3WOiUnCnx8cNpjueCvuhaCNjES-rLRmU1J1xQDg9Gp6kAdEHvd6AQ7aQmtknQlkxmFUrFtPZgMzGwud3T1MwoClgPLPBNhvHMtylTWYtiPVXxkZ9p1FL6PolmBIdiYlbD3TMPp-J5dTnMagWCxPvymASPGR8yWT6B_3aJVF.RInApAleGFQKdrYk-xgId3W4JWkDfNoM83oowd_aExk&dib_tag=se&keywords=%E3%83%94%E3%83%B3%E3%83%98%E3%83%83%E3%83%80&qid=1738770687&sprefix=%E3%83%94%E3%83%B3%E3%83%98%E3%83%83%E3%83%80%2Caps%2C184&sr=8-6)、[Aliexpress](https://ja.aliexpress.com/item/4000988113226.html?spm=a2g0o.productlist.main.1.f5e9504919i7cs&algo_pvid=0faaf3d1-01ac-480c-adeb-03af18d69b31&algo_exp_id=0faaf3d1-01ac-480c-adeb-03af18d69b31-0&pdp_npi=4%40dis%21JPY%21338%21338%21%21%212.16%212.16%21%402101246417387707472938869e5c5c%2110000013202368860%21sea%21JP%213272919614%21X&curPageLogUid=dewA4J1qYQTB&utparam-url=scene%3Asearch%7Cquery_from%3A)、[共立エレ](https://eleshop.jp/shop/g/gEAT417/)|
|積層セラミックコンデンサ 0.1μF|5円 x 2|[秋月電子*](https://akizukidenshi.com/catalog/g/g113582/)、[千石電商]()、[Aliexpress](https://ja.aliexpress.com/item/1287630682.html?spm=a2g0o.productlist.main.9.175f54c24NEjEV&algo_pvid=a2f7a971-c44e-4945-90e0-bfbb4ac78321&algo_exp_id=a2f7a971-c44e-4945-90e0-bfbb4ac78321-4&pdp_npi=4%40dis%21JPY%21316%21316%21%21%212.02%212.02%21%40212e532617387710468902192e507b%218199178653%21sea%21JP%213272919614%21X&curPageLogUid=m8XomzCcLJXi&utparam-url=scene%3Asearch%7Cquery_from%3A)、[共立エレ](https://eleshop.jp/shop/g/gJ8R311/)|
|LED 5mm|10円x2|[秋月電子](https://akizukidenshi.com/catalog/goods/search.aspx?search=x&keyword=LED+5mm&search=search)、[千石電商](https://www.sengoku.co.jp/mod/sgk_cart/search.php?cid=3104)、[Aliexpress](https://ja.aliexpress.com/w/wholesale-LED-5mm.html?spm=a2g0o.productlist.search.0)、[共立エレ](https://eleshop.jp/shop/goods/search.aspx)、[部屋に落ちているやつ*](https://www.google.com/search?q=%E7%89%87%E4%BB%98%E3%81%91&udm=2)|
|CH552G|80円|[AliExpress*](https://ja.aliexpress.com/w/wholesale-CH552G.html?spm=a2g0o.detail.search.0)、[Aitendo](https://www.aitendo.com/product/20923)|
|マイクロUSBコネクタ|50円|[DigiKey](https://www.digikey.jp/ja/products/detail/molex/0480370001/857603)、[Amazon*](https://www.amazon.co.jp/gp/product/B07RB5PQPF/ref=ox_sc_act_title_1?smid=AANM8PRMV1MBN&psc=1)、[Aliexpress](https://ja.aliexpress.com/item/1005006980236503.html?spm=a2g0o.productlist.main.11.5b246dfa6gVxna&algo_pvid=e5ebbfb1-c5ba-47c3-a191-0d60e10349a8&algo_exp_id=e5ebbfb1-c5ba-47c3-a191-0d60e10349a8-10&pdp_ext_f=%7B%22order%22%3A%2212%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21JPY%21325%21325%21%21%2115.51%2115.51%21%40%2112000038925710643%21sea%21JP%213272919614%21X&curPageLogUid=OLOFevvnuXlZ&utparam-url=scene%3Asearch%7Cquery_from%3A)|
|抵抗 220Ω|5円x2|[秋月電子](https://akizukidenshi.com/catalog/g/g125221/)、[千石電商](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=8ATS-7UHP)、[Aliexpress](https://ja.aliexpress.com/w/wholesale-220%CE%A9-%E6%8A%B5%E6%8A%97.html?spm=a2g0o.productlist.search.0)、[部屋に落ちているやつ*](https://www.google.com/search?q=%E7%89%87%E4%BB%98%E3%81%91&udm=2)|
|抵抗 1kΩ|5円 x 2|[秋月電子](https://akizukidenshi.com/catalog/g/g125103/)、[千石電商](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=EEHD-5FDE)、[Aliexpress](https://ja.aliexpress.com/item/1005005610622035.html?spm=a2g0o.productlist.main.5.3055eIYxeIYxTA&algo_pvid=288a1761-3d43-4706-b163-90d23132c4cc&algo_exp_id=288a1761-3d43-4706-b163-90d23132c4cc-4&pdp_ext_f=%7B%22order%22%3A%22142%22%2C%22eval%22%3A%221%22%7D&pdp_npi=4%40dis%21JPY%21429%21429%21%21%212.82%212.82%21%40%2112000033742116327%21sea%21JP%213272919614%21X&curPageLogUid=HDrgYbXeChSZ&utparam-url=scene%3Asearch%7Cquery_from%3A)、[部屋に落ちているやつ*](https://www.google.com/search?q=%E7%89%87%E4%BB%98%E3%81%91&udm=2)|
|タクトスイッチ 6mm|10円x2|[秋月電子](https://akizukidenshi.com/catalog/g/g103647/)、[千石電商](https://www.sengoku.co.jp/mod/sgk_cart/detail.php?code=7DLE-TGMW)、[Aliexpress](https://ja.aliexpress.com/item/1005002487399422.html?spm=a2g0o.productlist.main.17.74105102lIvY3e&algo_pvid=f8bcedaa-1815-4947-a627-c3e9298692f5&algo_exp_id=f8bcedaa-1815-4947-a627-c3e9298692f5-8&pdp_npi=4%40dis%21JPY%21361%21347%21%21%212.31%212.22%21%402101062a17387733100332982e9665%2112000020837840555%21sea%21JP%213272919614%21X&curPageLogUid=leM75KGeaVcK&utparam-url=scene%3Asearch%7Cquery_from%3A)、[部屋に落ちているやつ*](https://www.google.com/search?q=%E7%89%87%E4%BB%98%E3%81%91&udm=2)|

「 * 」マークのついているものは、私が使用しているものです。とりあえずつけばOKです。
