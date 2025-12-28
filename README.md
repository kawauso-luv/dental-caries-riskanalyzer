# Dental Caries Risk Analyzer
![Dental](https://github.com/user-attachments/assets/cf66e989-05e6-4731-bbf1-0e0d640fbba1)


## 概要
本プロジェクトは、架空の歯科健診データを用いて虫歯リスクを分析し、統計処理・可視化を行った後、ユーザーの生活習慣に基づいた簡易的な虫歯リスク判定と改善提案を行う教育用アプリケーションです。

## 使用技術
- Python
- NumPy
- Pandas
- Matplotlib
- Google Colab

## 機能
- 歯科健診データの基本統計量（平均・標準偏差）の計算
- 間食回数・歯磨き回数と虫歯本数の可視化
- 簡易的な虫歯リスクスコアの計算
- ユーザー入力によるセルフチェックと改善提案

## データについて
本プロジェクトで使用しているデータは、
すべて教育目的で作成した架空のデータです。
実在の患者情報は一切含まれていません。

## 注意事項
本アプリケーションは教育目的のものであり、
実際の医療診断・治療を目的としたものではありません。

## 実行方法
1. Google Colab で本リポジトリを開く
2. ノートブックを上から順に実行
3. InputがColab上で上手く動作しない場合は、Input箇所をコメントアウトして、固定データをお使いください。「# Googlecolab用のデモ（inputが動かないとき用）」より下6行のコメントアウトを外すことで使用できます。

Colab外での実行は想定していませんが、もし行う場合は`dental_data.csv` をアップロードしてお使いください。

上手く実行できれば、以下のようなグラフが表示されます。<br>
<img width="554" height="455" alt="regression_plot" src="https://github.com/user-attachments/assets/b3cc4c47-a78a-4787-9389-b5e03bcadbbd" />

その後にシミュレーションが開始し、ユーザー入力を求めてきます。
<img width="1585" height="552" alt="スクリーンショット (16)" src="https://github.com/user-attachments/assets/ea74694c-a128-471d-82c9-6acf80061201" />

![Dental (1)](https://github.com/user-attachments/assets/b25b9c96-970a-4148-9a50-300428787da8)

