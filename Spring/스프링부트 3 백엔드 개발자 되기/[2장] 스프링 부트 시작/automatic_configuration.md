## 🔍 자동 구성

스프링 부트는 애플리케이션에서 최소한의 설정만으로도 실행되게 여러 부분을 자동 구성시킴.

서버를 시작할 때 구성 파일을 읽어와서 설정하는 것을 자동 구성이라고 함.

자동 설정은 META-INF에 있는 spring-factories 파일에 담겨 있음.

ex) h2에서 자동 구성되는 클래스는 AutoConfiguration, 속성값을 정의해놓은 클래스는 Properties를 이름 끝에 붙임.
