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
    <craft name="chair" module="craft-chair"/>
    <row spacing="2">
        <chair transform="scale(2,2,2)"></chair>
        <chair></chair>        
    </row>
</craft>
```

![example](example.png)