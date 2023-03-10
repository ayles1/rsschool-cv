# Dmitriy Seliverstov

### Frontend developer

---

##### Contact information:

###### Phone: +7 999 164 27 44

###### Email: ayles1113@gmail.com

###### Telegram: @ylokas

---

### About me:

I'm 19 years old and currently learning to become a frontend developer. I can study for 12-14 hours a day, because its very interesting for me.And i hope i am studying fast enough.I am studying not only coding, but other interesting related things i hope help me in job in future.

---

### Stack:

- HTML
- CSS, SCSS, Tailwind CSS, Material UI , BEM
- JavaScript (Basics, ES6 syntax, Asynchronous JS, Browser API, DOM, basic-middle algorithms)
- TypeScript
- React, Redux(Saga,React,Persist)
- Web Socket API, Telegram API
- Node JS (Express, NestJS)
- Git, GitHub

---

### Code Example

> Leet Code find longest palindrome task

```
var longestPalindrome = function(str) {
    const dict = {}
    let sum = 0
    hasOdd = false
    str.split('').map((l)=>dict[l]?dict[l] += 1 : dict[l] = 1)
    for(let str in dict){
        if(dict[str] % 2 === 1){
            hasOdd = true
            if(dict[str]>2){
                sum += dict[str] - 1
            }
        }else{
            sum += dict[str]
        }
    }
    if(hasOdd){
        sum+=1
    }
    return sum
};
```

### Experience :

- Nail salon - https://github.com/ayles1/Nail-salon
- Mini games - https://github.com/ayles1/mini-games

### Languages

- ###### Russian - native
- ###### English - Upper-intermediate
- ###### French - Beginner
