標籤： #ln #htmlandcss 
來源：[[Html&CSS 學習筆記]]

# flex shrink 和 grow 搭配使用的現象
因為 shrink 和 grow 是收縮和擴張的比，而非實際尺寸的比例，所以當有兩個元素A和B，其中一個元素A的 shrink 和 grow 數字都大於另一個時，就會出現母元素變很大時，A會擴張得比B快；但當母元素變得太小時，B也會縮得比B快。

---

related: [[202102151407 flex-shrink]][[202102151410 flex-grow]]