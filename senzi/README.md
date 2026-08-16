# 妖夜綺談（senzi）— 最終版靜態網站

這是可以直接上傳到 GitHub `notes` repo 裡 `senzi/` 資料夾的完整靜態網站，純 HTML + CSS，沒有用任何框架（不需要 Jekyll / Hugo 之類的建置流程），上傳後開啟 GitHub Pages 就能直接運作。

## 網站架構（改版後）

導覽列現在是四個項目：**押花手帳｜文屋千蒔｜無生｜藏圖閣**

- **押花手帳**（`oshibana-techo.html`）：全部文章（文屋千蒔／宵闇異聞／無生／未分類）合併在一起，新到舊排序
- **文屋千蒔**（`wenwu-qianshi.html`）／**無生**（`wusheng.html`）：角色介紹頁，不再是文章列表
- **藏圖閣**（`gallery.html`）：不變

原本「文屋千蒔」「無生」的分類文章列表搬到新網址：
- 文屋千蒔分類文章列表 → `archive-wenwu-qianshi.html`
- 無生分類文章列表 → `archive-wusheng.html`
- 宵闇異聞分類文章列表 → `xiaoan-yiwen.html`（網址不變，但不再放在導覽列，只能透過文章 tag 點擊到達）
- 未分類 → `unsorted.html`（同上，不放導覽列，只能透過押花手帳裡的文章直接點進去）

所有文章卡片與文章內頁上的分類標籤（tag），點下去都會連到對應的 archive 頁面。

## 角色介紹頁的圖片說明

文屋千蒔、無生頁面裡使用的圖片，目前直接連到 Plurk 圖床的外部網址（不是存在 `images/` 資料夾裡），這樣網站可以正常運作，但長期穩定性不如自己存放圖片。如果之後想把這兩張圖也下載存進 `images/` 資料夾，改成本地路徑會更保險，可以再跟我說。

## 資料夾結構

```
senzi/
├── index.html                      首頁
├── style.css                       共用樣式表
├── oshibana-techo.html             押花手帳（全部文章合併列表）
├── wenwu-qianshi.html              文屋千蒔角色介紹頁
├── wusheng.html                    無生角色介紹頁
├── archive-wenwu-qianshi.html      文屋千蒔分類文章列表
├── archive-wusheng.html            無生分類文章列表
├── xiaoan-yiwen.html                宵闇異聞分類文章列表
├── unsorted.html                    未分類文章列表
├── gallery.html                     藏圖閣
├── posts/                           16 篇文章內頁
│   └── *.html
└── images/                          圖片存放處（見下方下載清單）
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

「✦（來自於他人的贈圖）」那 8 張是別人畫給站主的應援圖／同人圖，版權屬於原作者（見上表署名），不是站主本人的創作。搬到新網站繼續公開展示前，建議保留完整署名或先聯繫原作者確認。

## 之後想幫「單色」「彩圖」加圖片

藏圖閣頁面（`gallery.html`）目前分成單色、彩圖、✦（來自於他人的贈圖）、小日常四個區塊，單色跟彩圖目前是空的。因為網站是純 HTML，沒有另外的建置流程，所以要新增圖片得直接編輯 `gallery.html`：

1. 先把要用的圖片存進 `images/` 資料夾
2. 打開 `gallery.html`，找到「單色」或「彩圖」那個標題底下的 `<p class="gallery-empty">（尚未加入圖片）</p>`
3. 把整段換成類似這樣的區塊（可以直接複製「✦（來自於他人的贈圖）」區塊裡任一個 `<div class="gallery-item">...</div>` 來改）：

```html
<div class="gallery-grid">
  <div class="gallery-item">
    <img src="images/你的檔名.jpg" alt="" loading="lazy" onclick="openLightbox('images/你的檔名.jpg')">
    <div class="gallery-credit">（如果有想加的說明文字）</div>
  </div>
</div>
```

4. 如果同一區要放多張，把 `<div class="gallery-item">...</div>` 這一整段複製貼上多次，都放在同一個 `<div class="gallery-grid">...</div>` 裡面即可

## 之後想自己微調內容

網站的文字內容目前是直接寫死在各個 `posts/*.html` 裡（沒有另外用 Markdown 建置流程），如果之後想調整某篇文章的簡述換行、文字內容等，可以直接找到對應的 html 檔案，搜尋 `post-excerpt` 或 `article-body` 這些 class 所在位置修改文字即可，不需要整個網站重新產生。

## 部署到 GitHub

1. 把整個 `senzi/` 資料夾放進你的 `notes` repo（跟先前討論的一樣，`A.github.io` repo 底下開 `senzi/` 資料夾）
2. 把上表圖片存進 `senzi/images/`
3. 到 repo 設定裡開啟 GitHub Pages（Source 選 main branch / root）
4. 完成後網址會是 `A.github.io/notes/senzi/`（或依你實際 repo 名稱而定）
