# Elena Lisichenok

## Junior Frontend Developer

### Contacts

**Phone:** +7 (952) 207 52 66
**E-mail:** elisichenok@gmail.com
**Telegram:** @panilisica
**Discord:** elena-lis


### Personal Statement

Being a certified historian, I worked for eight years in the field of culture, but decided to become a front-end developer, since this profession involves continuous self-improvement and involvement in the world of modern technologies.


I started my acquaintance with HTML, CSS and JavaScript with code-simulators, but the magic of code writing quickly fascinated me, so I started studying web development at one of the well-known online schools. Here I completed several training projects, developed skills and work speed, worked in a team in conditions close to real development.


I like challenging problems because solving them inspires me to develop further.


### Skills

* HTML5, CSS3
* Sass
* JavaScript/ES6 Basics
* Git, GitHub
* VS Code
* Figma
* Gulp Basics


### Code Example

![My Codewars Profile](https://www.codewars.com/users/lena-lis/badges/large "My Codewars Profile Badge")

**Find the missing element between two arrays:** *given two integer arrays where the second array is a shuffled duplicate of the first array with one element missing, find the missing element.*

```
function findMissing(arr1, arr2) {
  let dictionary = {};
  arr1.forEach((element) => (element in dictionary) ? dictionary[element] += 1 : dictionary[element] = 1);
  arr2.forEach((element) => (element in dictionary) ? dictionary[element] -= 1 : dictionary[element] = 1);
  for (let key in dictionary) {
    if (dictionary[key] > 0) return +key;
  }
}
```