# E2E 테스트 시나리오: 입력 유효성 검사

## 목적

사용자가 메모 작성 시 필수 필드(제목, 내용)를 비워둔 채 저장하려고 할 때, 적절한 경고 메시지가 표시되는지 확인합니다.

## 시나리오 단계

1.  메인 페이지에 접속합니다.
2.  '새 메모' 버튼을 클릭하여 메모 작성 폼을 엽니다.
3.  제목과 내용을 비워둔 채 '저장하기' 버튼을 클릭합니다.
4.  "제목과 내용을 모두 입력해주세요." 라는 경고창이 나타나는지 확인합니다.
5.  폼이 닫히지 않고 그대로 유지되는지 확인합니다.
6.  제목만 입력하고 '저장하기' 버튼을 클릭합니다.
7.  다시 경고창이 나타나는지 확인합니다.
8.  내용만 입력하고 '저장하기' 버튼을 클릭합니다.
9.  다시 경고창이 나타나는지 확인합니다.
10. '취소' 버튼을 눌러 폼을 닫습니다.
