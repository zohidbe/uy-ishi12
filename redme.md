# JavaScript String Metodlari

JavaScript dasturlash tilida string-ler bilan ishlash uchun ko'p qo'llaniladigan metodlar mavjud. Ular orasida:

## 1. `length` Metodi

Bu metod string uzunligini qaytaradi:

```javascript
let str = "Salom, dunyo!";
let length = str.length;
console.log(length); // 13
2. charAt(index) Metodi
Berilgan indeksdagi belgini qaytaradi:


2. charAt(index) Metodi
Berilgan indeksdagi belgini qaytaradi:

javascript\
Copy code
let str = "Salom, dunyo!";
let char = str.charAt(3);
console.log(char); // o
3. indexOf(substring) Metodi
Berilgan qatorni (substring) boshidan qidiruv natijasida birinchi indeksni qaytaradi:


3. indexOf(substring) Metodi
Berilgan qatorni (substring) boshidan qidiruv natijasida birinchi indeksni qaytaradi

javascript
Copy code
let str = "Salom, dunyo!";
let index = str.indexOf("dunyo");
console.log(index); // 7
4. slice(start, end) Metodi
Berilgan oraliqdagi qismini kesib olish:


4. slice(start, end) Metodi
Berilgan oraliqdagi qismini kesib olish:


javascript
Copy code
let str = "Salom, dunyo!";
let sliced = str.slice(7, 12);
console.log(sliced); // dunyo