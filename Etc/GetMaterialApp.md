```dart
import 'package:get/get.dart';

// MaterialApp에도 있는 속성은 제외하고 작성함
GetMaterialApp(
	// 시작 라우트 주소
	initialRoute: --
	// 라우트 주소 목록
	getPages: [
		GetPage(
			name: '/state-simple',
			page: () => StateSimple(),
		),
		GetPage(
			name: '/state-reative',
			page: () => StateReactive(),
		),
	],
);
```

[get | Flutter Package](https://pub.dev/packages/get)