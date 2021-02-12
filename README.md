# calculator 만들기(1) 
## javascript
---

1️⃣ delete 기능

```js
const del = document.querySelector(".del");

del.addEventListener("click", (e) => {
    input.value = input.value.slice(btnClick.length, -1);
});
```



2️⃣ 초기화(AC) 기능

```js
const reset = document.querySelector(".clear");

reset.addEventListener("click", (e) => {
    input.value = "";
});
```



3️⃣ 연산 기능

```js
const resultBtn = document.querySelector(".result");

resultBtn.addEventListener("click", (e) => {
    input.value = eval(input.value);
});
```
