# Се темаи мухим :
+ **1.Condition**
+ **Loops**
+ **Functions**
---
# Condition `if-else`
+ **if-else ин як блок кодехай ки агар if шартмон дуруст шудак дуруш медроя кор мекна агар набоша else кор мекна**
+ # Мисол :
+ ```javaScript
  if(true){
  console.log("seb")
  }
  else{
  console.log("Nok")
  }
  ```
  ![Снимок экрана 2024-09-10 135502](https://github.com/user-attachments/assets/7765d870-668e-4a4a-bdfd-6266fe7daf9b)

  ---
  # Condition ```Ternary operator``` :
+   **```ternary operator``` ин як шакли кутохи if-else мебошад**
+   **Соддагии истифода: Ternary operator барои ифодаҳои кӯтоҳ ва содда мувофиқ аст, ки дар як сатри код навишта мешаванд. If-else барои ифодаҳои мураккаб ва дароз мувофиқ аст, ки метавонанд якчанд сатри кодро дар бар гиранд.**
# Истифода бурдани ternary operator Мисол:
```java
console.log(10 == 10 ? "Run1" : 20 == 20 ? "Run2" : 30 == 30 ? "Run3" : null)
```
![](https://www.atatus.com/blog/content/images/2023/03/java-ternary-operator.png)

---
# Condition `Switch Case` :
 ### Switch Caseин як блок Мкоде буда ки элемента месанча агар монанд бошан функция кор мекна
 ![](https://www.programiz.com/sites/tutorial2program/files/javascript-switch-statement_0.png)
 ## Мисол двр код:
```JavaScript
let m = "2"
switch(m){
  case "1":
    console.log("Jun")
    break
  case "2":
    console.log("Feb")

  case "3":
      console.log("March")

  default :
    console.log("12 <= m")
}
```
---
# Loop `For`
## For ин як операторай ки цикл месоза ва дар дурунш 3 параметр дора 
![](https://www.tutorialspoint.com/javascript/images/for_loop.jpg)
### Мисол дар код:
```
let str = '';

for (let i = 0; i < 9; i++) {
  str = str + i;
}

console.log(str);
```

# Loop `while`
**Дастури while ҳалқаеро эҷод мекунад, ки
ин дастурро то он даме иҷро мекунад, ки
шарти санҷишӣ арзиши ҳақиқиро қабул намекунад. 
Шарт пеш аз иҷро ҳисоб карда мешавад
дастурҳо. Давраи навбатии while
то он даме, ки n аз се камтар шавад, такрор мешавад.
Эзоҳ: барои қатъ кардани оператори танаффус Истифода Баред
пеш аз он ки шарт арзиши ҳақиқиро қабул кунад, давр занед.**
![](https://cdn.educba.com/academy/wp-content/uploads/2019/11/Do-While-Loop-in-JavaScript-main.png)
```
let n = 0;

while (n < 3) {
  n++;
}

console.log(n);
```

---

# Loop `do while`
**Дастури do...while давра эҷод мекунад
, ки ин дастурро то
то он даме, ки шарти санҷишӣ арзиши false-ро қабул намекунад. 
Шарт пас аз иҷро ҳисоб карда мешавад
дастурҳо, ки дар натиҷаи он нишон дода шудааст
дастурамал ҳадди аққал як маротиба иҷро карда мешавад. Дар
мисоли зерин давраи do аст...while
ҳадди аққал як маротиба иҷро карда мешавад ва то он даме, ки арзиши i
на камтар аз 5**

# Се роҳи сохтани функсия дар JavaScript

## 1. Function Declaration
Ин усули анъанавии эълон кардани функсия мебошад.

```javascript
function add(a, b) {
    return a + b;
}
console.log(add(2, 3));
```
# 2.function Expression 
### Дар ин усул, функсия ҳамчун ифода эълон карда мешавад ва ба тағйирёбанда таъин карда мешавад.
```
const add = function(a, b) {
    return a + b;
};
console.log(add(2, 3)); 

```
 # 3. Arrow Function
**Ин усули кӯтоҳшудаи эълон кардани функсия мебошад, ки дар ES6 муаррифӣ шудааст.**

```
const add = (a, b) => a + b;
console.log(add(2, 3)); 

```



