const getSquare = (num) => {
  return num * num;
};

export default getSquare;

const isEven = (num) => {
  return num % 2 === 0;
};

export default isEven;
const castNumber = (value) => {
  const num = Number(value);
  if (Number.isNaN(num)) {
    return 'given value is not convertible';
  }
  return num;
};

export default castNumber;
const checkType = (value) => {
  return typeof value;
};

export default checkType;
const countVowels = (text) => {
  const vowels = ['a', 'e', 'i', 'o', 'u'];
  let count = 0;

  for (let i = 0; i < text.length; i++) {
    const char = text[i].toLowerCase();
    if (vowels.includes(char)) {
      count++;
    }
  }

  return count;
};

export default countVowels;
