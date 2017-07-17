# Original-Regexpal
regpal 0.1.4 — a JavaScript regular expression tester（汉化版）
# regex_pattern
正则表达式校验各种字符串的语法库
### 正则语法校验工具 [RegexTool](http://regex.gioov.net)
- `/.+/` // 判断是否已输入
- `/^1{1}[0-9]{10}$/` //  匹配大陆手机号码，匹配实例：18869923333
- `/^(https?://)?(\w+\.)+[a-zA-Z]+$/` // 匹配全部可能 加 `http:// https://`  或 未加 `http:// https://`，匹配实例：http://www.gioov.com ，www.gioov.com
- `/^(\w+\.)+[a-zA-Z]+$/` // 匹配未加 `http://` 或 `https://`，匹配实例：www.gioov.com
- `/^(https?://)+(\w+\.)+[a-zA-Z]+$/` // 匹配只加 `http://` 或 `https://`，匹配实例：https://www.gioov.com
- `/^[1-9]{1}[0-9]{4,10}$/` // 匹配qq号码，匹配实例：1176394803
- `/^\w+(\.\w+)?@\w+.+[a-zA-Z]$/` // 匹配email，匹配实例：godcheese@qq.com
- `/^\d+$/` // 匹配数字，匹配实例：12

 // 判断语言
- `/^[\u2E80-\u9FFF]+$/` // 匹配汉字，其中`\u2E80-\u9FFF`为汉字unicode内码编码区间，匹配实例：中国
- `/^[a-zA-Z]$/` // 匹配英文字母，匹配实例：abc

// 其它
- `/^[初|高][一|二|三]（[1-9][0-9]*）班$/u` // 匹配中学班级，匹配实例：高（2）班
- `/^[一|二|三|四|五|六]（[1-9][0-9]*）班$/u` // 匹配小学班级，匹配实例：六（1）班
