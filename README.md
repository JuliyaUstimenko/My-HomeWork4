# My-HomeWork4
const num = (A, B) => {
    if (A === B){
      return B;
    } else if(A < B) {
      return A + ' ' +num(A + 1, B);
    }else {
      return num(A, B + 1) +' ' + B;
    }
  };
  console.log(num(15, 1));
