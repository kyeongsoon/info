# 수업 타이머

도입 · 전개 · 정리 단계와 그 안의 세부 활동별로 시간을 재는 수업 타이머입니다.

## 파일

| 파일 | 설명 |
|---|---|
| `수업타이머.exe` | 윈도우용 프로그램 (설치 없이 실행, 인터넷 없이 동작) |
| `index.html` | 웹 버전 (브라우저에서 바로 실행) |
| `수업타이머_5차시_인기동영상데이터분석.xlsx` | 5차시 '인기 동영상 데이터 분석' 수업 설계 엑셀 |
| `fonts/`, `js/`, `icon.png` | 화면에 쓰는 글꼴과 라이브러리 |
| `neutralino.config.json` | exe를 다시 빌드할 때 쓰는 설정 (Neutralinojs 6.8.0) |

## 주요 기능

- 단계별 · 활동별 카운트다운, 시간이 끝나면 자동으로 다음 활동 (기본 켜짐)
- 원형 타이머 화면 전환 (`P`)
- 작게 보기 (`M`): 단계 · 남은 시간 · 활동 이름 · 수업 흐름만 표시, 원형 타이머도 가능
- 항상 위에 띄우기 (`T`)
- 예약 시각 자동 시작, 윈도우 작업 스케줄러로 프로그램 자동 실행 예약 (exe 전용)
- 엑셀로 수업 설계 저장 · 불러오기 (3행 '시작 시각' 칸에 자동 시작 시각 입력)

## 웹 버전 주소

GitHub Pages를 켜면 `https://kyeongsoon.github.io/info/lesson-timer/` 에서 열립니다.
웹 버전에서는 항상 위, 창 크기 조절, 컴퓨터 자동 실행 예약 기능이 동작하지 않습니다.

## exe 다시 빌드하기

```bash
npm i -g @neutralinojs/neu
mkdir app && cp neutralino.config.json app/ && mkdir app/resources
cp -r index.html icon.png fonts js app/resources/
cd app && neu update && neu build --embed-resources
```
