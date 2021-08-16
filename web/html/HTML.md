# HTML

### Hyper Text Markup Language

- Hyper: 텍스트 등의 정보가 동일 선상에 있는 것이 아니라 다중으로 연결되어 있는 상태

- Hyper Text: 참조(하이퍼 링크)를 통해 사용자가 한 문서에서 다른 문서로 즉시 접근할 수 있는 텍스트



### 구글 효과

-정보접근이 가능한 컴퓨터가 있는 경우, 인간은 정보 자체를 기억하려하기 보다 오히려 정보를 저장한 곳을 기억 하려 함

\- 사람들은 컴퓨터를 가장 중요한 정보 수집원으로 활용하며 이를 활용할 경우 주변인과 대화가 줄어드는 경향을보임

\- 인간은 찾기 쉬운 정보일수록 더욱 기억하지 못하는 경향이 있음



### 기본 구조

```html
<!DOCTYPE html>
<html lang="en">
    
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
    
<body>
  <h1>목적은 정보를 보여주기 위함</h1>
  
  <form action="">
    이름<input type= "text">
    지역<input type= "date">
    온도<input type= "password">

  </form>
</body>
</html>
```

- !+tab 부분: root

- head와 body 부분으로 구분
  - head : 문서 제목, 문자 코드(인코딩) , css선언, 외부로딩 파일 지정 | 브라우저에 나타나지 않음
  - body: 브라우저 화면에 나타나틑 정보호 실제 내용에 해당