## Action 创建  

Action的创建非常简单，Action可以看作是js中的一个对象。

```js
const DELETE_USER_BY_ID="DELETE_USER_BY_ID"

function createaction(id){
    return {
        type:DELETE_USER_BY_ID;
        id:id
    }
}
```



