---
layout: default
title: How to use?
---

# How to use?

* TOC
{:toc}

- [Back to main page]({{site.baseurl}}/index.html)

## prose.io

---

[prose.io](http://prose.io)是一個線上編輯系統。透過prose.io，可以簡單的新增、修改、刪除在github上面的檔案。修改過後的結果也會自動更新顯示在這個(hh-faq)網站上。

## 登入

---

在使用prose.io以前，必須要先申請一個[github帳號](https://github.com/join)

申請完以後進入[prose.io](http://prose.io)會看到以下的畫面，選擇"Only public repositories"並且按下"AUTHORIZE"，讓prose.io可以存取你github帳號內的資料

![]({{site.baseurl}}/assets/login.png)

## Repository列表

---

登入以後會看到如下圖的github repository列表

![]({{site.baseurl}}/assets/repo-list.png)

點選"hh-faq"進入文章列表

**\*如果列表裡面沒有出現"hh-faq"的話，可能是權限沒有設定，請聯絡Daniel(<daniel@hahow.in>)**
  
## 文章列表

---

![]({{site.baseurl}}/assets/article-list.png)

- 搜尋 - 在"Filter Files"的框框內打入文章標題就可以搜尋

> **這邊要注意一點，因為prose.io的中文支援有點問題，所以用來搜尋的標題會是文章的"Title"而不是"Chinese Title"**

> ![]({{site.baseurl}}/assets/search-title.png)

- 新增 - 點選綠色的"NEW FILE"按鈕就可以新增檔案

- 修改 - 點選"Edit"按鈕可以修改

- 刪除 - 點選垃圾桶按鈕可以刪除

## 文章

---

![]({{site.baseurl}}/assets/article.png)

### 檔案名稱

prose.io會將檔案名稱和文章標題連結，但是因為對中文語系的支援有問題，造成存檔的時候會發生錯誤，所以在新增文章的時候**建議文章標題使用英文**

![]({{site.baseurl}}/assets/article-title.png)

### 修改

prose.io使用的是kramdown，kramdown是markdown語法的一種，詳細的樣式可以參考[這裡]](http://kramdown.gettalong.org/syntax.html)。但是為了保持FAQ的樣式一致性，建議都只使用編輯器工具列提供的樣式

想要嵌入youtube影片的話插入以下的程式碼，把YOUTUBE_ID換成要插入影片的ID就可以了

`<iframe src="https://www.youtube.com/embed/YOUTUBE_ID" width="560" height="315" frameborder="0" allowfullscreen=""></iframe>`

### Meta Data

在前面有提到prose.io對中文語系的支援有問題，那我們到底要怎麼幫文章取中文的標題呢？點選右邊的Meta Data按鈕

![]({{site.baseurl}}/assets/meta-data.png)

裡面可以輸入、設定標題(Chinese Title)、分類(Category)以及章節(Section)

### 預覽

點選Preview按鈕就會開新分頁，可以預覽修改後的結果

### 儲存

點選Save按鈕，會打開像下圖的輸入框

![]({{site.baseurl}}/assets/save.png)

裡面可以稍微描述這次修改了什麼，但是不寫也沒關係，接著按下COMMIT按鈕就會儲存了

## 修改完畢

---

修改完畢再回到這個網站，找到相對應的分類、章節，點進文章內就可以看到你剛剛修改的成果了！

**\*因為prose.io和github需要一點時間編譯你修改的結果，所以如果沒有修改的話可以再等個10~20秒，重新整理後應該就會更新了**
