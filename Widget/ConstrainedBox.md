```dart
ConstrainedBox(
	// 제한 설정
	constraints: BoxConstraints(
		maxHeight: 300, 
		minHeight: 200,
		maxWidth: 500,
		minWidth: 200
	),
	// 자식 요소
	child: Container()
)
```

[ConstrainedBox class - widgets library - Dart API](https://api.flutter.dev/flutter/widgets/ConstrainedBox-class.html)