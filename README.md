 # 玉山

# 競賽網址
https://tbrain.trendmicro.com.tw/Competitions/Details/10?utm_source=SWC&utm_medium=fb&utm_campaign=T_Brain10&fbclid=IwAR2bSf37WWlKWw3qFJnkEBj41GvymmCqs4_DaGS9jbkvUMUDUFUcNHBln3s



訓練集的授權日期為 1~90，共 90 天的信用卡授權交易紀錄，請參賽者預測授權日期在 91~120 的各筆交易是否為盜刷。

----------
![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1570710926724_image.png)

# 欄位分析
| 欄位                                | 說明                                                | 欄位特性/解釋                                                                                                                                                                                                                                             | 每個col分析                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |                                                                                                                                                                                                                                                                                          |
| --------------------------------- | ------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| acqic                             | 收單行代碼                                             | 類別                                                                                                                                                                                                                                                  | insfginsfg有6051種類別，超過3000筆的有48種<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568535367579_image.png)                                                                                                                                                                                                                                                                                                                                                                 | 盜刷率超過10%<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568542176393_image.png)                                                                                                                                    |
| contp                             | 交易類別                                              | 分0~6種     類別                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568535415888_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541243893_image.png)                                                                                                                                                    |
| etymd                             | 交易型態                                              | 分0~10種     類別                                                                                                                                                                                                                                       | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568535464750_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541321830_image.png)                                                                                                                                                    |
| mchno                             | 特店代號                                              | 特約商店代號 類別                                                                                                                                                                                                                                           | 89316種類別,超過3000筆的有47種<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568535823664_image.png)                                                                                                                                                                                                                                                                                                                                                                           | ![](https://paper-attachments.dropbox.com/s_CC3D065EEB9F2FD65EFBE37E9C4F55743A240E206DA1AD7FFA4CEFAB16147A4E_1569227702863_Image+6.png)                                                                                                                                                  |
| mcc                               | MCC_CODE                                          | https://kknews.cc/zh-tw/finance/6n6l8m3.html<br>把他理解成 在哪個產業消費 類別                                                                                                                                                                                    | 434種類別,超過3000筆的有62<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568535897637_image.png)                                                                                                                                                                                                                                                                                                                                                                              | ![](https://paper-attachments.dropbox.com/s_CC3D065EEB9F2FD65EFBE37E9C4F55743A240E206DA1AD7FFA4CEFAB16147A4E_1569227801637_Image+8.png)                                                                                                                                                  |
| iterm                             | 分期期數                                              | 0~8 類別                                                                                                                                                                                                                                              | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568535923972_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1570638768281_image.png)                                                                                                                                                    |
| scity                             | 消費城市                                              | 0~6671 類別                                                                                                                                                                                                                                           | 5698種類別,超過3000筆的有34<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568535983947_image.png)                                                                                                                                                                                                                                                                                                                                                                             | ![](https://paper-attachments.dropbox.com/s_CC3D065EEB9F2FD65EFBE37E9C4F55743A240E206DA1AD7FFA4CEFAB16147A4E_1569228191162_Image+10.png)<br><br>![](https://paper-attachments.dropbox.com/s_CC3D065EEB9F2FD65EFBE37E9C4F55743A240E206DA1AD7FFA4CEFAB16147A4E_1569228325616_Image+12.png) |
| stocn                             | 消費地國別                                             | 0~107 <br>這應該也屬於類別<br>跟消費城市應該要有相關<br>類別                                                                                                                                                                                                             | contpecfg107種類別,超過3000筆的有11<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536011508_image.png)                                                                                                                                                                                                                                                                                                                                                                     | ![](https://paper-attachments.dropbox.com/s_CC3D065EEB9F2FD65EFBE37E9C4F55743A240E206DA1AD7FFA4CEFAB16147A4E_1569228376314_Image+14.png)<br><br>![](https://paper-attachments.dropbox.com/s_CC3D065EEB9F2FD65EFBE37E9C4F55743A240E206DA1AD7FFA4CEFAB16147A4E_1569228420780_image.png)    |
| bacno                             | 歸戶帳號<br><br>bacno 可視為使用者的代碼                       | 歸戶即是利用每位客戶的身份證字號當做帳號，簡化登入步驟，輕鬆管理多個帳戶。<br>所以應該是人頭的意思 類別                                                                                                                                                                                              | 有95214種類別，分佈太散考慮先不帶入<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536105079_image.png)                                                                                                                                                                                                                                                                                                                                                                            |                                                                                                                                                                                                                                                                                          |
| cano                              | 交易卡號                                              | 這個跟bacon一樣(目測) 類別                                                                                                                                                                                                                                   | 有129413種類別，分佈太散考慮先不帶入<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536124730_image.png)                                                                                                                                                                                                                                                                                                                                                                           |                                                                                                                                                                                                                                                                                          |
| hcefg<br><br>可以drop 跟insfg        | 支付型態                                              | 0~9 類別                                                                                                                                                                                                                                              | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536154344_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541367878_image.png)                                                                                                                                                    |
| csmcu<br><br>消費幣別跟所在國家是否相同（要推測）   | 消費幣別<br><br>csmcu的代碼是消費時使用的幣別                     | 0~75 類別                                                                                                                                                                                                                                             | 72種類別,超過3000筆的有8<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536203396_image.png)<br><br><br>消費最多的是62貨幣  <br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1570642242903_image.png)<br><br><br>消費62貨幣的筆數按時間段排列（hour）<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1570642666028_image.png)<br><br><br>消費大多在白天，故猜測62是台幣 | ![](https://paper-attachments.dropbox.com/s_CC3D065EEB9F2FD65EFBE37E9C4F55743A240E206DA1AD7FFA4CEFAB16147A4E_1569227552108_Image+2.png)<br><br>![](https://paper-attachments.dropbox.com/s_CC3D065EEB9F2FD65EFBE37E9C4F55743A240E206DA1AD7FFA4CEFAB16147A4E_1569227641089_Image+4.png)   |
| stscd                             | 狀態碼                                               | 0~4<br>我猜這是交易狀態<br>類似尚未付款 付款完成之類的<br>類別                                                                                                                                                                                                             | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536240328_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541396549_image.png)                                                                                                                                                    |
| ecfg                              | 網路交易註記                                            | 是否是網路交易 布林值(Y/N)                                                                                                                                                                                                                                    | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536289208_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541426937_image.png)                                                                                                                                                    |
| insfg                             | 分期交易註記                                            | 是否分期 布林值(Y/N)                                                                                                                                                                                                                                       | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536312690_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541462556_image.png)                                                                                                                                                    |
| ovrlt                             | 超額註記碼                                             | 是否超額 布林值(Y/N)                                                                                                                                                                                                                                       | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536332857_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541474703_image.png)                                                                                                                                                    |
| flbmk<br><br>有na，另外成為一群<br>類別     | Fallback註記<br><br>flbmk代表是否透過刷磁條的方式完成交易           | Fallback Charge:回退交易，是指晶片卡(EMV)的交易本該使用晶片進行交易，但因為各種問題(技術問題、偽造卡、攻擊等)，使得通過不支持EMV的POS機或者支持EMV卡的POS機，使用磁條信息進行了交易。<br>flbmk代表是否透過刷磁條的方式完成交易，<br>原文網址：[https://read01.com/5zGgy2.html](https://read01.com/5zGgy2.html)<br><br>是否使用磁條交易(一般刷卡) 布林值(Y/N/null) | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536353558_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541493144_image.png)                                                                                                                                                    |
| flg_3dsmk<br><br>有na，另外成為一群<br>類別 | 3DS交易註記                                           | 3DS是3-Domain Secure的簡稱<br>三方驗證<br>布林值(Y/N/null)                                                                                                                                                                                                     | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536376169_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541510422_image.png)                                                                                                                                                    |
| fraud_ind                         | 盜刷註記                                              | y<br>布林值(0/1)                                                                                                                                                                                                                                       | 1.34%的盜刷率<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536392336_image.png)                                                                                                                                                                                                                                                                                                                                                                                       |                                                                                                                                                                                                                                                                                          |
| 以下不太確定欄位定義                        |                                                   |                                                                                                                                                                                                                                                     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |                                                                                                                                                                                                                                                                                          |
| locdt<br><br>直接帶入值                | 授權日期                                              | 日期                                                                                                                                                                                                                                                  | 90種類別，日期的形態很奇怪，是全數字，分佈平均<br>test 跟 train的類別完全沒有重複， 所以直接帶入值<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536518454_image.png)                                                                                                                                                                                                                                                                                                                                      | 盜刷率超過2%的：<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541707351_image.png)                                                                                                                                   |
| loctm <br><br>1.類別<br>2.直接帶入值     | 授權時間<br>loctm格式為時分秒，<br>若時間為下午三點十分零秒，則會顯示151000.0 | 時間(這個要再問下)                                                                                                                                                                                                                                          | ![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1570641627782_image.png)                                                                                                                                                                                                                                                                                                                                                                                                        | 盜刷率超過3%的：<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568541794893_image.png)                                                                                                                                   |
| txkey                             | 交易序號                                              | 流水號                                                                                                                                                                                                                                                 | 純流水號，考慮先不帶入<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568536683457_image.png)                                                                                                                                                                                                                                                                                                                                                                                     |                                                                                                                                                                                                                                                                                          |
| conam<br><br>1.類別<br>2.直接帶入值      | 交易金額-台幣(經過轉換)                                     | 就是花費的錢<br>但我不確定怎麼分類                                                                                                                                                                                                                                 | 具有重複性，建議按類別算，例如刷1016.34元的盜刷率有30%（下方有詳細代碼）做2個欄位， 一個類別，一個直接帶入值<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568535609567_image.png)                                                                                                                                                                                                                                                                                                                                    | 頭500筆數最多，<br>盜刷率超過3%的：<br><br>![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568540310161_image.png)                                                                                                                      |

