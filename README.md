# OpenSCAD 螺絲元件生成器

這是一個用於生成各種螺絲元件的 OpenSCAD 程式，可以產生：
- 螺栓（多種頭型）
- 螺母（標準和蝶形）
- 墊圈
- 螺桿

## 功能特點

- 支援多種螺絲頭型：
  - 六角頭
  - 套筒頭
  - 圓頭套筒
  - 沉頭套筒

- 支援多種驅動類型：
  - 套筒型
  - 十字型
  - 一字型

- 完整的參數化設計：
  - 可自訂尺寸
  - 可調整螺紋參數
  - 支援標準規格（如 ISO262）

## 使用方法

1. 安裝 [OpenSCAD](https://openscad.org/)
2. 下載並打開 `c.scad` 檔案
3. 根據需求調整參數：
   - 選擇元件類型（螺栓、螺母、墊圈、螺桿）
   - 設定尺寸參數
   - 選擇頭型和驅動類型
4. 預覽並匯出 STL 檔案

## 預設參數說明

- 預設配置適用於 8mm 直徑的螺絲元件
- 螺距預設為 2mm（適用於大多數情況）
- 螺紋角度預設為 45 度（最適合 3D 列印）

## 列印建議

為獲得最佳效果：
- 使用低速列印
- 使用較低溫度
- 建議使用實心填充
- 建議先列印測試件進行調整

## 來源與授權

本專案是基於以下作品修改：
- 原始作者：Mike Thompson (mike_linus @ Thingiverse)
- 原始專案：['Nut Job' @ Thingiverse](http://www.thingiverse.com/thing:8796)
- 使用程式庫：polyScrewThread_r1.scad（作者：aubenc @ Thingiverse）

### 授權說明

本作品採用 [創用 CC 姓名標示-非商業性-相同方式分享 3.0 澳洲授權條款](http://creativecommons.org/licenses/by-nc-sa/3.0/au/deed.zh_TW)

程式庫部分（polyScrewThread_r1.scad）採用 CC Public Domain 授權

## 版本歷史

- v8 (2017/1/1) - 移除已棄用的 assign 語句
- v7 (2016/3/6) - 新增螺母面數和套筒深度控制
- v6 (2015/2/21) - 新增蝶形螺母翼展比例
- v5 (2015/1/11) - 新增十字和一字驅動類型
- v4 (2014/12/31) - 新增表面紋理選項
- v3 (2014/11/2) - 改進蝶形螺母演算法
- v2 (2013/12/8) - 新增套筒頭類型
- v1 (2013/12/1) - 初始版本

## 注意事項

1. 根據不同的 3D 印表機可能需要微調參數
2. 建議先進行小規模測試再進行大量生產
3. 如果發現配合不當，可調整螺紋外徑參數

## 貢獻

歡迎提交 Issue 或 Pull Request 來改進這個專案。

## 相關連結

- [原始專案頁面](http://www.thingiverse.com/thing:8796)
- [OpenSCAD 官網](https://openscad.org/)
- [ISO262 標準參考](https://www.iso.org/standard/2896.html) 