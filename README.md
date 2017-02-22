# a-simple-Mvvm
基于getter和setter的一个简易Mvvm

```html
<input type="text" v-model="hello" value="">
    <div id="template">
        {{hello}}
    </div>
    <div class="template">
        {{bind}}
 </div>
 ```
 ```js
    var vue = new Vue({
        ele: '#template',
    });
    var vue1 = new Vue({
        ele: '.template',
        data: {
            bind: 'hey i am a vue lover'
        }
    })
```
