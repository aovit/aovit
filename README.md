- 👋 Hi, I’m @aovit
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
aovit/aovit is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

//1) Programa una función que cuente el número de caracteres de una cadena de texto, pe. miFuncion("Hola Mundo") devolverá 10.
const myfunction = (str) => console.log(str.length);
myfunction("Hola Mundo");

//2) Programa una función que te devuelva el texto recortado según el número de caracteres indicados, pe. miFuncion("Hola Mundo", 4) devolverá "Hola".
const myFunction = (str, num) => console.log(str.slice(0, num));
myFunction("Hola Mundo", 4);

//3) Programa una función que dada una String te devuelva un Array de textos separados por cierto caracter, pe. miFuncion('hola que tal', ' ') devolverá ['hola', 'que', 'tal'].
const myStrSeparate = (str, separator) => console.log(str.split(separator))
myStrSeparate("hola que tal", ' ');

//4) Programa una función que repita un texto X veces, pe. miFuncion('Hola Mundo', 3) devolverá Hola Mundo Hola Mundo Hola Mundo.
const myStrRepeat = (str, num) => console.log(str.repeat(num))
myStrRepeat("Hola Mundo ", 3);

