```dart
Container(
	// 
	decoration: BoxDecoration(
		// 색상
		color: const Color(0xff7c94b6),
		image: const DecorationImage(
			image: NetworkImage('https://flutter.github.io/assets-for-api-docs/assets/widgets/owl-2.jpg'),
			fit: BoxFit.cover,
		),
		// 테두리
		border: Border.all(
			color: Colors.black,
			width: 8,
		),
		// 테두리 둥글기
		borderRadius: BorderRadius.circular(12),
		// 테두리 그림자
		// [] 배열로 여러 그림자 넣을 수 있음
		boxShadow: 

		// 그래디언트
		gradient: LinearGradient(
			// 색상 리스트
			colors: [Color(0xffB5A4FF), Color(0xff7E69F7)],
			// 시작, 끝 위치
			begin: Alignment.topCenter,
			end: Alignment.bottomCenter,
		)
	),
)
```

[BoxDecoration class - painting library - Dart API](https://api.flutter.dev/flutter/painting/BoxDecoration-class.html)