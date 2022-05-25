```dart
Container(
	decoration: BoxDecoration(
		color: Colors.amber,
		borderRadius: BorderRadius.circular(30),
		boxShadow: BoxShadow(
			// 그림자 색상
			color: Colors.grey[500],
			// 오프셋(그림자 표시 범위) X/Y 그림자 위치 이동
			offset: Offset(4.0, 4.0),
			// 그림자 가장자리 흐릿함 조절
			blurRadius: 15.0,
			// blur 적용전 그림자 범위 팽창 정도 조절
			spreadRadius: 1.0,
		)
	)
)
```

[BoxShadow class - painting library - Dart API](https://api.flutter.dev/flutter/painting/BoxShadow-class.html)