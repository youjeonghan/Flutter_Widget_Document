```dart
Text(
	// 내용
	'bold text',
	softWrap: true,
	// 오버플로우시
	// TextOverflow.ellipsis 넘어간 부분 ...으로 보여줌
	overflow: TextOverflow.ellipsis,
	// 최대 줄수
	maxLines: 1,
	// 문자를 수평적으로 배치하는 방법. (center, left, right, end, ...)
	textAlign: TextAlign.center,
	// 문자 배치 방향. (ltr:왼쪽에서 오른쪽으로, rtl:오른쪽에서 왼쪽으로, ...)
	textDirection : ,
	// 문자의 스타일 지정
	style: TextStyle(fontWeight: FontWeight.bold),
)
```

[Text class - widgets library - Dart API](https://api.flutter.dev/flutter/widgets/Text-class.html)