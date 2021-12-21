### 모노미노도미노 게임

![all](https://blog.kakaocdn.net/dn/dvSqH8/btqXu4y1D2s/9P1ahBYaKZmcRttToldo9k/img.png) <br/>
참고자료 </br>
- [pygame 라이브러리 사용법 참고](https://www.youtube.com/watch?v=Dkx8Pl6QKW0&t=456s) <br/>
- [게임 아이디어 참조](https://www.acmicpc.net/problem/19235)
- 해당 게임은 60초내에 점수를 많이 얻는 것을 목표로 하는 게임이다.
- 블록은 총 세 종류로 스페이스 바를 누르면 랜덤해서 나온다.
![bar](https://upload.acmicpc.net/1453b25c-e0c1-4b99-9eda-bba9336beab1/-/preview/)
- 해당 블록은 방향기로 빨간색 블록 안에서만 이동 가능하다
![all](https://blog.kakaocdn.net/dn/dvSqH8/btqXu4y1D2s/9P1ahBYaKZmcRttToldo9k/img.png).
- 버튼 q를 누르면 블록이 놓인 위치에서 부터 초록색 보드로 블록이 이동하고, 파란색 보드로
블록이 이동한다.
- 블록의 이동은 다른 블록을 만나거나 보드의 경계를 만나기 전까지계속해서 이동한다.
- 테트리스와 같은 원리로 초록색 구간에서는 한 행이 블록들로 가득 차있으면 그 행의
블록들은 모두 사라지고 1점을 얻는다.
- 또한 파랑색 구간에서는 한 열이 블록들로 가득차 있으면 그 열의 블록들은 모두 사라지고 1점을 얻는다.
- 단 연한 파랑, 연한 초록색 구간에 블록이 진입하면 진입한 블록 수만큼 점수가 깎이고 연한 파랑색 구간에 진입한 블록
수만큼 열기준 우측으로 평행이동, 연한 초록색 구간에 진입한 블록 수만큼 행 기준 아래로평행이동한다.



