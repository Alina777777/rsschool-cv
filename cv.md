# __rsschool-cv__
1. ### Labutina Alina
2. __Contact information:__
* Phone: +79210163921
* E-mail: Labutina_aa@mail.ru
3. __Briefly About Myself:__
_My education is completely different from the field of programming - this is music. However, I am very interested in what I started doing on the course at RS school and I believe, that my ability to learn quickly and my perseverance will lead me through this path of becoming a proficient Frontend Developer._
4. __Skills and Proficiency:__
* HTML5, CSS3
* JavaScript Basics
* Git, GitHub
* VS Code
* Adobe Photoshop
5. __Code example:__
Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.
```function peak(arr) {
  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```
6. __Courses:__ JavaScript/Front-end. Stage 0
7. __Languages:__
* English - Intermediate
