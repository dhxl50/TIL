# CSS Basic
CSS에 관한 공부 내용을 간단히 정리하였다.(정리 + Cheat Sheet)

## Cascading : 적용 우선순위
하나의 태그에 여러 CSS효과가 중첩됐을 때, 이는 우선순위를 가진다.

- style attribute > id selector > class selector > tag selector > browser

구체적이고 명시적일수록 우선순위가 높고, 포괄적일 수록 우선순위가 낮다.
> `!important;` 를 입력해주면 강제적으로 우선순위를 높일 수 있다.

## Prseudo class selector : 가상 클래스 선택자
element들의 상태에 따라 가변적으로 선택이 가능한 선택자

- ***:link*** - 방문한 적이 없는 링크
- ***:visited*** - 방문한 적이 있는 링크
- ***:hover*** - 마우스를 올려 놓았을 때
- ***:active*** - 마우스로 클릭했을 때
- ***:focus*** - 포커싱 되었을 때 (가장 뒤에 넣는 것을 권장)


## Element : Inline vs Block level
- Inline : 화면 일부(자기자신) 영역만을 차지한다.
- Block level : 화면 전체를 사용한다.

> `display` 속성을 이용해 원하는 대로 변경할 수 있다.



---

## Box model
Contents의 부피감(width, heigth)과 거리감(padding, margin)을 결정한다.

> **Inline element**에는 width와 height를 적용할 수 없다.

> `box-sizing:border-box;` 속성을 이용하면 sizing의 기준을 content -> ***content+border*** 로 변경할 수 있다.

## Position : relative vs static
- position은 기본으로 `static`속성을 가진다.
- Offset(left, right, top, bottom)을 사용하기 위해서는 `static`이외의 속성이 적용 돼 있어야 한다.

## Position : absolute
- ***static이 아닌 부모 element*** 기준으로 위치를 설정하게 된다.
- 그러나 초기 위치는 바로 위 부모 element를 기준으로 결정되기 때문에, offset을 이용해서 직접 위치를 조절해야 한다.
- 부모로부터의 link가 끊기므로 속성을 상속받지 않는다.

## Position : fixed
- 스크롤과 상관없이 자신의 위치를 고정한다.
- 부모로부터의 link가 끊기므로 속성을 상속받지 않는다.