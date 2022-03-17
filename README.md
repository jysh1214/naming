# Naming #

自己的 cpp 命名規範。

## 名詞 ##

### 數量 ###
- xxxCount    : 代表 xxx 的數量，預期會被改變，之後會拿來做運算
- numberOfXxx : 代表 xxx 的數量，預期不會被改變
- xxxSize     : 代表 xxx 內的元素個數，其中 xxx 為 collection

### 類別 ###
- 
- 

### 物件資訊 ###
- info   : 物件內可公開的數據，通常不可更改
- desc   : 可由外部更改，會改變物件行為
- config : 通常獨立於物件，可能是由外部文件讀取而來，可用來產生物件

### 其他 ###
- duplicateXxx : 重複的 xxx
- maxVal, minVal


## 動詞 ##

## 一般函式 ##
- 數術用語，演算法名稱，特定領域專有名詞
- clac     : 單純運算後回傳結果
- load     : 透過檔案系統或資料庫讀取資料
- download : 從非本地獲取資料

## 對 collection 操作 ##
- set     : 改寫單筆資料
- map     : 對每個元素套用某個規則
- get     : 使用 index 讀取 collection 以獲取指定資料，通常只有一筆資料
- find    : 讀取特定資料但不知道 index 為何，先計算 index 再 get
- extract : 從 collection 獲得多筆資料，通常帶有 find 功能
- fetch   : 從 stream，socket 等獲取資料

## 新增和建立 ##
- make     : 淺拷貝，注意來源的生命週期
- clone    : 深拷貝
- copy     : 將數據複製到另一個已經分配好的記憶體
- create   : 從無到有產生物件
- generate : 產生一筆數據，如亂數或字串等

## 移除和刪除 ##
- remove  : 從 collection 移除元素
- destroy : 刪除整個物件
- release : 
- clean   : 清空物件內的 collection

## 其他 ##

### 連接 ###
- connect : 影校處理中連接線段
- join : 連接字串或是路徑

### debug ###
- dump : 將 info 另外存放

