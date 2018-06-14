# Experiment on Using Topic Sentence for Neural News Headline Generation
- Jan Wira Gotama Putra (東工大), Hayato Kobayashi (ヤフー/理研AIP), Nobuyuki Shimizu (ヤフー)
- 言語処理学会第24回年次大会(NLP2018)
- http://anlp.jp/proceedings/annual_meeting/2018/pdf_dir/A1-2.pdf

# どんなもの？
- encoder-decoderモデルを用いたニュースの見出し生成タスクにおいて、先行研究では文章の第一文を使うことが多い
- 本研究では、トピックセンテンス（文章内の重要な文章）を使った場合の影響を調べる
  - 第一文よりもトピックセンテンスの方が有用か否か
  - 第一文に加えてトピックセンテンスも使った場合にも有用か否か

# 先行研究と比べてどこがすごい？
上記に記載

# 技術や手法のキモはどこ？
## 「トピックセンテンス」の定義
文献[14]に基づき、以下のように定義する

>Topic sentence contains the core elements ⟨subject, verb, object⟩ and at least one subordinate element time or location

# どうやって有効だと検証した？

<img src="https://cdn-ak.f.st-hatena.com/images/fotolife/u/upura/20180506/20180506224643.png">

# 議論はある？
- 「トピックセンテンス」以外の重要文抽出アルゴリズムについても検討したい

# 次に読むべき論文は？
NULL
