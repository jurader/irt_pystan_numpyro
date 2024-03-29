# pystanとnumpyroで実装されたベイズ項目応答理論 (IRT)
このレポジトリには、下記の論文のソースコードがあります。

このソースコードにはIRT（1PL-IRTと2PL-IRT）がpystanとnumpyroで実装されています。
下記の論文では、このレポジトリのソースコードを用いて、1PL-IRTと2PL-IRTの潜在パラメータの推定結果をpystanとnumpyroの間で比較しました。


# 必要条件
ソースコードはipynb(notebook)ファイルとして記述されています。
下記の論文では、実験のためにGoogle Colaboratoryを使用しました。

Google Colaboratoryでは、以下のソフトウェアパッケージが使用されました。

* pystan, バージョン 3.3.0
* jax, バージョン 0.4.4
* jaxlib, バージョン 0.4.4+cuda11.cudnn82
* numpyro, バージョン 0.10.1


# ソースコードの作者
本レポジトリのソースコードの作者は以下のとおりです。

* 西尾 瑞穂（神戸大学・京都大学）
* 太田英司（[双葉数理技術](https://futaba-nt.com/)） 


# 論文
本レポジトリのソースコードを使用する場合は、可能ならば以下の論文を引用してください。

## Journal paper
Nishio M, Ota E, Matsuo H, Matsunaga T, Miyazaki A, Murakami T. 2023. Comparison between pystan and numpyro in Bayesian item response theory: evaluation of agreement of estimated latent parameters and sampling performance. PeerJ Computer Science 9:e1620 

* DOI: https://doi.org/10.7717/peerj-cs.1620
* URL: https://peerj.com/articles/cs-1620/

## プレプリント論文

* DOI: https://doi.org/10.1101/2023.03.29.23287903
* URL：https://medrxiv.org/cgi/content/short/2023.03.29.23287903v1


# ライセンス
このレポジトリのソースコードは、MITライセンスで提供されています。詳しくはこのリポジトリのライセンスファイルをご覧ください。
