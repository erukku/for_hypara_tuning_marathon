# for_hypara_tuning_marathon

## 内容
- ヒューリスティック時に、Optunaでパラメータ調整をする

## 本コード以外に必要なもの
- スコア計算できるコード(score_calc.py)
  - python以外はshell部分を各自書き換える事で可能
- スコア計算用のテストデータ
- 調整するパラメータ
    
## 想定環境
- google colab(python)

## 使い方
1. 自身のgoogle colabにfor_hypara_marathon.ipynbを開く
2. 所定の場所にスコア評価コード、テストデータを追加
  - google driveに{contest_name}ディレクトリを作成
  - {contest_name}/inディレクトリも作成
  - score_calc.py:{contest_name}/
  - テストデータ:{contest_name}/in/
3. for_hypara_marathon.ipynb内のパラメータ調整部分を各自のパラメータに変更 
4. for_hypara_marathon.ipynbを実行

