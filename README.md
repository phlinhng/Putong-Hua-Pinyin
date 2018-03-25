# Putong Hua Pinyin 新普通話拼音
漢語拼音方案設計簡潔縝密，然其為追求書寫方便而失去了一些發音特徵，用於拼寫國人之姓名時難免訛誤。  
本方案以漢語拼音為藍本，參酌通用拼音、國語羅馬字、注音二式、WG拼音、耶魯拼音等華語拼音方案制定，供各界人士拼寫漢字時參考。本人非語言專業，懇請先進批評指教。  
  
**Putong-Hua-Pinyin** (PH-Pinyin) is a romanization system modified from Hanyu-Pinyin for spelling Modern Mandarin, which can fix some unambiguous sound when non-native Mandarin speaker trying to pronounce Mandarin.

# PH拼音對照表   
* ＰＨ: Putung-Hua Pinyin  
* 汉拼: Hanyu Pinyin
## 聲母 Consonants
| | | | | | | | | | | | | | | |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|**注音**|ㄅ|ㄆ|ㄇ|ㄈ|ㄉ|ㄊ|ㄋ|ㄌ|ㄍ|ㄎ|ㄏ|ㄐ|ㄑ|ㄒ
|**汉拼**|b|p|m|f|d|t|n|l|g|k|h|j|q|x
|**ＰＨ**|b|p|m|f|d|t|n|l|g|k|h|j|ch|s
|**注音**|ㄓ|ㄔ|ㄕ|ㄖ|ㄗ|ㄘ|ㄙ|ㄧ|ㄨ|ㄩ
|**汉拼**|zh|ch|sh|r|z|c|s|y|w|ü
|**ＰＨ**|zh|ch|sh|r|z|ts|s|y|w|yu

## 單韻母 Single Vowels
| | | | | | | | | | |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|**注音**|ㄧ|ㄨ|ㄩ|ㄚ|ㄛ|ㄜ|ㄝ|ㄦ|ㄭ
|**汉拼**|i|u|ü|a|o|e|ê|er|i
|**ＰＨ**|i|u|**eu**|a|o|e|e|er|**j** 
* ㄨㄩ變化規則見「結合韻母」

## 複韻母 Compound Vowels
| | | | | | | | | |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|**注音**|ㄢ|ㄣ|ㄤ|ㄥ|ㄞ|ㄟ|ㄠ|ㄡ|
|**汉拼**|an|en|ang|eng|ai|ei|ao|ou
|**ＰＨ**|an|en|ang|eng|ai|ei|ao|ou

## 結合韻母 Compound/Final Vowels
| | | | | | | | | | | | | |
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:| :----:| :----:|
|**注音**|ㄧㄝ|ㄩㄝ|ㄧㄢ|ㄨㄢ|ㄩㄢ|ㄧㄣ|ㄨㄣ|ㄩㄣ|ㄧㄥ|ㄨㄥ|ㄨㄥ|ㄩㄥ
|**汉拼**|ie|üe|in|uan|üan|in|un|ün|ing|eng|ong|iong
|**ＰＨ**|ie|**iue**|**ien**|**wan**|uan|in|**uen**|**eun**|ing|eng|ong|**ung**
* 翁weng 同tung

## 例外規則 Exceptions
席ㄒㄧ xi  
謝ㄒㄧㄝ  xie  
熊ㄒㄩㄥ  siung

# 與漢語拼音方案比較 Difference with Hanyu Pinyin
1. 不用**ê,ü**這兩個帶裝飾的字母，儘量減少使用英文少見的字首**q**,**x**  
Remove **ê** and **ü** which are not basic Latin alphabet and reduce usages of **q** and **x** which are rarely used as the first capital in English.
2. 恢復縮寫。 **-iu** → **-iou** , **-un** → **-uen**  
Recover some simplified rules in Hanyu Pinyin. **-iu** → **-iou** , **-un** → **-uen** 
3. 歸併音位：**ㄑ/ㄔ** → **ch**，**ㄒ/ㄙ** → **s**。由於**ㄐㄑㄒ**後面永遠接**ㄧㄩ**，**ㄓㄔㄕ**後面永不接**ㄧㄩ**，這麼做並不會有拼音衝突。 
Combine ㄑ/ㄔ and ㄒ/ㄕ respectively, since **ㄑㄒ** always come with **ーㄨ** and **ㄔㄕ** never come with **ーㄨ** they will not conflict with each other. eg. 七Chi 吃Chih
4. **ㄘ** → **ts** (國羅, _Gwoyeu Romatzyh_), **ㄑ** → **ch**(_Wade-Giles_), **ㄒ** → **hs**(_Wade-Giles_)  
5. **ㄩ** → **eu** , **ㄩㄥ** → **ung** , **空韻i** → **j** 
6. 根據注音規則，ㄧㄢ應唸作ien，拼法從之(_Wade-Giles_)。  
Adjust some compound vowels. Check "結合韻母 Compound/Final Vowels" for details.

# 範例 Example
* 以下範例不標音調。

中文：井水不犯河水  
漢拼：Jing Shui Bu Fan He Shui  
ＰＨ：Jing Shuei Bu Fan He Shuei  
  
中文：區塊鏈技術的應用與未來  
漢拼：Qu Kuai Lian Ji Shu De Ying Yong Yu Wei Lai  
ＰＨ：Cheu Kuai Lien Ji Shu De Ying Yung Yu Wei Lai  
  
中文：東邊日出西邊雨，道是無晴卻有晴。  
漢拼：Dong Bian Ri Chu Xi Bian Yu, Dao Shi Wu Qing Que You Qing.  
ＰＨ：Dong Bien Rj Chu Xi Bien Yu, Dao Shj Wu Ching Chiue You Ching.  
 
中文：君不見高堂明鏡悲白髮朝如青絲暮成雪  
漢拼：Jun Bu Jian Gao Tang Ming Jing Bei Bai Fa Zhao Ru Qing Si Mu Cheng Xue   
ＰＨ：Juen Bu Jien Gao Tang Ming Jing Bei Bai Fa Zhao Reu Ching Sj Mu Cheng Siue

中文：青青河畔草，鬱鬱園中柳。  
漢拼：Qing Qing He Pan Cao, Yu Yu Yuan Zhong Liu.  
ＰＨ：Ching Ching He Pan Tsao, Yu Yu Yuan Zhong Liou.  
  
中文：願君多採擷，此物最相思。  
漢拼：Yuan Jun Duo Cai Jie, Ci Wu Zui Xiang Si.  
ＰＨ：Yuan Juen Duo Tsai Jie, Tsj Wu Zuei Siang Sj.

# 感謝 Sepcial Thanks to
感謝PTT站友**Thirdshadow**在編寫過程提供的寶貴意見。  
  
目前版本 Current Version: 3.4  
本文最後編寫時間: Mar-25-2018 02:09PM (UTC+8)
