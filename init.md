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




