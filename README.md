# My-HomeWork3
function ucfirst(str) {
    return str[0].toUpperCase() + str.substr(1, str.length)
  }
   let str = 'hello'
   str = str.split(' ').map(function(item){
    return ucfirst(item);
  })
  console.log(str);
  