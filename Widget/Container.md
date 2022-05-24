```dart
Container(
	// 패딩 속성
	padding: EdgeInsets.all(50),
	// 너비
	width: 300,
	// 높이
	height: 300,
	// 크기 제한 정하기
	constraints: BoxConstraints(minHeight: 200, maxHeight: 700),
	// 마진 속성
	margin: EdgeInsets.all(50),

	// 컨테이너 꾸미기
	decoration: BoxDecoration(
		// 컨테이너의 background color
		color: Colors.white,

		// 컨테이너의 border 모양
		borderRadius: BorderRadius.all(
			Radius.circular(70),
		),

		// 컨테이너의 그림자
		boxShadow: [
			BoxShadow(
				color: Colors.grey[600],
				blurRadius: 20,
				spreadRadius: 2,
			),
		],

		// border 꾸미기
		border: Border.all(
			color: Colors.black,
			width: 3,
		),
	),
	// 감싸는 요소
	child: Text(
		"컨테이너",
		style: TextStyle(fontSize: 50),
	),
)
```

[https://api.flutter.dev/flutter/widgets/Container-class.html](https://api.flutter.dev/flutter/widgets/Container-class.html)