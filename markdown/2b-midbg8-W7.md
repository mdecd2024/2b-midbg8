---
Title: 2b-midbg8協同產品設計實習-W7
Date: 2024-04-04 13:20
Category: w7
Tags: 網誌編寫
Slug: 2024-Spring-w7-blog-tutorial
Author: 41023132、41039138
---

2b-midbg8 協同產品設計實習課程.

<!-- PELICAN_END_SUMMARY -->

# 課程內容

## 內容管理系統

本課程採 Github Classroom 建立分組倉儲, 並由學員自行利用 cmsimde_site 作為 Github 倉儲的引擎目錄, 利用 Python 執行網頁編輯. 之後再轉檔為

靜態網頁, 以便利用 Github Pages 所提供的 WWW 伺服器呈現協同產品設計過程的相關多媒體內容

除了章節式的網站外, cmsimde_site 還額外利用 Pelican 管理使用者所建立的網誌, 以及利用 Reveal 管理使用者所建立的網際簡報.

cd2024 課程採用了四種不同的方法進行, 其中包括 Replit、Codespaces、Gitpod 以及 localhost. 

協同設計的架構上, 個人與分組的倉儲中, 有了以下協同模式:

1. 分組網站內容的協同 : 
  
    其中包括章節式的網站內容與網誌內容, 可以透過 Python 程式方法整合各學員子模組中的 
    config/content.htm 以及 markdown/*.md 檔案至分組網站中

2. 分組報告內容的協同 : 採用的是 Github Actions 與近端 MikTeX 中的 xelatex 將 .tex 轉為 pdf 的整合過程 

3. 分組產品設計的 PLM 協同 : 
    
    採用的是 Odoo PLM 模組,將網站內容、報告內容視為產品, 從協同架構的訂定作為起點, 完成資料展示作為終點

4. 分組零組件設計的協同 : 
    
    分別採用 Solvespace 作為鋼球平衡台範例, 讓學員使用 Siemens NX 1872 進行協同零組件繪圖設計, 並將各零件的 .prt 檔案納入各學員的倉儲進行組立

5. 分組模擬場景設計的協同 : 
    
    當各分組順利完成鋼球平衡台的零組件轉檔後, 一旦進入 CoppeliaSim 場景後, 必須逐一配置感測器, 找到合用或最佳的協同產品設計模式.

6. 分組專案簡報設計的協同 : 
    
    在上述各產品設計階段所累積的各種資料, 該如何有效整合到專案完成後必須進行的網際簡報中。


## 分組網站內容的協同

## 章節式網站內容

## 週記式網誌內容

## 網際簡報內容












