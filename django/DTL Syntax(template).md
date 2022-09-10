# DTL Syntax(template)

: django template에서 사용하는 built-in template system

- Variable

  ```python
  {{ variable }}
  ```

  - render()를 사용하여 views.py에서 정의한 변수를 template 파일로 넘겨 사용하는 것
  - _로 시작 할 수 없다. 공백이나 (.)도 불가
  - dot(.)를 사용하여 변수 속성에 접근 가능
  - render()의 세번째 인자로 {'Key': value}와 같이 딕셔너리 형태로 넘겨주며, Key값이 변수명이 된다.

- Filters

  ```python
  {{ variable|filter }}
  ```

  - 변수를 수정 ex) |lower, |truncatewords:30 

- Tags

  ```python
  {% tag %}
  ```

  - 출력 텍스트를 만들거나, 반복 또는 논리를 수행하여 제어 흐름을 만든다.

  - ex) 

    ```python
    {% if %}{% endif %}
    ```

- Comments

  ```python
  {# #} #한줄
  {% comment %} # 여러 줄
  {% endcomment %}
  ```

  - 주석