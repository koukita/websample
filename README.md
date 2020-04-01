# websample
CSVを編集してホームページ等にアップすると、ページの表や地図が自動更新されます  
Excelなどで作成した「Shift-JIS」のCSVも文字化けせずに表示できます。

## CSVをHTMLテーブルに変換
Excelなどで作成したCSVを、オープンデータポータルにアップすることでHTMLのテーブルを作成する
https://koukita.github.io/websample/csv2table_array.html
- テーブル作成にはプラグイン不要（文字コードの変換にencode.jsを使用）
- サンプルは、条件によりセルの色塗りも行う  
　　
　　  
　　  
## D3.jsで地図表示とCSV結合＋色塗り
北海道地図と市町村コードが同じCSVのデータを北海道地図と結合して色分けする
https://koukita.github.io/websample/d3_csv_join.html  
- 地図の描画はD3を使用  
- 北海道の地図データ（市町村ポリゴン、市町村ポイント）は北海道オープンデータポータルに保存されている  
　　https://www.harp.lg.jp/opendata/dataset/1379.html
- そのため、地図データは更新する必要はなし。データCSVを更新すると、色分けも更新される。
