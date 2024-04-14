타이머 만들기
==========
앱스쿨 수업시간에 사용하기 위한 타이머 만들기
-----------------------------------
> 요구사항
> 1. 수업시간에 사용해야 하므로 화면을 많이 차지 않는 크기로 제작
> 2. 화면 상단 고정
> 3. 기존 베이스 코드는 3분 이하 설정 불가능
> 4. 종료 시 알람 소리 변경

### Update
***
- 4/14
  - 종료 아이콘으로 변경 시 애니메이션 추가
  - 60초로 입력했을 때 1분으로 자동 수정되는 기능 추가
    
- 4/12
  - 타이머 시작/일시정지 버튼 변경
    - `SF Symbols`의 모래시계 아이콘 사용
    - 실행중/일시정지/종료 상태일 때 아이콘 분류
  - 클릭하면 증가하는 타이머 구간 변경
    - 시간 직접 입력(TextField 사용)
    - 입력 구간 적용: 초기값 "00", 2자리 숫자(59분 60초)
  - 실시간 시간 변동 시각화
  - 일시정지 기능 추가
