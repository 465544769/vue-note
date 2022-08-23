# axios、mockjs

# axios
## 安装
```
yarn add axios
```
或
```
npm install axios
```

## 使用
```js
import axios from "axios";

export default {
created() {
    axios.get("/manage/productpanel").then((data) => {
      this.tbData = data.data.data;
    });
  },
}

```

# mockjs
## 安装
```
yarn add mockjs -D
```
或
```
npm install mockjs -D
```

## 使用
```js
import mockjs from "mockjs";

mockjs.mock('/manage/productpanel', 'get', {
    'data|10': [
        {
            'id|+1': 1,
            productname: "@cname",
            isActived: "@boolean",
            isDelete: "@boolean",
        }
    ]
})
```