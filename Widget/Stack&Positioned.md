```dart
Stack(
	children: [
		// 겹칠거 1번
		위젯,

		// 겹칠거 2번 (1번 보다 위에 보임)
		Positioned(
			// 왼쪽 모서리 기준으로 이동해서 위치 설정
			left: 60,
			top: 60,
			// 위치 바꿔 보여줄 위젯
			child: SvgPicture.asset("assets/icons/profile_add.svg"),
		)
	],
)
```

[Stack class - widgets library - Dart API](https://api.flutter.dev/flutter/widgets/Stack-class.html)

- **Stack**는 자식 중 가장큰 사이즈를 따라간다
- **Positioned** 위젯을 통해 섬세한 위치를 설정 가능하다