## 1. 3자리 숫자 랜덤 생성 기능 구현.

-   MissionUtils 라이브러리를 설치하고 제대로 설치되었는지 확인해야 한다.
-   Random을 사용해서 기능을 구현한다.

## 2. 숫자 입력받아서 볼, 스트라이크, 낫씽 판단하는 기능 구현.

-   1단계를 통과하면 MissionUtil 라이브러리가 성공적으로 설치된 것이다.
-   Console 을 이용해서 3자리 숫자를 입력받아서 판단하는 기능을 구현한다.

## 3. 3자리 숫자가 아닌 다른 입력 예외 처리.

-   3자리 숫자가 아닌 다른 입력이 들어왔을 경우, 프로그램을 종료시킨다.
-   이 때 throw를 날려서 예외처리를 하고, 프로그램을 종료.

## 4. 코드 리팩토링

-   indent의 깊이나 너무 깊은 것이 있는지 체크한다.
-   play()에 몰아져 있는 기능을 분리한다.
-   에어비앤비 코딩 컨벤션을 최대한 따르도록 코드를 수정한다.

## 5. Jest 이용하여 기능 테스트하기.

-   test 코드 작성법을 학습하고 적용해본다.
