# URL

### Dispatcher(발송자, 운항 관리자)로서의 URL

- ##### URL 주소를 변수로 사용하는 것

- ##### URL의 일부를 변수로 지정하여 view 함수의 인자로 넘길 수 있음

```python
path(‘/accounts/user/<int:user_pk>/’, …)
# accounts/user/1 → (1번 user 관련 페이지)
# accounts/user/2 → (2번 user 관련 페이지)
```

