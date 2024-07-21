
# HTML Form 을 통한 정적 이메일 송신기

입력 폼을 작성 후 이메일 보내기 버튼을 누르면 내 메일로 이메일이 오게 된다. 또한, 스프레드 시트에 언제 누가 무슨 메시지를 보냈는지도 알 수 있다.

원리는 간단하다.
서버 없이 기능을 구현하다 보니 Google API를 통해 스프레드 시트를 저장한 내 구글 계정이 메일의 발신자가 되는 것이고, 입력 폼에 작성 후 이메일을 전송하면 나의 메일로 내용이 발송 되는 구조이다.

![mail-box](https://github.com/user-attachments/assets/a4c1abe2-b7de-4209-9020-8d9985bda0e4)

![google-sheet](https://github.com/user-attachments/assets/d8b3875d-dd84-448d-8fcc-9a952758b283)
