```dart
ListView(
	// true: 부모의 크기를 가짐 / false: 내부 요소만큼의 크기를 가짐
	shrinkWrap: false,
	// 스크롤 방향
	scrollDirection: (Axis.horizontal | Axis.vertical),

	// 패딩
	padding: const EdgeInsets.symmetric(vertical: 30),

	// 요소
	children: <Widget>[
		Container(
			height: 50,
			color: Colors.amber[600],
			child: const Center(child: Text('Entry A')),
		),
		Container(
			height: 50,
			color: Colors.amber[500],
			child: const Center(child: Text('Entry B')),
		),
		Container(
			height: 50,
			color: Colors.amber[100],
			child: const Center(child: Text('Entry C')),
		),
	],
)
```

```dart
ListView.builder(
	padding: const EdgeInsets.all(8),
	itemCount: people.length + 1,
	itemBuilder: (BuildContext context, int index) {
		if (index == 0) return HeaderTile();
		return PersonTile(people[index-1]);
	},
)
```

[ListView class - widgets library - Dart API](https://api.flutter.dev/flutter/widgets/ListView-class.html)

- ListView는 부모 위젯의 높이에 맞추기 때문에 Column에 넣으면 에러가남 (Column은 높이가 무한임)
		- Expanded로 감싸서 문제 해결 가능