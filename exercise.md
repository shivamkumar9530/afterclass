#Multiple choice

-in the following code how can you get the card flip


```html
const pics = [...document.querySelectorAll('[class^="card"]')];
function flip(){
    console.log(this);
    this.classList.add("flip");
}
```


1.for(let i = 0; i < pics.length; i++){
    pics[i].addEventListener("click", flip);
}
2.for(let i = 0; i < pics.length; i++){
    pics[i].addEventListener("Onclick", flip);
}
3.for(let i = 0; i < pics.length; i++){
    pics[i].addEvent("click", flip);
}
4.for(let i = 0; i < pics.length; i--){
    pics[i].addEventListener("click", flip);
}
