# position

- static
  - 일반적인 요소의 배치 순서에 따름(좌측 상단)
  - 부모 요소 내에서 배치될때는 부모 요소의 위치를 기준으로 배치



top, bottom, left, right 를 이용해서 이동 가능하다

- relative: 상대위치
  - 자기 자신의  static 위치를 기준으로 이동
- absolute: 절대 위치
  - static과 투명하지만 다른 층에 있다고 생각하면 relative 차이점을 알 수 있다. 
  - static 이 아닌 가장 가까이 있는 부모/조상 요소를 기준으로 이동(없는 경우는 body에 붙는 형태)
- fixed: 고정 위치
  - viewport 기준으로 이동
  - 스크롤시에도 항상 같은 곳에 위치함