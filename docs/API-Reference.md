# API 參考

開發者面向 C# 類別 (Academy, Agent, Decision and Monitor) 以記錄並兼容於自動生成HTML文件工具-
[Doxygen](http://www.stack.nl/~dimitri/doxygen/)。

若要生成這 API 參考，
[下載 Doxygen](http://www.stack.nl/~dimitri/doxygen/download.html)
並且執行下方指令，在 `docs/` 資料夾內:

```sh
doxygen dox-ml-agents.conf
```

`dox-ml-agents.conf` 是一個 Doxygen 給 ML-Agents 工具的組態檔案，包含已正確格式化的類別。
生成的 HTML 檔案將會被放置在 `html/` 子資料夾中。打開子資料夾中的 `index.html` 將導航到 API 的參考首頁。
須注意 `html/` 中已經包含 `.gitignore` 檔案。

在不久的將來，我們的目標是擴大我們的文件以包含所有 Unity C# 類別和 Python API。
