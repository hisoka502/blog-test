標籤： #ln #htmlandcss 
來源：[[Html&CSS 學習筆記]]

# 沒有規劃 grid-template-areas 時也能替 item 指定 area
直接在 items 的 style 中寫入 `grid-area {x/x/x/x}`即可幫它指定 area，而不需先在 `container 寫 grid-template-areas` 的指令。 其中四個x分別代表：水平方向起始的 line 編號，垂直方向起始的 line 編號，水平方向終點的 line 編號，垂直方向終點的 line 編號。以九宮格為例，若要替 item 指定 最上方第一欄，三列的 area 作為 header，那就這樣寫：`grid-area {1/1/2/4}`



---

related: [[202102161208 grid-template-areas]]