## Aleksiej Kuncewicz

## Contact Info

- E-mail: aleksiej.kuncewicz@gmail.com
- Linkedin: [Aleksiej Kuncewicz](https://pl.linkedin.com/in/aleksiej-kuncewicz)

## Summary

Good quality of code is important for me as people I work with. I always try to follow code principles like DRY, YAGNI, KISS and so on. I think leaving comments is good only when the code is complex. Anyway, you should write code which other developers can understand without any ‘hints’.

Moreover, I like to learn new things and implement them in project I participate. I always have a lot of ideas and inspiration to share with.

I prefer to meet deadlines and sometimes complete tasks earlier. I am an initiative developer with a strong math mind. And I would like to meet people like me in my future job.

## Skills

_Good knowledge_: HTML, CSS, SASS, JS, MySQL, React JS, GIT, NPM, Yarn, REST API, respon/adapt design

_Strong basic knowledge_: Python, Java, PHP, Automatyka i Robotyka, Blender, PostegreSQL, Bootstrap, node.js, jquery, XAMPP

## Code example

### Codewars Task: Duplicate Encoder

The goal of this exercise is to convert a string to a new string where each character in the new string is `<(>` if that character appears only once in the original string, or `<)>` if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.

#### Examples

`<din>` => `<(((>`

`<recede>` => `<()()()>`

`<Success>` => `<)())())>`

`<(( @>` => `<))((>`

#### Notes

Assertion messages may be unclear about what they display in some languages. If you read `<...It Should encode XXX>`, the `<XXX>` is the expected result, not the input!

```javascript
function duplicateEncode(word) {
  const leftParenthesis = String.fromCharCode(40),
    rightParenthesis = String.fromCharCode(41);
  var changedWord = "";
  word = word.toLowerCase();
  for (let i = 0; i < word.length; i++) {
    let character = word.charAt(i);
    changedWord +=
      word.lastIndexOf(character) == word.indexOf(character)
        ? leftParenthesis
        : rightParenthesis;
  }
  return changedWord;
}
```

## Experience

- Writing code in the university on c++, java, JS, assembler
- Solving tasks in [Codewars](https://www.codewars.com/users/Aleksiej)
- Create react project using [The Rick and Morty API](https://rickandmortyapi.com/). [GitHub Repository](https://github.com/losha97/api-example-rick-morty)
- Create web app for adding, changing and deleteing questions with answers from/to database and generating PDF doc by FPDF) using PHP, JS, XAMPP, FPDF library with OOP

## Education

- 2013/09 – 2016/04 - ZSOiT III Liceum Ogólnokształcące im. Jędrzeja Śniadeckiego Technikum w Jeleniej Górze
- 2016/10 – 2020/03 - Politechnika Wrocławska Filia w Jeleniej Górze
  - Kierunek: Informatyka Przemysłowa
  - Specjalność: Inteligentne Systemy przemysłowe
- 2019/11/25 - completed and certificated the KNX eCampus ETS Course

## Languages

#### English

Learning in primary elementary, middle and high school

#### Polish

Native

#### Russian

Native
