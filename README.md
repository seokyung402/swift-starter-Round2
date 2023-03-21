# 코드 스타터 캠프 2주차 미션을 위한 저장소입니다.
---
# STEP 1.
# 로또 당첨번호 생성기 순서도 생성하기

---
# STEP 2 - 수정
# 내 번호와 맞추어보기!
- "STEP 1"에서 한 순서도로 만든 함수: createWinningLottoNumber()
    + `Int.random(in: )`을 사용해서 무작위로 숫자를 입력할 수 있도록 했습니다.
- 내 로또 번호와 당첨 번호를 비교하는 함수: compareLottoNumber()
    + `set`의 `intersection`을 사용해 같은 번호가 있는지 확인했습니다.
    + 또한, `intersection`으로 구한 집합 뒤에 `sorted()`를 붙이면 배열이 되는 것을 이용했습니다.
    + 이후, 출력에는 `for문`을 사용해 배열의 각 원소를 방문하며 마지막 원소일 때에는 ", "를 안붙이고 출력하도록 하였습니다. 
- compareLottoNumber()에서 argument label에 전치사 with과 to를 사용했습니다.

