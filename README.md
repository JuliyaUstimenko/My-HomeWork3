# My-HomeWork3
let arr = [1,'test','text',444];
 function getLength(arr) {
     if(!arr || !Array.isArray(arr)){
        alert("Error!");
         return 0;
     }
     return arr.length;
 }
 console.log(getLength(arr));
