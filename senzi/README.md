# 妖夜綺談（senzi）— 最終版靜態網站

這是可以直接上傳到 GitHub `notes` repo 裡 `senzi/` 資料夾的完整靜態網站，純 HTML + CSS，沒有用任何框架（不需要 Jekyll / Hugo 之類的建置流程），上傳後開啟 GitHub Pages 就能直接運作。

## 資料夾結構

```
senzi/
├── index.html              首頁
├── style.css                共用樣式表
├── wenwu-qianshi.html        分類頁：文屋千蒔
├── xiaoan-yiwen.html          分類頁：宵闇異聞
├── wusheng.html               分類頁：無生
├── unsorted.html               分類頁：未分類
├── gallery.html                 藏圖閣
├── posts/                        16 篇文章內頁
│   └── *.html
└── images/                        圖片存放處（目前是空的，見下方）
```

## 圖片下載清單

網站裡所有圖片路徑都已經寫成指向 `images/` 資料夾的**相對路徑**，你只要把圖片實體檔案存進這個資料夾、檔名跟下表一致即可，完全不需要傳給我，也不用改任何 HTML。

| 來源網址（下載用） | 存檔檔名 | 用在哪裡 |
|---|---|---|
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/280446624.jpg | 280446624.jpg | 正確的模樣 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/880962235_orig.jpg | 880962235_orig.jpg | 方成俗世上篇 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/603295820.jpg | 603295820.jpg | 緣起緣滅 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/916303662_orig.jpg | 916303662_orig.jpg | 所愛之物 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/121862080.jpg | 121862080.jpg | 靈山有狐 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/7450044.jpg | 7450044.jpg | 二ノ夜（上）迷子 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/3733918.jpg | 3733918.jpg | 二ノ夜（下）迷子 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/6177693_orig.jpg | 6177693_orig.jpg | 三ノ夜（上）墨田川的河童 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/1421558808.png | 1421558808.png | 三ノ夜（下）墨田川的河童（第一張） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/3408570_orig.gif | 3408570_orig.gif | 三ノ夜（下）墨田川的河童（第二張） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/260372859.jpg | 260372859.jpg | 五ノ夜（上）留下的 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/351284431.jpg | 351284431.jpg | 五ノ夜（下）留下的 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/792418100.jpg | 792418100.jpg | 異聞一（完）櫻吹雪 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/660283509.jpg | 660283509.jpg | 已逝之日 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/1427573578.png | 1427573578.png | 首頁（主視覺／關於） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/3666440_orig.jpg | 3666440_orig.jpg | 藏圖閣（小千日 提供） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/5918597_orig.png | 5918597_orig.png | 藏圖閣（小藻井 提供） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/2989941_orig.jpg | 2989941_orig.jpg | 藏圖閣（古莉絲 提供） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/7850908_orig.jpg | 7850908_orig.jpg | 藏圖閣（小紅霏 提供） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/738645_orig.jpg | 738645_orig.jpg | 藏圖閣（小紅霏 提供） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/7772827_orig.jpg | 7772827_orig.jpg | 藏圖閣（小紅霏 提供） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/1525473_orig.jpg | 1525473_orig.jpg | 藏圖閣（宮達前輩 提供） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/5481640_orig.jpg | 5481640_orig.jpg | 藏圖閣（宮達前輩 提供） |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/5230215_orig.jpg | 5230215_orig.jpg | 藏圖閣「小日常」漫畫 |
| https://senzi.weebly.com/uploads/4/4/8/4/44849241/4107970_orig.jpg | 4107970_orig.jpg | 藏圖閣「小日常」漫畫 |

《關於那孩子》這篇沒有圖片，不用另外處理。

## 藏圖閣版權提醒

「單色／彩圖」那 8 張是別人畫給站主的應援圖／同人圖，版權屬於原作者（見上表署名），不是站主本人的創作。搬到新網站繼續公開展示前，建議保留完整署名或先聯繫原作者確認。

## 之後想自己微調內容

網站的文字內容目前是直接寫死在各個 `posts/*.html` 裡（沒有另外用 Markdown 建置流程），如果之後想調整某篇文章的簡述換行、文字內容等，可以直接找到對應的 html 檔案，搜尋 `post-excerpt` 或 `article-body` 這些 class 所在位置修改文字即可，不需要整個網站重新產生。

## 部署到 GitHub

1. 把整個 `senzi/` 資料夾放進你的 `notes` repo（跟先前討論的一樣，`A.github.io` repo 底下開 `senzi/` 資料夾）
2. 把上表圖片存進 `senzi/images/`
3. 到 repo 設定裡開啟 GitHub Pages（Source 選 main branch / root）
4. 完成後網址會是 `A.github.io/notes/senzi/`（或依你實際 repo 名稱而定）
