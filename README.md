# Pic-API
簡單的PHP隨機圖片API
## 使用
- 下載原始碼並將其放置在您的網站根目錄中。通過[域名]訪問即可。
- API的地址為 [域名]/img.php。
- 要添加更多的API，只需複製img.php文件並重新命名（API將自動創建相應的圖片庫和統計文件）。
- 調用API獲取圖片時，直接修改API對應的圖片庫中的圖片鏈接即可。
## 预览
預覽網站：[https://imgapiphp.arcelibs.repl.co](https://imgapiphp.arcelibs.repl.co/)


## 文件说明
|文件名|描述|额外|
|-|-|-|
|index.php|首页文件|**必要**|
|img.php|随机图片API|**必要**|
|img.txt|API图片链接库|**必要，自动创建**|
|pvimg.txt|API调用统计|自动创建|
|PVIP.txt|API调用来源记录|自动创建|
|IP.txt|API调用网站数量|自动创建|
|log.log|API调用记录|自动创建|
