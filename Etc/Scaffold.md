```dart
Scaffold(
	// 배경색
	backgroundColor: 
	// 네비게이션바 라고도 함
	appBar: AppBar(
		title: Text('Sample Code'),
	),
	// 가운데 영역
	body: Center(
		child: Text('You have pressed the button $_count times.'),
	),
	// 다른 창 으로 이동할 수 있는 버튼들이 있는 영역 / Tab Bar라고도 함
	bottomNavigationBar: BottomAppBar(
		child: Container(
			height: 50.0,
		),
	),
	//창 위에 떠 있는 효과를 주는 버튼
	floatingActionButton: FloatingActionButton(
		onPressed: () => setState(() {
			_count++;
		}),
		tooltip: 'Increment Counter',
		child: Icon(Icons.add),
	),
	// 플로팅 버튼 위치 설정
	floatingActionButtonLocation: FloatingActionButtonLocation.centerDocked,
);
```

[Scaffold class - material library - Dart API](https://api.flutter.dev/flutter/material/Scaffold-class.html)

- 가장 최 상단, 중간 영역, 최하단, 그리고 떠 있는 버튼을 지원해주는 클래스