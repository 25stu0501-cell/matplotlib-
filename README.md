# matplotlib-
# matplotlib 주요 기능 정리

| 기능       | 사용법 예시              | 설명                        |
|------------|-------------------------|-----------------------------|
| 선 그래프  | `plt.plot(x, y)`        | 기본 선 그래프 그리기         |
| 막대 그래프| `plt.bar(categories, values)` | 막대 그래프 그리기          |
| 산점도     | `plt.scatter(x, y)`     | 점으로 된 산점도 그리기       |
| 제목       | `plt.title("제목")`      | 그래프 제목 지정             |
| 축 이름    | `plt.xlabel("X축")`      | X축 레이블 지정             |
|            | `plt.ylabel("Y축")`      | Y축 레이블 지정             |
| 색상       | `color='red'`           | 선, 점, 막대 색 지정          |
| 선 스타일  | `linestyle='--'`        | 실선, 점선 등 스타일 변경      |
| 마커       | `marker='o'`            | 점 모양 지정                 |
| 축 범위    | `plt.xlim(0, 10)`       | X축 범위 지정               |
|            | `plt.ylim(0, 100)`      | Y축 범위 지정               |
| 그리드     | `plt.grid(True)`         | 배경 격자선 표시             |
| 범례       | `plt.legend()`          | 그래프 범례 표시             |

---

## 예시 코드

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4]
y = [10, 20, 25, 30]

plt.plot(x, y, color='blue', linestyle='--', marke
