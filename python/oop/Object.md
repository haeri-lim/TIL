### Object

---



#### **파이썬는 모두 객체로 이뤄져있다.**

#### **객체는 특정 타입의 인스턴스이다.**



- 객체
  - 타입
  - 속성(attribute)
  - 조작법(method)



- is

  객체의 아이엔티티를 검사하는 연산자

- isinstance(object, classinfo)

  - classinfo가 instance거나 subclass인 경우 True
  - classinfo가 tuple인경우 하나라도 일치하면 True
  - classinfo가 type이거나 type으로 구성되지 않은 경우 typerror



- 클래스[객체들의 분류] 정의

  class MyClass:

- 인스턴스[실체] 생상

  my_instance = MyClass()

- 매서드 호출

  my_instance .my_method()

- 속성

  my_instance .my_attribute