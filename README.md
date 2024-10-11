# 내배캠 스프링 플러스 심화 주차 개인과제

## TroubleShooting
```
@Query("SELECT t FROM Todo t WHERE " +
        "(:weather IS NULL OR t.weather = :weather)" +
        "AND (:startDate IS NULL OR t.modifiedAt >= :startDate)" +
        "AND (:endDate IS NULL OR t.modifiedAt <= :endDate)")
```

#### ⏩ JPQL 사용: @Query의 기본 쿼리는 JPQL이다. 처음 사용해봐서 복잡한 쿼리를 직접 작성해야 하니 괄호도 빼먹고 기호도 빼먹어서 작성에 어려움이 있었다. 
#### ⏩ 기본 메서드로는 표현하기 힘든 복잡한 데이터 조회 로직이 필요한 경우에 유용하게 사용된다고 하는데 그런 것 같다.
 


## 회고 
####  ⏩ QueryDSL을 사용해봤다면 쿼리 최적화도 되고 검색 기능의 성능이 높아지지 않았을까 하는 아쉬움 
####  ⏩ EC2, RDS, S3 를 다음에는 꼭 사용해 보는 것으로 하겠다! 
####  ⏩ 전체적으로 강의에 더 집중하느라 온전히 집중하지 못해 아쉬웠다 .
