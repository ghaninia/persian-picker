<h1 dir="rtl">طریقه استفاده</h1>
<p dir="rtl">ابتدا شما باید پوشه asset را به پروژتون اضافه کنید بعد از اضافه کردن طبق دستور زیر میتوانید از این پلاگین استفاده کنید :</p>

```html 
<input type="text" readonly class="date"/>
```

```js 
    $('.date').on('click', function(e) {
        e.preventDefault();
        $.dateSelect.show({
            element: $(this)
        });
    });
```
