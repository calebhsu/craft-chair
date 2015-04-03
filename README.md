# craft-chair

Parameterized chair model.

### Install
    $ npm install craft-chair

### Parameters
- legHeight: adjusts height of chair legs
- length: adjusts length of seat
- width: adjusts width of seat

### Example
```html
<craft>
    <craft name="chair" module="calebhsu/craft-chair"/>
    <lineup spacing="2">
        <scale factor="2">
            <chair></chair>
        </scale>
        <chair></chair>        
    </lineup>
</craft>
```

![example](example.png)