# **欄位分析+長條圖**
| 項目               | acqic <br>收單行代碼                                                                                                                       | bacno 歸戶帳號                                                                                                                            | cano <br>交易卡號                                                                                                                         | conam 交易金額<br>台幣(經過轉換)                                                                                                                | contp <br>交易類別                                                                                                                        | csmcu <br>消費幣別                                                                                                                        | ecfg <br>網路交易註記                                                                                                                       | etymd <br>交易型態                                                                                                                        | flbmk <br>Fallback 註記                                                                                                                 | flg_3dsmk <br>3DS 交易註記                                                                                                                | fraud_ind <br>盜刷註記                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 型別               | 類別                                                                                                                                    | 類別                                                                                                                                    | 類別                                                                                                                                    | 數值                                                                                                                                    | 類別                                                                                                                                    | 類別                                                                                                                                    | 類別YN                                                                                                                                  | 類別                                                                                                                                    | 類別YN                                                                                                                                  | 類別YN                                                                                                                                  | Y                                                                                                                                     |
| 原始<br>類別數        | Length: 6051                                                                                                                          | Length: 95214                                                                                                                         | Length: 129413                                                                                                                        | Length: 72961                                                                                                                         | Length: 7                                                                                                                             | Length: 72                                                                                                                            | Length: 2                                                                                                                             | Length: 11                                                                                                                            | Length: 2                                                                                                                             | Length: 2                                                                                                                             | Length: 2                                                                                                                             |
| 數值分布             | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570089745484_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570089804689_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090102889_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570089845391_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570089881048_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090148834_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090285453_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090173154_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090334085_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090342628_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090349138_image.png) |
| 長條圖              | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570197492568_image.png) |                                                                                                                                       |                                                                                                                                       | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570200408230_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570196859572_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570196878463_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570196937555_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570196948080_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570196981901_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570196993424_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570197021990_image.png) |
| 盜刷數值分布           | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570203921792_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570204560969_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570204693347_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570204804961_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570204851446_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570204927917_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570204986663_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205058546_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205092926_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205122358_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205154072_image.png) |
| 盜刷<br>類別數        | Length: 556                                                                                                                           | Length: 8643                                                                                                                          | Length: 8730                                                                                                                          | Length: 7147                                                                                                                          | Length: 5                                                                                                                             | Length: 45                                                                                                                            | Length: 2                                                                                                                             | Length: 10                                                                                                                            | Length: 2                                                                                                                             | Length: 2                                                                                                                             | Length: 1                                                                                                                             |
| 重要排名             |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       | 2                                                                                                                                     | 3                                                                                                                                     |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |
| 盜刷變數重要性<br>(熱度圖) | -0.084                                                                                                                                | 0.00029                                                                                                                               | 0.0046                                                                                                                                | 0.017                                                                                                                                 | 0.023                                                                                                                                 | 0.013                                                                                                                                 | 0.16                                                                                                                                  | 0.068                                                                                                                                 | 0.0019                                                                                                                                | -0.022                                                                                                                                | -                                                                                                                                     |



