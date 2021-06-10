# CSS Basic
CSS에 관한 공부 내용을 간단히 정리하였다.

## Prseudo class selector : 가상 클래스 선택자
element들의 상태에 따라 가변적으로 선택이 가능한 선택자

- :link - 방문한 적이 없는 링크
- :visited - 방문한 적이 있는 링크
- :hover - 마우스를 올려 놓았을 때
- :active - 마우스로 클릭했을 때
- :focus - 포커싱 되었을 때 (가장 뒤에 넣는 것을 권장)

## Cascading : 적용 우선순위
하나의 태그에 여러 CSS효과가 중첩됐을 때, 이는 우선순위를 가진다.

- style attribute > id selector > class selector > tag selector > browser

구체적이고 명시적일수록 우선순위가 높고, 포괄적일 수록 우선순위가 낮다.
그러나, **!important;** 를 입력해주면 강제적으로 우선순위를 높일 수 있다.

## Inline vs Block
