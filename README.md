# 내배캠 스프링 플러스 심화 주차 개인과제

## TroubleShooting
```
@Query("SELECT t FROM Todo t WHERE " +
        "(:weather IS NULL OR t.weather = :weather)" +
        "AND (:startDate IS NULL OR t.modifiedAt >= :startDate)" +
        "AND (:endDate IS NULL OR t.modifiedAt <= :endDate)")
```
