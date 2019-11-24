# My-HomeWork3
arr = [[[1, 4], [3, 7]], [[5, 7], [8, 10]]];
sum = 0;
for(let i = 0; i < arr.length; i++) {
  for(let j = 0; j < arr[i].length; j++) {
    sum += arr[i][j].reduce(function(sum, item) {
    return sum + item;
    })
  }
}
console.log(sum);