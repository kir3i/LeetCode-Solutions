# 542. 01 Matrix

## solution 1

시간복잡도 : O(NM)

알고리즘 : BFS

풀이 설명 : 행렬의 요소가 0인 지점을 모두 큐에 저장하고 방문 처리합니다. 이후 BFS를 돌면서 새로 방문하게 되는 지점에 BFS 사이클 횟수에 해당하는 숫자를 할당하고 방문 처리합니다. 너비 우선 탐색이 끝난 후의 행렬을 반환합니다.

소스코드 : [link](./542-yongjoonseo.py)

