# TODO

## Need mobile phone

https://disk.yandex.com/

## https://wizardforcel.gitbooks.io/gopl-zh/content/ch5/ch5-06.html

- 練習 5.10： 重寫 topoSort 函數，用 map 代替切片併移除對 key 的排序代碼。驗證結果的正確性（結果不唯一）。

- 練習 5.11： 現在線性代數的老師把微積分設爲了前置課程。完善 topSort，使其能檢測有向圖中的環。

- 練習 5.12： gopl.io/ch5/outline2（5.5 節）的 startElement 和 endElement 共用了全局變量 depth，將它們脩改爲匿名函數，使其共享 outline 中的局部變量。

- 練習 5.13： 脩改 crawl，使其能保存發現的頁面，必要時，可以創建目録來保存這些頁面。隻保存來自原始域名下的頁面。假設初始頁面在 golang.org 下，就不要保存 vimeo.com 下的頁面。

- 練習 5.14： 使用 breadthFirst 遍歷其他數據結構。比如，topoSort 例子中的課程依賴關繫（有向圖）,個人計算機的文件層次結構（樹），你所在城市的公交或地鐵線路（無向圖）
