```dart
// 전체여백을 지정하는 옵션
EdgeInsets.all(10.0)

// 특정영역에만 여백을 지정하고 싶을때 사용
EdgeInsets.only(bottom: 5.0)
EdgeInsets.only(left: 5.0)

// 왼쪽,위,오른쪽,밑 순으로 지정
EdgeInsets.fromLTRB(4, 0, 4, 0)

// 수평(horizontal), 수직(vertical)을 기준으로 여백지정
EdgeInsets.symmetric(horizontal: 8.0)
EdgeInsets.symmetric(vertical: 8.0)
```