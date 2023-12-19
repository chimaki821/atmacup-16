# atmacup-16

atmaCup #16 (https://www.guruguru.science/competitions/22/ ) での学生8位解法。

##　動かし方
inディレクトリを作成しその中にデータ

- test_log.csv
- test_session.csv
- train_label.csv
- train_log.csv
- yado.csv

を入れる。`make_data.ipynb` を動かして `data/yado_with_count.csv` を作成する。
その後、 `main.ipynb` を動かして `out/last_sub.csv` を作成する。