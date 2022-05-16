# Context

애플리케이션의 환경에 대한 정보를 담고 있습니다.

애플리케이션의 상태, 정보를 얻거나 리소스, 데이터베이스 등에 접근하기 위해 사용합니다.

context는 application context와 activity context가 있습니다.

#### Application Context

싱글턴 인스턴스이며 application의 라이프사이클에 묶여있습니다.

애플리케이션 전체에서 사용할 라이브러리 등을 초기화 할 때 사용해야합니다.

위 상황에서 Activity Context를 사용할 경우 메모리 누수가 발생할 수 있습니다.

#### Activity Context

activity의 라이프사이클에 묶여있습니다.

GUI 조작 등 Application Context보다 많은 기능을 제공합니다.
