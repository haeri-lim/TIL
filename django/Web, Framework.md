# Web

### Static web page(정적 웹 페이지)

- 미리 저장된 파일이 모든 사용자에게 똑같이 그대로 전달되는 웹페이지
- HTML, CSS, JavaScript롷 작성됨



### Dynamic web page(동적 웹 페이지)

- 서버가 추가적인 처리 과정 이후 클라이언트에게 응답을 보냄
- 사용자와 상호작용하기 때문에 페이지 내용은 그때그때 다르다.
- python, java, c++ 사용, DB와 상호작용함



---

# Framework

### Framework

- 프로그래밍에서 특정 운영 체제를 위한 응용프로그램 표준 구조를 구현하는 클래스와 라이브러리 모임
- 재사용할 수 있는 수많은 코드를 프레임워크로 통합하여 개발자가  새로운 애플리케이션을 위한 표준코드를 다시 작성하지 않아도 가능하게 도와줌

### Web framework

- 웹페이지를 개발하는 과정에서 겪는 어려움을 줄이는 것이 주목적



### Framework Architecture

- 사용자 인터페이스로부터 프로그램 로직을 분리하여 애플리케이션을 서로 영향없이 쉽게 고칭수 있도록함
- MTV Pattern(Django) , MVC(c: controller)
  - Model : 데이터 구조 정의, DB 기록을 관리(추가, 수정, 삭제)
  - Template : 파일의 구조나 레이아웃을 정의(보여주는 화면)
  - View : HTTP 요청을 수신하고 HTTP 응답을 반환 | Model을 통해 요청을 충족시키는데 필요한 데이터에 접근| template에게 응답의 서식 설정을 맡김 