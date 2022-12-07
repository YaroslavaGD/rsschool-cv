# Yaroslava Hryzadubova

## Junior Frontend Developer

## Contact information:

* __Phone:__ +38 050 2194008
* __E-mail:__ yaroslava.gd@gmail.com
* __Telegram:__ @yaroslava_gd

## Briefly About Myself:

Bla-bla

## Skills and Proficiency:

* HTML5, CSS3
* JavaScript
* Git, GitHub
* VS Code, IntelliJ IDEA
* Adobe Photoshop, Figma

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

## Education:
Donetsk National Technical University
Faculty of computer information technologies and automation
Years: 2010-2017
Specialization: 

## Languages:
* English - Basic (A2)
* German - Intermediate/Upper-intermediate (B2 - Telc)
* Russian - Native
* Ukrainian - Intermediate