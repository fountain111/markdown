# SRILM 统计语言模型

    生成count统计信息
    ngram-count -vocab segment_dict.txt -text train_data -order 3 -write my.count -unk 
    
    生成语言模型lm
    ngram-count -read my.count -order 3 -lm train.lm -interpolate 
    
    segment_dict.txt 是词典 ，一行代表一个分词(thchs30有两列，在做词典时，ngram会自动取第一列)
    train_data 是整个语料 ，一行行语料，用空格区分词
    
    词典分汉字词典、音素词典，
    
    要训练音素词典 segment_dict 和train_data 使用音素即可

## 根据thchs30的语料，重新制作phone和word的语言模型
### word 
	Required : lexicon.txt ,train_data(训练语料)
    利用dacidian的词典进行训练.
### phone
	Required :lexcion.txt，train_data 
    音素字典和音素级语料
    
搜集

    
    
    
    
	
