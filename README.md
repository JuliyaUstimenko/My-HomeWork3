# My-HomeWork3
let take = function sequence(fn, count){
    let arr = [];
    for(let i=0; i<count; i++){
     arr[i] = fn();
    }
    return arr;
   }
let gen2 = sequence(0, 2);
console.log(take(gen2, 5)); 


