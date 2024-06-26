## 清大(NTHU) EEclass 助教(TA)小工具

**作者**: 孫利東  
**背景**: 我是清大統計所的孫利東，曾擔任統計學助教。在擔任助教期間，我遇到了一些效率問題，這促使我開發了一些自動化工具來解決這些問題。

### 遇到問題描述

1. **學生作業提交(homework update)**: 學生提交作業時，文件名稱不統一，且在批改完畢後需要重新上傳到系統，這個過程非常耗時且繁瑣。
2. **考試座位表(seat_table_generation)**: 考試時需要手動排座位，這不僅耗時，而且容易出錯。

### 解決方案

#### 作業批改自動化

為了解決作業提交的問題，我開發了一個自動化工具，該工具能夠：

- **標準化文件名稱**: 自動重新命名所有提交的作業文件，以便它們符合標準格式。（目前僅開放PDF檔）
- **一鍵匯入筆記軟體**: 允許一次將所有作業文件匯入到筆記軟體中，便於批改。
- **將作業平分到多個資料夾中**: 由於作業會由多個助教共同批改，為增加批改效率，提供將作業均分到多個資料夾中，方便助教們分配作業和管理
- **作業自動上傳及成績自動登記**: 助教們批改完的作業整理好後，可以自動化的上傳作業到eeclass，不再需要中間上傳作業的人力

#### 考試座位自動排位

考試座位自動排位工具提供：

- **自動生成座位表**: 根據學生名單自動生成座位表，確保每次考試座位的隨機性和公正性。
- **易於調整**: 如果需要手動調整某些座位，也可以輕鬆進行。

### 使用方法
* 對應資料夾有相關使用說明

### 後續可能開發方向（歡迎各位發PR修正）
* 相關套件requirement.txt檔
* 整理成方便使用的UI介面
* 操作說明


### 結語

這些工具旨在節省助教和教師的時間，讓他們能夠更專注於教學和學生互動，而不是繁瑣的行政工作。希望這些工具能夠幫助其他教師和助教解決類似的問題。

