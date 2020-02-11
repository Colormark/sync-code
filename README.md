## Promise.all
```javascript  
Promise.all([
    fetch('style.json')
        .then(function (res) {
            return res.json();
        }),
    fetch('data.json')
        .then(function (res) {
            return res.json();
        })
])
    .then(function (dataArray) {
     

    });
```
