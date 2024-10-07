# [퀘스트 3] 코드 페어프로그래밍 : N-gram

- 문제 정의 : 다음 조건을 확인하여 Avengers Script에서 워드 단위의 2-gram을 구하고, Script에서 가장 빈도가 높은 2-gram 페어를 찾아라!

- 요구사항
  - string, collection, n-gram으로 풀어야함
  - Avengers.txt 파일을 사용한다.
  - 모든 문자는 소문자로 변환한다.
  - 모든 기호를 제거한 후, 2-gram을 구한다.
  - "I am hungry......very much..."를 word단위로 자르면 , ['i', 'am', 'hungry','very','much'] 가 되어야 한다.

- 출력 예시
```
입력값 :
print(max2gram, countdict[max2gram])
print(Counter(baglist))

출력값 : ('it', 's') 68 Counter({('it', 's') : 68, ('i', 'm') : 52 , ('don', 't'): 43, ...
```
