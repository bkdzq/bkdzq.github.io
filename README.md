---
title: "About"
permalink: "/about/"
layout: page
---

这是up主依托该框架建立的博客：
https://github.com/niklasbuschmann/contrast

I use the framework below to construct my website:
https://github.com/niklasbuschmann/contrast

---
title: "About"
permalink: "/about/"
layout: page
---

这是up主依托该框架建立的博客：
https://github.com/niklasbuschmann/contrast

I use the framework below to construct my website:
https://github.com/niklasbuschmann/contrast


## 本地運行
bundle exec jekyll serve
## git work flow
## 【一】首次 clone 遠端項目（第一次下載倉庫）
# 從 GitHub 以 SSH 方式 clone 到本地資料夾（推薦）
git clone git@github.com:你的用戶名/你的倉庫名.git

# 或使用 HTTPS（如果沒設置 SSH）
git clone https://github.com/你的用戶名/你的倉庫名.git

## 【二】將你自己的新文件更新進來，並提交變更
# config user name
git config user.name "你的名字"
git config user.email "你的郵箱"

# 查看當前狀態
git status

# 將所有變更加入暫存區（新增/修改/刪除的文件）
git add .

# 提交更改，寫清楚提交說明
git commit -m "更新個人網站內容：新增 resume 頁面，修正錯字"

# 推送到 GitHub
git push

## 【三】從 GitHub 拉取最新內容（防止 push 衝突）
# 拉取最新內容合併到本地
git pull
