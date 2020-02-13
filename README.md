# Conut Down With Pure JavaScript

```HTML
<span id="countdown">10</span> Restantes <br>
<textarea onkeyup="countDouw(this.value)" id="text"></textarea>
```

```JAVASCRIPT
function countDouw(v) {
    quantity = 10;
    total = v.length;
    if(total <= quantity) {
        res = quantity - total;
        document.getElementById('countdown').innerHTML = res;
    } else {
        document.getElementById('text').value = v.substr(0,quantity);
    }
}
```

> By m18web

[Site](https://m18web.com.br)
