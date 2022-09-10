# HTML 'form' element

### 사용자로부터 할당된 데이터를 서버로 전송하는 역할을 담당

- ##### action : 입력 데이터가 전송될 URL 지정

- ##### method : 입력 데이터 전달 방식 지정



- ##### input : 사용자로 부터 데이터를 입력 받음

  - name : 중복가능, 양식을 제출했을 때 name이라는 이름에 설정된 값을 넘겨서 값을 가져올수 있음

    ​			GET/POST 방식으로 서버에 전달하는 파라미터(name == key, value == value) 

    ​			?key=value&key=value 형태로 전달

- ##### label : 사용자 인터페이스 항목에 대한 설명(caption)을 나타냄

  - input에 id 속성 부여
  - label에는 input의 id 와 동일한 값의 for 속성이 필요

- ##### for : for 속성의 값과 일치하는 id를 가진 문서의 첫 번째 요소를 제어

  - labelable elements : label 요소와 연결할 수 있는 요소(not hidden type), select, textarea

- ##### id : 전체문서에서 고유해랴 하는 식별자를 정의, linking, scripting, styling 시 요소를 식별

  
