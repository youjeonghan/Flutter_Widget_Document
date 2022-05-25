```dart
final _controller = TextEditingController();

TextField(
	// 컨트롤러 통해 텍스트 필드 현 상태 확인 가능
	controller: _controller
	// 조정
	decoration: InputDecoration(
		// 힌트
		hintText: "힌트",
		// 힌트 텍스트 스타일
		hintStyle: TextStyle(),
		// 내부 패딩 조절하기
		contentPadding: EdgeInsets.all(0),
		// 내부 색상 채우기
		filled: true,
		// 내부 색상
		fillColor: Colors.white,
		// 포커스시 테두리
		focusedBorder: OutlineInputBorder(
			borderSide: const BorderSide(
				// 테두리 색상
				color: Colors.transparent,
			),
			// 테두리 모서리
			borderRadius: BorderRadius.circular(20.0),
		),
		// 사용가능시 테두리
		enabledBorder: OutlineInputBorder(
			borderSide: const BorderSide(
				// 테두리 색상
				color: Colors.transparent,
			),
			borderRadius: BorderRadius.circular(20.0),
		),
	), // decoration

	// 키보드 타입 지정
	keyboardType: TextInputType.number,
	// 위젯 보일시 커서 자동으로 타겟 여부
	autofocus: false
	// 최대 줄수
	maxLines: 1
	// 입력 텍스트 스타일
	style: TextStyle(),
	// 필드안 입력, 삭제시 실행 함수
	// 입력한값이 인자로 들어옴
	onChanged: (text) => {function()},
)
```

[TextField class - material library - Dart API](https://api.flutter.dev/flutter/material/TextField-class.html)

[InputDecoration class - material library - Dart API](https://api.flutter.dev/flutter/material/InputDecoration-class.html)