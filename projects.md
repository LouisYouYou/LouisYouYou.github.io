---
layout: default
title: Projects | Louis You
permalink: /projects/
---

# 🚀 Project Experience

以下專案內容為依據我的技術能力、實務背景與產業場景所整理的 **代表性專案模型**，用以呈現我的系統分析、架構整合、開發與落地能力。

  <div class="project-card">
    <div class="project-card-header">
      <h3>AIoT 端到端實戰整合專案</h3>
      <span class="project-card-number">PROJECT 01</span>
    </div>
    <div class="project-section">
      <div class="project-section-label">概述</div>
      <p>Embedded × Linux × Cloud × AI / LLM 全棧整合，涵蓋感測控制、即時通訊、影像分析與智慧決策。</p>
    </div>
    <div class="project-section">
      <div class="project-section-label">技術堆疊</div>
      <div class="skill-tags">
        <span class="skill-tag">Raspberry Pi</span>
        <span class="skill-tag">Arduino</span>
        <span class="skill-tag">Linux GPIO</span>
        <span class="skill-tag">Flask</span>
        <span class="skill-tag">MQTT</span>
        <span class="skill-tag">MySQL</span>
        <span class="skill-tag">TensorFlow</span>
        <span class="skill-tag">OpenCV</span>
        <span class="skill-tag">YOLO</span>
        <span class="skill-tag">LLM + RAG</span>
      </div>
    </div>
    <div class="project-section">
      <div class="project-section-label">特點</div>
      <p>可實際部署、可維運的系統架構，從硬體感測到 AI 推論的完整端到端流程。</p>
    </div>
  </div>

## 1. AIoT 智慧監控與異常偵測平台

### 專案定位
建置一套可部署於工廠、設備場域或機房環境的 AIoT 監控系統，透過感測器、邊緣裝置與影像分析，進行異常狀態監測、警示通知與資料留存。

### 我的角色
- 系統架構規劃
- 邊緣設備整合
- 後端資料流設計
- 異常通知機制建置
- Linux 環境部署與維運

### 技術架構
- Edge Device：Raspberry Pi
- Sensor / Interface：GPIO / UART / I2C / SPI
- Backend：Python / Flask
- Protocol：MQTT
- AI / Vision：OpenCV / YOLO
- Storage：MySQL / MS SQL
- OS：Linux

### 主要工作內容
- 整合感測器資料採集與設備狀態回傳
- 建立影像辨識流程，進行異常檢測
- 設計 Web Dashboard 顯示設備狀態
- 異常事件觸發後，自動推送通知
- 建立可維護的模組化部署方式

### 專案成果
- 提升設備異常反應速度
- 降低人工巡檢負擔
- 建立可擴充的 AIoT 架構雛形
- 具備導入更多場域的可行性

  <div class="project-card">
    <div class="project-card-header">
      <h3>檔案治理與 NAS 同步策略</h3>
      <span class="project-card-number">PROJECT 03</span>
    </div>
    <div class="project-section">
      <div class="project-section-label">問題</div>
      <p>檔案散落、版本混亂、備份不可驗證。</p>
    </div>
    <div class="project-section">
      <div class="project-section-label">解法</div>
      <p>建立資料夾規範、命名規則、三層備份與還原演練 SOP。</p>
    </div>
    <div class="project-section">
      <div class="project-section-label">成果</div>
      <div class="project-metrics">
        <span class="project-metric">還原時間由 2 小時降至 15 分鐘</span>
      </div>
    </div>
    <div class="project-section">
      <div class="project-section-label">技術堆疊</div>
      <div class="skill-tags">
        <span class="skill-tag">Synology</span>
        <span class="skill-tag">OneDrive</span>
        <span class="skill-tag">Google Drive</span>
        <span class="skill-tag">Versioning</span>
      </div>
    </div>
  </div>

## 2. LINE 官方帳號精準分眾推播系統

### 專案定位
建置一套以 LINE Messaging API 為核心的客戶互動平台，讓企業可依不同使用者條件進行分群推播、訊息追蹤與互動管理。

### 我的角色
- Webhook 架構設計
- 後端 API 開發
- 使用者資料結構設計
- 分眾邏輯規劃
- 測試環境建置與驗證

### 技術架構
- Backend：Python / Flask
- Messaging：LINE Messaging API
- Webhook：ngrok / Webhook Endpoint
- Database：MySQL / SQLite
- Integration：Google Sheets / CRM-like logic

### 主要工作內容
- 接收 follow / message event 並寫入資料庫
- 建立 userId 對應機制與名單管理
- 設計分眾欄位與推播規則
- 將後台操作流程簡化為可管理模式
- 先以小量推播驗證，再規劃擴大名單使用

### 專案成果
- 建立可執行的 LINE 自動化互動流程
- 讓分眾推播從人工作業轉為系統化流程
- 提升行銷操作效率與客戶管理精準度

---

## 3. 企業知識問答系統（RAG / LLM）

### 專案定位
導入企業文件知識檢索與 AI 問答能力，讓內部人員能快速查詢 SOP、制度、文件與作業知識，減少重複詢問成本。

