# CSS

### Cascading Style Sheets

```html
h1(선택자){
	color: blue;(선언)
	font-size(속성): 15px;(값)
}
```



- 인라인

  - 해당 태그에 직접 style 속성을 활용

    ```html
    <h1 style="color:blue; font-size: 15px;">Hello</h1>
    ```

- 내부 참조(embedding)

  - head 태그 내에 아래 처럼 지정

    ```html
    h1(선택자){
    	color: blue;(선언)
    	font-size(속성): 15px;(값)
    }
    ```

- 외부 참조(link file)- 분리된 CSS 파일

  ```html
  <link rel="stylesheet" href="mystyle.css">
  ```

