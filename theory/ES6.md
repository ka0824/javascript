## ES6

> ### 화살표 함수

```

() => console.log('hi');

```

> ### 클래스 / class

상속 개념을 가진 객체를 만듬.

```
class Test {
  constructor() {
    this.text = 'hi';
  }
}

const example = new Test;
console.log(example) /// Test {text: "hi"}

```

> ### 템플릿 문자열 / 백틱(``)의 사용
<br/>

> ### 비구조화 / destructuring
<br/>

> ### spread syntax
<br/>

> ### let, const
<br/>

> ### for...of
<br/>

> ### import, export 문
<br/>

> ### Map, Set, WeakMap, WeakSet
<br/>

- Map  
순서를 기억하는 객체 형태
key로 문자열 대신 다른 타입도 할당 가능

- Set  
중복된 값이 없는 배열 형태

- WeakMap   
key로 객체만 받는 Map
기존 객체를 약한 참조해서 메모리 누수를 방지함(?)  <= 이해 필요

- WeakSet  
객체만 값으로 받는 Set
기존 객체를 약한 참조해서 메모리 누수를 방지함(?)  <= 이해 필요
<br/>

> ### Symbol 타입
유일한 값을 가지는 원시타입, html에서의 key 역할

<br />

> ### promise
비동기 처리를 할 때에 사용.
.then()으로 정상적으로 처리 됐을 때에 리턴되는 값을 계속 이어서 사용 가능


