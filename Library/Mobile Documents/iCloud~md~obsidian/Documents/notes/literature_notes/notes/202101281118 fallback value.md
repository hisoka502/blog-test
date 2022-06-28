標籤： #ln #htmlandcss 
來源：[[Html&CSS 學習筆記]]

# fallback value
為避免找不到 variable 的 value 找不到，導致元素無法正常顯示，可以使用 fallback value，作為備用的 value。
格式範例，以黑色作為顏色的 fallback value 為例：

var(--example-value-color, `black`)

---

related:
- 概念類似 [[202101112207 嵌入 google font]]中，備用的字體）