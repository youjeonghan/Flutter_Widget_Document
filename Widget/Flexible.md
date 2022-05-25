```dart
Flexible(
	// 자리를 차지할 비율
	flex: 1
	// 공간을 어떻게 맞출지
	// FlexFit.tight 남은 공간 모두 차지
	fit: FlexFit.tight,
	// 안에 넣을 요소
	child: Text(),
)
```

[Flexible class - widgets library - Dart API](https://api.flutter.dev/flutter/widgets/Flexible-class.html)

- `Expanded`는 Flexible인데 fit이 FlexFit.tight로 고정된 위젯