# Beecrownd 


* Atividade 2602 - Nível 4
  
  <img width="1087" height="76" alt="2602" src="https://github.com/user-attachments/assets/9f493f88-4cf5-4713-a8ef-7f3ad32a195b" />
  
  <img width="1129" height="304" alt="2602 - accepted" src="https://github.com/user-attachments/assets/f23ae2e9-9efa-4b16-9beb-be8c3afffe44" />

  
``` sql
SELECT
	A.name AS CLIENT
FROM
	customers AS A
WHERE
	A.state = 'RS';
```


* Atividade 2603 - Nível 1
  
  <img width="1080" height="32" alt="2603" src="https://github.com/user-attachments/assets/5b958c1e-181e-459a-8867-ccb5c6141a2a" />
  
  <img width="1085" height="307" alt="2603 accepted" src="https://github.com/user-attachments/assets/94db8ae8-f64f-45ad-b4dc-31414bd19a56" />
  

  ``` sql
  SELECT
  	A.name AS NAME,
  	A.street AS STREET
  FROM
  	customers as A
  WHERE
  	city = 'Porto Alegre';
  ```

  
* Atividade 2607 - Nível 1
  
  <img width="1089" height="40" alt="2607" src="https://github.com/user-attachments/assets/e423e46c-d14e-41f6-9985-01f0b3bf5420" />
  
  <img width="1086" height="307" alt="2607 accepted" src="https://github.com/user-attachments/assets/29c50d51-d9c2-4fee-8e18-5117ce3bf4e9" />


  ``` sql
  SELECT 
    A.city AS CITY
  FROM 
      providers AS A
  ORDER BY 
      city ASC;
  ```


* Atividade 2604 - Nível 2
  
  <img width="1081" height="35" alt="2604" src="https://github.com/user-attachments/assets/74cb2c71-2bf3-49a2-a660-92f805a1e5bd" />
  
  <img width="1088" height="300" alt="2604 accepted" src="https://github.com/user-attachments/assets/c5b11953-3f9e-48a5-9feb-7772a91ff58d" />

``` sql
SELECT 
    A.id AS ID,
    A.name AS NAME 
FROM 
    products AS A
WHERE 
    price < 10 or price > 100;
```


* Atividade 2610 - Nível 3

  <img width="1089" height="42" alt="2710" src="https://github.com/user-attachments/assets/8f148264-0128-4012-8f16-c17261483b8a" />
  
  <img width="1092" height="317" alt="2610 accepted" src="https://github.com/user-attachments/assets/affa7a74-f7c2-4ab9-8941-61ff30d948a2" />

  ``` sql
  SELECT 
    ROUND(AVG(A.price), 2) AS AVERAGE_RODUCTS
  FROM 
    products AS A;
  ```

  * Atividade 2608 - Nível 1
    
    <img width="1084" height="41" alt="2608" src="https://github.com/user-attachments/assets/3a026b41-f51e-4ada-a59f-5c2a1a1468a2" />
    
    <img width="1080" height="313" alt="2608 acceptde" src="https://github.com/user-attachments/assets/3fc31907-5613-4ed2-a7a2-0646ac4ce176" />
``` sql
    SELECT 
      MAX(price) AS price,
      MIN(price) AS price
  FROM products;
```

* Atividade 2744 - Nível 1

<img width="1073" height="38" alt="2744" src="https://github.com/user-attachments/assets/48c86de6-e9a5-4aad-bc14-fe3dc79dac61" />

<img width="1075" height="320" alt="27744 accpetd" src="https://github.com/user-attachments/assets/c91749f5-57a3-478f-a1cf-bf2b6382effc" />

  ``` sql
  SELECT 
    a.id AS id,
    a.password AS password,
    MD5(a.password) AS MD5
FROM 
    account as a;
  ```

* Atividade 2745 - Nível 3
  
  <img width="1084" height="39" alt="2745" src="https://github.com/user-attachments/assets/7bf017b3-3070-4e23-b64f-4a05067e725d" />

  <img width="1095" height="311" alt="2745 accepted" src="https://github.com/user-attachments/assets/913b5178-fb80-4dae-9c50-ae49ea095e0f" />

  
  ``` sql
    SELECT 
   A.name as name,
   ROUND(salary * 0.10, 2) AS tax
  FROM 
      people as A
  WHERE 
      salary > 3000;
  ```

  * Atividade 2624 - Nível 3
    
    <img width="1091" height="46" alt="2624" src="https://github.com/user-attachments/assets/75d553a8-e7ed-4859-808d-b006dc1e1302" />
    
    <img width="1068" height="332" alt="2624 accepted" src="https://github.com/user-attachments/assets/4c4450c4-6a0a-48e5-a9ee-c3c48d6dfaba" />

``` sql
    SELECT COUNT(DISTINCT city) AS count
FROM customers;
```

* Atividade 2615 - Nível 1
  
  <img width="1100" height="35" alt="2615" src="https://github.com/user-attachments/assets/2f3ff8a3-f8a2-4560-8c44-0b3091c3b617" />
  
  <img width="1058" height="296" alt="2615 accepted" src="https://github.com/user-attachments/assets/c75cbaf0-5d08-41db-a071-63384ec083c4" />

  
  ``` sql
  SELECT
  DISTINCT city
  FROM 
      customers as a;
  ``` 
