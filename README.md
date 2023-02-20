### Screenshot

![](./screenshot.png)


### Links

- [URL](https://rollingdicebilska.netlify.app/)

### Built with

- HTML
- CSS
- JavaScript


### What I learned


```js
const rollDice = random =>{
    dice.style.animation = 'rolling 4s';
    setTimeout(() => {
        switch(random){
            case 1:
                dice.style.transform = 'rotateX(0deg) rotateY(0deg)';
                break;
            case 6:
                dice.style.transform = 'rotateX(180deg) rotateY(0deg)';
                break;
            case 2:
                dice.style.transform = 'rotateX(-90deg) rotateY(0deg)';
                break;
            case 5:
                dice.style.transform = 'rotateX(90deg) rotateY(0deg)';
                break;
            case 3:
                dice.style.transform = 'rotateX(0deg) rotateY(90deg)';
                break;
            case 4:
                dice.style.transform = 'rotateX(0deg) rotateY(-90deg)';
                break;
            default:
                break;
        }
        dice.style.animation = 'none';
    }, 4050);
}
```


## Author

- Based on - [AsmrProg](https://www.youtube.com/watch?v=HuEBqPpQkMw)