| 項目               | hcefg <br>支付形態                                                                                                                        | insfg  <br>分期交易註記                                                                                                                     | iterm <br>分期期數                                                                                                                        | locdt <br>授權日期                                                                                                                        | loctm <br>授權時間                                                                                                                        | mcc <br>MCC_CODE                                                                                                                      | mchno <br>特店代號                                                                                                                        | ovrlt <br>超額註記碼                                                                                                                       | scity <br>消費城市                                                                                                                        | stocn <br>消費地國別                                                                                                                       | stscd <br>狀態碼                                                                                                                         | txkey <br>交易序號                                                                                                                        |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- |
| 型別               | 類別                                                                                                                                    | 類別YN                                                                                                                                  | 類別                                                                                                                                    | 類別                                                                                                                                    | 類別                                                                                                                                    | 類別                                                                                                                                    | 類別                                                                                                                                    | 類別YN                                                                                                                                  | 類別                                                                                                                                    | 類別                                                                                                                                    | 類別                                                                                                                                    | 流水號                                                                                                                                   |
| 類別數              | Length: 10                                                                                                                            | Length: 10                                                                                                                            | Length: 9                                                                                                                             | Length: 90                                                                                                                            | Length: 84810                                                                                                                         | Length: 434                                                                                                                           | Length: 89316                                                                                                                         | Length: 2                                                                                                                             | Length: 5698                                                                                                                          | Length: 103                                                                                                                           | Length: 5                                                                                                                             | Length: 1521787                                                                                                                       |
| 數值分布             | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090399695_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570204213399_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090422527_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570200972404_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570201010265_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570201067762_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090527841_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090543372_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090763843_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090783580_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090794320_image.png) | ![](https://paper-attachments.dropbox.com/s_16601F5343BC45240F82B9CFE05396CAC65ABFD8D764CAAD3D4D0C3D125E8339_1570090820044_image.png) |
| 長條圖              | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570197029782_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570204726346_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570197081449_image.png) |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570197131901_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570197138779_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570197196033_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570197208713_image.png) |                                                                                                                                       |
| 盜刷數值分布           | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205183142_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205220099_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570204358094_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205253130_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205283112_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205306846_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205328427_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205373830_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205394871_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570205433665_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570203694256_image.png) |                                                                                                                                       |
| 盜刷<br>類別數        | Length: 5                                                                                                                             | Length: 2                                                                                                                             | Length: 4                                                                                                                             | Length: 90                                                                                                                            | Length: 17456                                                                                                                         | Length: 192                                                                                                                           | Length: 200                                                                                                                           | Length: 2                                                                                                                             | Length: 1800                                                                                                                          | Length: 58                                                                                                                            | Length: 3                                                                                                                             |                                                                                                                                       |
| 重要排名             | 5                                                                                                                                     |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       |                                                                                                                                       | 1                                                                                                                                     | 4                                                                                                                                     |
| 盜刷變數重要性<br>(熱度圖) | 0.026                                                                                                                                 | -0.018                                                                                                                                | -0.015                                                                                                                                | -0.012                                                                                                                                | -0.043                                                                                                                                | -0.0028                                                                                                                               | -0.012                                                                                                                                | 0.018                                                                                                                                 | -0.029                                                                                                                                | -0.16                                                                                                                                 | 0.28                                                                                                                                  | 0.034                                                                                                                                 |



