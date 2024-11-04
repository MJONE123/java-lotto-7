# java-lotto-precourse


##🎯 기능 목록
### 1. 로또 번호 생성
- 각 로또 티켓에 대해 1~45 사이의 중복되지 않는 6개의 번호를 무작위로 생성
- 사용자가 입력한 구입 금액에 따라 여러 개의 로또 티켓을 발행하며, 티켓 한 장의 가격은 1000원
- 생성된 로또 번호는 오름차순으로 정렬한 후 출력
- 당첨 번호와 중복되지 않는 보너스 번호 1개도 생성

### 2. 당첨 번호 입력
- 당첨 번호와 보너스 번호를 사용자로부터 입력받아 당첨 결과를 계산
- 당첨 번호는 1~45 사이의 숫자며 중복이 없음을 검증

### 3. 당첨 내역 계산
- 각 티켓을 당첨 번호와 비교하여 일치하는 개수를 계산
- 기준에 맞는 당첨 기준에 따라 상금을 계산하여 출력
  - 1등 : 6개 일치(20억원)
  - 2등 : 5개 일치 + 보너스 번호 일치(3천만원)
  - 3등 : 5개 번호 일치(150만원)
  - 4등 : 4개 번호 일치(5만원)
  - 5등 : 3개 번호 일치(5천원)

### 4. 수익률 계산
- 총 수익률을 계산하여 출력

### 5. 오류 처리
- 잘못된 입력(ex: 범위를 벗어난 번호 or 중복 값)이 있을 경우 [ERROR]로 시작하는 오류 메시지를 출력
- IllegalArgumentException을 발생시켜 유효하지 않은 입력을 관리

