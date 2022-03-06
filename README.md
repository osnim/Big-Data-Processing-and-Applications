# Big-Data-Processing-and-Applications

### 정보융합학부 4학년 2학기 전공과목 빅데이터처리및응용 최종 프로젝트

- PostgreSQL과 psycopg2를 이용하여 Dijkstra알고리즘 구현

- sid : 시작 노드
- fid : 도착 노드
- weight : 가중치
- 제공 데이터 설치 방법
- createdb –U postgres problem
- psql –U postgres –d problem –f 

![image](https://user-images.githubusercontent.com/79408217/156922966-6d1fb0bd-faf1-421e-b33f-bcef8f2a9583.png)

예시

출발 노드를 입력하시오: 1
도착 노드를 입력하시오: 5
경로는 [1, 1363, 1364, 1366, 1369, 1403, 1401, 1218, 1223, 1225, 1226, 1219, 5] 입니다.

dump파일은 약 25만개 노드가 있는 빅데이터로 두 노드의 최단 경로를 다익스트라 알고리즘을 이용하여 구현한 python 코드입니다.    

