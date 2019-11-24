# My-HomeWork3
str = 'var_text_hello';
let arr = str.split('_');
for(let i = 1; i < arr.length; i++) {
  arr[i] = ucfirst(arr[i]);
}
str = arr.join('');
console.log(arr);

