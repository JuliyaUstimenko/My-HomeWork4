# My-HomeWork4
function numbers( n){
    if (n === 1){
    return 1;
}
     return n + numbers(n + 1);
}
  console.log(numbers(10 ));
