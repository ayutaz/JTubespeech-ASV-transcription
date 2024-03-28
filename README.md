# JTubespeech-ASV-transcription

[JTubespeech-ASV: Japanese speech corpus for automatic speaker verification / 日本語話者照合用コーパス](https://sites.google.com/site/shinnosuketakamichi/research-topics/jtubespeech-asv_corpus)の音声を[reazon-research/reazonspeech-nemo-v2](https://huggingface.co/reazon-research/reazonspeech-nemo-v2)を使って文字お越しをしたデータ

# データの詳細

各データは以下のフォーマットになっています。

## JTubespeech-ASV_transcription_results.json

```json
{
    "ファイル名": "ファイル名",
    "テキスト内容": "文字お越しテキスト",
    "音声の長さ": "音声の長さ(s)"
},
```

## JTubespeech-ASV_transcription_results.csv

```csv
ファイル名,テキスト内容,音声の長さ
```

# 備考

こちらの文字お越しは、[AiHUB](https://aihub.co.jp/)様に計算リソースをご提供いただきました。