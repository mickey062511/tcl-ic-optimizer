# Tcl IC 設計優化工具

**Final Project #1 ─ 進階程式設計期末專題 (5%)**

本專案使用 **OpenROAD + Tcl** 開發，實現 IC 設計自動化。

## 專題符合要求
- 使用 Tcl 查詢 OpenDB / IC Layout 資訊
- 協助 Power、Performance、Area (PPA) 優化分析
- 提供功率優化建議

## 主要檔案
- **`ic_optimizer.tcl`** ← 主程式腳本（已上傳）

## 執行方式
```bash
# 在 OpenROAD 環境中執行
openroad -no_init -exit ic_optimizer.tcl
