- #### f-strings

```python
print(f'hello {name:>10s} {score:.3f}')

'''
왼쪽정렬    : {문자:10s}
가운데 정렬  : {정수:^10d}
오른쪽 정렬  : {실수:>10f}

'''

import datetime
today = datetime.datetime.now()
print(f'오늘은 {today:%y}년 {today:%m}월 {today:%d}일 {today:%A}')
```

