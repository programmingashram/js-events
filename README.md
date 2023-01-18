Event is basicllay allow us to add an trigger for the changes, like when user click a button then something will come.🚀

### There are many types of events
    1. 📁 onclick Event
    2. 📁 onChange Event
    3. 📁 Onkeyup Event (Key - Keyboard button)
    4. 📁 OnKeydown Event
    
  
  
#### Onclick Event🧩

>  That is allow us to add a trigger in html ***element***, that will execute the changes when element is **clicked**.

***📝index.js***
```
function test(){
    let element = document.querySelector('.content');
    element.style.backgroundColor = "red";
    element.style.color = "white";
    element.style.padding = "10px";
}
```

***📝index.html***

```
<div class="content" onclick="test();">
    <h1>
        Heading
    </h1>
    <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic fuga officiis laborum maiores iste atque inventore a. Sapiente dolore repellat consectetur similique eius dignissimos quidem, nobis, fugit molestias, doloribus dicta.
    </p>
</div>
```
<hr>
 
 
#### 🧩 Onchange Event 
>      With the help of onchange event, we can get the values from input, when we click outside of input.
      
 ***index.js***
```
function test2(){
    let element = document.getElementById('input');
    console.log(element.value);
}
```

***index.html***

```
<form action="">
    <input type="text" value="Shivam" placeholder="Type Something" id="input" onchange="test2();"/>
</form>
 ```
<hr>
 
#### 🧩Onkeyup Event 
>      With the help of Onkeyup Event, we can get the values from input when user realse the key of keyboard.
      
***📝index.js***
```
function test2(){
    let element = document.getElementById('input');
    console.log(element.value);
}
```

***📝index.html***

```
 <form action="">
    <input type="text" value="User Input" placeholder="Type Something" id="input" onkeyup="test2();"/>
 </form>
 ```
<hr>
 
#### 🧩Onkeydown Event 
> With the help of Onkeydown Event, we can get the values from input when user down(push) the key (button) of keyboard.
      
      
***📝index.js***
```
function test2(){
    let element = document.getElementById('input');
    console.log(element.value);
}
```

***📝index.html***

```
 <form action="">
   <input type="text" value="user inpur" placeholder="Type Something" id="input" onkeydown="test2();"/>
 </form>
 ```
