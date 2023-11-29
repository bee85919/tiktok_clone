### 3.2 Project files
- UI 확인할 때 mobbin 이라는 사이트를 참고하면 좋다.


### 4.3 Sign Up Form
- method나 프로퍼티 이름 앞에 _를 달면 private이 된다.
    - 위젯의 생명 주기에 관련된 메서드들은 앞에 _가 없는 것을 볼 수 있다.

- code challenge: sign_up_screen.dart
    - "Use email & password" 버튼을 GestureDetector로 감싸주었다. 유저의 버튼 클릭을 감지하기 위해서다. 여기에 GestureDetector를 넣는 대신에 AuthButton에 함수를 전달할 수 있게 만들고 이 FractionallySizedBox를 GestureDetector로 감싸는 방법을 구현해 볼 수 있을까?