## 衍生變數
| 項目               | dttm<br>日期+時間                                                                                                                         | scitocn<br>國家+城市                                                                                                                      | percsmcu<br>金額花費<br>收入族群 | tmm<br>時間<br>6小為一節                                                                                                                    | freq<br>每日刷卡次數 |  |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------- | -------------- |  |
| 型別               | 類別                                                                                                                                    | 類別                                                                                                                                    | 類別                       | 類別                                                                                                                                    | 數值             |  |
| 類別數              | Length: 1298020                                                                                                                       | Length: 5974                                                                                                                          |                          | Length: 4                                                                                                                             |                |  |
| -                | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570200275712_image.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570200868150_image.png) |                          | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570267654665_image.png) |                |  |
| 盜刷變數重要性<br>(熱度圖) | -0.0038                                                                                                                               | -0.13                                                                                                                                 |                          | 0.062                                                                                                                                 |                |  |
| 原欄位<br>重要變數      | 日期-0.012 & 時間-0.043                                                                                                                   | 國家-0.16 & <br>城市-0.029                                                                                                                |                          | 時間-0.043                                                                                                                              |                |  |



# 觀察欄位

參考了上一屆的第一名分析角度
認為衍生欄位非常重要
上一屆有利用指數函數還原原本房價

    像 1000 萬這類整數倍價格會經常出現，是個很重要的觀察
    而事實上 5萬的倍數 (1000萬以下) 與 50 萬的倍數 (1億以下) 也都是，
    把他們轉換後的價格畫在數線上會發現兩個相鄰的價格差距會隨金額增加而遞增，代表是非線性 (若是線性的話原始價格都差5萬，轉換後價格的差距會一樣)
    大概算了一下斜率變化會得知跟 exponential curve 比較相近，但直接去做 curve fitting 又會有誤差
    後來觀察到轉換後的價格有一些竟然是整數，而且很多都是以 96452 結尾的，當下就猜 96452 應為加上去的常數 (其實是196452)，
    扣掉之後再回頭做 curve fitting 答案就呼之欲出了
    其實解這道數學題的主要意義在於，我們假設了某建物的價格分佈為 log normal distribution 作為理論模型，因此需要準確的 total price 來避免誤差



