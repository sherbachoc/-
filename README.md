export const multiplyTwoNumbers = (a, b) => a * b;
export const getMaxNumber = (a, b) => Math.max(a, b);
export const castReversedBoolean = (value) => !value;
export const determineEntrance = (num) => {
  if (num >= 1 && num <= 20) { return 1; }
  if (num >= 21 && num <= 48) { return 2; }
  if (num >= 49 && num <= 90) { return 3; } return 0;
};
export const getSum = (num) => {
  if (num === 0) return 0;
  return Array.from(String(num), Number).reduce((a, b) => a + b, 0);
};
