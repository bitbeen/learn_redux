# Action

Action在Redux是一个状态的承载体而言，在Redux中状态是不可变的，如果要创建改变一个Action可以通过构造一个新的Action。

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



