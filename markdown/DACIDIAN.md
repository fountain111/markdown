# 大词典 AISHELL的定义
## layer-1 word ->拼音(音节、syllabel)

	word和发音（拼音）用tab分割
    
    多个发音用;分号分割
    
    每个发音是拼音序列,包含音调,用空格分割
    
    tone,声调分为0,1,2,3,4 5个调， 
    
    任何人都可以往这个词典里添加内容，符合上述格式即可
    
   ### 例子
    
    ...
    裤子    KU_4 ZI_0
    好事    HAO_4 SHI_4;HAO_3 SHI_4
    教授    JIAO_1 SHOU_4;JIAO_4 SHOU_4
    ...
    语音识别  YU_3 YIN_1 SHI_2 BIE_2
    傅里叶变换 FU_4 LI_3 YE_4 BIAN_4 HUAN_4
    
    
   
   
   ## layer-2 拼音（音节,syllabel）->音素(phone)
    syllabel ->phone
    syllable and its phoneme representation are seperated by tab
	$0 is the NULL-Initial phone.
  
   ### 暂不考虑英文、中英文混杂、方言等情况
   
 