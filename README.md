# practice03
# Project_02

## 專案二：Costco好市多 商品經驗老實說</br>
### 一、研究動機</br>
因時勢所趨，人們待在家的時間增加，導致大量採購的需求增加，且因為在家中上班節省了通勤時間進而提升了自行下廚的意願。為了節省比價、蒐集資訊的時間，本組希望可以藉由數據分析製作出可提供即時熱門商品清單的小工具。而在通路的選擇上，則以較常前往的「Costco」作為範例。</br>

### 二、熱門度的定義</br>
蒐集、統計Costco FB社團最多人討論的商品名稱，並下載Costco官網的商品清單(篩選條件預設以推薦順序做排序)，假定兩者重疊部分的商品即為最具討論度且為官方最為推薦之商品。

### 三、程式開發流程</br>
![p1]()

### 四、開發過程描述</br>
* 步驟一：資料來源(Costco FB社團、Costco官網)</br>
![p2]()
![p3]()
* 步驟二：爬蟲(Costco FB社團)</br>
`儲存位置：MongoDB`</br>
![p4]()
* 步驟三：資料前處理(讀取MongoDB內文檔、斷詞、統計字詞出現次數、儲存到MongoDB)</br>
![p5]()
![p6]()
![p7]()
* 步驟四：爬蟲(Costco官網)</br>
`儲存位置：MongoDB`</br>
![p8]()
* 步驟四：模糊比對</br>
![p9]()
![p10]()
* 步驟五：使用者操作介面</br>
![p11]()
### 五、成果展示</br>
![ui]()
### 六、現行問題</br>
![p12]()
### 七、未來展望</br>
![p13]()
