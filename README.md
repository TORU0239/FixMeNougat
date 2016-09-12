# FixMeNougat
안드로이드 누가 버전에서 정상적으로 동작하도록 앱을 수정해주세요.

# Compatibility Issue List
다음과 같은 상황에서 오류가 발생합니다.

1. 멀티윈도우 모드 진입시 앱이 종료될 수 있습니다.
2. 멀티윈도우 모드상에서 Load Image 버튼을 클릭하면 앱이 종료됩니다.
3. 멀티윈도우 모드에서 화면 크기를 변경할때마다 메모리 사용량이 증가합니다. (Memory Leak)
4. 설정에서 DisplaySize를 변경한 후 앱에 다시 진입하면 앱이 종료됩니다.
5. 네트워크 요청 버튼을 클릭한 후 잠시 시간이 지나면 앱이 종료됩니다.
6. 확장 라이브러리 읽기 버튼을 클릭한 후 잠시 시간이 지나면 앱이 종료됩니다.
7. 앱이 Doze on the go (Extended Doze)모드에 진입하면 네트워크 연결이 끊깁니다.
8. 리스트뷰에 포함된 Search EditText 위젯 상에서 한글 입력을 할 수 없습니다.
