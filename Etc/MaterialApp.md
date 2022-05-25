```dart
MaterialApp(
	// 디버그 태그 표시
	debugShowCheckedModeBanner: false,
	// 앱의 한 줄 설명
	title: 'MaterialApp',
	// 앱의 테마 지정
	theme: ThemeData(
		// 상호작용 요소에 사용되는 색상
		brightness: Brightness.light,
		// 앱의 주요부분 배경 색 (앱바, 탭바 등)
		primaryColor: Colors.greenAccent,
		// 위젯의 전경색
		accentColor: Colors.redAccent,
		// 앱에 기본으로 사용될 폰트
		fontFamily: 'IBM-Sans'
	),
	// MaterialApp의 기본 경로로 앱 실행 시 가장 먼저 볼 수 있는 화면
	home: Scaffold(
		appBar: AppBar(
			title: Text('MaterialApp'),
			centerTitle: true,
		),
		body: Column(
			mainAxisAlignment: MainAxisAlignment.center,
			children: [
				Center(
					child: FloatingActionButton(
						onPressed: () {},
					),
				)
			],
		),
	),
);
```

[Material class - material library - Dart API](https://api.flutter.dev/flutter/material/Material-class.html)

- 전체 앱을 감싸는 최상위 클래스이다.