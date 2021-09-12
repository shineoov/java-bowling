# 볼링 게임 점수판
## 진행 방법
* 볼링 게임 점수판 요구사항을 파악한다.
* 요구사항에 대한 구현을 완료한 후 자신의 github 아이디에 해당하는 브랜치에 Pull Request(이하 PR)를 통해 코드 리뷰 요청을 한다.
* 코드 리뷰 피드백에 대한 개선 작업을 하고 다시 PUSH한다.
* 모든 피드백을 완료하면 다음 단계를 도전하고 앞의 과정을 반복한다.

## 온라인 코드 리뷰 과정
* [텍스트와 이미지로 살펴보는 온라인 코드 리뷰 과정](https://github.com/next-step/nextstep-docs/tree/master/codereview)

--- 
## 기능 요구 사항
- [X] 프레임이 스트라이크이면 "X", 스페어이면 "9 | /", 미스이면 "8 | 1", 과 같이 출력하도록 구현한다.
- [X] 10 프레임은 스트라이크이거나 스페어이면 한 번을 더 투구할 수 있다.

## 기능 목록
- [X] 입력받은 플레이어 수 만큼 이름을 입력받는다.
    - [X] 플레이어명은 3글자로 제한한다.
- [X] 모든 프레임이 완료될 때 까지 넘어트린 핀 개수를 입력한다.
    - [X] 넘어트릴수 있는 핀 개수는 0 ~ 10개 이다.
    - [X] 한프레임에 투구가 완료되면 다음 프레임으로 넘어간다.      
    - [X] 마지막 프레임에서는 스트라이크 이거나 스페어면 한번 더 핀 개수를 입력한다.
- [X] 진행중인 스코어보드를 출력한다.
  - [X] 프레임 상태를 출력한다. 
  - [X] 프레임 별 해당 점수를 구한다.
    - [X] 스트라이크일경우 다음 2번의 투구까지 접수를 합산 한다.
    - [X] 스페어일경우 다음 1번의 점수를 합산한다.
- [ ] 플레이어 수를 입력받는다.
- [ ] 플레이어 수 만큼 스코어보드를 출력한다.
