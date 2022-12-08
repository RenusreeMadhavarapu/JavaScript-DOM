8. Webiste Name: [Google](https://www.google.com/)

### Topics

       Remove Elements

### Sample Image

![Sample One](./Pic14.png)

### Tasks

     Remove alternate languages from the home page languages listed

### Output

![Output](./Pic15.png)

### code


    const list = document.getElementById("SIvCob");
    list.removeChild(list.firstElementChild);

    //to remove at certain position
     list.removeChild(list.children[i]);

    to remove upto certain index
    const list = document.getElementById("SIvCob");
     let total=list.children.length
      console.log(total)
    for (let i=0;i<total/2;i++) {

    list.removeChild(list.children[i]);
    }
