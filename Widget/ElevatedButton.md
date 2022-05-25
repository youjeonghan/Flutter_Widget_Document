```dart
ElevatedButton(
	// 액션
	onPressed: () => {},
	// 스타일
	style: ElevatedButton.styleFrom(
		// 바탕색
		primary: color,
		// 글자색
		onPrimary: color,
		// 그림자
		elevation: 0,
		// 모양
		shape: RoundedRectangleBorder(
			borderRadius: BorderRadius.circular(10.0),
		),
		// 버튼 패딩
		padding: EdgeInsets.zero,
	),
	// 안에 넣을 위젯
	child: Text(text),
)
```

[ElevatedButton class - material library - Dart API](https://api.flutter.dev/flutter/material/ElevatedButton-class.html)

[styleFrom method - ElevatedButton class - material library - Dart API](https://api.flutter.dev/flutter/material/ElevatedButton/styleFrom.html)