註解:目前認為insfg，ecfg，ovrlt是廢物欄位
         因為當盜刷為1時他都是0
         可以理解成當這個欄位是1的時候基本上不會有盜刷

![](https://paper-attachments.dropbox.com/s_CC3D065EEB9F2FD65EFBE37E9C4F55743A240E206DA1AD7FFA4CEFAB16147A4E_1570201138607_.png)


         這個憨仔被盜刷過4次
         收單行號代碼變了
         contp 交易類別沒有變
         eytmd 交易型態也沒變
         盜刷的stscd只有0,1,2

![](https://paper-attachments.dropbox.com/s_CC3D065EEB9F2FD65EFBE37E9C4F55743A240E206DA1AD7FFA4CEFAB16147A4E_1570202233560_2.png)


這資料也蠻直接的 當我盜刷設成1
stscd設成1的時候
他直接顯示出 stscd= 1 且stocn(消費國別)=102 可以說是百分之百盜刷



## **建德的貼標方法可以嘗試看看**


----------
# **資料圖**
| 資料樣貌                                                                                                                                           | 收單行代碼分布                                                                                                                                      | 重要變數水波圖                                                                                                                                              | 各年收入1年的平均刷卡金額                                                                                                                         | 盜刷重要變數<br>欄位stscd重要                                                                                                                                         |
| ---------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![資料型態大概長這樣](https://paper-attachments.dropbox.com/s_1823FAB7D5B2D658FABE8A2B8F5D087A6CAE945DE34DE4619DB78956A39E83A4_1567829387914_image.png) | ![收單行代碼分布](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1568275000131_acqic.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570177565740_+2019-10-04+16.19.36.png) | ![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570268054383_image.png) | etymd VS fraud<br><br>![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570256871109_image.png) |
|                                                                                                                                                |                                                                                                                                              |                                                                                                                                                      | [來源](https://drive.google.com/drive/folders/1ovzOZZcVfYfhDvzKS_kIKS23fo_wIB7k)                                                        | stscd VS fraud<br><br>![](https://paper-attachments.dropbox.com/s_A03CF54F3055A5ECAA500922BB16DA9984FAAC941F21973A21A4575C30A1DA54_1570256852190_image.png) |




----------
# 盜刷率分析

按消費金額筆數（筆數=account）前500的金額來看，以下為盜刷率超過3%的金額，其中刷1016.34元的盜刷率有30%，其次是814.14元和155.07元
可以試試看把金錢調成布林，盜刷率大於平均（1.34%）是1，其他的是0

    # 某欄位類別的盜刷率篩選，已經寫成活的了，可以每個欄位都丟丟看
    '''col是欄位，可以修改'''
    col="conam"
    col_count=df[col].value_counts()
    '''取前500筆，可以修改'''
    head=500
    bad=[]
    # 取出每個類別值，算出盜刷率
    for i in col_count.index[0:head]:
        find=df[df[col]==i]
        true=find[find.fraud_ind == 1]
        present=len(true)/len(find)
        bad.append(present)
    
    test = pd.DataFrame(columns=["category", "bad_percent","acount"])
    test.category=col_count.index[0:head]
    test.bad_percent=bad
    test.acount=col_count.values[0:head]
    '''  >0.03 取盜刷率d大於3的類別值，可以修改'''
    test[test["bad_percent"]>0.03]
![](https://paper-attachments.dropbox.com/s_3E86DC0C2F8298B3ED8C44A5B802F9E162084D3CA1A4ED9DC29074B1698D409F_1568540310161_image.png)



    import pandas as pd
    
    train_df = pd.read_csv("esun_train.csv",encoding="utf-8")
    test_df = pd.read_csv("test.csv",encoding="utf-8")
    train_df


    train_df = train_df.fillna("N")



    train_df["ecfg"] = train_df["ecfg"].apply(lambda x: 1 if x =='Y' else 0)
    train_df["flbmk"] = train_df["flbmk"].apply(lambda x: 1 if x =='Y' else 0)
    train_df["flg_3dsmk"] = train_df["flg_3dsmk"].apply(lambda x: 1 if x =='Y' else 0)
    train_df["insfg"] = train_df["insfg"].apply(lambda x: 1 if x =='Y' else 0)
    train_df["ovrlt"] = train_df["ovrlt"].apply(lambda x: 1 if x =='Y' else 0)



    project=train_df
    column=["acqic","contp","etymd","mchno","mcc","iterm",
            "scity","stocn","hcefg","csmcu","stscd","locdt","loctm",
            "conam"]
    for col in column:
        '''col是欄位，可以修改'''
    #     col="csmcu"
        col_count=train_df[col].value_counts()
        bad=[]
        # 取出每個類別值，算出盜刷率
        for i in col_count.index:
            find=train_df[train_df[col]==i]
            true=find[find.fraud_ind == 1]
            present=len(true)/len(find)
            bad.append(present)
        cat="category_"+col
        bad_per="bad_percent_"+col
        test = pd.DataFrame(columns=[cat, bad_per])
        test[cat]=col_count.index
        test[bad_per]=bad
        # test.acount=col_count.values
        '''  >0.03 取盜刷率d大於百分之三的類別值，可以修改'''
        #test[test["bad_percent"]>0.03]
        #test.sort_values(by=['bad_percent'],ascending= False)
    
        #train_df["csmcu_bad"]=bad
        project=pd.merge(project,test, how='left',
                         left_on=col,right_on=cat)
    
        project.drop(columns=[cat])
        print(cat)




    project = project.drop(columns=['category_acqic', 'category_contp',
           'category_etymd','category_mchno',  'category_mcc',
           'category_iterm','category_scity',  'category_stocn',
            'category_hcefg','category_csmcu',  'category_stscd',
            'category_locdt','category_loctm',  'category_conam',])
    project.columns


    train_df = train_df.drop(columns=["acqic","contp","etymd","mchno","mcc","iterm",
            "scity","stocn","hcefg","csmcu","stscd","locdt","loctm",
            "conam","bacno","cano","txkey"])
    train_df.columns()


    project.to_csv('esun_train.csv', encoding='utf-8', index=False)



    from sklearn.model_selection import train_test_split
    
    X_train, X_test, y_train, y_test = 
                        train_test_split(train_df.drop(["fraud_ind"],axis=1)
                        , train_df["fraud_ind"], test_size=0.1, random_state=42)



----------
# **演算法**
| 演算法           | Isolation Forest | Random Forest | Decision Tree Classfier |
| ------------- | ---------------- | ------------- | ----------------------- |
| 沒處理           | **0.00014**      | **0.350445**  | **0.452751**            |
| Mean Encoding | **0.500475**     |               |                         |

oneclass svoneclass sv

| 李長榮提建議的檢測異常的模型，目前試了IsolationForest，F1 - score ：0.5<br>以下三種都是非監督式學習，故而只是把test_test帶入計算，就能直接揪出異常點<br><br>資料的處理還是用mean encording ，但是是用train_trian的平均值，test_test NA的數值用該欄位中位數來填 |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ![](https://paper-attachments.dropbox.com/s_0C66310B97772C16EA81DC0FF959B1005CF600C916C2C3590AC1D1684C21430F_1569898632716_image.png)                                       |



----------
## IsolationForest


    from sklearn.ensemble import IsolationForest
    #max_samples=400,森林裡有幾顆樹
    #contamination 要抓出多少比例的異常
    clf = IsolationForest(n_estimators=10, max_samples='auto',
                          n_jobs=-1,contamination=0.015) 
    clf.fit(X_test_test)
    y_pred_train = clf.predict(X_test_test)
    #先看看出來的Y^長啥樣
    pd.Series(y_pred_train).value_counts()
    #Y^是1跟-1，所以要轉換成0跟1
    y_pre_train=y_pred_train
    y_pre_train[y_pre_train==1]=0
    y_pre_train[y_pre_train==-1]=1
    #先看看出來的Y^長啥樣
    pd.Series(y_pre_train).value_counts()
    # 看看f1
    f1_score(y_train, y_pre_train)
    # 混淆矩陣
    matrix=confusion_matrix(y_test,y_pre_train, labels=[1,0])
    matrix
    



https://medium.com/@cyeninesky3/oneclass-svm-%E7%95%B0%E5%B8%B8%E6%AA%A2%E6%B8%AC%E4%BB%BB%E5%8B%99-anomaly-detection-%E7%9A%84%E7%AE%97%E6%B3%95%E7%90%86%E8%A7%A3%E8%88%87%E5%AF%A6%E8%B8%90-cf5f0bbb01c0

----------
## Random Forest

找出最佳參數  n_estimators、max_depth

    from sklearn.ensemble import RandomForestClassifier
    from sklearn.model_selection import GridSearchCV
    clf = RandomForestClassifier()
    grid = {
        "n_estimators":range(25, 35, 1),
        "max_depth":range(6, 10)
    }
    gridsearch = GridSearchCV(clf, param_grid=grid, cv=10, n_jobs=8)
    gridsearch.fit(data_train, target_train)
    gridsearch.best_params_

計算模型成效

    from sklearn.model_selection import cross_val_score
    import numpy as np
    clf = RandomForestClassifier(n_estimators=31, max_depth=9)
    scores = cross_val_score(clf, data_train, target_train, cv=10)
    print("十次:", scores)
    print("平均:", np.average(scores))

Train Model

    clf = RandomForestClassifier(n_estimators=31, max_depth=9)
    clf.fit(data_train, target_train)

f1 socre

    from sklearn.metrics import f1_score
    # f1 score
    pre = clf.predict(data_test)
    f1 = f1_score(target_test, pre)
    print(f1)

輸出結果

    result = pd.DataFrame()
    pid = test_df["txkey"].astype(int)
    pre = clf.predict(test)
    result["txkey"] = pid
    result["fraud_ind"] = pre
    # result.to_csv("esun_RandomForest.csv", index=False)
    result


----------
## DecisionTreeClassfier

Train Model

    from sklearn.tree import DecisionTreeClassifier
    clf = DecisionTreeClassifier(max_depth = 15 , min_samples_leaf = 20)
    clf = clf.fit(data_train,target_train)

畫決策樹

    import graphviz
    dot_data = export_graphviz(clf,out_file=None,
                               feature_names=x_train.columns,
                               class_names=["NO","YES"],
                               filled=True,rounded=True,
                               special_characters=True)
    graph = graphviz.Source(dot_data)
    from sklearn.tree import export_graphviz
    graph

accuracy score

    from sklearn.metrics import accuracy_score
    pre = clf.predict(data_test)
    print("accuracy score : ", accuracy_score(target_test,pre)* 100, "%")

f1 score

    from sklearn.metrics import f1_score
    f1 = f1_score(target_test, pre)
    print("F1 score : ",f1)

輸出結果

    result = pd.DataFrame()
    pid = test_df["txkey"].astype(int)
    pre = clf.predict(test)
    result["txkey"] = pid
    result["fraud_ind"] = pre
    result.to_csv("esun_Decision.csv", index=False)
    result


----------
# **lightgbm**
    import pandas as pd
    
    train_df = pd.read_csv("train.csv",encoding="utf-8")
    test_df = pd.read_csv("test.csv",encoding="utf-8")
    train_df = train_df.fillna("N")
    test_df = train_df.fillna("N")
    # ValueError: DataFrame.dtypes for data must be int, float or bool.
    # Did not expect the data types in fields ecfg, flbmk, flg_3dsmk, insfg, ovrlt
    train_df["ecfg"] = train_df["ecfg"].apply(lambda x: 1 if x =='Y' else 0)
    train_df["flbmk"] = train_df["flbmk"].apply(lambda x: 1 if x =='Y' else 0)
    train_df["flg_3dsmk"] = train_df["flg_3dsmk"].apply(lambda x: 1 if x =='Y' else 0)
    train_df["insfg"] = train_df["insfg"].apply(lambda x: 1 if x =='Y' else 0)
    train_df["ovrlt"] = train_df["ovrlt"].apply(lambda x: 1 if x =='Y' else 0)
    test_df["ecfg"] = test_df["ecfg"].apply(lambda x: 1 if x =='Y' else 0)
    test_df["flbmk"] = test_df["flbmk"].apply(lambda x: 1 if x =='Y' else 0)
    test_df["flg_3dsmk"] = test_df["flg_3dsmk"].apply(lambda x: 1 if x =='Y' else 0)
    test_df["insfg"] = test_df["insfg"].apply(lambda x: 1 if x =='Y' else 0)
    test_df["ovrlt"] = test_df["ovrlt"].apply(lambda x: 1 if x =='Y' else 0)



    import json
    import lightgbm as lgb
    import pandas as pd
    from sklearn.metrics import mean_squared_error
    from sklearn.datasets import load_iris
    from sklearn.model_selection import train_test_split
    from sklearn.datasets import  make_classification
    
    
    
    # 加載數據
    
    X_train, X_test, y_train, y_test = train_test_split(
        train_df.drop(['fraud_ind'], axis=1), train_df[['fraud_ind']], test_size=0.3)
    
    # 要符合lgb的數據格式
    lgb_train = lgb.Dataset(X_train, y_train)
    lgb_eval = lgb.Dataset(X_test, y_test, reference=lgb_train)
    
    # 參數以字典形式編寫
    params = {
        'task': 'train',
        'boosting_type': 'gbdt',  
        'objective': 'regression', 
        'metric': {'l2', 'auc'},  
        'num_leaves': 31,   
        'learning_rate': 0.05, 
        'feature_fraction': 0.9, 
        'bagging_fraction': 0.8, 
        'bagging_freq': 5,  
        'verbose': 1 
    }
    
    print('Start training...')
    # 訓練 cv and train
    gbm = lgb.train(params,lgb_train,num_boost_round=20,valid_sets=lgb_eval,early_stopping_rounds=5)
    
    print('Save model...')
    # 保存模型
    gbm.save_model('model.txt')
    
    print('Start predicting...')
    # 預測數據
    y_pred = gbm.predict(X_test, num_iteration=gbm.best_iteration)
    # 評估模型
    print('The rmse of prediction is:', mean_squared_error(y_test, y_pred) ** 0.5)
    




# **參考資料區**
| 上一屆第一名GitHub              | https://github.com/GitYCC/tbrain_esun_house_price_predict/       |
| ------------------------- | ---------------------------------------------------------------- |
| 上一屆T-brain討論區             | https://tbrain.trendmicro.com.tw/Discussion/Forum/7              |
| Boosting演算法優缺比較(有提到演算法差異) | https://codertw.com/%E7%A8%8B%E5%BC%8F%E8%AA%9E%E8%A8%80/510420/ |


