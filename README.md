# My-HomeWork4
function getSum(num) {
        let sum = 0, n;
        while (num) {
            n = num % 10;
            num = (num - n) / 10;
            sum += n;
        }
        return sum;
    }
    console.log(getSum(365));
    