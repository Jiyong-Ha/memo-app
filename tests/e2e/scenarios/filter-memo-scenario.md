# E2E 테스트 시나리오: 카테고리 필터링

## 목적

사용자가 카테고리 드롭다운 메뉴를 사용하여 특정 카테고리의 메모만 필터링할 수 있는지 확인합니다.

## 시나리오 단계

1.  메인 페이지에 접속합니다.
2.  카테고리 필터 드롭다운을 클릭합니다.
3.  '업무' 카테고리를 선택합니다.
4.  메모 목록에 '업무' 카테고리에 속한 "Supabase 마이그레이션 완료" 메모만 표시되는지 확인합니다.
5.  통계 정보에 필터링된 메모 개수가 '1개 메모 (전체 3개 중)'으로 표시되는지 확인합니다.
6.  '필터 초기화' 버튼을 클릭합니다.
7.  카테고리 필터가 '전체 카테고리'로 변경되고, 전체 메모 목록이 다시 표시되는지 확인합니다.
