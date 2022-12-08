11. Webiste Name: [realme](https://www.realme.com/in/)

### Topics

       querySelector,style,background-image

### Sample Image

![Sample One](./Pic20.png)

### Tasks

    change the realme logo to ineuron logo

### Output

![Output](./Pic21.png)

### code


const list =document.querySelector(".logo.gtag")

       const image = document.createElement("img")
           image.src="https://ineuron.ai/images/ineuron-logo.png";
            list.appendChild(image);
            image.style.width="200px";
           list.removeChild(list.firstElementChild);
           
