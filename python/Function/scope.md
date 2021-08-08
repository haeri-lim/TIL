- Local scope 

함수

- Enclosed scope

특정 함수의 상위 함수

- Global scope

함수 밖의 변서, import 모듈

- Built-in  scope

파이썬 안에 내장되어 있는 함수 또는 속성



```python
global # local scope에서 grobal 변수 값을 변경, 이미 존재하지 않는 변수도 가능
```

```python
nonlocal 
# 전역을 재외하고 가장 가까운 scope 변수를 연결함, global과는 달리 이미 존재하는 이름만 가능 
# 매겨변수, for 루프 대상, 클래스/함수 정의등으로 덩의되면 안됌
```

