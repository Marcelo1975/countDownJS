# Conut Down With Pure JavaScrip

```HTML
<span id="countdown">10</span> Restantes <br>
<textarea onkeyup="countDouw(this.value)" id="text"></textarea>
```

```JAVASCRIP
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

> Por m18web

[Site](https://m18web.com.br)
