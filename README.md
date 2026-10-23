# workout-tracker-

## 레슨 노트
운동 끝나고 말로 정리한 레슨 포인트는 `lessons.json`에 날짜별로 쌓는다. 앱(index.html)이 이 파일을 읽어 그날 화면의 "레슨 핵심 정리"와 "레슨 노트"(고칠 습관 포함)에 보여 준다.
- 항목: date, sport(유도/레슬링/주짓수), type, key(오늘의 핵심 한 줄), sections[{h, items[{t, fix?, star?}]}]
- fix = 본인 습관 중 고칠 것(레슨에서 지적된 것만)
