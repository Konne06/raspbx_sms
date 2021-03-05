# raspbx_sms
适配分机账户的短信规则
·当向国内“1”开头的号码发送短信时直接发送会自动适配国号（原始dongle命令原始发短信必须加国号），即不需要添加国号。

  1开头号码指所有中国大陆的1开头号码，包括10086，130，132，139。。。等等等

·当向国内其他开头的号码发送短信时需要手动添加国号

  如95开头的客服号码，发送短信时需加国号

·当发送国际短信时，只需正常添加国号即可

  如美国+1，韩国+82等


*dongle命令发送短信时，超过140个字符（70个汉字）将无法发出。
 当不按照上述规则正确添加国号时，短信将无法发出。
