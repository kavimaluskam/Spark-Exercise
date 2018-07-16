# Answer of exercise

## Q1.
- 1a: 
    - number of pageviews: 1,303,198 
- 1b: 
    - article with greatest number of pageviews: 827
    - corresponding pageviews: 49,249
- 1c:
    - article with greatest number of pageviews **in every hours**:
    
        |hour|article_id|count|
        |----|----------|-----|
        |  00|       830| 3105|
        |  01|       155| 4933|
        |  02|       830| 2914|
        |  03|       374| 5404|
        |  04|       374| 6139|
        |  05|       897| 4418|
        |  06|       813| 3214|
        |  07|       740| 2517|
        |  08|       712| 3045|
        |  09|       712| 1937|
        |  10|       827| 6702|
        |  11|       827| 7198|
        |  12|       827| 6428|
        |  13|       827| 5518|
        |  14|       827| 4806|
        |  15|        67| 6942|
        |  16|       827| 3139|
        |  17|       871| 2274|
        |  18|       827| 1072|
        |  19|       827|  696|
        |  20|       827|  391|
        |  21|       827|  430|
        |  22|        85| 1636|
        |  23|        85| 4229|

- 1d:
    - average number of pageviews per person: 2.400 (approx. to 3 dec.) 
    - median number of pageviews per person: 1.0 (approx. to 1 dec.)

## Q2.
- 2a:
    - number of sessions: 774,587
- 2b:
    - user_id with largerest nubmer of sessions: c82275f3
    - corresponding sessions number: 39
- 2c:
    - average session length: 144.024 sec (approx. to 3 dec.)
    - median session length: 0.0 sec (approx. to 1 dec.)

## Remarks: 

concerning the dataset certain missing ids are found:

|server_ts|e_n|uid|device|server_dt|article_id|
|---------|---|---|------|---------|----------|
|        0|  0|119|     0|        0|        31|

Yet as the missing data does not greatly affect the analysis. No data removal is done to retain data.