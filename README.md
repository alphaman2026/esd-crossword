# ESD 십자말풀이

반도체 · 정전기 용어 17개로 만든 십자말풀이 게임 (10×10).

**플레이**: https://alphaman2026.github.io/esd-crossword/

- 이름 입력 후 시작, 단어 정답 시 글자당 100점, 시간 보너스(15분 기준), 힌트 -50 / 오답 -30
- 글로벌 순위: esd-hunter 와 같은 Firebase RTDB(`hof` 경로)를 공유하며 `g:"xw"` 태그로 구분
  (DB 규칙이 `hof` 외 경로 쓰기를 막고 있어 경로를 공유. esd-hunter 쪽은 `!v.g` 필터로 분리)
- 오프라인이면 이 기기 순위(localStorage)로 자동 전환
