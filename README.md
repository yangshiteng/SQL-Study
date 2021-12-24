# SQL-Study

## SQL 175 

![image](https://user-images.githubusercontent.com/60442877/147315998-82c4f160-963b-4884-a709-8fa4ecfae1a6.png)

select P.firstName, P.lastName, A.city, A.state
from Person as P left join Address as A on P.personId = A.personId
