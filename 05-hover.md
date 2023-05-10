# 今日の演習（05-hover)

## CSSアニメーション（hover)

### **【ソースコード】**

```html
    <div id="section1">
        <h3>① :hover</h3>
        <div class="section">
            <div class="button1-1" class="button">①color</div>
            <div class="button1-2" class="button">②width</div>
            <div class="button1-3" class="button">③transform</div>
            <div class="button1-4" class="button">④transform</div>
        </div>
    </div>
```

```css
    .button1-1{
        width:200px;
        height: 55px;
        background-color: rgb(173, 253, 253);
        border-radius: 50px;
        text-align: center;
        padding-top:30px;
    }

    .button1-1:hover{   /*疑似クラス:選択されたときに特定の状態を指定する*/
        background-color: rgb(51, 124, 124);    /*色を変化*/
        color:#fff;
    }
```
