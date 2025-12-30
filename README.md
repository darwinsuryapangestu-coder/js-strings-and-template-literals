# js-strings-and-template-literals
Practice project on JavaScript strings and template literals(Jonas Schmedtmann course. 

const firstName = 'Darwin';
const job = 'Manager';
const birthYear = 1989;
const year = 2025;

const darwin = "I'm " + firstName + ', a ' + (year - birthYear) + ' years old ' + job + '!';
console.log(darwin);

const darwinNow = `I'm ${firstName}, a ${year - birthYear} years old ${job}!`;
console.log(darwinNow);

console.log('Just a regular string...');

console.log(`String with \n\
multiple \n\
lines`);

console.log('String multiple lines');
