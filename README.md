以下收集均为java匹配表达式，若用其他语言有些符号可能需要考虑是否转义。

## 匹配两个符号中间的内容
  例如：text'hello'haha     
  匹配表达式：(?<=').*(?=')    
  匹配结果： 
  hello  
    
  例如：【业务场景定义】\n#license：【牌照方】     
  匹配表达式：(\\【[^\\】]*\\】)    
  匹配结果：  
  业务场景定义
  牌照方
