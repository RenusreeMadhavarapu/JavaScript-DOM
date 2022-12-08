10. Webiste Name: [Freecodecamp](https://www.freecodecamp.org/)

### Topics

       querySelector, mouseover, click eventListener,  callback function, style,

### Sample Image

![Sample One](./Pic18.png)

### Tasks

    Target the button and change background colour on mouseover

### Output

![Output](./Pic19.png)

### code


const list = document.querySelector(".login-btn-text")
 list.addEventListener('mouseover' ,myFun)


function myFun(){
document.querySelectorAll(".login-btn-text")[1].style.backgroundColor="red";
}