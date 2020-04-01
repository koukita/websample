# websample

Excelなどで作成したCSVを、オープンデータポータルにアップすることでHTMLのテーブルを作成する
https://koukita.github.io/websample/csv2table_array.html
- サンプルは、条件によりセルの色塗りも行う  
  
北海道地図と市町村コードが同じCSVのデータを北海道地図と結合して色分けする
https://koukita.github.io/websample/d3_csv_join.html  
- 地図の描画はD3を使用  
- 北海道の地図データ（市町村ポリゴン、市町村ポイント）は北海道オープンデータポータルに保存されている  
　　https://www.harp.lg.jp/opendata/dataset/1379.html
- そのため、地図データは更新する必要はなし。データCSVを更新すると、色分けも更新される。
