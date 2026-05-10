# tw-news-yahoo 專案規則

## 注意：這是 printing-press 的 submodule

此 repo 同時作為以下專案的 submodule：

- **printing-press**：https://github.com/StrongerShen/printing-press（路徑：`library/tw-news-yahoo/`）

如果是從 printing-press 工作，請參考該 repo 的 CLAUDE.md 了解完整工作流（submodule 推送、README 更新規則等）。

## Build

```bash
# macOS
go build -o tw-news-yahoo .

# Windows（cross-compile）
GOOS=windows GOARCH=amd64 go build -o tw-news-yahoo.exe .
```

兩個 binary 都要一起 build 並 commit。

## README 規則

功能有異動時，必須同步更新 `README.md`。
