標籤： #ln #htmlandcss 
來源：[[Html&CSS 學習筆記]]

# fixed position
和 absolute position 類似，但是 fixed position 是以整個螢幕顯示的畫面邊緣作為絕對的參考基準。而且會直接忽略掉其他元素的關係（也就是說可能會蓋掉元素）。
所以，當使用 fixed position，且沒有設定上下左右的關係時，它會留在預設位置，但同時原本順位在下方的元素也會跑到該元素的位置，呈現上下兩個圖層的視覺感。

以常用的 nav bar 舉例，貼在畫面上方的nav bar 應該要如此設定：

`.navbar {
	position:fixed;
	tpp: 0px;
	left: 0px;
	}`

---

related: [[202102121244 relative position]][[202102121248 absolute position]]