# LLM 開発の標準コード・手順

以下、Geniac LLM 開発案件における LLM 開発コード・手順の標準化です。  
利用しても利用しなくても構いません。ご自由にお使いください。  
**ただし「LLM 評価手順」は必ず利用してください（開発した LLM のランキングに使うため）。**

## ジョブシステム利用手順

サーバにログインしてジョブシステムを利用する手順です。  
[こちら](infra/README.md)

## データ収集加工手順

LLM 学習用データを収集加工する手順です。  
mC4(Japanese)のダウンロード、一連の加工処理を含みます。  
[こちら](data_management/README.md)

## LLM 学習手順

LLM 学習手順です。  
トークナイザー学習、事前学習、事後学習（ファインチューニング）を含みます。  
[こちら](train/README.md)

## LLM 評価手順

LLM 評価手順です。  
本企画の評価指標である Nejumi Leaderboard Neo における評価手順となります。  
[こちら](eval/README.md)

## Contributors

```
@software{ucllm-nedo,
  author       = {Kawanishi, Hotsuyuki and
                  Shinozuka, Fumiya and
                  Harada, Keno and
                  Alfredo, Solano Martinez and
                  Noumi, Yoshihiro and
                  Yu, Zhenxuan and
                  Kobashi, Yohei and
                  Kojima, Takeshi},
  title        = {Standard Codes and Procedures for LLM Development},
  month        = 3,
  year         = 2024,
  url          = {https://github.com/matsuolab/ucllm_nedo_prod}
}
```
