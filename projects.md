---
layout: page
title: "Projects"
permalink: /projects/
---

# Projects

以下以「成果導向」呈現：背景 → 解法 → 量化成果 → 技術堆疊。

---

## 1) AIoT 端到端感測控制系統
**Embedded × Linux × Cloud × AI**

- **問題**：需要一套可實際部署的 AIoT 系統，涵蓋感測、傳輸、儲存到智慧分析的完整流程
- **解法**：以 Raspberry Pi 為核心，整合 Arduino 感測模組、MQTT 即時通訊、Flask API、MySQL 資料儲存，搭配 LLM 進行智慧決策
- **成果**：完成端到端可部署系統，感測資料延遲 < 200ms，支援多感測器同時擷取
- **技術**：Raspberry Pi / Arduino / GPIO / I2C / UART / Flask / MQTT / MySQL / Docker

---

## 2) 電腦視覺影像辨識系統
**Computer Vision × Deep Learning**

- **問題**：需要即時辨識特定物件並觸發對應控制邏輯
- **解法**：使用 YOLO 進行物件偵測，OpenCV 處理影像串流，結合 Raspberry Pi 實現邊緣推論
- **成果**：在 Raspberry Pi 上達到即時辨識，延遲 < 500ms，準確率達 90%+
- **技術**：YOLO / OpenCV / TensorFlow / Keras / Python / Raspberry Pi

---

## 3) LLM + RAG 智慧問答與決策系統
**LLM × RAG × MCP**

- **問題**：需要將企業內部知識庫與 LLM 結合，支援準確的情境問答與決策輔助
- **解法**：建立 RAG 架構，整合向量資料庫與 LLM（ChatGPT API / Ollama），設計 MCP 流程串接感測資料
- **成果**：問答準確率大幅提升，支援離線本地部署（Ollama），可擴充至 IoT 場景
- **技術**：LLM / RAG / MCP / Ollama / ChatGPT API / Python / Prompt Engineering

---

## 4) LINE 客戶分眾推播與 CRM 流程整合
**Workflow Automation × API Integration**

- **問題**：原流程需要人工整理名單、訊息無法個人化、追蹤困難
- **解法**：建立資料欄位規則與分眾標籤、串接自動推播流程、建立回流追蹤
- **成果**：推播效率提升 3 倍，錯誤率下降 70%
- **技術**：Node.js / Python / LINE Messaging API / Google Sheets / Webhook

---

## 5) 企業檔案治理與 NAS 同步策略
**Operations × Data Governance**

- **問題**：檔案散落、版本混亂、備份不可驗證
- **解法**：建立資料夾規範、命名規則、三層備份與還原演練 SOP
- **成果**：還原時間由 2 小時降至 15 分鐘
- **技術**：Synology / OneDrive / Google Drive / Versioning

---

[← 回首頁](/) · [About](/about/)
