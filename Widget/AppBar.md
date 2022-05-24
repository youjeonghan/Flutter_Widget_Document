```dart
AppBar(
	// 뒤로가기 버튼 생성 여부
	// true(default): 생성 / false: 제거
	automaticallyImplyLeading: false,
	// 앱바 텍스트
	title: Text('Welcome to AppBar'),
	// Text 가운데 정렬 여부
	centerTitle: true,
	// 앱바의 왼쪽 UI
	leading: IconButton(icon: Icon(Icons.menu), onPressed: null),
	// 앱바의 왼쪽 UI 영역 크기
	leadingWidth
	// title 수평 공백 (음수도 가능)
	titleSpacing: 0,
	// 앱바의 오른쪽 UI / 버튼 활성화
	actions: [
		IconButton(icon: Icon(Icons.image), onPressed: null),
		IconButton(icon: Icon(Icons.navigate_next), onPressed: null),
	],
	// 앱바의 배경색
	backgroundColor: Colors.red,
	// 앱바의 그림자 설정
	elevation: 100,
)
```

[AppBar class - material library - Dart API](https://api.flutter.dev/flutter/material/AppBar-class.html)