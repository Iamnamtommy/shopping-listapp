# shopping-listapp

간단한 쇼핑 리스트 웹앱 (HTML/CSS/JS, Supabase 저장)

## 기능
- 항목 추가 / 완료 표시 / 삭제
- 완료 항목 일괄 삭제
- 라이트·다크 모드 자동 대응

## 데이터 저장
Supabase의 `shopping_items` 테이블(`id`, `name`, `done`, `created_at`)에 저장합니다.
`index.html`의 `SUPABASE_URL`, `SUPABASE_ANON_KEY`를 본인 프로젝트 값으로 바꿔 사용하세요.

## 실행
`index.html`을 브라우저로 열면 됩니다.
