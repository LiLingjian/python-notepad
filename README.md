# python-notepad
- 将文本类型的list转为list
```
import json

str_list = "[11.23,23.34]"
list_list = json.loads(str_list)
print(type(list_list))

```
