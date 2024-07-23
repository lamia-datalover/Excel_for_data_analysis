# How to use concatenate :
This formula joins two or more text strings into one string .
<br>
=CONCATENATE(B2,"",C2) , it means that there will be a space between B2 and C2.
![concatenate](https://github.com/user-attachments/assets/416b631a-906a-41c0-b5a0-107f03f94201)
<br>
In case you want to create an adress mail using the first name and last name you can do the following:
<br>
=CONCATENATE(B2,".",C2,"@gmail.com")
<br>
![mails](https://github.com/user-attachments/assets/7a8e65e3-d14b-4476-be42-a1eda737f192)
# How to use substitute :
It replaces existing text with new text in a text string
<br>
=SUBSTITUTE(H2,"/","-"), it means that in the H2 we want to replace / by -
<br>
![sub1](https://github.com/user-attachments/assets/86ca0fc3-c4f1-4472-a827-09bd5f346f21)
<br>
=SUBSTITUTE(H2,"/","-",1) , to substitute only the first / with -
<br>
![1instance](https://github.com/user-attachments/assets/8bcb8d59-29ee-4501-bd7c-67cf4e892802)
<br>
=SUBSTITUTE(H2,"/","-",2) , to substitute  only the second / with -
<br>
![2instance](https://github.com/user-attachments/assets/d35e9a35-9700-468d-92ec-766e6fb3f48a)
# How to use SUM/SUMIF/SUMIFS:
SUM adds all the number of a range 
<br>
=SUM(G2:G10)
<br>
![somme](https://github.com/user-attachments/assets/8620370d-a658-4fd4-93ee-ed25f640fddf)
