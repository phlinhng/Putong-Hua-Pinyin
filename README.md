# Putong Hua Pinyin 新普通話拼音
漢語拼音方案設計簡潔縝密，然其為追求書寫方便而失去了一些發音特徵，用於拼寫國人之姓名時難免訛誤。  
本方案參考漢語拼音、通用拼音、國語羅馬字、注音二式、WG拼音、耶魯拼音等華語拼音方案，供各界人士拼寫漢字時參考。本人非語言專業，懇請先進批評指教。  
  
**Putong-Hua-Pinyin** (PH-Pinyin) is a romanization system modified from Hanyu-Pinyin for spelling Modern Mandarin, which can fix some unambiguous sound when non-native Mandarin speaker trying to pronounce Mandarin.

# PH拼音與注音對照表
## 聲母
| | | | | | | | | | | | | | | |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|**注音**|ㄅ|ㄆ|ㄇ|ㄈ|ㄉ|ㄊ|ㄋ|ㄌ|ㄍ|ㄎ|ㄏ|ㄐ|ㄑ|ㄒ
|**ＰＨ**|b|p|m|f|d|t|n|l|g|k|h|j|ch|sh
|**注音**|ㄓ|ㄔ|ㄕ|ㄖ|ㄗ|ㄘ|ㄙ|ㄧ|ㄨ|ㄩ
|**ＰＨ**|zh|ch|sh|r|z|ts|s|y|w|yu

## 單韻母
| | | | | | | | | | |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|**注音**|ㄧ|ㄨ|ㄩ|ㄚ|ㄛ|ㄜ|ㄝ|ㄦ|ㄭ
|**ＰＨ**|i|u|yu|a|o*|e|eh|er|ih 
* ㄅㄛbuo ㄆㄛpuo ㄇㄛmuo

## 複韻母
| | | | | | | | | |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|**注音**|ㄢ|ㄣ|ㄤ|ㄥ|ㄞ|ㄟ|ㄠ|ㄡ|
|**ＰＨ**|an|en|ang|eng*|ai|ei|ao|ou
* 和ㄅㄆㄇㄈ結合時寫作ong
## 結合韻母
| | | | | | | |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|**注音**|ㄧㄣ|ㄨㄣ|ㄩㄣ|ㄧㄥ|ㄨㄥ|ㄩㄥ
|**ＰＨ**|in|uen|yun|ing|ong|iong
### 關於ㄩㄣ和ㄩㄥ的說明
* ㄩ=ㄧ(y/i)+ㄨ(u) = yu/iu  
* ㄩㄣ=ㄩ(yu)+ㄣ(n) = yun  
* ㄩㄥ=ㄩ(iu)+ㄥ(ng) = iung -> iong

# 與漢語拼音方案比較 Difference from Hanyu Pinyin
1. 不用**ê,ü**這兩個帶裝飾的字母，也不用英文少見的字首**q**,**x**  
Remove **ê** and **ü** which are not basic Latin alphabet and **q** and **x** which are rarely used as the first capital in English.
2. 取消縮寫以維持發音。漢語拼音有縮寫規則以求行文流暢，PH拼音只做為輔助發音故保持全寫。  
Cancel simplified rule in Hanyu Pinyin. Remain **-iu** and **-un** as **-iou-** and **-uen**
3. **ㄑㄒ**和**ㄔㄕ**共用**ch,sh**，由於**ㄐㄑㄒ**後面永遠接**ㄧㄩ**，**ㄓㄔㄕ**後面永不接**ㄧㄩ**，這麼做並不會有拼音衝突。  
Use **ch** and **sh** to represent both **ㄑ/ㄔ** and **ㄒ/ㄕ** respectively, since **ㄑㄒ** always come with **ーㄨ** and **ㄔㄕ** never come with **ーㄨ** they will not conflict with each other. eg. 七Chi 吃Chih 西Shi 師Shih
4. **ㄘ**改為**ts**（國羅）  
Change alphabet of **ㄘ** to **ts**（_Gwoyeu Romatzyh_）
5. **ㄩ**改為**yu**（漢拼草案），**ㄝ**改為**eh**（威妥瑪），空韻使用**ih**（國羅）  
Change alphabet of **ㄩ** to **yu** (_early draft of Hanyu pinyin_), **ㄝ** to **eh** (_Wade–Giles_), **ㄭ** (minimal vowel of ㄓ,ㄔ,ㄕ,ㄖ,ㄗ,ㄘ,ㄙ) to **ih** (_Gwoyeu Romatzyh_) 
6. 增加**ㄅㄆㄇ+ㄛ**時補ㄨ的規則，以符合台灣人實際發音習慣。  
**bo** **po** **mo** should be spell as **buo** **puo** **muo** to fix the missing "u" sound
7. 增加**ㄅㄆㄇㄈ+ㄥ**時轉寫為**bpmf+ong**的規則，理由同第6點。  
**beng** **peng** **meng** **feng** should be spell as **bong* **pong** **mong** **fong** for adjustment

# 與通用拼音的比較
1. **ㄑㄒ**和**ㄔㄕ**共用**ch,sh**，由於**ㄐㄑㄒ**後面永遠接**ㄧㄩ**，**ㄓㄔㄕ**後面永不接**ㄧㄩ**，這麼做並不會有拼音衝突
2. **ㄐㄑㄒ**不使用通拼的**ji,chi,shi**方式，因此沒有如囧**jiong/jyong**的變化規則  
3. **ㄓ**用漢拼的**zh**而不用通拼的**jh**

# 範例
* 標注調號的方案沒有研究，因此以下範例均不標。

中文：井水不犯河水  
漢拼：Jing Shui Bu Fan He Shui  
ＰＨ：Jing Shuei Bu Fan He Shuei  
  
中文：區塊鏈技術的應用與未來  
漢拼：Qu Kuai Lian Ji Shu De Ying Yong Yu Wei Lai  
ＰＨ：Chyu Kuai Lian Ji Shu De Ying Yong Yu Wei Lai  
  
中文：為愛付出瘋狂/為夢受一點傷  
漢拼：Wei Ai Fu Chu Feng Kuang / Wei Meng Shou Yi Dian Shang  
ＰＨ：Wei Ai Fu Chu Fong Kuang / Wei Mong Shou Yi Dian Shang  
  
中文：東邊日出西邊雨，道是無晴卻有晴。  
漢拼：Dong Bian Ri Chu Xi Bian Yu, Dao Shi Wu Qing Que You Qing.  
ＰＨ：Dong Bian Rih Chu Shi Bian Yu, Dao Shih Wu Ching Chyueh You Ching.  
  
中文：青青河畔草，鬱鬱園中柳。  
漢拼：Qing Qing He Pan Cao, Yu Yu Yuan Zhong Liu.  
ＰＨ：Ching Ching He Pan Tsao, Yu Yu Yuan Zhong Liou.  
  
中文：願君多採擷，此物最相思。  
漢拼：Yuan Jun Duo Cai Jie, Ci Wu Zui Xiang Si.  
ＰＨ：Yuan Jyun Duo Tsai Jieh, Tsih Wu Zuei Shiang Sih.
