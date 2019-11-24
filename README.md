# My-HomeWork3
str = '123456';
arr = str.split('');
for(let i = 0; i < arr.length; i++) {
  if(i % 2 !== 0) {
    let b = arr[i - 1];
    arr[i - 1] = arr[i];
    arr[i] = b;
  }
}
str = arr.join('')
console.log(str)
