# Template inheritance(템플릿 상속)

- 코드 재사용성에 초점을 맞춰서 사이트의 모든 공총 요소를 포함, 하위 템플릿이 재정의(override) 할 수 있는 블록을 정의하는 기본 'skeleton' 템플릿을 만들 수 있음



```python
{% block content %} {% endblock%}
```

- 하위 템플릿에서 재지정(overriden) 할 수 있는 블록을 정의



```python
{% extends '' %}
```

- 자식 템플릿이 부모 템플릿을 확장한다는 것을 알림



app_name/templates { 'DIRS' : [BASE_DIR / 'templates'] } 경로 설정