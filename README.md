# My-HomeWork3
let age = prompt('Введите возраст');
 function checkAge(n) {
    n = n || undefined;
     if(n === undefined){
         alert('Введите возраст!');
        return;
     }
     if (n >= 16) {
        alert('Добро пожаловать');
    } else {
         alert('Вы еще молоды')
     }
 }
 checkAge(age);