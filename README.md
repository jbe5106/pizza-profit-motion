# 이익의 공식 — 30초 키네틱 타이포그래피

`PRICE × QUANTITY − COST = PROFIT` 구조로 피자 프랜차이즈 9개 매장(가상 데이터)의 2022→2026년(1~8월 누계) 실적을 설명하는 30초 영상입니다.

- 웹에서 보기: https://jbe5106.github.io/pizza-profit-motion/
- 영상 파일: [`docs/video.mp4`](docs/video.mp4)

## 구성
- `index.html` — 루트 컴포지션(장면·내레이션·자막·발표자 배치)
- `compositions/s1~s5.html` — 장면 5개 (공식 → 가격·수량 → 비용 → 이익률 → 결론)
- `compositions/captions.html` — 자막(검은 바탕·흰 글씨)
- `compositions/presenter.html` — 코드로 그린 발표자, 내레이션 음량에 맞춘 입 모양
- `assets/vo/` — 장면별 한국어 내레이션(edge-tts, ko-KR-InJoonNeural)

## 다시 렌더링
```bash
npx hyperframes render
```
한글 글꼴은 Windows의 맑은 고딕(로컬 글꼴)을 씁니다.
