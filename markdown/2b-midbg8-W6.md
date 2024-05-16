---
Title: 2b-midbg8協同產品設計實習-W6
Date: 2024-03-28 13:20
Category: w6
Tags: 網誌編寫
Slug: 2024-Spring-w6-blog-tutorial
Author: 41023132、41039138
---

2b-midbg8 協同產品設計實習課程.

<!-- PELICAN_END_SUMMARY -->

# 心得


# 課程內容

 ## 論文中英並列

 將論文用成中英並列後並在分組網站的 Release 或 downloads 區完成 2b-midbgx_report.pdf製作

 ## 修改main.yml

 打開目標檔案添加  - name: Initialize submodules 和 run: git submodule update --init --recursive

 範例設定[main.yml ](https://github.com/mdecd2024/2b-midbg4/blob/02599cb79d65cb1f48186c2db59b5dc9d812f599/.github/workflows/main.yml)可在連結中看到代碼實際添加的位置

 ## 教學影片分組和自評

影片分工上字幕和錄自評影片

在影片上填上字幕, 另行上傳到可以嵌入到各分組的網站上

從影片字幕中整理出逐字稿, 放在影片下方, 以 .txt 連結安排

並在各嵌入的教學影片下方, 以摘要方式說明該影片的教學重點

 
 ## ODOO, NX, Sourcetree, Github and Replit下載和應用

 利用 ODOO PLM, Siemens NX, Sourcetree, Github 分組倉儲與 Replit 打造協同產品開發環境
 
 在[2b-6](https://mde.tw/cd2024/blog/2024-cd-2b-w6.html)
 
 中下載 Siemens NX1872.7z  Sourcetree_portable.7z Solvespace_model _2d_for_cd2024_w6.7z

 NX, Sourcetree 與 CoppeliaSim 設定檔案與管理分組倉儲的權限, 必須存至可攜系統, 並分別從可攜系統啟動後的命令列中啟動

## Replit 檢視靜態網站

從第三周開始, 原先可以讓倉儲的動態網站與靜態網站共用 443 https 的方式, 也就是利用 SStatic 後查驗靜態網站的功能已經失效, 

必須將靜態網站的檢視與動態編輯網站的啟動分開, 才能在將 Replit 網站與網誌改版的內容, 在推向 Github 倉儲之前進行查驗.

<div id="disqus_thread"></div>
<script>
    /**
    *  RECOMMENDED CONFIGURATION VARIABLES: EDIT AND UNCOMMENT THE SECTION BELOW TO INSERT DYNAMIC VALUES FROM YOUR PLATFORM OR CMS.
    *  LEARN WHY DEFINING THESE VARIABLES IS IMPORTANT: https://disqus.com/admin/universalcode/#configuration-variables    */
    /*
    var disqus_config = function () {
    this.page.url = PAGE_URL;  // Replace PAGE_URL with your page's canonical URL variable
    this.page.identifier = PAGE_IDENTIFIER; // Replace PAGE_IDENTIFIER with your page's unique identifier variable
    };
    */
    (function() { // DON'T EDIT BELOW THIS LINE
    var d = document, s = d.createElement('script');
    s.src = 'https://blog-1-4.disqus.com/embed.js';
    s.setAttribute('data-timestamp', +new Date());
    (d.head || d.body).appendChild(s);
    })();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>

