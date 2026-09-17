# protein_tracker

유청단백질(웨이 프로틴) 국내 실구매가 자동 추적용 데이터 저장소.

- `data/price_history.json` — 제품별 최근 관찰가/최근 알림가 이력. 클라우드 루틴이 매일 이 파일을 읽고(전일 대비 비교), 갱신 후 다시 커밋합니다.
- 판단 로직(제품 분류, 가격 등급, 알림 조건)은 별도 스케줄 작업 정의(SKILL.md, 로컬 `C:\Users\Jack\.claude\scheduled-tasks\protein-price-tracker\`)에 있습니다.
