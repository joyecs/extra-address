# extra-address
从string里找出地址信息，返回json格式数据. 包含了中国的所有地址信息。
背景信息：
客户上传快递单的Excel文件，从excel里面提取出地址信息，省市路等信息顺序不定，但是中间有空格隔开。
需要分析信息哪个是省份，哪个是城市等， 返回格式： 
{
  "province": "xxx",
  "city": "xxx",
  "street": "xxx",
  ....
}
