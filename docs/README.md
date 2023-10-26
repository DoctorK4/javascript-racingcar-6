# 미션 - 자동차 경주

## 구현 기능 목록 

### 1. 자동차 이름 입력 기능
- 입력받은 이름을 쉼표 단위로 구분한다.
- 5자 초과의 이름을 가진 경우, 예외를 발생시킨다.

### 2. 시도 횟수 입력 기능
- 자연수가 아닌 숫자를 입력한 경우, 게임을 진행할 수 없기 때문에 예외를 발생시킨다.
- 숫자 타입이 아닌 경우, 예외를 발생시킨다.

### 3. 각 차수 실행 및 출력 기능
- 각 참가자별로 0에서 9사이 랜덤값을 추출한다.
- 추출값에 따라 4 이상인 경우 전진시킨다. 
- 각 차수의 결과를 출력한다.
- 전체 차수 데이터에 현재 차수 데이터를 반영한다.

### 4. 최종 우승자 출력 및 게임 종료 기능
- 각 차수들의 결과를 취합한 데이터를 바탕으로 가장 높은 최종 우승자를 출력한다.
- 우승자가 여러 명일 경우 쉼표(,)를 이용하여 구분한다.
- 게임을 종료한다.