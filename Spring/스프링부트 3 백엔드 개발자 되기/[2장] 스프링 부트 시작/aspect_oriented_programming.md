## 6. 🔍 관점 지향 프로그래밍

AOP를 약자로, Aspect Oriented Programming를 관점 지향 프로그래밍이라고 함.

프로그래밍에 대한 관심을 [핵심 관점, 부가 관점]으로 나누어서 관심 기준으로 모듈화하는 것.

<br>

부가 관점에 해당하는 로직을 모듈화해서 이를 핵심 관점 코드에서 분리할 수 있게 해줌.

분리함으로써 핵심 관점 코드에만 집중할 수 있게 되었고 프로그램의 변경, 확장에도 유연하게 대응할 수 있게 됨.

<br>

ex) 계좌 이체, 고객 관리하는 프로그램

각 프로그램에는 로깅 로직, 즉 지금까지 벌어진 일을 기록하기 위한 로직,

여러 데이터를 관리하기 위한 데이터베이스 연결 로직을 포함
   
    핵심 관점 : 계좌 이체, 고객 관리 로직
    부가 관점 : 로깅, 데이터베이스 연결 로직
