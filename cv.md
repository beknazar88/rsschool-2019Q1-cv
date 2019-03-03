# Igor Samartsev - Junior Front-End Developer
Kyrgyzstan, Bishkek.

<a href="tel:+996700075943" title="Mobile phone">+996700075943</a>

<a href="mailto:igorsamartsev@gmail.com" title="E-mail">igorsamartsev@gmail.com</a> 

## Summary
Hello.  
My name is Igor.  
I teach web coding in my city. I have more than 30 people studying offline.

My goal is to become a professional front-end developer and be in demand on the market. I really like what I do. I am willing to learn a lot and make myself better.

## Skills

- HTML
- CSS
- Bootstrap
- Basic knowledge of JavaScript
- SASS(SCSS)
- Git
- NPM
- Gulp
- Basic knowledge of Illustrator/Photoshop;
- Flexbox & basic of CSS Grid

## Code examples
```
module.exports = function getLoveTrianglesCount(preferences = []) {

  let count = 0;
  for (let i=0; i<preferences.length; i++){
    let number = preferences[i] - 1;
    let secondnumber = preferences[number] - 1;
    let lastnumber= preferences[secondnumber] -1;
    if (lastnumber == secondnumber) continue;
    if ((lastnumber) ==i ){
      count ++;
    }
 }
  return count/3;
};

```
```
module.exports = function makeExchange(currency) {
  let result = {
    "H": 50,
    "Q": 25,
    "D": 10,
    "N": 5,
    "P": 1
  }
  if (currency > 10000){
    return {error: "You are rich, my friend! We don't have so much coins for exchange"};
  }
  if (currency < 1){
    return  {};
  }

  result.H = Math.floor(currency/50);
  currency = currency -(result.H * 50);
  result.Q = Math.floor((currency / 25));
  currency = currency -(result.Q* 25);
  result.D = Math.floor((currency /10));
  currency = currency -(result.D * 10);
  result.N = Math.floor((currency /5));
  currency = currency -(result.N * 5);
  result.P = Math.floor((currency /1));

  for (let key in result) {
    if (result[key]===0) {
      delete result[key];
    }
  }
  return result;

}
```

## Experience
I worked as a web programmer at Sibers. Orders were from America, Canada and Australia. A little earlier, I worked on Russian freelancing for three years.

I am a website coding trainer, and therefore I improve every day. Great teaching experience.

Now I am actively studying react and redux.

## Education
Incomplete higher education in software engineering.
HTML Academy Html, Css
CodeCademy - Html, Css
Stepik - Python
Loftschool - Js course
## My english

I can read the documentation and can understand and use frequently-used everyday expressions as well as simple phrases to meet immediate needs.
March 4th I start offline English courses.