# Country-code-basic-SQL-Hacker-rank
<pre>SELECT C.CUSTOMER_ID,C.NAME,
      CONCAT("+",CC.COUNTRY_CODE,C.PHONE_NUMBER)
        FROM CUSTOMERS C 
          JOIN COUNTRY_CODES CC ON C.COUNTRY=CC.COUNTRY
<pre/>
                                                          
                                                          <img algn="right" alt="coding durgesh kumar" width ="70" height="70" align="left" src="https://media3.giphy.com/media/H4zuMszyEiULul0iq0/giphy.gif?cid=6c09b9528xckz63n8lbuucquyonvwkden20wd19ocjeqtgri&rid=giphy.gif&ct=s">
