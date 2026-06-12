# 時川國際品牌資產 / Shichuan International Brand Assets

時川國際的 logo 與品牌資產存放區，提供穩定的 raw URL 給 Skill 與外部工具引用。

## 目錄結構

- `logo/mark/` — 純 logo mark（三豎符號），給角落與小尺寸場景
- `logo/horizontal/` — 橫式 logo（mark + 文字並排），給頁眉、頁尾、寬幅場景
- `logo/vertical/` — 直式 logo（mark + 文字堆疊），給封面、章節節點

每組各有 Black / White 兩個版本：
- **Black**：純黑 logo，給亮色背景（米色、白色）使用
- **White**：純白 logo，給深色背景（黑底、深綠、深藍）使用

## SVG 規格（Mark 版本）

- viewBox: `0 0 200 200`
- 三柱中心 x: `53 / 100 / 147`
- 柱寬: `12`
- 頂部切角: `34°`（左低右高，象徵成長）
- 三柱頂部 y: `102 / 72 / 42`（等差遞增 30）
- 半圓底圓心 y: `164.8`，半徑 `6`
- 純色填充，黑色為 `#000000`，白色為 `#FFFFFF`

## 引用方式

正式專案請用 tagged URL 而非 main 分支，避免改版時舊專案被影響：

```
https://raw.githubusercontent.com/konodio-dev/shichuan-brand/v1.0/logo/mark/Logo_Mark_Black.svg
```

當前版本：v1.0

## 授權

MIT License（檔案本身為時川國際所有，授權對象為「使用此 repo 中檔案於合法引用情境」之使用者）。
