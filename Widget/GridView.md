```dart
GridView.count(
	// 서브축 몇개까지 넣을지
	crossAxisCount: 2,
	// 그리드뷰 겉 패딩
	padding: const EdgeInsets.all(10),
	// 서브축 사이 공간
	crossAxisSpacing: 10,
	// 자식 요소 비율 가로/세로
	childAspectRatio: 1/2,
	children: [
		CustomButton(
			text: "거래지역",
			color: ThemeColors.white,
			textColor: ThemeColors.purple040,
			width: (MediaQuery.of(context).size.width - 40 - 20) * 0.5,
			height: 90,
		),
		CustomButton(
			text: "asd",
			color: ThemeColors.white,
			textColor: ThemeColors.purple040,
			width: (MediaQuery.of(context).size.width - 40 - 20) * 0.5,
			height: 90,
		),
	],
)
```

[Create a grid list](https://docs.flutter.dev/cookbook/lists/grid-lists)

[GridView class - widgets library - Dart API](https://api.flutter.dev/flutter/widgets/GridView-class.html)

[GridView.count constructor - GridView class - widgets library - Dart API](https://api.flutter.dev/flutter/widgets/GridView/GridView.count.html)