  ------   :1 

    ----||   :1 and only 1 

    ----o|   :0 or 1 

    -----{   :many 

    ----|{   :1 or more (1以上) 

    ----o{   :0 or many (0以上) 

  

 

これだと縦につながる 

customer       |o--o{     order 

order          ||--|{     order_detail 

order_detail    }--||     items 

items          }o--||     category 

  

 

left    le 

right   ri 

up      up 

down    do 

  

  

'/ 

 

customer       |o-ri-o{     order 

order          ||-ri-|{     order_detail 

order_detail    }-do-||     items 

items          }o-le-||     category 
