- 生産効率関するKPI
    - worker efficiency 労働生産性効率
        - actual personnel work time/actual personnel attendance time
        - = APWT/APAT
    - Allocation ratio 負荷度
        - sum(actual busy time) involved in a production order/actual order execution time
        - = sum(AUBT)/AOET
            - AUBT: planned busy time(PBT) - actual unit down time(ADOT)
            - AOET: start time - end time of a production order
            - AOET: AUBT + actual transport time + actual queuing time.
    - Throughput rate 生産量比率
        - Produced quantity of an order/AOET
        - = PQ/AOET
          - PQ: the quantity that a work unit has produced in relation to a production order.
    - Allocation efficiency　実稼働/稼働計画　比率
        - actual unit busy time/planned unit busy time
        - = AUBT/PBT
            - PBT: planned operation time - planned down time
    - Utilization efficiency　利用効率
        - actual production time/actual unit busy time
        - = APT/AUBT
            - APT: actual time during which a work unit is producing. It includes only the value-adding functions.
        - range: 0% to 100%
    - OEE index　設備総合効率
    - NEE index　正味設備効率
    - Availability　設備有効性
    - Effectiveness　工程効率
