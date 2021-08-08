- enumerate

리스트를 순회하면서 index값을 같이 출력하는 내장 함수

```python
members = ['민수', '영희', '철수']
```

```python
for idx, member in enumerate(members):
    print(idx, member)
```

0 민수

1 영희

2 철수

```python
list(enumerate(members))
```

[(0, '민수'), (1, '영희'), (2, '철수')]

```python
list(enumerate(members, start=1)) # start를 지정하면 인덱시 시작값을 정할 수 있다.
```

[(1, '민수'), (2, '영희'), (3, '철수')]