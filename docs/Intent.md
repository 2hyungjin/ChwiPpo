# Intent

인텐트는 수행할 작업의 추상적인 설명입니다.(메시징 객체)

인텐트를 활용해 액티비티를 실행할 수도, 브로드캐스트를 보낼 수도, 백그라운드 서비스와 소통할 수도 있습니다.

인텐트는 명시적 인텐트와 암시적 인텐트로 나뉩니다.

**명시적 인텐트**

앱 안에서 구성 요소를 시작할 때 사용합니다.

액티비티  또는 서비스의 클래스 이름을 통해 시작합니다.

액티비티 전환, 서비스 실행 등이 해당합니다.

**암시적 인텐트**

특정 이름을 대지 않고 작업을 선언하여 다른 앱의 구성 요소가 처리할 수 있게 합니다.

암시적 인텐트를 사용하면 안드로이드 시스템이 Manifast 파일에 선언된 인텐트 필터와 비교하여 적절한 구성 요소를 찾습니다.
