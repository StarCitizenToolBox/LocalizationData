# TCTP / 星際公民繁體中文(台灣本地化修正)翻譯計畫
此計劃旨在針對遊戲內容、設定選項等內容進行台灣本地化用語修正，並透過高標準的專業學術資料來源與對遊戲世界觀塑造進行深入的研究實現了頂尖水準的翻譯。

[**立即下載**](https://sctranslator.danidomen.com/download?locale=cn_traditional&hash=4ff20a445456db1ef318f3b1c000b481)

![image.png](https://s2.loli.net/2024/05/10/fQjzaOGX9UstqBN.jpg)

與我們一同改進翻譯品質：[加入 Discord](https://discord.gg/4YKMayH2AD)・[翻譯修正建議](https://forms.office.com/r/f8WGe7zjTX)

---

## **重點改進內容**
- 對遊戲內文本翻譯進行**台灣用語本地化**
- 更正確專業的**遊戲設定選項**詞彙
- 符合**遊戲世界觀塑造**的風格進行改善的文本
- 符合國家標準的**天文與飛航專業學術用語**

---

## **文件下載**
[**Github (Startech.)**](https://github.com/everland-3769/StarCitizen-TCTP/releases)
> 透過 Github 查閱/下載所有歷史發行版本

[**Github (StarCitizenToolBox)**](https://github.com/everland-3769/StarCitizen-TCTP/releases)
> 透過 SC工具箱的 Github 倉庫查閱/下載所有歷史發行版本 (此倉庫包含了漢化組提供的簡體中文翻譯，如需使用由 TCTP 提供的繁體中文版本請下載版本後綴帶有 `TW` 的文件)

---

## **安裝方式** - SC工具箱快速安裝 (建議)
此方法非常簡單快捷，只需要透過 Microsoft Store 安裝 [SC工具箱](https://apps.microsoft.com/detail/9nf3swfwnkl1?ocid=pdpshare&hl=zh-tw&gl=US) 就能進行繁體中文的安裝，工具箱有此計劃提供的繁體中文翻譯版本，你只需要點擊安裝即可完成所有安裝步驟。

**你也可以透過下面的影片教學安裝其他來源的翻譯文件：**
https://www.youtube.com/watch?v=Ei1ZdvlBVPs

此安裝方式由 `xkeyC` 提供 / [Github](https://github.com/StarCitizenToolBox)

---

## **安裝方式** - 工具輔助安裝
此方法僅適用於將遊戲本體安裝在 **系統碟(如D:槽)** 之外的玩家，如果你的遊戲安裝在系統碟的話，進行自動安裝時將會被系統權限阻擋。

**步驟：**
- 點選 [這裡](https://hsinyu-chen.github.io/SC-localization-installer/public/) 前往安裝畫面。
- 依照畫面上的說明將 **ini文件** 拖曳到方框或是直接點選方框。
- 選擇一種安裝方式。
- 享受你的繁體中文本地化翻譯！

此安裝方式由 `dynameis_tw` 提供 / [Github](https://github.com/hsinyu-chen/SC-localization-installer)

---

## **安裝方式** - 手動安裝
這個方法適用於那些對電腦操作有一定基礎的玩家，這個方法在初次安裝時可能需要耗費一點功夫。

**步驟：**
- 在以下路徑中創建一個新資料夾：
 - `\StarCitizen\LIVE\data\Localization\New Folder`
- 將資料夾重新命名為：
 - `chinese_(traditional)`
- 將先前翻譯好的 global.ini 檔案放入該資料夾中
- 在 user.cfg 檔案中加入一行 CVAR 指令：
 - `g_language = chinese_(traditional)`
- 更新後，正常啟動遊戲。

如果你沒有 “user.cfg” ，可以按以下步驟創建一個：
1. 創建一個文字文件，並將其命名為 “user.txt“ 
2. 將副檔名由 .txt 更改為 .cfg
3. 將 “user.cfg” 放入路徑：\StarCitizen\LIVE
4. 可使用記事本或其他文字編輯器開啟並編輯 “user.cfg”。
