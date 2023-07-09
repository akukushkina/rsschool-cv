# Anastasiia KUKUSHKINA
## Web Developer

## Contacts:

- E-mail: <akyukyushkina@gmail.com>
- Phone: +447387984723
- LinkedIn: <https://www.linkedin.com/in/anastasiia-kukushkina-904778182/>

## About Me:

As a web developer, I focus on developing and implementing responsive and user-friendly web applications. I utilize my skills in HTML, CSS, and
JavaScript to create visually appealing websites that adhere to coding standards and best practices. I am proficient in troubleshooting and debugging
issues, ensuring the smooth functionality of the websites I work on. This experience enhances my technical abilities and reinforces my attention to
detail in writing clean and well-documented code. 

## Skills:

- HTML5
- CSS3
- SASS
- JavaSript
- SQL
- GIT
- BEM

## Certificates

- Front End Pro (Hillel IT School)
- Data and SQL (Code First Girls)


## Code Samples

Change background on click

```
const button = document.querySelector('.change');
const colorName = document.querySelector('.color__name');
const colors = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 'A', 'B', 'C', 'D', 'E', 'F'];

button.addEventListener('click', function(){
   let hexColor = '#';
   for(let i = 0; i < 6; i++){
     hexColor += colors[changeColor()];
   }
   colorName.textContent = hexColor;
   document.body.style.backgroundColor = hexColor;
});

function changeColor(){
   let color = Math.floor(Math.random() * colors.length);
   return color;
}

```

## Education

National University Odesa Law Academy
Specialist
Law
09/2013 - 05/2017

## Languages

- Ukrainian (Native)
- English (Fluent)
- German (Begginer)

## Portfolio

- Change background color on click <https://akukushkina.github.io/change_color/>
- Landing page for school <https://akukushkina.github.io/school/>
- Split effect <https://akukushkina.github.io/split/>
- Sound board <https://akukushkina.github.io/sound_board/>
- Dad jokes <https://akukushkina.github.io/dadJokes/>
- Landing page for web developer <https://akukushkina.github.io/web__pages/>
