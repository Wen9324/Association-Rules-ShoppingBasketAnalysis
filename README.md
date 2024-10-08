# Association-Rules ( Market Basket Analysis )
## Introduction
關聯規則（Association Rules）是一種在購物籃分析（Market Basket Analysis）中廣泛應用的數據挖掘技術，旨在發現大量交易數據中不同商品之間的有趣關聯或模式；
而購物籃分析的主要目的是找到在同一次購物中經常一起購買的商品組合，從而幫助零售商制定促銷策略、優化商品陳列、提高銷售額。
在關聯規則的資料挖掘中，常用的衡量標準包括支持度（Support）、置信度（Confidence）和提升度（Lift）：
- 支持度（Support）：表示某一規則中出現的商品組合在所有交易中出現的頻率，是可以用來衡量這些商品組合的受歡迎程度。
+ 置信度（Confidence）：表示在已經購買了某一組商品的情況下，另一組商品也被購買的概率，用於衡量了關聯規則的可靠性。
* 提升度（Lift）：表示購買某一組商品的行為是否真正提升了購買另一組商品的可能性，當提升度大於1表示正關聯，小於1表示負關聯。

關聯規則的應用不僅限於零售業，還可擴展到醫療、金融、電商推薦系統等多個商業領域，用於揭示、發現隱藏在數據中的關聯關係。
