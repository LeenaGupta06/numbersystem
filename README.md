# numbersystem
const numbers = [
    3, 7, 2, 15, 9, 20, 5, 14, 12, 1, 8, 11, 6, 19, 4, 10, 17, 13, 16, 18,
  ];
  const evennumbers = [];
  const oddnumbers = [];

  for (let i=0; i<numbers.length; i++){
    if (numbers[i]%2===0){
        evennumbers.push(numbers[i])
    }else{
        oddnumbers.push(numbers[i])
    }
  } 
  console.log(evennumbers);
  console.log(oddnumbers);

  
To find all the prime numbers
const numbers = [
  19, 23, 4, 16, 28, 13, 31, 8, 29, 14, 6, 35, 2, 11, 17, 5, 9, 27, 12, 30,
];

function isprime(num){
if (num<=1) {
console.log(num + 'is not prime');
}else {
let prime = true;
for (let i=2; i<=
