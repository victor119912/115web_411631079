# 115web_411631079

網路程式設計課程 Repository。

## Week 1：GitHub 與開發環境

- 建立符合學號格式的 GitHub Repository。
- 將 Repository clone 到本機工作資料夾。
- 使用 VS Code 開啟專案並透過終端機操作。

## Week 2：Git 基礎與版本控制

本週練習 Git 的基本工作流程：

```text
修改檔案 -> git status -> git diff -> git add
-> git commit -> git log -> git push
```

我學會使用以下指令管理版本：

- `git status`：查看檔案狀態。
- `git diff`：查看尚未加入暫存區的修改。
- `git add`：將修改加入暫存區。
- `git commit`：建立版本紀錄。
- `git log --oneline`：查看提交歷史。
- `git push`：將本機 commit 推送到 GitHub。
- `git pull`：取得遠端 Repository 的最新內容。

本次練習也建立 `.gitignore`，避免提交 `node_modules/`、`.env` 與 `*.log` 等不應放進 Repository 的檔案。
