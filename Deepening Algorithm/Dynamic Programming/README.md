# Dynamic Programming Algorithm
</br>
  
## 1. DP(;Dynamic Programming)란?
  
**def)** 이미 계산된 결과(하위 문제)는 별도의 메모리 영역에 저장하여 다시 계산하지 않도록 설계함으로써 메모리를 적절히 사용하여 수행 시간 효율성을 비약적으로 향상시키는 알고리즘  

☛ **Dynamic**: 프로그램 실행 도중 필요한 메모리를 할당하는 기법이 아닌 '기억한다'라고 생각하면 된다.  
☛ **Programming**: 컴퓨터 프로그래밍이 아닌 테이블을 만든다는 뜻이다.  


</br>  
  
* * *

## 2. DP 알고리즘을 사용할 수 있는 조건
```markdown
i) 최적 부분 구조 (Optimal Substructure)
: 상위 문제를 나눈 부분 문제들의 해를 모아 상위 문제를 해결 가능해야 함

ii) 중복되는 부분 문제 (Overlapping Subproblem)
: 동일한 부분 문제를 반복적으로 해결해야 함
```
&nbsp; 위와 같은 경우 DP를 사용하면 단순 재귀를 사용했을 때보다 높은 효율의 코드를 작성할 수 있다.
 
* * *

## 3. DP 풀이 단계
```markdown
1) 해결하고자 하는 문제가 DP 문제인지 확인
2) 최소한의 매개변수를 가지고 상태 표현식(State Expression) 결정
3) 상태의 관계를 수립 → 점화식 세우기
4) Tabulation(Bottom Up) 또는 Memoization(Top Down)을 이용하여 문제 해결
```

* * *