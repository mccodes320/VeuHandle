1. Vue 3 框架簡介
1.1 用來組織、簡化複雜的網頁開發
1.2 基於 HTML、CSS、JavaScript
1.3 模板、回應式、組件設計
1.4 漸進式框架

2. Vue 3 課程簡介
2.1 須具備 HTML、CSS、JavaScript 基礎
2.2 主要學習目標為前後端分離式的單一頁面網站應用
2.3 採用 Composition API
2.4 採用 Single File Components

3. Vue 3 專案快速開始
3.1 安裝 VS Code、Node.js
3.2 使用終端機命令介面
3.3 建立 Vue 專案資料夾
3.4 安裝第三方套件
3.5 執行、測試範例網頁 



1. 
2. 下載 node.js: Node.js v22.11.0 (LTS)
https://nodejs.org/zh-tw
3. 環境變數設定 Path新增 C:\Program Files\nodejs\
4. 執行 npm
如果碰到
PS D:\VeuHandle> npm
npm : 因為這個系統上已停用指令碼執行，所以無法載入 C:\Program Files\nodejs\npm.ps1 檔案。如需詳細資訊，請參閱 about_Execution_Policies，網址為 https:/go.microsoft.com/fwlink/?Li
nkID=135170。
位於 線路:1 字元:1
+ npm
+ ~~~
    + CategoryInfo          : SecurityError: (:) [], PSSecurityException
    + FullyQualifiedErrorId : UnauthorizedAccess

開啟 powershell 
確認是否是限制
PS C:\Users\Macro> get-executionpolicy
Restricted

是的話就放寬限制
PS C:\Users\Macro> set-executionpolicy remotesigned

執行原則變更
執行原則有助於防範您不信任的指令碼。如果變更執行原則，可能會使您接觸到 about_Execution_Policies 說明主題 (網址為
https:/go.microsoft.com/fwlink/?LinkID=135170) 中所述的安全性風險。您要變更執行原則嗎?
[Y] 是(Y)  [A] 全部皆是(A)  [N] 否(N)  [L] 全部皆否(L)  [S] 暫停(S)  [?] 說明 (預設值為 "N"): Y


D:\VeuHandle>

### 執行 

PS D:\VeuHandle\vue-training> npm run dev

![image](https://github.com/user-attachments/assets/92631579-598f-4360-9c9f-7cbd105ce2db)

![image](https://github.com/user-attachments/assets/88cd40c1-87d6-46c3-9be0-69dff60411d3)
















