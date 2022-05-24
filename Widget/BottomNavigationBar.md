```dart
BottomNavigationBar(
	// 요소 리스트
	items: const <BottomNavigationBarItem>[
		BottomNavigationBarItem(
			icon: Icon(Icons.home),
			label: 'Home',
		),
		BottomNavigationBarItem(
			icon: Icon(Icons.business),
			label: 'Business',
		),
	],
	// 인덱스 위치
	currentIndex: _selectedIndex,
	// 배경색
	backgroundColor: Colors.transparent,
	// selected된 컬러
	selectedItemColor: Colors.amber[800],
	// unselected된 item color
	unselectedItemColor: Colors.grey,
	// unselected된 label text
	showUnselectedLabels: true,
	// BottomNavigationBar Type -> fixed = bottom item size고정
	// BottomNavigationBar Type -> shifting = bottom item selected 된 item이 확대
	type: BottomNavigationBarType.shifting,
	// 탭 이벤트시 액션 (value로 index 번호 넘어옴)
	onTap: (value) => _onItemTapped()
)

void _onItemTapped(int index) {
	setState(() {
		selectedIndex = index;
	});
}
```

[BottomNavigationBar class - material library - Dart API](https://api.flutter.dev/flutter/material/BottomNavigationBar-class.html)