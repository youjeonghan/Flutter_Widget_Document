```dart
FutureBuilder(
	future: _fetchData(),
	builder: (BuildContext context, AsyncSnapshot snapshot) {
		if (snapshot.hasData) {
			return 위젯; // (데이터 있는 경우)
		} else if (snapshot.hasError) {
			return Text('error'); // 에러난 경우
		}
		return 위젯; //(데이터 없는 경우)
)

Future<List> _fetchData() async {
		String jsonString = await rootBundle
				.loadString('assets/temp_data/attention_item_list.json');
		final jsonResponse = json.decode(jsonString);
		return jsonResponse;
	}
```

[FutureBuilder class - widgets library - Dart API](https://api.flutter.dev/flutter/widgets/FutureBuilder-class.html)