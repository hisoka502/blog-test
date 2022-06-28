標籤： #ln #htmlandcss 
來源：[[Html&CSS 學習筆記]]

# grid-template-areas
有時候我們會希望把 cell 依據特殊目的或用途分組，例如都是用在 header 或 footer，這時候，可以在 container 中使用 `grid-template-areas`的指令達成。若有個九宮格的 grid，想把上中下三列分成 header, content 和 footer，範例如下：
`grid-template-areas:
"header header header"
"content content content"
"footer footer footer"`
如果不需要為特定的 cell 指定分組，可以在該 cell 位置處用單純的 `.` 代表。

---

related: