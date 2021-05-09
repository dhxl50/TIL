# HTML Basic
HTML의 모든 내용을 담고있지는 않으며, 복습한 내용들만 간단히 작성하였다.

## 1. DOM
문서 객체 모델(Document Object Model, DOM)은 구조화된 문서를 표현하는 방식이다.

Javascript와 같은 프로그래밍 언어를 이용하면, DOM 객체에 접근하여 HTML 문서의 요소들을 제어할 수 있다.

## 2. Tag and Element
**Tag**는 *`<a>`*, *`</a>`*, *`<div>`*, *`</div>`* 와 같이 괄호로 둘러쌓인 부분을 말하며, 시작 태그(여는 태그)와 끝 태그(닫는 태그)로 구분된다.

**Element**는 시작태그 + 내용(content) + 끝태그를 모두 합친 것을 의미한다.

또한, *<br/>*과 같은 빈 요소도 Element이다.

## 3. Block and Inline element
Element에는 **블록(block)** 타입 요소와 **인라인(inline)** 타입 요소가 있다.
- Block 타입 요소
 - 항상 새로운 라인에서 시작한다.
 - 해당 라인의 모든 너비를 차지한다.
 - 대표적인 태그로는 `<div>`, `<p>`, `<form>` 등이 있다.
 
 
- Inline 타입 요소
 - 새로운 라인에서 시작하지 않는다.
 - content 만큼만 너비를 차지한다.
 - 대표적인 태그로는 `<span>`, `<a>`, `<img>` 등이 있다.

## 참조
- https://developer.mozilla.org/ko/docs/Web/API/Document_Object_Model/Introduction
- https://developer.mozilla.org/ko/docs/Web/HTML/Element