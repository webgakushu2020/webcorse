# 今日の演習（05-transition)

## CSSアニメーション(transition)

### **【ソースコード】**

```html
    <div id="section2">
        <h3>②transition + :hover</h3>
        <p>変化の仕方を指定するプロパティー</p>
        <div class="section">
            <div class="button2-1" class="button">①color</div>
            <div class="button2-2" class="button">②width</div>
            <div class="button2-3" class="button">③transform</div>
            <div class="button2-4" class="button">④transform</div>
        </div>
    </div>
```

```css
    .button2-1{
        width:200px;
        height: 55px;
        background-color: rgb(173, 253, 253);
        border-radius: 50px;
        text-align: center;
        padding-top:30px;

        transition:all 2s ease-in 0.5s; /*transition と :hover*/
    }

    .button2-1:hover{
        background-color: rgb(51, 124, 124);
        color:#fff;
    }
```
