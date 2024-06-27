# Yaroslava Hryzadubova

## Frontend Developer

## Contact information:
* __E-mail:__ yaroslava.gd@gmail.com
* [__LinkedIn__](https://www.linkedin.com/in/yaroslava-hryzadubova-7725a4147/)
* [__GitHub__](https://github.com/YaroslavaGD)
* Address: Berlin, Germany

## Briefly About Myself:
Frontend Developer with 2 years of experience in developing web applications using JavaScript, HTML5, CSS3, SASS, and PHP. Specialized in designing user-friendly interfaces and solving complex problems. Experienced in working with React, Angular, e-commerce applications, and WordPress templates. At the moment I am in Berlin in search of work, learning German and English.

## Skills and Proficiency:
* Languages: JavaScript, TypeScript, HTML5, CSS3, SCSS, PHP
* Frameworks/Libraries: Angular, React, Redux, jQuery
* Tools: Webpack, NPM, Git, Jira, CommerceTools SDK, Jest, ESLint, Prettier, Husky, Mui, Formik, OpenCart, Wordpress, VS Code, IntelliJ IDEA, Adobe Photoshop, Figma

## Code example:
__Bouncings Balls from CODEWARS:__ _A child is playing with a ball on the nth floor of a tall building. The height of this floor above ground level, h, is known._
_He drops the ball out of the window. The ball bounces (for example), to two-thirds of its height (a bounce of 0.66)._
_His mother looks out of a window 1.5 meters from the ground._
_How many times will the mother see the ball pass in front of her window (including when it's falling and bouncing?_

_Three conditions must be met for a valid experiment:_
_Float parameter "h" in meters must be greater than 0_
_Float parameter "bounce" must be greater than 0 and less than 1_
_Float parameter "window" must be less than h._

_If all three conditions above are fulfilled, return a positive integer, otherwise return -1._

```
function bouncingBall(h, bounce, window) {
    let numDrops = 0
    let currentHeight = h;
    
    if (bounce >= 1 ||  bounce <= 0) return -1;

    while (currentHeight > window) {
        currentHeight *= bounce;
        numDrops = numDrops + 2;
    }

    return numDrops - 1;
}
```

## Experience:
September 2017 - July 2019: Fullstack Developer in Plscoach.Me, Kyiv, Ukraine
* Developed custom templates and an admin interface for WordPress (e.g., [InfoVision](https://infovision.ua/)).
* Created a library for linking delivery information.
* Integrated the Telegram API for order notifications on a pizza ordering website ([GoodChef](https://goodchef.com.ua/)).
* Improved user interactions and increased usability.
* Technologies Used: WordPress, jQuery, JavaScript, HTML5, CSS3, PHP, API Nova Post, Telegram API, OpenCart.

## Education:
* Donetsk National Technical University, Pokrovsk, Ukraine
* Faculty of computer information technologies and automation
* Years: 2010-2017
* Specialization: Software engineering

## Courses:
2023-2024: The Rolling Scopes School ([Angular 2023Q4](https://app.rs.school/certificate/okyxmx0t), [JavaScript/Frontend 2023Q1](https://app.rs.school/certificate/7na9vrj2))
2021-2022: German Courses (Goethe-Institut and VHS) in Berlin

## Languages:
* German (Upper-Intermediate, B2)
* English (Basic, A2)
* Ukrainian (Fluent)
* Russian (Fluent)