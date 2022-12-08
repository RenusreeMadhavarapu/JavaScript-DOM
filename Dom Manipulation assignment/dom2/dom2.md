2. Website Name: [Apple](https://support.apple.com/en-in)

### Task

![Store](./Picture_3.png)

### Fetch all the product name and store in an array

### Output

['iPhone', 'Mac', 'iPad', 'Watch', 'AirPods', 'Music', 'TV']

### code

     const array1=document.querySelectorAll(".as-imagegrid-item-title .a11y")
        array1.forEach(e => {

             e.innerText="";
           
        });
     const array2 =document.querySelectorAll(".as-imagegrid-item-title")
     const final=[];


        array2.forEach(element => {

            final.push(element.innerText);

            
        });
        console.log(final);
     
