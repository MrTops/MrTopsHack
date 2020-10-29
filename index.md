# MrTopsHacks

**Intro**

> Hello user,
> 
> Thank you for using my website for hacks.
> 
> \- MrTops, Programmer

## Hacks

### Free-Rice-Hack
Free Rice Hack is a console command that automatically answers questions in the basic math pre-algebra section.
This section contains the instructions for injecting it and the code itself.

Free riced is a hack for **[free rice](https://freerice.com/categories/basic-math-pre-algebra)**

**CODE**
```js
let getCard = () => {
    try {
        let solution = eval(document.getElementsByClassName("card-title")[0].innerHTML.replace("x", "*").split("=")[0]);
        let cards = document.getElementsByClassName("card-button");
        if (cards[0].innerHTML == solution) cards[0].click();
        else if (cards[1].innerHTML == solution) cards[1].click();
        else if (cards[2].innerHTML == solution) cards[2].click();
        else if (cards[3].innerHTML == solution) cards[3].click();
        else cards[0].click();
    }
    catch {
        try {
            document.getElementsByClassName("card-button")[0].click();
        }
        catch {
            alert("FATAL ERROR");
        }
    }
};
setInterval(getCard, 1000);
```

**HOW TO INJECT & USE**
1. hit ```ctrl + shift + i``` to open the inspector
2. in the new page that opened go to the console tab
3. copy and paste the code and hit enter
4. if you get a error lmk

--

### Quizzlet Matching Hack
Pauses timer for quizzlet matching game.
I did **not** make this, I minified and converted it.

[quizzlet](https://quizlet.com/)

**CODE**
```js
for (var F = setTimeout(";"), i = 0; i < F; i++) clearTimeout(i);
```
*\`\`updated 10 - 23 - 2020 | removed auto answering, much smaller\`\`*

this hack will start when the enter key is hit in the last step, you might want to refresh the page to get a new timer and do the steps fast to get the lowest time

**HOW TO INJECT & USE**
1. hit ```ctrl + shift + i``` to open the inspector
2. in the new page that opened go to the console tab
3. copy and paste the code and hit enter
4. if you get a error lmk
