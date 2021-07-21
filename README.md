# cms2toj
將CMS格式轉換成TOJ格式

## 使用方法
1. `cmsDumpExporter -S -U -P -G /path/to/temp/directory`
    * 可以加上`-c CONTEST_ID`指定比賽來減少匯出所需時間
2. `python cms2toj.py /path/to/temp/directory /path/to/output/directory`

* 本程式可以在任意目錄執行
* `/path/to/temp/directory` 暫存目錄，可以任意指定
* `/path/to/output/directory` 輸出目錄，可以任意指定
* **注意**：本程式結束時，壓縮尚未完成，請檢查壓縮檔大小不再變動時才是壓縮完畢。
