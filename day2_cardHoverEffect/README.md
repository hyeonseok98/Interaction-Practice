### Card Hover Effect

---

출처: https://www.youtube.com/watch?v=Q8BamnhOmWc

#### [새롭게 알게된 점]

- forwards: 애니메이션이 끝나고 끝난 상태 유지할 수 있도록 해 줌. 안그러면 원래 처음 상태 돌아감
- pointer-events: none; -> 포인터를 hover했을 때 계속 반복적으로 애니메이션이 실행되는 것을 막아줌. 한 애니메이션이 완전히 끝날 수 있게 도와준다.
- animation-delay를 통해 시간차 애니메이션 만드는 법

#### [소감]

- 하나하나 따로 놓고 보면 익숙한 애니메이션이지만 이렇게 쓰일 수 있다는 걸 알게 되었다. overflow: initial; -> hidden 속성을 없애서 카드 안쪽에서 바깥쪽으로 액션을 주는 애니메이션이 인상적이었다.