### 我的角色
- RAG 應用設計
- 文件流程規劃
- Prompt 設計
- 知識來源整理
- 系統整合與驗證

### 技術架構
- LLM Application
- RAG Workflow
- Internal Document Retrieval
- API Integration
- Python-based orchestration

### 主要工作內容
- 盤點可用知識來源與文件格式
- 規劃文件切塊與檢索流程
- 建立問答邏輯與回覆結構
- 針對常見內部查詢情境優化提示詞
- 測試問答準確性與實務可用性

### 專案成果
- 降低內部資訊搜尋成本
- 提高知識文件可利用率
- 提供 AI 導入企業內部流程的可行範例

---

## 4. 企業 IT 基礎架構與資訊安全整合優化

### 專案定位
針對企業既有 IT 環境進行網路、伺服器、資安與系統整合作業，提升穩定性、安全性與維運效率。

### 我的角色
- MIS / Infra Engineer
- 系統維運與疑難排解
- 網路與資安設備管理
- 跨部門技術支援

### 技術範圍
- Windows Server / Linux
- IIS / SQL Server / Database Backup & Restore
- Router / Switch / Firewall
- Fortigate / Check Point / Juniper
- AD / Permission / IT Support

### 主要工作內容
- 伺服器環境建置與維護
- 網路設備調整、障礙排除與流量控管
- 防火牆與資安規則管理
- SQL 備份還原與應用系統支援
- 處理企業使用者端與後端系統問題

### 專案成果
- 提升企業 IT 環境穩定度
- 降低服務中斷風險
- 建立可持續維運的資訊架構基礎

---

## 5. 製造場域資料整合與流程數位化

### 專案定位
將製造現場設備、報表、人工流程與資料流進行整合，降低重工、提升可追蹤性，並為後續 AI 導入打底。

### 我的角色
- 系統分析
- 流程整合設計
- 報表與資料庫開發
- 現場需求轉系統需求

### 技術架構
- ASP.NET / VB.NET / C#
- MSSQL / MySQL
- ETL / Webhook / Report Integration
- Excel / FineReport / ERP-like integration

### 主要工作內容
- 將現場流程轉為數位化作業
- 設計報表、查詢與資料回寫流程
- 串接內部系統與資料表
- 提升跨部門資料透明度
- 為後續自動化與 AI 分析預留資料基礎

### 專案成果
- 減少人工整理與重複輸入
- 提升資訊一致性與追蹤效率
- 建立數位化轉型初步成果

---

### 專案實際驗收
AI 影像辨識與物件偵測應用
角色：開發與整合支援  
使用技術：Python、OpenCV、YOLO、TensorFlow

- 參與影像辨識與物件偵測應用開發，完成 3 種辨識情境 的模型測試與驗證
- 協助處理約 5,000 筆 測試影像資料，提升資料前處理與模型測試效率
- 將辨識結果整合至應用流程，使平均辨識準確率提升至約 90% 以上
- 依實際使用需求調整參數與輸出格式，降低人工判讀時間約 30%

---
AIoT 感測資料整合專案
角色：系統整合與測試  
使用技術：Raspberry Pi、Arduino、感測器、Python

- 參與 2 種以上感測器 的資料蒐集與設備串接作業
- 完成 Raspberry Pi 與 Arduino 間資料傳輸流程測試，資料成功傳送率達 99%
- 建立基礎資料處理流程，每日可穩定處理約 10,000 筆 感測資料
- 協助現場測試與問題排除，將設備異常排查時間縮短約 20%

---
網站前後端系統開發專案
角色：全端開發  
使用技術：C#、JavaScript、HTML/CSS、MySQL、ASP.NET、API

- 負責網站前後端功能開發與維護，完成約 8 項主要功能模組
- 串接資料庫與外部 API，支援每日約 3,000 次 資料交換請求
- 參與系統測試與除錯，將上線後功能異常率降低至 5% 以下
- 依需求調整畫面與流程，改善使用者操作步驟約 25%
- 協助專案按期交付，維持開發進度達成率 95%

---
資安與網路設備維運專案
角色：資安網管支援  
使用技術：Fortinet、Windows Server、Linux、網路設備管理

- 協助管理約 50 台以上 內部設備與伺服器環境
- 配置與維護防火牆規則，降低非預期連線與存取風險
- 處理每月平均約 20 件 資安或系統異常問題
- 協助帳號權限與存取控管，強化內部資訊安全流程
- 透過例行檢查與維運，將系統停機時間控制在每月 1 小時以內


## 🔧 我擅長的專案類型

- AIoT 系統建置
- LLM / RAG 企業應用
- Webhook / API / LINE 整合
- 資料庫與後端系統整合
- Linux / Server / Network 維運
- 製造場域流程數位化
- AI 導入前的 IT 基礎建設整備

---

## 📌 補充說明

本頁專案為依據本人技術能力、產業背景與典型業務場景所整理之代表性專案，重點在於呈現：

- 問題理解能力
- 系統分析能力
- 架構設計能力
- 技術整合能力
- AI 與企業流程落地能力

---

[← 回首頁](/) · [About](/about/)
