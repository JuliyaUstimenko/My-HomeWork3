# My-HomeWork3
function map(fn, array){
   let narr = [];
     for(let i = 0; i < array.length; i++){
       narr.push(square(array[i]))
   }      
    return narr
    }
    console.log(map(square, [1,3,5,7])); 
