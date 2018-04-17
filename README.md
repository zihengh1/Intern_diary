### 2/22 
- 實習心得：
第一天工作上班
0930~1730

輔翔學長成為我的師父 <br>
但他 3/5 要入伍當研替一個月 <br>
上午完成爬蟲實作 <br>
將開放資料 JSON 文件抓下來並分析 <br>
了解專案中參數意義 <br>
中餐和謹瑋學長、欣紘學姊吃中飯 <br>
欣紘學姊暑假要去荷蘭留學、已婚 <br>
謹瑋學長進入實驗室大約半年、之前在陽明念研究所 <br>

- 近期工作目標：（3/1號前完成）
將感測器的數據上傳網路並抓取下來 <br>
再做分析結果 <br>

- 學習點：
1. Python 爬蟲
2. JSON 文件格式
3. Python基本程式設計
4. 初淺了解專案架構及程式
5. Linux 指令要再深入複習
6. sudo、apt-get (鳥哥）
7. vi 環境撰寫程式
8. SHT31 感測器架設
9. I2C 與樹莓派連接
10. G5 PM2.5 與樹莓派連接
11. 麵包板基礎知識
12. Javascript 基礎程式設計
13. Think speak 平台認識
14. GitHub 基礎學習

### 2/23
- 實習心得：
0930~1830

上午將 SHT31 sensor 讀取每秒的溫濕度資料的程式完成 <br>
並且成功將 data 上傳 thingspeak 的 my channel <br>
中午和大家一起吃一家吐司店當午餐 <br>
然後有去刮刮樂店 <br>
謹瑋學長刮中五百 <br>
很喜歡那裡工作環境 <br>
師父對我很好教我很多知識 <br>
下午學會 G5 sensor 的讀取程式 <br>
也同樣的將 data 上傳 thingspeak 上 <br>
但是接下來要用 UART 技術讓 raspberry pi 可以同時接收12台 sensor <br>
不太能了解 pigpio 函式庫的運作 <br>
下班後和師父一起用餐聊了很多東西 <br>
覺得自己待在那邊一天就很賺 <br>
後來他沒讓我請他吃飯 <br>

- 近期工作目標：
搞定 raspberry GPIO 問題讓多個 sensor 接上去 <br>
並且成功讀取資料再上傳 thingspeak <br>

- 學習點：
1. SHT31 感測器讀取資料
2. G5 感測器讀取資料
3. Git 實際操作並熟練
4. vi 環境熟練
5. Python 基本程式設計
6. Thingspeak 平台上傳實作
7. UART 技術認識
8. Raspberry pi 接腳圖的認識

### 2/26
- 實習心得：
1030~1900

上午搭計程車花了320 元用 15 分鐘殺到中研院 <br>
路上遇到謹瑋學長他拿著咖啡很悠閒的進去 <br>
我真傻 <br>
但是還是不要再睡過頭了 <br>
把一顆 G5 sensor 用 UART 方式接上 <br>
在完成讀資料的 code 解碼完成 <br>
中午大家一起吃拉亞 <br>
回來後接上第二顆 G5 sensor 並上傳資料完成 <br>
但是要讓四台 sensor 每秒上傳 data 之後還要多加點東西 <br>
之後師傅開始帶我學 LASS 7688 的基礎知識和初始化作業 <br>
他不在的時候我要將四台 sensor 同時接上 並上傳 <br>
還要多了解整個 Anysense 專案的 code <br>
要快點再將 LASS 7688 sensor 摸透 <br>

- 近期工作目標：
接上4 個 sensor 同時每秒接收資料 <br>
摸熟專案的 code <br>
以及學長丟給我的 doc <br>

- 學習點：
1. UART 技術實作
2. 操控 Raspberry pi 的 GPIO
3. 了解專案硬體設施及軟體大略架構

### 3/2
- 實習心得：
1230~1800

開學了 <br>
上完演算法就趕來中研院 <br>
沒想到師傅還在 <br>
下午把整個程式碼修過一遍 <br>
發現在供電不足的情況下 <br>
會讓感測器讀取資料不完全 <br>
所以要補足資料不齊的狀況 <br>
使用開發版解決三顆 G3 sensor 供電不足的狀況 <br>
之後再自己焊接 USB 線 <br>
為了趕晚上和婕如的晚餐 <br>
沒有把國產感測器接上讀取 <br>
下次不能再這樣了 <br>
 
- 近期工作目標：
接上三個國產感測器並放到老師實驗室測試兩個禮拜 <br>
學會 multiple threading <br>

- 學習點：
1. 解決硬體設施供電不足的情況
2. 優化程式碼
3. 焊接 USB 線 

### 3/5
- 實習心得
0910~1800

今天終於完成感測器的連接及程式碼修訂 <br>
第一次在這裡做完一件事工作 <br>
對學長也有點交代了 <br>
東逸學長今天早上在考駕照前突然來找我 <br>
他想教我一些前端網頁的東西 <br>
我很開心也很謝謝他介紹給我一些好用的開發工具和網站 <br>
希望可以趕快想個目標自己架個網站 <br>
師傅今天去當兵了 <br>
中午和欣紘學姊和謹瑋學長吃胡適小學對面的麵店 <br>
回來遇到 Sochid 一位來自印度的博班學長 <br>
跟他打個招呼卻發現自己最近英文實在爛得 <br>
完全失去與人溝通的能力 <br>
英文真的要好好加強了 <br>
之後上去找老師架感測器的設備 <br>
老師看完覺得我做的太不安全太不專業 <br>
所以希望我能跟韻捷學長弄出開發版 <br>

- 近期工作目標：
架出一個網站（之後再加強後端學習）<br>
和韻捷學長學習開發版的相關知識 <br>
熟練前端網頁設計 <br>

- 學習點：
1. 認識前端網頁的開發工具
2. nohup exe & 指令
3. eagle pcb 知識
4. 感測器供電問題

### 3/9
- 實習心得
1300~1800

下午帶大家的龍角跑去上班 <br>
公車上超多人飲料快被擠爆 <br>
那天來了新的研助 LEO 學長 <br>
也第一次遇見韻捷學長他一開始在忙 <br>
叫我自己先載 Sparkfun 的元件 library <br>
他忙完一陣子後大家一起到一間研討室 <br>
韻捷學長開始教大家如何使用 eagle <br>
雖然時間很短學的東西很少 <br>
但是還是有了一點基本概念 <br>
後來老師就來實驗室 <br>
他希望我能學會自己印刷一個 pcb <br>
接下來到下班為止我都在樓上實驗室裝 3 台感測器的佈置 <br>

- 近期工作目標：
設計電路板
電學基礎知識

- 學習點：
1. eagle 開發軟體認識及操作
2. python time 模組應用

### 3/12
- 實習心得
0850~1800

早上從北投到中研院路程大概一個小時又十五分鐘左右 <br>
星期六帶東逸學長和謹瑋學長去貓空泡茶 <br>
不錯的體驗和他們互動越來越多了 <br>
上午將電路介紹及 eagle 教學影片看完 <br>
還是沒什麼長進 <br>
接下來把國產感測器的程式碼做最後修訂 <br>
開始燒錄剩下兩台 rpi  <br>
但由於改版預設有關遠端連線的設定遲遲無法成功登入 <br>
慢慢找資料爬文 <br>
終於完成今天的工作 <br>
星期五要去老師實驗室架設 <br>
星期四晚上要去找韻捷學長學習 <br>

- 近期工作目標：
設計電路板
自己構想專題及搜集資料
東逸學長的網站

- 學習點：
1. rpi 燒錄
2. 遠端連線方式
3. ip查詢套件
4. VNC 認識
5. 印製電路版教學影片

### 3/16
- 實習心得
1330~2130

中午從政大幫泉恆學姊買麵疙撘來中研院 <br>
還是沒搭上679 <br>
電路圖昨天就去找韻捷學長完成 <br>
回家把 GPIO 接上今天開始要把它印刷出來 <br>
做了五片失敗了三片 <br>
首先先將設計圖印成黑白，彩色的會失敗 <br>
印在描圖紙上，在貼在 pcb 原版上 <br>
曝光 90 秒後開始用顯影劑把第一層洗掉 <br>
再來是用酸性蝕刻液將 pcb 泡成黃色 <br>
接下來對 GPIO 的洞以及插座進行鑽孔 <br>
最後將元件焊上電路板韓要測試是否有短路或是斷線問題 <br>
一次接上五個 sensor 還是有點吃力 <br>
週六回家進行測試，但由於在室內進行實驗，數值變化不大結果不佳 <br>
週日將程式優化並將資料轉成 csv 檔 <br>
並學習 pandas 與 numpy 等 library 實作 <br> 

- 近期工作目標：
實際測試 sensor 

- 學習點：
1. 電路板印製
2. python output a file
3. pandas and numpy
4. sensor 輸出編碼的程式優化

### 3/19
- 實習心得
0830~1800

早上從北投出發花了一個小時又10分鐘抵達 <br>
接下來開始將週日寫的程式碼放入 raspberry pi 中 <br>
看了有關 CV 值計算上的問題 <br>
並對對照組 G5 sensor 程式碼進行更動 <br>
增加輸出檔案與時間的功能 <br>
但實際測試發現會一堆亂碼不合我所要的資料格式 <br>
中午大家又去吃了拉亞，吃到有點小膩了 <br>
下午繼續對程式進行更動 <br>
請 Rita 學姊幫我借研討室做實驗卻發現那裡沒有網路線 <br>
到樓下開始正式對工研院 sensor 進行測試 <br>
還是讀出一堆亂碼 <br>
發現有三種實驗結果 <br>
第一種是亂碼5a9dffffff424dxxxxx <br>
第二種是正常424d00000019fxxxxxx，算出來的 pm2.5 太大 <br>
第三種才是最後算出來準確的 <br>
猜想會不會是 pcb 板子的問題或是出風口進風口的擺設問題 <br>
最後下班前把所有 sensor 帶回家 <br>
希望下週能有報告出來 <br>

- 近期工作目標：
將實驗做完，做完資料分析並產出報告

- 學習點：
1. python csv 
2. nohup python -u exe & 解決問題
 
### 3/22
- 實習心得
1245~2130

今天終於搭到679去上班 <br>
沿途風景很棒，舒適又怡人的午後 <br>
對於最近的工作開始感到煩躁，我不是討厭那邊的環境 <br>
而是對於手上麻煩的實驗感到倦怠 <br>
下週就要交報告了，最重要得資料還沒出來 <br>
下午開始就進行程式更動及最後修訂 <br>
對於字串解碼跟 GPIO 控制更能有效解決 <br>
到快五點左右為了解決之前電路板供電不足的情形 <br>
第一次自己刷了新的電路板去解決 <br>
但是很不幸的在打洞的步驟慢慢開始發現這次的新板子 <br>
在尺寸明顯比上次小，也因此排針上不去 <br>
最終失敗結束 <br>

- 近期工作目標：
把實驗 data 產出來

- 學習點：
1. 電路板印刷
2. python Excetion handle

### 3/25
- 實習心得
加班 1020~1730

週末和輔翔繼續加班，把板子的問題處理完 <br>
但是尺寸不合，最終放棄 <br>
使用備案，開始燒錄更多的樹莓派 <br>
一個 sensor 配上一個 樹莓派 <br>
下載了迅速燒錄的軟體 <br>

- 近期工作目標：
完成實驗


### 3/26
- 實習心得
0830~1830

很緊張的一天，只剩一個禮拜就要結案 <br>
資料還是出不來，原因出在供電問題及實驗場地是否具備充足的網路線 <br>
供電問題在早上一連串的燒錄樹莓派解決完畢 <br>
網路線問題最後是採用開機後直接執行 python 程式 <br>
中餐大家出去吃，我和輔翔繼續完成工作 <br>
嘗試過多種開機後自動執行的方式 <br>
最後選擇在 rc.local 中嵌入程式得以執行 <br>
接下來就是把 sensor 帶回家做測試 <br>
資料分析的程式也有初步的架構和學習 <br>

- 近期工作目標：
完成實驗，資料分析

- 學習點：
1. 樹莓派的開機後自動執行
2. rpi 底層 kernal 的認識

### 3/29
- 實習心得
1300~1830

一個禮拜的實驗後，實驗有了好的發展 <br>
雖然比預期少了許多實驗的時間 <br>
但是總算有資料可以拿來分析 <br>
下午開始把資料做整理，然後開始撰寫報告 <br>
先是從謹瑋那裏 <br>
從資料庫撈出的離實驗場所最近感測器去做分析 <br>
除了將他歸類整理 <br>
還要處理時間差的問題 <br>
缺漏值的部分就要用內插法將他補齊才能做圖 <br>

- 近期工作目標：
完成報告

- 學習點：
1. missing data 如何處理
2. 時間差問題
3. 更熟練pandas and numpy 
4. matplotlib 深入繪圖
5. 實驗報告撰寫方式

### 3/30
- 實習心得
0900~1800

今天是報告截止的最後一天，整天都在趕報告 <br>
除了最基本的折線圖比較 <br>
還加入附近實驗室空氣盒子的比較 <br>
算出共變異數並分析其一致性 <br>
找出 sensor 中有兩個是有問題的裝置 <br>
學習如何繪製 scatter plot matrix 以及基本 sklearn lib 的線性回歸 <br>
並用 R - square 驗證其正確性 <br>
最後再加上耗電問題 <br>
以上都是撰寫在報告中的內容 <br>
時間稍短但是蠻順利完成，並寄給老師過目 <br>

- 近期工作目標：
工研院案子初次實驗結案

- 學習點：
1. 整個資料分析的過程及程式碼撰寫
2. 共變異數計算
3. 相關係數計算
4. 統計檢定
5. 回歸分析
6. R - square 驗證回歸之正確性
7. scatter plot matrix 繪製
8. 瓦數計算

### 4/2
- 實習心得:
0930~1730

早上跟輔祥討論最終報告的內容 <br>
並將 rpi 一些初始設定刪除，以便之後他人使用 <br>
雖然老師有邀我一同與工研院院方開會 <br>
但是星期二的學業實在忙碌，實在抽不開身 <br>
只好婉拒，有點可惜，因為這是在中研院完成的案子 <br>
並且也是自己親手完成的 <br>
下午有點悠閒，看了演算法，做了點筆記 <br>
實在了無新意，之後就開始跟輔祥整理實驗室 <br>
他稱這項工作為認識基本硬體並整理 <br>
我不無他想，很開心很慶幸自己能參與這裡實驗室的計畫 <br>
並親手完成一個案子 <br>

- 近期工作目標：
找到新的方向，看是要做專題還是其他的

### 4/9
- 實習心得
0830~1830

經過清明連假的充電及整理 <br>
開始構思下個步驟的方向 <br>
輔祥上次有跟我提過的聊天機器人 <br>
我也利用早上時間去了解一些基礎平台架設 <br>
但是還是有點摸不著頭緒 <br>
開始學習 node.js 的文件及使用方法 <br>
還有開始摸熟 javascript 的語法 <br>
下午輔祥跟我提到希望我把工研院的系統架得更好 <br>
所以繪製新的板子繼續努力的將電路板完成 <br>
最終由於板子保固年限的問題，還是宣告失敗 <br>
離開前把 atom 編輯器基本設定架好 <br>
實際操演過 node.js 的一些模組化 <br>
有點迷惘這次的工作方向，因為 chatbot 的案子已經有碩班學長在做了 <br>
而且我想加強的定位服務也因為很多 API 限制沒辦法完成 <br>
這些都是牽扯到隱私權的問題，所以發展性也滿少的 <br>

- 近期工作目標：
學會 node.js + javascript，把基本的 chatbot 平台做出來

- 學習點：
1. node.js、npm 基礎認識
2. 學習javascript   
3. atom 編輯器的基本使用和設置
4. chatbot 平台的基礎設置及認識
5. LINE API 的創建
6. 認識 webhook

### 4/13
- 實習心得
1250~1730

下午到那邊開始繼續學習node.js 的應用和文件 <br>
越來越有心得，使用 atom 也越來越得心應手 <br>
接著和輔祥去資服處找老師開會 <br>
開完回老師有兩件事交代，也就是工研院的電路板要快點做出來 <br>
再來就是不要做 chatbot 改作嵌入式系統之後再加入實驗室已有的 AI 演算法 <br>
三點多和泉恆學姊去看銘鋒老師在中研院開的球賽，雖然沒有跟老師 <br>
見到面說到話，但是和場下的碩班學長聊了蠻多的 <br>
兩人都是已經申請上美國研究所的學長，也多多寒暄了幾句 <br>
回來之後便開始對新拿到的開發版做摸索 <br>
了解 STM32 系統的開發及程式撰寫 <br>
之後還要加緊看些 utensorflow 的文件 <br>
晚餐與謹瑋學長吃自助餐，聊到他想離職的事 <br>
聊了很多，收穫很多，職場的生活真的就是用密密麻麻的人際關係串連起來的 <br>
我也要好好建立自己的人脈網 <br>

- 近期工作目標：
摸熟嵌入式系統（ＳＴＭ３２）以及utensorflow

- 學習點：
1. node.js 繼續學習
2. STM32 的基本介紹及設定
3. 人際關係的重要性

### 4/16
- 實習心得：
0930~1800

早上有點睡過頭，到中研院之後
先是對於 node.js 繼續學習
半小時後，開始繼續對 STM32 開發環境做熟悉
再 mbed 上寫了幾支範例 code ，成功在開發板上操控 LED
一直沒有把 mbed os 好好建置在自己本機中
中午去吃了五號餐館，老實說有點鳥...
工作上的未來目標就是做 AIoT 把 deep learning 放到嵌入是系統上
之後再做邊際運算
下午繼續做一些 sample code 開發
持續在網路上找尋好用 library
以及其他範例，對於操控 GPIO 以及讀資料還是有點生疏
日後要盡快補足缺漏的知識

- 近期工作目標：
嵌入式系統、STM32F4 GPIO 控制及讀資料

- 學習點：
1. javascript 學習
2. 嵌入式系統學習
3. STM32F4 操控 LED
4. mbed 開發環境
5. sample code 應用
