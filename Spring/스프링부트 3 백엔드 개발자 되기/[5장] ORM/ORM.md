## 🔍 ORM 이란?

object-relational mapping의 약자

자바의 객체와 데이터베이스를 연결하는 프로그래밍 기법

데이터베이스의 값을 마치 객체처럼 사용할 수 있음.

SQL을 전혀 몰라도 자바 언어로만 데이터베이스에 접근해서 원하는 데이터를 받아올 수 있음.

즉, 객체와 데이터베이스를 연결해 자바 언어로만 데이터베이스를 다룰 수 있게 도와주는 도구

<br>

### ✔ 장점

1. SQL을 직접 작성하지 않고 사용하는 언어로 데이터베이스에 접근할 수 있음.

2. 객체지향적으로 코드를 작성할 수 있기 때문에 비즈니스 로직에만 집중할 수 있음.

3. 데이터베이스 시스템이 추상화되어 있기 때문에 MySQL -> PostgreSQL으로 전환한다고 해도 추가로 드는 작업이 거의 없다. 즉, 데이터베이스 시스템에 대한 종속성이 줄어듦.

4. 매핑하는 정보가 명확함으로 ERD에 대한 의존도를 낮출 수 있고 유지보수할 때 유리함.

<br>

### ✔ 단점

1. 프로젝트의 복잡성이 커질수록 사용 난이도 증가

2. 복잡하고 무거운 쿼리는 ORM으로 해결이 불가능한 경우가 있음.
