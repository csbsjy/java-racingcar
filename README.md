# 자동차 경주 게임
## 진행 방법
* 자동차 경주 게임 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)


### 모델링

**view**
- 사용자에게 이동시도 횟수 입력을 요청한다 
    - 숫자 검증
- 사용자에게 자동차 대수 입력을 요청핟다
    - 숫자 검증

- 자동차의 상태를 출력한다.
- 상태 출력은 매 경기에 대해 모두 출력해야 한다.

**레이싱게임**
- 참가 자동차들이 경기를 하도록 한다.

**자동차**
- 자동차는 주어진 횟수만큼 전진하거나 멈춘다.
- 랜덤값이 4 이상이면 움직이고, 그렇지 않으면 멈춘다

**도우미**
- 랜덤값을 0에서 9사이로 반환한다
 
