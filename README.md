# 정보 수업 사이트 모음

2학년 정보 수업에서 사용하는 활동 사이트를 보관하는 저장소입니다.
사이트마다 폴더 하나씩 들어 있습니다.

| 폴더 | 사이트 | 단원 · 차시 | 설명 |
|---|---|---|---|
| [digital-lab](digital-lab/) | 디지털 표현 실험실 | Ⅱ. 데이터 · 1. 데이터의 표현 · 2차시 | 문자·이미지·소리·동영상이 0과 1로 표현되는 과정을 직접 조작하며 확인 |
| [data-practice](data-practice/) | 데이터 수행평가 연습실 | Ⅱ. 데이터 · 수행평가(데이터의 표현·분석) 대비 | 개념 정리, 낱말 조각을 끌어다 놓는 서술형 답안 조립, 채점기준 자동 채점과 예시답안 (연습문제: 사물함 대여 · 문제 풀이와 단원평가) |
| [ai-lesson1](ai-lesson1/) | 인공지능 1차시 | Ⅳ. 인공지능 · 1. 인공지능과 학습 · 1차시 | AI인지 아닌지 판별, 사례 속 근거로 특성 찾기, 수행평가 문항 1 형식의 특성 연결 글쓰기(자가 점검표·예시답안·패들렛 제출 연결) |
| [lesson-timer](lesson-timer/) | 수업 타이머 | 교사용 (모든 차시) | 도입·전개·정리 활동별 타이머, 원형 타이머·작게 보기·예약 시작. 윈도우 exe와 웹 버전 |

## GitHub Pages 주소

Pages를 켜면 각 사이트는 아래 형식의 주소로 열립니다.

- `https://kyeongsoon.github.io/info/digital-lab/`
- `https://kyeongsoon.github.io/info/data-practice/`
- `https://kyeongsoon.github.io/info/ai-lesson1/`
- `https://kyeongsoon.github.io/info/lesson-timer/`

## 반별 패들렛 연결 (ai-lesson1)

- 선생님 설정은 주소 끝에 `#teacher`를 붙여 열면 보입니다. 예) `https://kyeongsoon.github.io/info/ai-lesson1/#teacher`
- 반 수를 넣고 '반 수만큼 줄 만들기' 또는 '+ 반 추가'로 반마다 패들렛 주소를 넣습니다.
- 설정에서 만들어지는 링크
  - 전체 반 공용 링크(`?padlets=…`): 학생이 활동 3에서 자기 반을 골라 제출
  - 반별 링크(`?padlet=…&class=…`): 반이 정해져 있어 고를 필요 없음
- 또는 `ai-lesson1/index.html` 스크립트 맨 위의 `PADLETS`에 `["반 이름", "패들렛 주소"]`를 적어 두면 링크 없이도 항상 적용됩니다.
- 적용 순서: 학생용 링크 → 코드의 `PADLETS` → 그 기기에 저장한 목록
