# My-HomeWork3
arr = [[4, 5, 1], [4, 3], [3]];
sum = 0;
for(let i = 0; i < arr.length; i++) {
  sum += arr[i].reduce(function(sum, item) {
    return sum + item;
  })
}
console.log(sum);
