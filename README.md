# D-Day Progress Tracker

마감일까지의 진행 상황을 도트 형태로 시각화하는 웹 애플리케이션입니다.  

---

## ✨ Features

- 📅 D-Day 표시 (D-숫자 / D-DAY / COMPLETE)
- 📊 전체 기간 대비 진행률(%) 계산
- 🔵 하루 단위 도트 시각화
  - 지나간 날짜: 채워진 점
  - 오늘: 강조 색상 표시
  - 남은 날짜: 기본 점
- 🖱 커스텀 툴팁
  - 날짜 표시
  - Day N 표시
- 🌙 라이트 / 다크 테마 전환
- 💾 테마 설정 localStorage 저장
- 🚨 마감 7일 이하 강조 모드

---

## 📆 Project Period

- **Start:** 2026-01-06  
- **End:** 2026-06-23  

날짜를 변경하려면 `script` 영역의 아래 부분을 수정하세요:

```javascript
const start = normalize(new Date("2026-01-06"));
const end = normalize(new Date("2026-06-23"));
```

도트 열 개수 변경
```
grid-template-columns: repeat(20, 10px);
```
