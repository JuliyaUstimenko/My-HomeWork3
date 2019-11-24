# My-HomeWork3
let n = prompt ('Введите число:');

 function getResult(x) {
   if(x > 10) {
        return Math.pow(x, 2);
    } else if(x < 7) {
         return 'Число меньше 7-ми.';
     } else if (x == 8) {
         return 7;
    } else if (x == 9){
         return 8;
     }
 }
 console.log(getResult(n));
